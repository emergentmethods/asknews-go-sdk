# \ByokAPI

All URIs are relative to *https://api.asknews.app*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteByokKey**](ByokAPI.md#DeleteByokKey) | **Delete** /v1/chat/byok/{provider} | Delete a stored BYOK API key for a provider
[**GetByokKey**](ByokAPI.md#GetByokKey) | **Get** /v1/chat/byok/{provider} | Get a stored BYOK API key hint for a provider
[**UpsertByokKey**](ByokAPI.md#UpsertByokKey) | **Put** /v1/chat/byok/{provider} | Store a BYOK API key for a provider



## DeleteByokKey

> DeleteByokKey(ctx, provider).Execute()

Delete a stored BYOK API key for a provider



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
	provider := "provider_example" // string | The BYOK provider

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.ByokAPI.DeleteByokKey(context.Background(), provider).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ByokAPI.DeleteByokKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**provider** | **string** | The BYOK provider | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteByokKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetByokKey

> ApiKeyResponse GetByokKey(ctx, provider).Execute()

Get a stored BYOK API key hint for a provider



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
	provider := "provider_example" // string | The BYOK provider

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ByokAPI.GetByokKey(context.Background(), provider).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ByokAPI.GetByokKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetByokKey`: ApiKeyResponse
	fmt.Fprintf(os.Stdout, "Response from `ByokAPI.GetByokKey`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**provider** | **string** | The BYOK provider | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetByokKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ApiKeyResponse**](ApiKeyResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpsertByokKey

> ApiKeyResponse UpsertByokKey(ctx, provider).UpsertApiKeyRequest(upsertApiKeyRequest).Execute()

Store a BYOK API key for a provider



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
	provider := "provider_example" // string | The BYOK provider
	upsertApiKeyRequest := *openapiclient.NewUpsertApiKeyRequest("ApiKey_example") // UpsertApiKeyRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ByokAPI.UpsertByokKey(context.Background(), provider).UpsertApiKeyRequest(upsertApiKeyRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ByokAPI.UpsertByokKey``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpsertByokKey`: ApiKeyResponse
	fmt.Fprintf(os.Stdout, "Response from `ByokAPI.UpsertByokKey`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**provider** | **string** | The BYOK provider | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpsertByokKeyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **upsertApiKeyRequest** | [**UpsertApiKeyRequest**](UpsertApiKeyRequest.md) |  | 

### Return type

[**ApiKeyResponse**](ApiKeyResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

