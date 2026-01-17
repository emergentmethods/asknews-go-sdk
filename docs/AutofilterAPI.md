# \AutofilterAPI

All URIs are relative to *https://api.asknews.dev*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Autofilter**](AutofilterAPI.md#Autofilter) | **Get** /v1/chat/autofilter | Generate filter params for AskNews endpoints



## Autofilter

> FilterParamsResponse Autofilter(ctx).Query(query).Execute()

Generate filter params for AskNews endpoints



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
	query := "query_example" // string | A description of what kind of news you want to get.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AutofilterAPI.Autofilter(context.Background()).Query(query).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AutofilterAPI.Autofilter``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Autofilter`: FilterParamsResponse
	fmt.Fprintf(os.Stdout, "Response from `AutofilterAPI.Autofilter`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiAutofilterRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **query** | **string** | A description of what kind of news you want to get. | 

### Return type

[**FilterParamsResponse**](FilterParamsResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

