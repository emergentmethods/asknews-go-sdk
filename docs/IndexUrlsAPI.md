# \IndexUrlsAPI

All URIs are relative to *https://api.asknews.app*

Method | HTTP request | Description
------------- | ------------- | -------------
[**IndexUrls**](IndexUrlsAPI.md#IndexUrls) | **Post** /v1/news/index_urls | Index a list of URLs into AskNews



## IndexUrls

> IndexUrlsResponse IndexUrls(ctx).URLIndexingRequest(uRLIndexingRequest).Execute()

Index a list of URLs into AskNews



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
	uRLIndexingRequest := *openapiclient.NewURLIndexingRequest(time.Now(), time.Now(), []openapiclient.ScrapedURLItem{*openapiclient.NewScrapedURLItem("Url_example")}) // URLIndexingRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.IndexUrlsAPI.IndexUrls(context.Background()).URLIndexingRequest(uRLIndexingRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `IndexUrlsAPI.IndexUrls``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `IndexUrls`: IndexUrlsResponse
	fmt.Fprintf(os.Stdout, "Response from `IndexUrlsAPI.IndexUrls`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiIndexUrlsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **uRLIndexingRequest** | [**URLIndexingRequest**](URLIndexingRequest.md) |  | 

### Return type

[**IndexUrlsResponse**](IndexUrlsResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

