# \WebsearchAPI

All URIs are relative to *https://api.asknews.dev*

Method | HTTP request | Description
------------- | ------------- | -------------
[**LiveWebSearch**](WebsearchAPI.md#LiveWebSearch) | **Get** /v1/chat/websearch | Run a live websearch.



## LiveWebSearch

> WebSearchResponse LiveWebSearch(ctx).Queries(queries).Lookback(lookback).Domains(domains).Strict(strict).Offset(offset).Execute()

Run a live websearch.



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
	queries := []*string{"Inner_example"} // []*string | A list of queries to be live searched, analyzed, distilled, and structured.
	lookback := int32(56) // int32 | Number of hours back to allow the websearch to look. Defaults to All time (optional)
	domains := []string{"Inner_example"} // []string | A list of domains to search. (optional)
	strict := true // bool | If true, the websearch will only return results that have a known publication date and are within the lookback period. (optional) (default to false)
	offset := int32(56) // int32 | The number of results to offset for followup queries. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebsearchAPI.LiveWebSearch(context.Background()).Queries(queries).Lookback(lookback).Domains(domains).Strict(strict).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebsearchAPI.LiveWebSearch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LiveWebSearch`: WebSearchResponse
	fmt.Fprintf(os.Stdout, "Response from `WebsearchAPI.LiveWebSearch`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiLiveWebSearchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **queries** | **[]string** | A list of queries to be live searched, analyzed, distilled, and structured. | 
 **lookback** | **int32** | Number of hours back to allow the websearch to look. Defaults to All time | 
 **domains** | **[]string** | A list of domains to search. | 
 **strict** | **bool** | If true, the websearch will only return results that have a known publication date and are within the lookback period. | [default to false]
 **offset** | **int32** | The number of results to offset for followup queries. | 

### Return type

[**WebSearchResponse**](WebSearchResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

