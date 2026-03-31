# \AnalyticsAPI

All URIs are relative to *https://api.asknews.app*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAssetSentiment**](AnalyticsAPI.md#GetAssetSentiment) | **Get** /v1/analytics/finance/sentiment | Get a timeseries of finance news sentiment for assets



## GetAssetSentiment

> FinanceResponse GetAssetSentiment(ctx).Asset(asset).Metric(metric).DateFrom(dateFrom).DateTo(dateTo).Execute()

Get a timeseries of finance news sentiment for assets



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
	asset := "asset_example" // string | The asset name to query for sentiment.
	metric := "metric_example" // string | The metric to obtain. Weighted metrics account for page-rank of original source. Higher page rank sources are weighted more heavily. (optional) (default to "news_positive")
	dateFrom := time.Now() // time.Time | The start date in ISO format (optional)
	dateTo := time.Now() // time.Time | The end date in ISO format (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AnalyticsAPI.GetAssetSentiment(context.Background()).Asset(asset).Metric(metric).DateFrom(dateFrom).DateTo(dateTo).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnalyticsAPI.GetAssetSentiment``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAssetSentiment`: FinanceResponse
	fmt.Fprintf(os.Stdout, "Response from `AnalyticsAPI.GetAssetSentiment`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAssetSentimentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **asset** | **string** | The asset name to query for sentiment. | 
 **metric** | **string** | The metric to obtain. Weighted metrics account for page-rank of original source. Higher page rank sources are weighted more heavily. | [default to &quot;news_positive&quot;]
 **dateFrom** | **time.Time** | The start date in ISO format | 
 **dateTo** | **time.Time** | The end date in ISO format | 

### Return type

[**FinanceResponse**](FinanceResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

