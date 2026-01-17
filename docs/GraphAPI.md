# \GraphAPI

All URIs are relative to *https://api.asknews.app*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BuildGraph**](GraphAPI.md#BuildGraph) | **Post** /v1/news/graph | Build a custom mega-news-knowledge graph



## BuildGraph

> GraphResponse BuildGraph(ctx).BodyBuildGraph(bodyBuildGraph).Execute()

Build a custom mega-news-knowledge graph



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
	bodyBuildGraph := *openapiclient.NewBodyBuildGraph() // BodyBuildGraph |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GraphAPI.BuildGraph(context.Background()).BodyBuildGraph(bodyBuildGraph).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GraphAPI.BuildGraph``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BuildGraph`: GraphResponse
	fmt.Fprintf(os.Stdout, "Response from `GraphAPI.BuildGraph`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBuildGraphRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **bodyBuildGraph** | [**BodyBuildGraph**](BodyBuildGraph.md) |  | 

### Return type

[**GraphResponse**](GraphResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

