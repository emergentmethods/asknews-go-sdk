# \DistributionAPI

All URIs are relative to *https://api.asknews.app*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DomainHitShare**](DistributionAPI.md#DomainHitShare) | **Get** /v1/distribution/stats/hit_share | Get the hit share for a list of domains in a time period
[**FindDomains**](DistributionAPI.md#FindDomains) | **Get** /v1/distribution/domains | Find domains
[**GetArticleHits**](DistributionAPI.md#GetArticleHits) | **Get** /v1/distribution/stats/count | Get article hits
[**GetDomain**](DistributionAPI.md#GetDomain) | **Get** /v1/distribution/domains/{name} | Get a domain by name
[**GetDomainQueries**](DistributionAPI.md#GetDomainQueries) | **Get** /v1/distribution/articles/domain_queries | Get queries that surfaced domain articles
[**TopNArticlesByHits**](DistributionAPI.md#TopNArticlesByHits) | **Get** /v1/distribution/articles/top_n | Get the top N articles by hits
[**TopNArticlesForDomain**](DistributionAPI.md#TopNArticlesForDomain) | **Get** /v1/distribution/articles/top_n_for_domain | Get the top N articles by hits for domain
[**TopNArticlesForDomainTimeseries**](DistributionAPI.md#TopNArticlesForDomainTimeseries) | **Get** /v1/distribution/articles/top_n_for_domain_timeseries | Get the top N articles by hits for domain with daily breakdown
[**TopNDomainsByHits**](DistributionAPI.md#TopNDomainsByHits) | **Get** /v1/distribution/domains/top_n | Get the top N domains by hits
[**UpdateDomain**](DistributionAPI.md#UpdateDomain) | **Put** /v1/distribution/domains/{name} | Update an existing domain



## DomainHitShare

> HitShareResponse DomainHitShare(ctx).DomainNames(domainNames).StartDate(startDate).EndDate(endDate).IsPublisher(isPublisher).Execute()

Get the hit share for a list of domains in a time period



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
	domainNames := []string{"Inner_example"} // []string | Domain names to filter by
	startDate := int32(56) // int32 | Start date to filter by (timestamp in seconds since epoch) (optional)
	endDate := int32(56) // int32 | End date to filter by (timestamp in seconds since epoch) (optional)
	isPublisher := true // bool | Only calculate hit share for publisher domains (optional) (default to true)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DistributionAPI.DomainHitShare(context.Background()).DomainNames(domainNames).StartDate(startDate).EndDate(endDate).IsPublisher(isPublisher).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DistributionAPI.DomainHitShare``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DomainHitShare`: HitShareResponse
	fmt.Fprintf(os.Stdout, "Response from `DistributionAPI.DomainHitShare`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDomainHitShareRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **domainNames** | **[]string** | Domain names to filter by | 
 **startDate** | **int32** | Start date to filter by (timestamp in seconds since epoch) | 
 **endDate** | **int32** | End date to filter by (timestamp in seconds since epoch) | 
 **isPublisher** | **bool** | Only calculate hit share for publisher domains | [default to true]

### Return type

[**HitShareResponse**](HitShareResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FindDomains

> PaginatedResponseReadDomainResponse FindDomains(ctx).Page(page).PerPage(perPage).Names(names).IsTollbit(isTollbit).Publisher(publisher).Execute()

Find domains



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
	page := int32(56) // int32 | Page number for pagination (optional) (default to 1)
	perPage := int32(56) // int32 | Number of items per page (optional) (default to 10)
	names := []string{"Inner_example"} // []string | List of domain names to filter by (optional)
	isTollbit := true // bool | Filter by tollbit status (optional)
	publisher := true // bool | Filter by publisher status (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DistributionAPI.FindDomains(context.Background()).Page(page).PerPage(perPage).Names(names).IsTollbit(isTollbit).Publisher(publisher).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DistributionAPI.FindDomains``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FindDomains`: PaginatedResponseReadDomainResponse
	fmt.Fprintf(os.Stdout, "Response from `DistributionAPI.FindDomains`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFindDomainsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** | Page number for pagination | [default to 1]
 **perPage** | **int32** | Number of items per page | [default to 10]
 **names** | **[]string** | List of domain names to filter by | 
 **isTollbit** | **bool** | Filter by tollbit status | 
 **publisher** | **bool** | Filter by publisher status | 

### Return type

[**PaginatedResponseReadDomainResponse**](PaginatedResponseReadDomainResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetArticleHits

> CountResponse GetArticleHits(ctx).DomainName(domainName).StartDate(startDate).EndDate(endDate).Execute()

Get article hits



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
	domainName := "domainName_example" // string | Domain name to filter by
	startDate := int32(56) // int32 | Start date to filter by (timestamp in seconds since epoch) (optional)
	endDate := int32(56) // int32 | End date to filter by (timestamp in seconds since epoch) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DistributionAPI.GetArticleHits(context.Background()).DomainName(domainName).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DistributionAPI.GetArticleHits``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetArticleHits`: CountResponse
	fmt.Fprintf(os.Stdout, "Response from `DistributionAPI.GetArticleHits`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetArticleHitsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **domainName** | **string** | Domain name to filter by | 
 **startDate** | **int32** | Start date to filter by (timestamp in seconds since epoch) | 
 **endDate** | **int32** | End date to filter by (timestamp in seconds since epoch) | 

### Return type

[**CountResponse**](CountResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDomain

> ReadDomainResponse GetDomain(ctx, name).Execute()

Get a domain by name



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
	name := "name_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DistributionAPI.GetDomain(context.Background(), name).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DistributionAPI.GetDomain``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDomain`: ReadDomainResponse
	fmt.Fprintf(os.Stdout, "Response from `DistributionAPI.GetDomain`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**name** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDomainRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ReadDomainResponse**](ReadDomainResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDomainQueries

> DomainQueriesResponse GetDomainQueries(ctx).DomainNames(domainNames).Limit(limit).StartDate(startDate).EndDate(endDate).Execute()

Get queries that surfaced domain articles



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
	domainNames := []*string{"Inner_example"} // []*string | Domain names to filter by
	limit := int32(56) // int32 | Limit for the number of articles (optional) (default to 10)
	startDate := int32(56) // int32 | Start date to filter by (optional)
	endDate := int32(56) // int32 | End date to filter by (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DistributionAPI.GetDomainQueries(context.Background()).DomainNames(domainNames).Limit(limit).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DistributionAPI.GetDomainQueries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDomainQueries`: DomainQueriesResponse
	fmt.Fprintf(os.Stdout, "Response from `DistributionAPI.GetDomainQueries`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetDomainQueriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **domainNames** | **[]string** | Domain names to filter by | 
 **limit** | **int32** | Limit for the number of articles | [default to 10]
 **startDate** | **int32** | Start date to filter by | 
 **endDate** | **int32** | End date to filter by | 

### Return type

[**DomainQueriesResponse**](DomainQueriesResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TopNArticlesByHits

> TopNArticlesByHitsResponse TopNArticlesByHits(ctx).Limit(limit).StartDate(startDate).EndDate(endDate).DomainNames(domainNames).Execute()

Get the top N articles by hits



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
	limit := int32(56) // int32 | Number of top domains to return (optional) (default to 10)
	startDate := int32(56) // int32 | Start date to filter by (timestamp in seconds since epoch) (optional)
	endDate := int32(56) // int32 | End date to filter by (timestamp in seconds since epoch) (optional)
	domainNames := []string{"Inner_example"} // []string | List of domain names to filter by (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DistributionAPI.TopNArticlesByHits(context.Background()).Limit(limit).StartDate(startDate).EndDate(endDate).DomainNames(domainNames).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DistributionAPI.TopNArticlesByHits``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TopNArticlesByHits`: TopNArticlesByHitsResponse
	fmt.Fprintf(os.Stdout, "Response from `DistributionAPI.TopNArticlesByHits`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTopNArticlesByHitsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** | Number of top domains to return | [default to 10]
 **startDate** | **int32** | Start date to filter by (timestamp in seconds since epoch) | 
 **endDate** | **int32** | End date to filter by (timestamp in seconds since epoch) | 
 **domainNames** | **[]string** | List of domain names to filter by | 

### Return type

[**TopNArticlesByHitsResponse**](TopNArticlesByHitsResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TopNArticlesForDomain

> TopNArticlesForDomainResponse TopNArticlesForDomain(ctx).DomainName(domainName).Limit(limit).StartDate(startDate).EndDate(endDate).Execute()

Get the top N articles by hits for domain



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
	domainName := "domainName_example" // string | Domain name to filter by
	limit := int32(56) // int32 | Number of top domain articles to return (optional) (default to 10)
	startDate := int32(56) // int32 | Start date to filter by (timestamp in seconds since epoch) (optional)
	endDate := int32(56) // int32 | End date to filter by (timestamp in seconds since epoch) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DistributionAPI.TopNArticlesForDomain(context.Background()).DomainName(domainName).Limit(limit).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DistributionAPI.TopNArticlesForDomain``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TopNArticlesForDomain`: TopNArticlesForDomainResponse
	fmt.Fprintf(os.Stdout, "Response from `DistributionAPI.TopNArticlesForDomain`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTopNArticlesForDomainRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **domainName** | **string** | Domain name to filter by | 
 **limit** | **int32** | Number of top domain articles to return | [default to 10]
 **startDate** | **int32** | Start date to filter by (timestamp in seconds since epoch) | 
 **endDate** | **int32** | End date to filter by (timestamp in seconds since epoch) | 

### Return type

[**TopNArticlesForDomainResponse**](TopNArticlesForDomainResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TopNArticlesForDomainTimeseries

> TopNArticlesTimeseriesResponse TopNArticlesForDomainTimeseries(ctx).DomainName(domainName).Limit(limit).StartDate(startDate).EndDate(endDate).Execute()

Get the top N articles by hits for domain with daily breakdown



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
	domainName := "domainName_example" // string | Domain name to filter by
	limit := int32(56) // int32 | Number of top domain articles to return per day (optional) (default to 10)
	startDate := int32(56) // int32 | Start date to filter by (timestamp in seconds since epoch) (optional)
	endDate := int32(56) // int32 | End date to filter by (timestamp in seconds since epoch) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DistributionAPI.TopNArticlesForDomainTimeseries(context.Background()).DomainName(domainName).Limit(limit).StartDate(startDate).EndDate(endDate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DistributionAPI.TopNArticlesForDomainTimeseries``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TopNArticlesForDomainTimeseries`: TopNArticlesTimeseriesResponse
	fmt.Fprintf(os.Stdout, "Response from `DistributionAPI.TopNArticlesForDomainTimeseries`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTopNArticlesForDomainTimeseriesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **domainName** | **string** | Domain name to filter by | 
 **limit** | **int32** | Number of top domain articles to return per day | [default to 10]
 **startDate** | **int32** | Start date to filter by (timestamp in seconds since epoch) | 
 **endDate** | **int32** | End date to filter by (timestamp in seconds since epoch) | 

### Return type

[**TopNArticlesTimeseriesResponse**](TopNArticlesTimeseriesResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## TopNDomainsByHits

> TopNDomainsByHitsResponse TopNDomainsByHits(ctx).Limit(limit).StartDate(startDate).EndDate(endDate).Names(names).Execute()

Get the top N domains by hits



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
	limit := int32(56) // int32 | Number of top domains to return (optional) (default to 10)
	startDate := int32(56) // int32 | Start date to filter by (timestamp in seconds since epoch) (optional)
	endDate := int32(56) // int32 | End date to filter by (timestamp in seconds since epoch) (optional)
	names := []string{"Inner_example"} // []string | List of domain names to filter by (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DistributionAPI.TopNDomainsByHits(context.Background()).Limit(limit).StartDate(startDate).EndDate(endDate).Names(names).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DistributionAPI.TopNDomainsByHits``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TopNDomainsByHits`: TopNDomainsByHitsResponse
	fmt.Fprintf(os.Stdout, "Response from `DistributionAPI.TopNDomainsByHits`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTopNDomainsByHitsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** | Number of top domains to return | [default to 10]
 **startDate** | **int32** | Start date to filter by (timestamp in seconds since epoch) | 
 **endDate** | **int32** | End date to filter by (timestamp in seconds since epoch) | 
 **names** | **[]string** | List of domain names to filter by | 

### Return type

[**TopNDomainsByHitsResponse**](TopNDomainsByHitsResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateDomain

> ReadDomainResponse UpdateDomain(ctx, name).UpdateDomainRequest(updateDomainRequest).Execute()

Update an existing domain



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
	name := "name_example" // string | 
	updateDomainRequest := *openapiclient.NewUpdateDomainRequest() // UpdateDomainRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DistributionAPI.UpdateDomain(context.Background(), name).UpdateDomainRequest(updateDomainRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DistributionAPI.UpdateDomain``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateDomain`: ReadDomainResponse
	fmt.Fprintf(os.Stdout, "Response from `DistributionAPI.UpdateDomain`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**name** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateDomainRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **updateDomainRequest** | [**UpdateDomainRequest**](UpdateDomainRequest.md) |  | 

### Return type

[**ReadDomainResponse**](ReadDomainResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

