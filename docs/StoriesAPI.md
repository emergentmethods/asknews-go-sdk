# \StoriesAPI

All URIs are relative to *https://api.asknews.dev*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetStories**](StoriesAPI.md#GetStories) | **Get** /v1/stories | Filter and search for top news narratives
[**GetStory**](StoriesAPI.md#GetStory) | **Get** /v1/stories/{story_id} | Get a story containing updates



## GetStories

> StoriesResponse GetStories(ctx).Query(query).Categories(categories).Uuids(uuids).StartTimestamp(startTimestamp).EndTimestamp(endTimestamp).SortBy(sortBy).SortType(sortType).Continent(continent).Offset(offset).Limit(limit).ExpandUpdates(expandUpdates).MaxUpdates(maxUpdates).MaxArticles(maxArticles).Method(method).ObjType(objType).Reddit(reddit).CitationMethod(citationMethod).SimilarityScoreThreshold(similarityScoreThreshold).Provocative(provocative).Strategy(strategy).Execute()

Filter and search for top news narratives



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/emergentmethods/asknews-go-sdk"
)

func main() {
	query := "query_example" // string | Query to be used for the search. If method='nl', then this will beused as a natural language query. If method='kw', then this willbe used as a direct keyword query. (optional)
	categories := []string{"Categories_example"} // []string | Categories to use for filtering the stories search (optional) (default to [])
	uuids := []*string{"Inner_example"} // []*string | A list of UUIDs to retrieve. (optional) (default to [])
	startTimestamp := int32(56) // int32 | Start timestamp to filter results on. (optional)
	endTimestamp := int32(56) // int32 | End timestamp to filter results on. (optional)
	sortBy := "sortBy_example" // string | Which type of sorting to perform. published: Sort by published date. coverage: Sort by coverage. sentiment: Sort by sentiment. relevance: Sort by relevance of similarity score/ranking. (optional)
	sortType := "sortType_example" // string | Whether to sort results in ascending or descending order. (optional)
	continent := *openapiclient.NewContinent() // Continent | Continents to filter by. (optional)
	offset := *openapiclient.NewOffset1() // Offset1 | Offset to use (optional) (default to 0)
	limit := int32(56) // int32 | Limit to use (optional) (default to 10)
	expandUpdates := true // bool | Whether to expand updates (optional) (default to false)
	maxUpdates := int32(56) // int32 | Max updates to use (optional) (default to 2)
	maxArticles := int32(56) // int32 | Max articles to use per update (optional) (default to 5)
	method := "method_example" // string | Method to use for query, 'nl' means natural language, and will run a semantic search on the stories database. 'kw' means keyword, and will search by keyword on the stories database. 'both' means that both methods will be used and results will be ranked according to IRR. (optional) (default to "kw")
	objType := []string{"ObjType_example"} // []string | Object type to filter by, can be a list with 'story' and/or 'story_update' (optional) (default to ["story"])
	reddit := int32(56) // int32 | Whether or not to include Reddit analysiswhere the integer indicates the number of threadsto include in the response. 0 is default. Requirespaid plan to access. (optional) (default to 0)
	citationMethod := "citationMethod_example" // string | Method to use for citation filtering. (optional) (default to "brackets")
	similarityScoreThreshold := float32(8.14) // float32 | Similarity score threshold to use when using query (optional) (default to 0.75)
	provocative := "provocative_example" // string | Filter stories based on how provocative the underlying articles are deemed based on the use of provocative language and emotional vocabulary. (optional) (default to "all")
	strategy := "strategy_example" // string | Strategy to use for automatically controlling the search. 'default' is the default strategy, which follows all filters faithfully. 'topstories' aims to give a diverse look at top news stories that are relevant to the current filter combination.'topstories_categories' aims to give the top stories for each category. 'topstories_continents' aims to give the top stories for each continent. (optional) (default to "default")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StoriesAPI.GetStories(context.Background()).Query(query).Categories(categories).Uuids(uuids).StartTimestamp(startTimestamp).EndTimestamp(endTimestamp).SortBy(sortBy).SortType(sortType).Continent(continent).Offset(offset).Limit(limit).ExpandUpdates(expandUpdates).MaxUpdates(maxUpdates).MaxArticles(maxArticles).Method(method).ObjType(objType).Reddit(reddit).CitationMethod(citationMethod).SimilarityScoreThreshold(similarityScoreThreshold).Provocative(provocative).Strategy(strategy).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StoriesAPI.GetStories``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetStories`: StoriesResponse
	fmt.Fprintf(os.Stdout, "Response from `StoriesAPI.GetStories`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetStoriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **query** | **string** | Query to be used for the search. If method&#x3D;&#39;nl&#39;, then this will beused as a natural language query. If method&#x3D;&#39;kw&#39;, then this willbe used as a direct keyword query. | 
 **categories** | **[]string** | Categories to use for filtering the stories search | [default to []]
 **uuids** | **[]string** | A list of UUIDs to retrieve. | [default to []]
 **startTimestamp** | **int32** | Start timestamp to filter results on. | 
 **endTimestamp** | **int32** | End timestamp to filter results on. | 
 **sortBy** | **string** | Which type of sorting to perform. published: Sort by published date. coverage: Sort by coverage. sentiment: Sort by sentiment. relevance: Sort by relevance of similarity score/ranking. | 
 **sortType** | **string** | Whether to sort results in ascending or descending order. | 
 **continent** | [**Continent**](Continent.md) | Continents to filter by. | 
 **offset** | [**Offset1**](Offset1.md) | Offset to use | [default to 0]
 **limit** | **int32** | Limit to use | [default to 10]
 **expandUpdates** | **bool** | Whether to expand updates | [default to false]
 **maxUpdates** | **int32** | Max updates to use | [default to 2]
 **maxArticles** | **int32** | Max articles to use per update | [default to 5]
 **method** | **string** | Method to use for query, &#39;nl&#39; means natural language, and will run a semantic search on the stories database. &#39;kw&#39; means keyword, and will search by keyword on the stories database. &#39;both&#39; means that both methods will be used and results will be ranked according to IRR. | [default to &quot;kw&quot;]
 **objType** | **[]string** | Object type to filter by, can be a list with &#39;story&#39; and/or &#39;story_update&#39; | [default to [&quot;story&quot;]]
 **reddit** | **int32** | Whether or not to include Reddit analysiswhere the integer indicates the number of threadsto include in the response. 0 is default. Requirespaid plan to access. | [default to 0]
 **citationMethod** | **string** | Method to use for citation filtering. | [default to &quot;brackets&quot;]
 **similarityScoreThreshold** | **float32** | Similarity score threshold to use when using query | [default to 0.75]
 **provocative** | **string** | Filter stories based on how provocative the underlying articles are deemed based on the use of provocative language and emotional vocabulary. | [default to &quot;all&quot;]
 **strategy** | **string** | Strategy to use for automatically controlling the search. &#39;default&#39; is the default strategy, which follows all filters faithfully. &#39;topstories&#39; aims to give a diverse look at top news stories that are relevant to the current filter combination.&#39;topstories_categories&#39; aims to give the top stories for each category. &#39;topstories_continents&#39; aims to give the top stories for each continent. | [default to &quot;default&quot;]

### Return type

[**StoriesResponse**](StoriesResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetStory

> StoryResponse GetStory(ctx, storyId).ExpandUpdates(expandUpdates).MaxUpdates(maxUpdates).MaxArticles(maxArticles).Reddit(reddit).CitationMethod(citationMethod).CondenseAuxillaryUpdates(condenseAuxillaryUpdates).Execute()

Get a story containing updates



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/emergentmethods/asknews-go-sdk"
)

func main() {
	storyId := "storyId_example" // string | The story UUID, update UUID, or URL safe title
	expandUpdates := true // bool | Whether to expand updates (optional) (default to true)
	maxUpdates := int32(56) // int32 | Max number of updates to include in the story object (optional) (default to 10)
	maxArticles := int32(56) // int32 | Max articles to include per update (optional) (default to 25)
	reddit := int32(56) // int32 | Whether to include Reddit analysis (optional) (default to 0)
	citationMethod := "citationMethod_example" // string | Method to use for citation filtering. (optional) (default to "brackets")
	condenseAuxillaryUpdates := true // bool | When requesting a particular story update, you can expand the assocaited updates by settined max_updates to the total you would like to get. If you want those updates to by condensed for reduced latency, you can set  condense_auxillary_updates to 'False'. (optional) (default to true)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.StoriesAPI.GetStory(context.Background(), storyId).ExpandUpdates(expandUpdates).MaxUpdates(maxUpdates).MaxArticles(maxArticles).Reddit(reddit).CitationMethod(citationMethod).CondenseAuxillaryUpdates(condenseAuxillaryUpdates).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `StoriesAPI.GetStory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetStory`: StoryResponse
	fmt.Fprintf(os.Stdout, "Response from `StoriesAPI.GetStory`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**storyId** | **string** | The story UUID, update UUID, or URL safe title | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetStoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **expandUpdates** | **bool** | Whether to expand updates | [default to true]
 **maxUpdates** | **int32** | Max number of updates to include in the story object | [default to 10]
 **maxArticles** | **int32** | Max articles to include per update | [default to 25]
 **reddit** | **int32** | Whether to include Reddit analysis | [default to 0]
 **citationMethod** | **string** | Method to use for citation filtering. | [default to &quot;brackets&quot;]
 **condenseAuxillaryUpdates** | **bool** | When requesting a particular story update, you can expand the assocaited updates by settined max_updates to the total you would like to get. If you want those updates to by condensed for reduced latency, you can set  condense_auxillary_updates to &#39;False&#39;. | [default to true]

### Return type

[**StoryResponse**](StoryResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

