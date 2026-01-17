# \NewsAPI

All URIs are relative to *https://api.asknews.dev*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetArticle**](NewsAPI.md#GetArticle) | **Get** /v1/news/{article_id} | Get an article by its UUID
[**GetArticles**](NewsAPI.md#GetArticles) | **Get** /v1/news | Get multiple articles by UUID
[**GetIndexCounts**](NewsAPI.md#GetIndexCounts) | **Get** /v1/index_counts | Get the index counts underlying AskNews
[**GetSourcesReport**](NewsAPI.md#GetSourcesReport) | **Get** /v1/sources | Get the sources underlying AskNews
[**SearchNews**](NewsAPI.md#SearchNews) | **Get** /v1/news/search | Search for enriched real-time news context



## GetArticle

> SearchResponseDictItem GetArticle(ctx, articleId).Execute()

Get an article by its UUID



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
	articleId := "articleId_example" // string | Article ID to retrieve

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NewsAPI.GetArticle(context.Background(), articleId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NewsAPI.GetArticle``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetArticle`: SearchResponseDictItem
	fmt.Fprintf(os.Stdout, "Response from `NewsAPI.GetArticle`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**articleId** | **string** | Article ID to retrieve | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetArticleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**SearchResponseDictItem**](SearchResponseDictItem.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetArticles

> []SearchResponseDictItem GetArticles(ctx).ArticleIds(articleIds).Execute()

Get multiple articles by UUID



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
	articleIds := []string{"Inner_example"} // []string | Article UUIDs to fetch.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NewsAPI.GetArticles(context.Background()).ArticleIds(articleIds).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NewsAPI.GetArticles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetArticles`: []SearchResponseDictItem
	fmt.Fprintf(os.Stdout, "Response from `NewsAPI.GetArticles`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetArticlesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **articleIds** | **[]string** | Article UUIDs to fetch. | 

### Return type

[**[]SearchResponseDictItem**](SearchResponseDictItem.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetIndexCounts

> []IndexCountItem GetIndexCounts(ctx).StartDatetime(startDatetime).EndDatetime(endDatetime).Domains(domains).Sampling(sampling).TimeFilter(timeFilter).Categories(categories).Provocative(provocative).ReportingVoice(reportingVoice).BadDomainUrl(badDomainUrl).PageRank(pageRank).StringGuarantee(stringGuarantee).StringGuaranteeOp(stringGuaranteeOp).ReverseStringGuarantee(reverseStringGuarantee).EntityGuarantee(entityGuarantee).EntityGuaranteeOp(entityGuaranteeOp).Languages(languages).Countries(countries).CountriesBlacklist(countriesBlacklist).Continents(continents).Sentiment(sentiment).Execute()

Get the index counts underlying AskNews



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
	startDatetime := time.Now() // time.Time | Start timestamp to filter by (optional)
	endDatetime := time.Now() // time.Time | End timestamp to filter by (optional)
	domains := []string{"Inner_example"} // []string | Domain or list of domains to get indexing counts for (optional)
	sampling := "sampling_example" // string | Sampling to use (optional) (default to "1d")
	timeFilter := "timeFilter_example" // string | Control which date type to filter on. 'crawl_date' is the date the article was crawled, 'pub_date' is the date the article was published. (optional) (default to "pub_date")
	categories := []string{"Categories_example"} // []string | Categories of news to filter on (optional)
	provocative := "provocative_example" // string | Filter articles based on how provocative they are deemed based on the use of provocative language and emotional vocabulary. (optional)
	reportingVoice := []string{"ReportingVoice_example"} // []string | Type of reporting voice to filer by. (optional)
	badDomainUrl := *openapiclient.NewBadDomainUrl1() // BadDomainUrl1 | blacklist of domains that must be excluded from resultsThis can be a single domain url or a list of domain urls. (optional)
	pageRank := int32(56) // int32 | maximum allowed pagerank for returned articles (optional)
	stringGuarantee := []string{"Inner_example"} // []string | If defined, the search will only occur on articles that contain this string. (optional)
	stringGuaranteeOp := "stringGuaranteeOp_example" // string | Operator to use for string guarantee. (optional) (default to "AND")
	reverseStringGuarantee := []string{"Inner_example"} // []string | If defined, the search will only occur on articles that do not contain this string. (optional)
	entityGuarantee := []string{"Inner_example"} // []string | Entity guarantee to filter by. This is a list of strings, where each string includes entity type and entity value separated by a colon. The first element is the entity type and the second element is the entity value. For example ['Location:Paris', 'Person:John'] (optional)
	entityGuaranteeOp := "entityGuaranteeOp_example" // string | Operator to use for entity guarantee. (optional) (default to "OR")
	languages := []string{"Languages_example"} // []string | Languages to filter by. This is the two-letter 'set 1' of the ISO 639-1 standard. For example: English is 'en'. (optional)
	countries := []string{"Inner_example"} // []string | Source countries to filter by (this is only for the publisher location, not the locations mentioned in articles. For Locations mentioned in articles, refer to entity_guarantee), countries must be the two-letter ISO country codeFor example: United States is 'US', France is 'FR', Sweden is 'SE'. (optional)
	countriesBlacklist := []string{"Inner_example"} // []string | Source countries to blacklist from search (this is only for the publisher location, not the locations mentioned in articles. For Locations mentioned in articles, refer to reverse_entity_guarantee), countries must be the two-letter ISO country codeFor example: United States is 'US', France is 'FR', Sweden is 'SE'. (optional)
	continents := []string{"Continents_example"} // []string | Continents to filter by (optional)
	sentiment := "sentiment_example" // string | Sentiment to filter news articles by. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NewsAPI.GetIndexCounts(context.Background()).StartDatetime(startDatetime).EndDatetime(endDatetime).Domains(domains).Sampling(sampling).TimeFilter(timeFilter).Categories(categories).Provocative(provocative).ReportingVoice(reportingVoice).BadDomainUrl(badDomainUrl).PageRank(pageRank).StringGuarantee(stringGuarantee).StringGuaranteeOp(stringGuaranteeOp).ReverseStringGuarantee(reverseStringGuarantee).EntityGuarantee(entityGuarantee).EntityGuaranteeOp(entityGuaranteeOp).Languages(languages).Countries(countries).CountriesBlacklist(countriesBlacklist).Continents(continents).Sentiment(sentiment).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NewsAPI.GetIndexCounts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetIndexCounts`: []IndexCountItem
	fmt.Fprintf(os.Stdout, "Response from `NewsAPI.GetIndexCounts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetIndexCountsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **startDatetime** | **time.Time** | Start timestamp to filter by | 
 **endDatetime** | **time.Time** | End timestamp to filter by | 
 **domains** | **[]string** | Domain or list of domains to get indexing counts for | 
 **sampling** | **string** | Sampling to use | [default to &quot;1d&quot;]
 **timeFilter** | **string** | Control which date type to filter on. &#39;crawl_date&#39; is the date the article was crawled, &#39;pub_date&#39; is the date the article was published. | [default to &quot;pub_date&quot;]
 **categories** | **[]string** | Categories of news to filter on | 
 **provocative** | **string** | Filter articles based on how provocative they are deemed based on the use of provocative language and emotional vocabulary. | 
 **reportingVoice** | **[]string** | Type of reporting voice to filer by. | 
 **badDomainUrl** | [**BadDomainUrl1**](BadDomainUrl1.md) | blacklist of domains that must be excluded from resultsThis can be a single domain url or a list of domain urls. | 
 **pageRank** | **int32** | maximum allowed pagerank for returned articles | 
 **stringGuarantee** | **[]string** | If defined, the search will only occur on articles that contain this string. | 
 **stringGuaranteeOp** | **string** | Operator to use for string guarantee. | [default to &quot;AND&quot;]
 **reverseStringGuarantee** | **[]string** | If defined, the search will only occur on articles that do not contain this string. | 
 **entityGuarantee** | **[]string** | Entity guarantee to filter by. This is a list of strings, where each string includes entity type and entity value separated by a colon. The first element is the entity type and the second element is the entity value. For example [&#39;Location:Paris&#39;, &#39;Person:John&#39;] | 
 **entityGuaranteeOp** | **string** | Operator to use for entity guarantee. | [default to &quot;OR&quot;]
 **languages** | **[]string** | Languages to filter by. This is the two-letter &#39;set 1&#39; of the ISO 639-1 standard. For example: English is &#39;en&#39;. | 
 **countries** | **[]string** | Source countries to filter by (this is only for the publisher location, not the locations mentioned in articles. For Locations mentioned in articles, refer to entity_guarantee), countries must be the two-letter ISO country codeFor example: United States is &#39;US&#39;, France is &#39;FR&#39;, Sweden is &#39;SE&#39;. | 
 **countriesBlacklist** | **[]string** | Source countries to blacklist from search (this is only for the publisher location, not the locations mentioned in articles. For Locations mentioned in articles, refer to reverse_entity_guarantee), countries must be the two-letter ISO country codeFor example: United States is &#39;US&#39;, France is &#39;FR&#39;, Sweden is &#39;SE&#39;. | 
 **continents** | **[]string** | Continents to filter by | 
 **sentiment** | **string** | Sentiment to filter news articles by. | 

### Return type

[**[]IndexCountItem**](IndexCountItem.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetSourcesReport

> []SourceReportItem GetSourcesReport(ctx).NPoints(nPoints).StartTimestamp(startTimestamp).EndTimestamp(endTimestamp).Metric(metric).Sampling(sampling).Execute()

Get the sources underlying AskNews



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
	nPoints := int32(56) // int32 | Number of points to return (optional) (default to 100)
	startTimestamp := int32(56) // int32 | Start timestamp to filter by (optional)
	endTimestamp := int32(56) // int32 | End timestamp to filter by (optional)
	metric := "metric_example" // string | Metric to filter by (optional) (default to "countries_diversity")
	sampling := "sampling_example" // string | Sampling to use (optional) (default to "1h")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NewsAPI.GetSourcesReport(context.Background()).NPoints(nPoints).StartTimestamp(startTimestamp).EndTimestamp(endTimestamp).Metric(metric).Sampling(sampling).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NewsAPI.GetSourcesReport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetSourcesReport`: []SourceReportItem
	fmt.Fprintf(os.Stdout, "Response from `NewsAPI.GetSourcesReport`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetSourcesReportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **nPoints** | **int32** | Number of points to return | [default to 100]
 **startTimestamp** | **int32** | Start timestamp to filter by | 
 **endTimestamp** | **int32** | End timestamp to filter by | 
 **metric** | **string** | Metric to filter by | [default to &quot;countries_diversity&quot;]
 **sampling** | **string** | Sampling to use | [default to &quot;1h&quot;]

### Return type

[**[]SourceReportItem**](SourceReportItem.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchNews

> SearchResponse SearchNews(ctx).Query(query).NArticles(nArticles).StartTimestamp(startTimestamp).EndTimestamp(endTimestamp).TimeFilter(timeFilter).ReturnType(returnType).Historical(historical).Method(method).SimilarityScoreThreshold(similarityScoreThreshold).Offset(offset).Categories(categories).DocStartDelimiter(docStartDelimiter).DocEndDelimiter(docEndDelimiter).Provocative(provocative).ReportingVoice(reportingVoice).DomainUrl(domainUrl).BadDomainUrl(badDomainUrl).PageRank(pageRank).DiversifySources(diversifySources).Strategy(strategy).HoursBack(hoursBack).StringGuarantee(stringGuarantee).StringGuaranteeOp(stringGuaranteeOp).ReverseStringGuarantee(reverseStringGuarantee).EntityGuarantee(entityGuarantee).ReverseEntityGuarantee(reverseEntityGuarantee).EntityGuaranteeOp(entityGuaranteeOp).ReturnGraphs(returnGraphs).ReturnGeo(returnGeo).Languages(languages).Countries(countries).CountriesBlacklist(countriesBlacklist).Continents(continents).Sentiment(sentiment).Premium(premium).Authors(authors).Execute()

Search for enriched real-time news context



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
	query := "query_example" // string | Query string that can be any phrase, keyword, question, or paragraph. If method='nl', then this will be used as a natural language query. If method='kw', then this will be used as a direct keyword query. This is not required, if it is not passed, then the search is based on the remaining filters only. (optional) (default to "")
	nArticles := int32(56) // int32 | Number of articles to return (optional) (default to 10)
	startTimestamp := int32(56) // int32 | Timestamp to start search from (optional)
	endTimestamp := int32(56) // int32 | Timestamp to end search at (optional)
	timeFilter := "timeFilter_example" // string | Control which date type to filter on. 'crawl_date' is the date the article was crawled, 'pub_date' is the date the article was published. (optional) (default to "crawl_date")
	returnType := "returnType_example" // string | Type of return value. 'string' means that the return is prompt-optimized and ready to be immediately injected into any prompt. 'dicts' means that the return is a structured dictionary, containing additional metadata (like a classic news api). Can be 'string' or 'dicts', or 'both'. 'string' guarantees the lowest-latency response 'dicts' requires more I/O, therefore increases latency (very slightly, depending on your network connection). (optional) (default to "dicts")
	historical := true // bool | Search on archive of historical news. Defaults to False, meaning that the search will only look through the most recent news (48 hours) (optional) (default to false)
	method := "method_example" // string | Method to use for searching. 'nl' means Natural Language, which is a string that can be any phrase, keyword, question, or paragraph that will be used for semantic search on the news. 'kw' means Keyword, which can also be any keyword(s), phrase, or paragraph, however the search is a direct keyword search on the database. 'both' means both methods will be used and results will be ranked according to IRR. 'both' may reduce latency by 10 pct in exchange  for improved accuracy. (optional) (default to "kw")
	similarityScoreThreshold := float32(8.14) // float32 | Similarity score threshold to determine which articles to return. Lower means less similar results  are allowed. (optional) (default to 0.5)
	offset := *openapiclient.NewOffset() // Offset | Offset for pagination. The n_articles is your page size, while your offset is the number of articles to skip to get to your page of interest. For example, if you want to get page 3 for n_article page size of 10, you would set offset to 20. (optional) (default to 0)
	categories := []string{"Categories_example"} // []string | Categories of news to filter on (optional)
	docStartDelimiter := "docStartDelimiter_example" // string | Document start delimiter for string return. (optional) (default to "<doc>")
	docEndDelimiter := "docEndDelimiter_example" // string | Document end delimiter for string return. (optional) (default to "</doc>")
	provocative := "provocative_example" // string | Filter articles based on how provocative they are deemed based on the use of provocative language and emotional vocabulary. (optional)
	reportingVoice := *openapiclient.NewReportingVoice() // ReportingVoice | Type of reporting voice to filer by. (optional)
	domainUrl := *openapiclient.NewDomainUrl() // DomainUrl | filter by domain url of interest. This can be a single domain or a list of domains. For example, 'npr.org' or ['nature.com', 'npr.org'] (optional)
	badDomainUrl := *openapiclient.NewBadDomainUrl() // BadDomainUrl | blacklist of domains that must be excluded from resultsThis can be a single domain url or a list of domain urls. (optional)
	pageRank := int32(56) // int32 | Maximum allowed page rank for returned articles. (optional)
	diversifySources := true // bool | Ensure that the return set of articles are selected from diverse sources. This adds latency to the search, but attempts to balance the representation of sources by country and source origins. In summary, a net is cast around your search, then the diversity of sources is analyzed, and your final result matches the large net diversity distribution. This means that your search accuracy is reduced, but you gain more diverse perspectives. (optional) (default to false)
	strategy := "strategy_example" // string | Strategy to use for searching. 'latest news' automatically setsmethod='nl', historical=False, and looks within the past 24 hours. 'news knowledge' automatically sets method='kw', historical=True, and looks within the past 60 days. 'news knowledge' will increase latency due to the  larger search space in the archive. Use 'default' if you want to control  start_timestamp, end_timestamp, historical, and method. (optional) (default to "default")
	hoursBack := int32(56) // int32 | Can be set to easily control the look back on the search. This is the same as controlling the 'start_timestamp' parameter. The difference is that this is not a timestamp, it is the number of hours back to look from the current time. Defaults to 24 hours. (optional) (default to 24)
	stringGuarantee := []string{"Inner_example"} // []string | If defined, the search will only occur on articles that contain strings in this list. (optional)
	stringGuaranteeOp := "stringGuaranteeOp_example" // string | Operator to use for string guarantee list. (optional) (default to "AND")
	reverseStringGuarantee := []string{"Inner_example"} // []string | If defined, the search will only occur on articles that do not contain strings in this list. (optional)
	entityGuarantee := []string{"Inner_example"} // []string | Entity guarantee to filter by. This is a list of strings, where each string includes entity type and entity value separated by a colon. The first element is the entity type and the second element is the entity value. For example ['Location:Paris', 'Person:John'] (optional)
	reverseEntityGuarantee := []string{"Inner_example"} // []string | Reverse entity guarantee to filter by. This is a list of strings, where each string includes entity type and entity value separated by a colon. The first element is the entity type and the second element is the entity value. For example ['Location:Paris', 'Person:John'] (optional)
	entityGuaranteeOp := "entityGuaranteeOp_example" // string | Operator to use for entity guarantee list. (optional) (default to "OR")
	returnGraphs := true // bool | Return graphs for the articles. Only available to Analyst tier and above. (optional) (default to false)
	returnGeo := true // bool | Return GeoCoordinates associated with locations discussed  inside the articles. Only available to Analyst tier and above. (optional) (default to false)
	languages := []string{"Languages_example"} // []string | Languages to filter by. This is the two-letter 'set 1' of the ISO 639-1 standard. For example: English is 'en'. (optional)
	countries := []string{"Inner_example"} // []string | Source countries to filter by (this is only for the publisher location, not the locations mentioned in articles. For Locations mentioned in articles, refer to entity_guarantee), countries must be the two-letter ISO country codeFor example: United States is 'US', France is 'FR', Sweden is 'SE'. (optional)
	countriesBlacklist := []string{"Inner_example"} // []string | Source countries to blacklist from search (this is only for the publisher location, not the locations mentioned in articles. For Locations mentioned in articles, refer to reverse_entity_guarantee), countries must be the two-letter ISO country codeFor example: United States is 'US', France is 'FR', Sweden is 'SE'. (optional)
	continents := []string{"Continents_example"} // []string | Continents to filter by. (optional)
	sentiment := "sentiment_example" // string | Sentiment to filter articles by. (optional)
	premium := true // bool | Include premium sources. (optional) (default to false)
	authors := []string{"Inner_example"} // []string | Authors to filter articles by. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NewsAPI.SearchNews(context.Background()).Query(query).NArticles(nArticles).StartTimestamp(startTimestamp).EndTimestamp(endTimestamp).TimeFilter(timeFilter).ReturnType(returnType).Historical(historical).Method(method).SimilarityScoreThreshold(similarityScoreThreshold).Offset(offset).Categories(categories).DocStartDelimiter(docStartDelimiter).DocEndDelimiter(docEndDelimiter).Provocative(provocative).ReportingVoice(reportingVoice).DomainUrl(domainUrl).BadDomainUrl(badDomainUrl).PageRank(pageRank).DiversifySources(diversifySources).Strategy(strategy).HoursBack(hoursBack).StringGuarantee(stringGuarantee).StringGuaranteeOp(stringGuaranteeOp).ReverseStringGuarantee(reverseStringGuarantee).EntityGuarantee(entityGuarantee).ReverseEntityGuarantee(reverseEntityGuarantee).EntityGuaranteeOp(entityGuaranteeOp).ReturnGraphs(returnGraphs).ReturnGeo(returnGeo).Languages(languages).Countries(countries).CountriesBlacklist(countriesBlacklist).Continents(continents).Sentiment(sentiment).Premium(premium).Authors(authors).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NewsAPI.SearchNews``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchNews`: SearchResponse
	fmt.Fprintf(os.Stdout, "Response from `NewsAPI.SearchNews`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchNewsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **query** | **string** | Query string that can be any phrase, keyword, question, or paragraph. If method&#x3D;&#39;nl&#39;, then this will be used as a natural language query. If method&#x3D;&#39;kw&#39;, then this will be used as a direct keyword query. This is not required, if it is not passed, then the search is based on the remaining filters only. | [default to &quot;&quot;]
 **nArticles** | **int32** | Number of articles to return | [default to 10]
 **startTimestamp** | **int32** | Timestamp to start search from | 
 **endTimestamp** | **int32** | Timestamp to end search at | 
 **timeFilter** | **string** | Control which date type to filter on. &#39;crawl_date&#39; is the date the article was crawled, &#39;pub_date&#39; is the date the article was published. | [default to &quot;crawl_date&quot;]
 **returnType** | **string** | Type of return value. &#39;string&#39; means that the return is prompt-optimized and ready to be immediately injected into any prompt. &#39;dicts&#39; means that the return is a structured dictionary, containing additional metadata (like a classic news api). Can be &#39;string&#39; or &#39;dicts&#39;, or &#39;both&#39;. &#39;string&#39; guarantees the lowest-latency response &#39;dicts&#39; requires more I/O, therefore increases latency (very slightly, depending on your network connection). | [default to &quot;dicts&quot;]
 **historical** | **bool** | Search on archive of historical news. Defaults to False, meaning that the search will only look through the most recent news (48 hours) | [default to false]
 **method** | **string** | Method to use for searching. &#39;nl&#39; means Natural Language, which is a string that can be any phrase, keyword, question, or paragraph that will be used for semantic search on the news. &#39;kw&#39; means Keyword, which can also be any keyword(s), phrase, or paragraph, however the search is a direct keyword search on the database. &#39;both&#39; means both methods will be used and results will be ranked according to IRR. &#39;both&#39; may reduce latency by 10 pct in exchange  for improved accuracy. | [default to &quot;kw&quot;]
 **similarityScoreThreshold** | **float32** | Similarity score threshold to determine which articles to return. Lower means less similar results  are allowed. | [default to 0.5]
 **offset** | [**Offset**](Offset.md) | Offset for pagination. The n_articles is your page size, while your offset is the number of articles to skip to get to your page of interest. For example, if you want to get page 3 for n_article page size of 10, you would set offset to 20. | [default to 0]
 **categories** | **[]string** | Categories of news to filter on | 
 **docStartDelimiter** | **string** | Document start delimiter for string return. | [default to &quot;&lt;doc&gt;&quot;]
 **docEndDelimiter** | **string** | Document end delimiter for string return. | [default to &quot;&lt;/doc&gt;&quot;]
 **provocative** | **string** | Filter articles based on how provocative they are deemed based on the use of provocative language and emotional vocabulary. | 
 **reportingVoice** | [**ReportingVoice**](ReportingVoice.md) | Type of reporting voice to filer by. | 
 **domainUrl** | [**DomainUrl**](DomainUrl.md) | filter by domain url of interest. This can be a single domain or a list of domains. For example, &#39;npr.org&#39; or [&#39;nature.com&#39;, &#39;npr.org&#39;] | 
 **badDomainUrl** | [**BadDomainUrl**](BadDomainUrl.md) | blacklist of domains that must be excluded from resultsThis can be a single domain url or a list of domain urls. | 
 **pageRank** | **int32** | Maximum allowed page rank for returned articles. | 
 **diversifySources** | **bool** | Ensure that the return set of articles are selected from diverse sources. This adds latency to the search, but attempts to balance the representation of sources by country and source origins. In summary, a net is cast around your search, then the diversity of sources is analyzed, and your final result matches the large net diversity distribution. This means that your search accuracy is reduced, but you gain more diverse perspectives. | [default to false]
 **strategy** | **string** | Strategy to use for searching. &#39;latest news&#39; automatically setsmethod&#x3D;&#39;nl&#39;, historical&#x3D;False, and looks within the past 24 hours. &#39;news knowledge&#39; automatically sets method&#x3D;&#39;kw&#39;, historical&#x3D;True, and looks within the past 60 days. &#39;news knowledge&#39; will increase latency due to the  larger search space in the archive. Use &#39;default&#39; if you want to control  start_timestamp, end_timestamp, historical, and method. | [default to &quot;default&quot;]
 **hoursBack** | **int32** | Can be set to easily control the look back on the search. This is the same as controlling the &#39;start_timestamp&#39; parameter. The difference is that this is not a timestamp, it is the number of hours back to look from the current time. Defaults to 24 hours. | [default to 24]
 **stringGuarantee** | **[]string** | If defined, the search will only occur on articles that contain strings in this list. | 
 **stringGuaranteeOp** | **string** | Operator to use for string guarantee list. | [default to &quot;AND&quot;]
 **reverseStringGuarantee** | **[]string** | If defined, the search will only occur on articles that do not contain strings in this list. | 
 **entityGuarantee** | **[]string** | Entity guarantee to filter by. This is a list of strings, where each string includes entity type and entity value separated by a colon. The first element is the entity type and the second element is the entity value. For example [&#39;Location:Paris&#39;, &#39;Person:John&#39;] | 
 **reverseEntityGuarantee** | **[]string** | Reverse entity guarantee to filter by. This is a list of strings, where each string includes entity type and entity value separated by a colon. The first element is the entity type and the second element is the entity value. For example [&#39;Location:Paris&#39;, &#39;Person:John&#39;] | 
 **entityGuaranteeOp** | **string** | Operator to use for entity guarantee list. | [default to &quot;OR&quot;]
 **returnGraphs** | **bool** | Return graphs for the articles. Only available to Analyst tier and above. | [default to false]
 **returnGeo** | **bool** | Return GeoCoordinates associated with locations discussed  inside the articles. Only available to Analyst tier and above. | [default to false]
 **languages** | **[]string** | Languages to filter by. This is the two-letter &#39;set 1&#39; of the ISO 639-1 standard. For example: English is &#39;en&#39;. | 
 **countries** | **[]string** | Source countries to filter by (this is only for the publisher location, not the locations mentioned in articles. For Locations mentioned in articles, refer to entity_guarantee), countries must be the two-letter ISO country codeFor example: United States is &#39;US&#39;, France is &#39;FR&#39;, Sweden is &#39;SE&#39;. | 
 **countriesBlacklist** | **[]string** | Source countries to blacklist from search (this is only for the publisher location, not the locations mentioned in articles. For Locations mentioned in articles, refer to reverse_entity_guarantee), countries must be the two-letter ISO country codeFor example: United States is &#39;US&#39;, France is &#39;FR&#39;, Sweden is &#39;SE&#39;. | 
 **continents** | **[]string** | Continents to filter by. | 
 **sentiment** | **string** | Sentiment to filter articles by. | 
 **premium** | **bool** | Include premium sources. | [default to false]
 **authors** | **[]string** | Authors to filter articles by. | 

### Return type

[**SearchResponse**](SearchResponse.md)

### Authorization

[APIKey](../README.md#APIKey)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

