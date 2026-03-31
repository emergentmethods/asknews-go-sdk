# \WikiAPI

All URIs are relative to *https://api.asknews.app*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SearchWiki**](WikiAPI.md#SearchWiki) | **Get** /v1/wiki/search | Search for Wikipedia context with natural language



## SearchWiki

> WikiSearchResponse SearchWiki(ctx).Query(query).NeighborChunks(neighborChunks).NDocuments(nDocuments).FullArticles(fullArticles).HybridSearch(hybridSearch).StringGuarantee(stringGuarantee).Diversify(diversify).IncludeMainSection(includeMainSection).Execute()

Search for Wikipedia context with natural language



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
	query := "query_example" // string | Natural language query that can be any phrase, keyword, question, or paragraph.  (optional) (default to "")
	neighborChunks := int32(56) // int32 | Number of neighbor chunks to attach and return. If 0, then no neighbor chunks will be returned.  (optional)
	nDocuments := int32(56) // int32 | Number of documents to return. If 0, then no documents will be returned.  (optional)
	fullArticles := true // bool | If true, then full articles will be returned. If false, then only chunks and their neighbors will be returned. Beware that returning full articles increases data size which increases token usage downstream. (optional)
	hybridSearch := true // bool | If true, then hybrid search will be used. If false, then only vector search will be used.  (optional)
	stringGuarantee := []string{"Inner_example"} // []string | List of strings that must be present in the results. If empty, then no string guarantee will be applied.  (optional)
	diversify := float32(8.14) // float32 | Diversity factor for MMR re-ranking. 0.0 means no diversity (pure relevance), 1.0 means full diversity.  (optional)
	includeMainSection := true // bool | If true, then the main section of the article will be included at the start of each chunk's content. If false, then only the chunk content will be returned. Useful because the main section often contains important context.  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WikiAPI.SearchWiki(context.Background()).Query(query).NeighborChunks(neighborChunks).NDocuments(nDocuments).FullArticles(fullArticles).HybridSearch(hybridSearch).StringGuarantee(stringGuarantee).Diversify(diversify).IncludeMainSection(includeMainSection).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WikiAPI.SearchWiki``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchWiki`: WikiSearchResponse
	fmt.Fprintf(os.Stdout, "Response from `WikiAPI.SearchWiki`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchWikiRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **query** | **string** | Natural language query that can be any phrase, keyword, question, or paragraph.  | [default to &quot;&quot;]
 **neighborChunks** | **int32** | Number of neighbor chunks to attach and return. If 0, then no neighbor chunks will be returned.  | 
 **nDocuments** | **int32** | Number of documents to return. If 0, then no documents will be returned.  | 
 **fullArticles** | **bool** | If true, then full articles will be returned. If false, then only chunks and their neighbors will be returned. Beware that returning full articles increases data size which increases token usage downstream. | 
 **hybridSearch** | **bool** | If true, then hybrid search will be used. If false, then only vector search will be used.  | 
 **stringGuarantee** | **[]string** | List of strings that must be present in the results. If empty, then no string guarantee will be applied.  | 
 **diversify** | **float32** | Diversity factor for MMR re-ranking. 0.0 means no diversity (pure relevance), 1.0 means full diversity.  | 
 **includeMainSection** | **bool** | If true, then the main section of the article will be included at the start of each chunk&#39;s content. If false, then only the chunk content will be returned. Useful because the main section often contains important context.  | 

### Return type

[**WikiSearchResponse**](WikiSearchResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

