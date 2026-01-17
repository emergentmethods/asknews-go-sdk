# \ForecastAPI

All URIs are relative to *https://api.asknews.app*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetForecast**](ForecastAPI.md#GetForecast) | **Get** /v1/chat/forecast | Make an expert forecast for a news event.



## GetForecast

> ForecastResponse GetForecast(ctx).Query(query).Lookback(lookback).ArticlesToUse(articlesToUse).Method(method).Model(model).CutoffDate(cutoffDate).UseReddit(useReddit).AdditionalContext(additionalContext).WebSearch(webSearch).Expert(expert).Execute()

Make an expert forecast for a news event.



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
	query := "query_example" // string | The requested forecast.
	lookback := int32(56) // int32 | The number of days to look back for the forecast. (optional) (default to 14)
	articlesToUse := int32(56) // int32 | The total number of relevant articles to be extracted from the news archive and used for the forecast. (optional) (default to 15)
	method := "method_example" // string | Method to use for the context search Currently only 'kw' is supported. (optional) (default to "kw")
	model := "model_example" // string | The model to use for the forecast. (optional) (default to "gpt-4.1-2025-04-14")
	cutoffDate := "cutoffDate_example" // string | The cutoff date for the forecast. String format is 'YYYY-MM-DD-HH:MM'. This is useful  for backtesting forecasts. (optional)
	useReddit := true // bool | Whether to use Reddit data for the forecast.enterprise customers only. (optional) (default to false)
	additionalContext := "additionalContext_example" // string | Additional context to use for the forecast. (optional)
	webSearch := true // bool | Whether to run a live web search and include results in the forecast. enterprise customers only. (optional) (default to false)
	expert := "expert_example" // string | The type of expert to use for the forecast. (optional) (default to "general")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ForecastAPI.GetForecast(context.Background()).Query(query).Lookback(lookback).ArticlesToUse(articlesToUse).Method(method).Model(model).CutoffDate(cutoffDate).UseReddit(useReddit).AdditionalContext(additionalContext).WebSearch(webSearch).Expert(expert).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ForecastAPI.GetForecast``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetForecast`: ForecastResponse
	fmt.Fprintf(os.Stdout, "Response from `ForecastAPI.GetForecast`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetForecastRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **query** | **string** | The requested forecast. | 
 **lookback** | **int32** | The number of days to look back for the forecast. | [default to 14]
 **articlesToUse** | **int32** | The total number of relevant articles to be extracted from the news archive and used for the forecast. | [default to 15]
 **method** | **string** | Method to use for the context search Currently only &#39;kw&#39; is supported. | [default to &quot;kw&quot;]
 **model** | **string** | The model to use for the forecast. | [default to &quot;gpt-4.1-2025-04-14&quot;]
 **cutoffDate** | **string** | The cutoff date for the forecast. String format is &#39;YYYY-MM-DD-HH:MM&#39;. This is useful  for backtesting forecasts. | 
 **useReddit** | **bool** | Whether to use Reddit data for the forecast.enterprise customers only. | [default to false]
 **additionalContext** | **string** | Additional context to use for the forecast. | 
 **webSearch** | **bool** | Whether to run a live web search and include results in the forecast. enterprise customers only. | [default to false]
 **expert** | **string** | The type of expert to use for the forecast. | [default to &quot;general&quot;]

### Return type

[**ForecastResponse**](ForecastResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

