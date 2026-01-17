# \AlertsAPI

All URIs are relative to *https://api.asknews.app*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAlert**](AlertsAPI.md#CreateAlert) | **Post** /v1/chat/alerts | Create an alert
[**DeleteAlert**](AlertsAPI.md#DeleteAlert) | **Delete** /v1/chat/alerts/{alert_id} | Delete an alert
[**GetAlert**](AlertsAPI.md#GetAlert) | **Get** /v1/chat/alerts/{alert_id} | Get an alert
[**GetAlertLogs**](AlertsAPI.md#GetAlertLogs) | **Get** /v1/chat/alerts/{alert_id}/logs | Get alert logs
[**GetAlerts**](AlertsAPI.md#GetAlerts) | **Get** /v1/chat/alerts | Get all created alerts
[**GetAllAlertLogs**](AlertsAPI.md#GetAllAlertLogs) | **Get** /v1/chat/alerts/logs | Get all alert logs
[**PutAlert**](AlertsAPI.md#PutAlert) | **Put** /v1/chat/alerts/{alert_id} | Update an alert
[**RunAlert**](AlertsAPI.md#RunAlert) | **Get** /v1/chat/alerts/{alert_id}/run | Run an existing alert



## CreateAlert

> AlertResponse CreateAlert(ctx).CreateAlertRequest(createAlertRequest).Execute()

Create an alert



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
	createAlertRequest := *openapiclient.NewCreateAlertRequest("*/15 * * * *", "Model_example", []openapiclient.SourcesInner{openapiclient.Sources_inner{AskNewsSource: openapiclient.NewAskNewsSource("Identifier_example")}}, []openapiclient.TriggersInner{openapiclient.Triggers_inner{EmailAction: openapiclient.NewEmailAction(*openapiclient.NewEmailParams("To_example"))}}) // CreateAlertRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AlertsAPI.CreateAlert(context.Background()).CreateAlertRequest(createAlertRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlertsAPI.CreateAlert``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAlert`: AlertResponse
	fmt.Fprintf(os.Stdout, "Response from `AlertsAPI.CreateAlert`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateAlertRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createAlertRequest** | [**CreateAlertRequest**](CreateAlertRequest.md) |  | 

### Return type

[**AlertResponse**](AlertResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAlert

> DeleteAlert(ctx, alertId).Execute()

Delete an alert



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
	alertId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The alert ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AlertsAPI.DeleteAlert(context.Background(), alertId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlertsAPI.DeleteAlert``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**alertId** | **string** | The alert ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteAlertRequest struct via the builder pattern


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


## GetAlert

> AlertResponse GetAlert(ctx, alertId).UserId(userId).Execute()

Get an alert



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
	alertId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The alert ID
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of the user to get logs for (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AlertsAPI.GetAlert(context.Background(), alertId).UserId(userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlertsAPI.GetAlert``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAlert`: AlertResponse
	fmt.Fprintf(os.Stdout, "Response from `AlertsAPI.GetAlert`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**alertId** | **string** | The alert ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAlertRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **userId** | **string** | The ID of the user to get logs for | 

### Return type

[**AlertResponse**](AlertResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAlertLogs

> PaginatedResponseAlertLog GetAlertLogs(ctx, alertId).UserId(userId).Page(page).PerPage(perPage).All(all).StartTimestamp(startTimestamp).EndTimestamp(endTimestamp).Execute()

Get alert logs



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
	alertId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The alert ID
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of the user to get logs for (optional)
	page := int32(56) // int32 | The page number to get (optional) (default to 1)
	perPage := int32(56) // int32 | The number of items per page (optional) (default to 10)
	all := true // bool | Whether to get all the alert logs (optional) (default to false)
	startTimestamp := int32(56) // int32 | Timestamp to start search from (optional)
	endTimestamp := int32(56) // int32 | Timestamp to end search at (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AlertsAPI.GetAlertLogs(context.Background(), alertId).UserId(userId).Page(page).PerPage(perPage).All(all).StartTimestamp(startTimestamp).EndTimestamp(endTimestamp).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlertsAPI.GetAlertLogs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAlertLogs`: PaginatedResponseAlertLog
	fmt.Fprintf(os.Stdout, "Response from `AlertsAPI.GetAlertLogs`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**alertId** | **string** | The alert ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAlertLogsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **userId** | **string** | The ID of the user to get logs for | 
 **page** | **int32** | The page number to get | [default to 1]
 **perPage** | **int32** | The number of items per page | [default to 10]
 **all** | **bool** | Whether to get all the alert logs | [default to false]
 **startTimestamp** | **int32** | Timestamp to start search from | 
 **endTimestamp** | **int32** | Timestamp to end search at | 

### Return type

[**PaginatedResponseAlertLog**](PaginatedResponseAlertLog.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAlerts

> PaginatedResponseAlertResponse GetAlerts(ctx).Page(page).PerPage(perPage).All(all).Execute()

Get all created alerts



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
	all := true // bool | Whether to get all the alerts (optional) (default to false)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AlertsAPI.GetAlerts(context.Background()).Page(page).PerPage(perPage).All(all).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlertsAPI.GetAlerts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAlerts`: PaginatedResponseAlertResponse
	fmt.Fprintf(os.Stdout, "Response from `AlertsAPI.GetAlerts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAlertsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** | The page number to get | [default to 1]
 **perPage** | **int32** | The number of items per page | [default to 10]
 **all** | **bool** | Whether to get all the alerts | [default to false]

### Return type

[**PaginatedResponseAlertResponse**](PaginatedResponseAlertResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAllAlertLogs

> PaginatedResponseAlertLog GetAllAlertLogs(ctx).AlertId(alertId).UserId(userId).Page(page).PerPage(perPage).All(all).StartTimestamp(startTimestamp).EndTimestamp(endTimestamp).Execute()

Get all alert logs



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
	alertId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The alert ID (optional)
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of the user to get logs for (optional)
	page := int32(56) // int32 | The page number to get (optional) (default to 1)
	perPage := int32(56) // int32 | The number of items per page (optional) (default to 10)
	all := true // bool | Whether to get all the alert logs (optional) (default to false)
	startTimestamp := int32(56) // int32 | Timestamp to start search from (optional)
	endTimestamp := int32(56) // int32 | Timestamp to end search at (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AlertsAPI.GetAllAlertLogs(context.Background()).AlertId(alertId).UserId(userId).Page(page).PerPage(perPage).All(all).StartTimestamp(startTimestamp).EndTimestamp(endTimestamp).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlertsAPI.GetAllAlertLogs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAllAlertLogs`: PaginatedResponseAlertLog
	fmt.Fprintf(os.Stdout, "Response from `AlertsAPI.GetAllAlertLogs`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetAllAlertLogsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **alertId** | **string** | The alert ID | 
 **userId** | **string** | The ID of the user to get logs for | 
 **page** | **int32** | The page number to get | [default to 1]
 **perPage** | **int32** | The number of items per page | [default to 10]
 **all** | **bool** | Whether to get all the alert logs | [default to false]
 **startTimestamp** | **int32** | Timestamp to start search from | 
 **endTimestamp** | **int32** | Timestamp to end search at | 

### Return type

[**PaginatedResponseAlertLog**](PaginatedResponseAlertLog.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PutAlert

> AlertResponse PutAlert(ctx, alertId).UpdateAlertRequest(updateAlertRequest).Execute()

Update an alert



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
	alertId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The alert ID
	updateAlertRequest := *openapiclient.NewUpdateAlertRequest() // UpdateAlertRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AlertsAPI.PutAlert(context.Background(), alertId).UpdateAlertRequest(updateAlertRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlertsAPI.PutAlert``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PutAlert`: AlertResponse
	fmt.Fprintf(os.Stdout, "Response from `AlertsAPI.PutAlert`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**alertId** | **string** | The alert ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiPutAlertRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateAlertRequest** | [**UpdateAlertRequest**](UpdateAlertRequest.md) |  | 

### Return type

[**AlertResponse**](AlertResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RunAlert

> AlertResponse RunAlert(ctx, alertId).UserId(userId).Execute()

Run an existing alert



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
	alertId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The alert ID
	userId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The ID of the user to get logs for (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AlertsAPI.RunAlert(context.Background(), alertId).UserId(userId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AlertsAPI.RunAlert``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RunAlert`: AlertResponse
	fmt.Fprintf(os.Stdout, "Response from `AlertsAPI.RunAlert`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**alertId** | **string** | The alert ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiRunAlertRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **userId** | **string** | The ID of the user to get logs for | 

### Return type

[**AlertResponse**](AlertResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

