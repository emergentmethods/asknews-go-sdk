# \ProfileAPI

All URIs are relative to *https://api.asknews.app*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetUserProfile**](ProfileAPI.md#GetUserProfile) | **Get** /v1/profiles/me | Get the current user&#39;s profile



## GetUserProfile

> ProfileResponse GetUserProfile(ctx).Execute()

Get the current user's profile



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
	resp, r, err := apiClient.ProfileAPI.GetUserProfile(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProfileAPI.GetUserProfile``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserProfile`: ProfileResponse
	fmt.Fprintf(os.Stdout, "Response from `ProfileAPI.GetUserProfile`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserProfileRequest struct via the builder pattern


### Return type

[**ProfileResponse**](ProfileResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

