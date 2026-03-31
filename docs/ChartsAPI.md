# \ChartsAPI

All URIs are relative to *https://api.asknews.app*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateChartsEndpoint**](ChartsAPI.md#CreateChartsEndpoint) | **Post** /v1/chat/charts | Create a chart



## CreateChartsEndpoint

> ChartResponse CreateChartsEndpoint(ctx).CreateChartRequest(createChartRequest).Execute()

Create a chart



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
	createChartRequest := *openapiclient.NewCreateChartRequest("Query_example") // CreateChartRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChartsAPI.CreateChartsEndpoint(context.Background()).CreateChartRequest(createChartRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChartsAPI.CreateChartsEndpoint``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateChartsEndpoint`: ChartResponse
	fmt.Fprintf(os.Stdout, "Response from `ChartsAPI.CreateChartsEndpoint`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateChartsEndpointRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createChartRequest** | [**CreateChartRequest**](CreateChartRequest.md) |  | 

### Return type

[**ChartResponse**](ChartResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

