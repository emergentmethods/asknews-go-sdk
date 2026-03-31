# \ChatAPI

All URIs are relative to *https://api.asknews.app*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeepNews**](ChatAPI.md#DeepNews) | **Post** /v1/chat/deepnews | Deep research into real-time news, archive news, and Google.
[**GetChatCompletions**](ChatAPI.md#GetChatCompletions) | **Post** /v1/openai/chat/completions | Get chat completions from a news-infused AI assistant
[**ListDeepnewsModels**](ChatAPI.md#ListDeepnewsModels) | **Get** /v1/chat/deepnews-models | List available DeepNews models



## DeepNews

> CreateDeepNewsResponse1 DeepNews(ctx).CreateDeepNewsRequest(createDeepNewsRequest).Execute()

Deep research into real-time news, archive news, and Google.

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
	createDeepNewsRequest := *openapiclient.NewCreateDeepNewsRequest([]openapiclient.CreateDeepNewsRequestMessage{*openapiclient.NewCreateDeepNewsRequestMessage("Role_example", "Content_example")}) // CreateDeepNewsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.DeepNews(context.Background()).CreateDeepNewsRequest(createDeepNewsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.DeepNews``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeepNews`: CreateDeepNewsResponse1
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.DeepNews`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDeepNewsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createDeepNewsRequest** | [**CreateDeepNewsRequest**](CreateDeepNewsRequest.md) |  | 

### Return type

[**CreateDeepNewsResponse1**](CreateDeepNewsResponse1.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, text/event-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetChatCompletions

> CreateChatCompletionResponse1 GetChatCompletions(ctx).CreateChatCompletionRequest(createChatCompletionRequest).Execute()

Get chat completions from a news-infused AI assistant



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
	createChatCompletionRequest := *openapiclient.NewCreateChatCompletionRequest([]openapiclient.CreateChatCompletionRequestMessage{*openapiclient.NewCreateChatCompletionRequestMessage("Role_example", "Content_example")}) // CreateChatCompletionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.GetChatCompletions(context.Background()).CreateChatCompletionRequest(createChatCompletionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.GetChatCompletions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetChatCompletions`: CreateChatCompletionResponse1
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.GetChatCompletions`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetChatCompletionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createChatCompletionRequest** | [**CreateChatCompletionRequest**](CreateChatCompletionRequest.md) |  | 

### Return type

[**CreateChatCompletionResponse1**](CreateChatCompletionResponse1.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json, text/event-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDeepnewsModels

> ListDeepNewsModelResponse ListDeepnewsModels(ctx).Execute()

List available DeepNews models



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.ListDeepnewsModels(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.ListDeepnewsModels``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDeepnewsModels`: ListDeepNewsModelResponse
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.ListDeepnewsModels`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListDeepnewsModelsRequest struct via the builder pattern


### Return type

[**ListDeepNewsModelResponse**](ListDeepNewsModelResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

