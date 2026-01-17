# \NewslettersAPI

All URIs are relative to *https://api.asknews.dev*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteNewsletter**](NewslettersAPI.md#DeleteNewsletter) | **Delete** /v1/chat/newsletters/{newsletter_id} | Delete a newsletter
[**DeleteNewsletterContact**](NewslettersAPI.md#DeleteNewsletterContact) | **Delete** /v1/chat/newsletters/{newsletter_id}/contacts/{contact_id} | Delete a newsletter contact
[**GetNewsletter**](NewslettersAPI.md#GetNewsletter) | **Get** /v1/chat/newsletters/{newsletter_id} | Get a newsletter
[**GetNewsletterContact**](NewslettersAPI.md#GetNewsletterContact) | **Get** /v1/chat/newsletters/{newsletter_id}/contacts/{contact_id} | Get a newsletter contact
[**GetNewsletterContacts**](NewslettersAPI.md#GetNewsletterContacts) | **Get** /v1/chat/newsletters/{newsletter_id}/contacts | Get newsletter contacts
[**GetNewsletters**](NewslettersAPI.md#GetNewsletters) | **Get** /v1/chat/newsletters | Get all created newsletters
[**GetPublicNewsletters**](NewslettersAPI.md#GetPublicNewsletters) | **Get** /v1/chat/newsletters/public | Get all public newsletters
[**PatchNewsletterContact**](NewslettersAPI.md#PatchNewsletterContact) | **Patch** /v1/chat/newsletters/{newsletter_id}/contacts/{contact_id} | Update a newsletter contact
[**PostNewsletter**](NewslettersAPI.md#PostNewsletter) | **Post** /v1/chat/newsletters | Create a newsletter
[**PostNewsletterContacts**](NewslettersAPI.md#PostNewsletterContacts) | **Post** /v1/chat/newsletters/{newsletter_id}/contacts | Create a newsletter contact
[**PutNewsletter**](NewslettersAPI.md#PutNewsletter) | **Put** /v1/chat/newsletters/{newsletter_id} | Update a newsletter
[**UnsubscribeNewsletter**](NewslettersAPI.md#UnsubscribeNewsletter) | **Post** /v1/chat/newsletters/{newsletter_id}/unsubscribe | Unsubscribe from a newsletter



## DeleteNewsletter

> DeleteNewsletter(ctx, newsletterId).Execute()

Delete a newsletter



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
	newsletterId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The newsletter ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.NewslettersAPI.DeleteNewsletter(context.Background(), newsletterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NewslettersAPI.DeleteNewsletter``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**newsletterId** | **string** | The newsletter ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteNewsletterRequest struct via the builder pattern


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


## DeleteNewsletterContact

> DeleteNewsletterContact(ctx, newsletterId, contactId).Execute()

Delete a newsletter contact



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
	newsletterId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The newsletter ID
	contactId := "contactId_example" // string | The contact ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.NewslettersAPI.DeleteNewsletterContact(context.Background(), newsletterId, contactId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NewslettersAPI.DeleteNewsletterContact``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**newsletterId** | **string** | The newsletter ID | 
**contactId** | **string** | The contact ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteNewsletterContactRequest struct via the builder pattern


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


## GetNewsletter

> NewsletterResponse GetNewsletter(ctx, newsletterId).Execute()

Get a newsletter



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
	newsletterId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The newsletter ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NewslettersAPI.GetNewsletter(context.Background(), newsletterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NewslettersAPI.GetNewsletter``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetNewsletter`: NewsletterResponse
	fmt.Fprintf(os.Stdout, "Response from `NewslettersAPI.GetNewsletter`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**newsletterId** | **string** | The newsletter ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetNewsletterRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**NewsletterResponse**](NewsletterResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetNewsletterContact

> NewsletterContactResponse GetNewsletterContact(ctx, newsletterId, contactId).Execute()

Get a newsletter contact



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
	newsletterId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The newsletter ID
	contactId := "contactId_example" // string | The contact ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NewslettersAPI.GetNewsletterContact(context.Background(), newsletterId, contactId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NewslettersAPI.GetNewsletterContact``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetNewsletterContact`: NewsletterContactResponse
	fmt.Fprintf(os.Stdout, "Response from `NewslettersAPI.GetNewsletterContact`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**newsletterId** | **string** | The newsletter ID | 
**contactId** | **string** | The contact ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetNewsletterContactRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**NewsletterContactResponse**](NewsletterContactResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetNewsletterContacts

> []NewsletterContactResponse GetNewsletterContacts(ctx, newsletterId).Execute()

Get newsletter contacts



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
	newsletterId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The newsletter ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NewslettersAPI.GetNewsletterContacts(context.Background(), newsletterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NewslettersAPI.GetNewsletterContacts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetNewsletterContacts`: []NewsletterContactResponse
	fmt.Fprintf(os.Stdout, "Response from `NewslettersAPI.GetNewsletterContacts`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**newsletterId** | **string** | The newsletter ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetNewsletterContactsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]NewsletterContactResponse**](NewsletterContactResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetNewsletters

> PaginatedResponseNewsletterResponse GetNewsletters(ctx).Execute()

Get all created newsletters



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
	resp, r, err := apiClient.NewslettersAPI.GetNewsletters(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NewslettersAPI.GetNewsletters``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetNewsletters`: PaginatedResponseNewsletterResponse
	fmt.Fprintf(os.Stdout, "Response from `NewslettersAPI.GetNewsletters`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetNewslettersRequest struct via the builder pattern


### Return type

[**PaginatedResponseNewsletterResponse**](PaginatedResponseNewsletterResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPublicNewsletters

> PaginatedResponseNewsletterPublicResponse GetPublicNewsletters(ctx).Page(page).PerPage(perPage).All(all).Execute()

Get all public newsletters



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
	page := int32(56) // int32 | The page number to get (optional) (default to 1)
	perPage := int32(56) // int32 | The number of items per page (optional) (default to 10)
	all := true // bool | Whether to get all the public newsletters (optional) (default to false)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NewslettersAPI.GetPublicNewsletters(context.Background()).Page(page).PerPage(perPage).All(all).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NewslettersAPI.GetPublicNewsletters``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPublicNewsletters`: PaginatedResponseNewsletterPublicResponse
	fmt.Fprintf(os.Stdout, "Response from `NewslettersAPI.GetPublicNewsletters`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetPublicNewslettersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** | The page number to get | [default to 1]
 **perPage** | **int32** | The number of items per page | [default to 10]
 **all** | **bool** | Whether to get all the public newsletters | [default to false]

### Return type

[**PaginatedResponseNewsletterPublicResponse**](PaginatedResponseNewsletterPublicResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PatchNewsletterContact

> NewsletterContactUpdateResponse PatchNewsletterContact(ctx, newsletterId, contactId).NewsletterContactRequest(newsletterContactRequest).Execute()

Update a newsletter contact



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
	newsletterId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The newsletter ID
	contactId := "contactId_example" // string | The contact ID
	newsletterContactRequest := *openapiclient.NewNewsletterContactRequest("Email_example") // NewsletterContactRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NewslettersAPI.PatchNewsletterContact(context.Background(), newsletterId, contactId).NewsletterContactRequest(newsletterContactRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NewslettersAPI.PatchNewsletterContact``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PatchNewsletterContact`: NewsletterContactUpdateResponse
	fmt.Fprintf(os.Stdout, "Response from `NewslettersAPI.PatchNewsletterContact`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**newsletterId** | **string** | The newsletter ID | 
**contactId** | **string** | The contact ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiPatchNewsletterContactRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **newsletterContactRequest** | [**NewsletterContactRequest**](NewsletterContactRequest.md) |  | 

### Return type

[**NewsletterContactUpdateResponse**](NewsletterContactUpdateResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostNewsletter

> NewsletterResponse PostNewsletter(ctx).CreateNewsletterRequest(createNewsletterRequest).Execute()

Create a newsletter



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
	createNewsletterRequest := *openapiclient.NewCreateNewsletterRequest("Daily Economy News", "Send me the latest news on the economy.", "0 0 * * *", "gpt-4o-mini", "Your Name <sender@domain.com>") // CreateNewsletterRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NewslettersAPI.PostNewsletter(context.Background()).CreateNewsletterRequest(createNewsletterRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NewslettersAPI.PostNewsletter``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostNewsletter`: NewsletterResponse
	fmt.Fprintf(os.Stdout, "Response from `NewslettersAPI.PostNewsletter`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostNewsletterRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createNewsletterRequest** | [**CreateNewsletterRequest**](CreateNewsletterRequest.md) |  | 

### Return type

[**NewsletterResponse**](NewsletterResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostNewsletterContacts

> NewsletterContactCreateResponse PostNewsletterContacts(ctx, newsletterId).NewsletterContactRequest(newsletterContactRequest).Execute()

Create a newsletter contact



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
	newsletterId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The newsletter ID
	newsletterContactRequest := *openapiclient.NewNewsletterContactRequest("Email_example") // NewsletterContactRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NewslettersAPI.PostNewsletterContacts(context.Background(), newsletterId).NewsletterContactRequest(newsletterContactRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NewslettersAPI.PostNewsletterContacts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostNewsletterContacts`: NewsletterContactCreateResponse
	fmt.Fprintf(os.Stdout, "Response from `NewslettersAPI.PostNewsletterContacts`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**newsletterId** | **string** | The newsletter ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiPostNewsletterContactsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **newsletterContactRequest** | [**NewsletterContactRequest**](NewsletterContactRequest.md) |  | 

### Return type

[**NewsletterContactCreateResponse**](NewsletterContactCreateResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PutNewsletter

> NewsletterResponse PutNewsletter(ctx, newsletterId).UpdateNewsletterRequest(updateNewsletterRequest).Execute()

Update a newsletter



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
	newsletterId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The newsletter ID
	updateNewsletterRequest := *openapiclient.NewUpdateNewsletterRequest() // UpdateNewsletterRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NewslettersAPI.PutNewsletter(context.Background(), newsletterId).UpdateNewsletterRequest(updateNewsletterRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NewslettersAPI.PutNewsletter``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PutNewsletter`: NewsletterResponse
	fmt.Fprintf(os.Stdout, "Response from `NewslettersAPI.PutNewsletter`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**newsletterId** | **string** | The newsletter ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiPutNewsletterRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateNewsletterRequest** | [**UpdateNewsletterRequest**](UpdateNewsletterRequest.md) |  | 

### Return type

[**NewsletterResponse**](NewsletterResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UnsubscribeNewsletter

> UnsubscribeNewsletter(ctx, newsletterId).Execute()

Unsubscribe from a newsletter



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
	newsletterId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The newsletter ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.NewslettersAPI.UnsubscribeNewsletter(context.Background(), newsletterId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NewslettersAPI.UnsubscribeNewsletter``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**newsletterId** | **string** | The newsletter ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiUnsubscribeNewsletterRequest struct via the builder pattern


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

