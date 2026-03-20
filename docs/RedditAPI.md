# \RedditAPI

All URIs are relative to *https://api.asknews.dev*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SearchReddit**](RedditAPI.md#SearchReddit) | **Get** /v1/reddit/search | Search Reddit, summarize threads, and return analysis.



## SearchReddit

> RedditResponse SearchReddit(ctx).Keywords(keywords).NThreads(nThreads).Method(method).Deep(deep).ReturnType(returnType).TimeFilter(timeFilter).Sort(sort).Execute()

Search Reddit, summarize threads, and return analysis.



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
	keywords := []*string{"Inner_example"} // []*string | Keywords used to search for relevant Reddit threads.
	nThreads := int32(56) // int32 | Number of Reddit threads to summarize and return (optional) (default to 5)
	method := "method_example" // string | The search method. Can be 'nl' or 'kw'. If 'nl', then the query will be used as a natural language query. If 'kw', then the query will be used as a direct keyword query. (optional) (default to "kw")
	deep := true // bool | Deep means that AskNews goes directly to Reddit, searches live, summarizes the threads live, and returns structured data for you. Deep=False means that AskNews looks in its existing database of Reddit threads and returns the most similar threads  (optional) (default to false)
	returnType := "returnType_example" // string | The return type. Can be 'dicts', 'string', or 'both'. (optional) (default to "string")
	timeFilter := "timeFilter_example" // string | The time filter. (optional) (default to "day")
	sort := "sort_example" // string | The sort order. (optional) (default to "relevance")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RedditAPI.SearchReddit(context.Background()).Keywords(keywords).NThreads(nThreads).Method(method).Deep(deep).ReturnType(returnType).TimeFilter(timeFilter).Sort(sort).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RedditAPI.SearchReddit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchReddit`: RedditResponse
	fmt.Fprintf(os.Stdout, "Response from `RedditAPI.SearchReddit`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchRedditRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **keywords** | **[]string** | Keywords used to search for relevant Reddit threads. | 
 **nThreads** | **int32** | Number of Reddit threads to summarize and return | [default to 5]
 **method** | **string** | The search method. Can be &#39;nl&#39; or &#39;kw&#39;. If &#39;nl&#39;, then the query will be used as a natural language query. If &#39;kw&#39;, then the query will be used as a direct keyword query. | [default to &quot;kw&quot;]
 **deep** | **bool** | Deep means that AskNews goes directly to Reddit, searches live, summarizes the threads live, and returns structured data for you. Deep&#x3D;False means that AskNews looks in its existing database of Reddit threads and returns the most similar threads  | [default to false]
 **returnType** | **string** | The return type. Can be &#39;dicts&#39;, &#39;string&#39;, or &#39;both&#39;. | [default to &quot;string&quot;]
 **timeFilter** | **string** | The time filter. | [default to &quot;day&quot;]
 **sort** | **string** | The sort order. | [default to &quot;relevance&quot;]

### Return type

[**RedditResponse**](RedditResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

