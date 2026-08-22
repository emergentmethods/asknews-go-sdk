# \WebsearchAPI

All URIs are relative to *https://api.asknews.app*

Method | HTTP request | Description
------------- | ------------- | -------------
[**LiveWebSearch**](WebsearchAPI.md#LiveWebSearch) | **Get** /v1/chat/websearch | Run a live websearch.



## LiveWebSearch

> WebSearchResponse LiveWebSearch(ctx).Queries(queries).Lookback(lookback).StartDatetime(startDatetime).EndDatetime(endDatetime).Engine(engine).Domains(domains).Strict(strict).Offset(offset).Execute()

Run a live websearch.



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/emergentmethods/asknews-go-sdk"
)

func main() {
	queries := []*string{"Inner_example"} // []*string | A list of queries to be live searched, analyzed, distilled, and structured.
	lookback := int32(56) // int32 | Number of hours back to allow the websearch to look. Defaults to All time (optional)
	startDatetime := time.Now() // time.Time | Earliest acceptable publication datetime for results. For v1, acts like the existing lookback filter. (optional)
	endDatetime := time.Now() // time.Time | Latest acceptable publication datetime for results.  (optional)
	engine := "engine_example" // string | Search engine version to use for live websearch results. (optional) (default to "v1")
	domains := []string{"Inner_example"} // []string | A list of domains to search. (optional)
	strict := true // bool | If true, the websearch will only return results that have a known publication date and are within the lookback period. (optional) (default to false)
	offset := *openapiclient.NewOffset1() // Offset1 | The number of results to offset for followup queries. Numeric for regular websearch; X (Twitter) searches return an opaque cursor string in response.offset â€” pass it back here to paginate. (optional) (default to 0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebsearchAPI.LiveWebSearch(context.Background()).Queries(queries).Lookback(lookback).StartDatetime(startDatetime).EndDatetime(endDatetime).Engine(engine).Domains(domains).Strict(strict).Offset(offset).Execute()
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
 **startDatetime** | **time.Time** | Earliest acceptable publication datetime for results. For v1, acts like the existing lookback filter. | 
 **endDatetime** | **time.Time** | Latest acceptable publication datetime for results.  | 
 **engine** | **string** | Search engine version to use for live websearch results. | [default to &quot;v1&quot;]
 **domains** | **[]string** | A list of domains to search. | 
 **strict** | **bool** | If true, the websearch will only return results that have a known publication date and are within the lookback period. | [default to false]
 **offset** | [**Offset1**](Offset1.md) | The number of results to offset for followup queries. Numeric for regular websearch; X (Twitter) searches return an opaque cursor string in response.offset â€” pass it back here to paginate. | [default to 0]

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

