# CreateDeepNewsRequestFilterParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Query** | Pointer to **string** | Query string that can be any phrase, keyword, question, or paragraph. If method&#x3D;&#39;nl&#39;, then this will be used as a natural language query. If method&#x3D;&#39;kw&#39;, then this will be used as a direct keyword query. This is not required, if it is not passed, then the search is based on the remaining filters only. | [optional] [default to ""]
**NArticles** | Pointer to **int32** | Number of articles to return | [optional] [default to 10]
**StartTimestamp** | Pointer to **int32** |  | [optional] 
**EndTimestamp** | Pointer to **int32** |  | [optional] 
**TimeFilter** | Pointer to **string** | Control which date type to filter on. &#39;crawl_date&#39; is the date the article was crawled, &#39;pub_date&#39; is the date the article was published. | [optional] [default to "crawl_date"]
**ReturnType** | Pointer to **string** | Type of return value. &#39;string&#39; means that the return is prompt-optimized and ready to be immediately injected into any prompt. &#39;dicts&#39; means that the return is a structured dictionary, containing additional metadata (like a classic news api). Can be &#39;string&#39; or &#39;dicts&#39;, or &#39;both&#39;. &#39;string&#39; guarantees the lowest-latency response &#39;dicts&#39; requires more I/O, therefore increases latency (very slightly, depending on your network connection). | [optional] [default to "dicts"]
**Historical** | Pointer to **bool** | Search on archive of historical news. Defaults to False, meaning that the search will only look through the most recent news (48 hours) | [optional] [default to false]
**Method** | Pointer to **string** | Method to use for searching. &#39;nl&#39; means Natural Language, which is a string that can be any phrase, keyword, question, or paragraph that will be used for semantic search on the news. &#39;kw&#39; means Keyword, which can also be any keyword(s), phrase, or paragraph, however the search is a direct keyword search on the database. &#39;both&#39; means both methods will be used and results will be ranked according to IRR. &#39;both&#39; may reduce latency by 10 pct in exchange  for improved accuracy. | [optional] [default to "kw"]
**SimilarityScoreThreshold** | Pointer to **float32** | Similarity score threshold to determine which articles to return. Lower means less similar results  are allowed. | [optional] [default to 0.5]
**Offset** | Pointer to [**Offset2**](Offset2.md) |  | [optional] [default to 0]
**Categories** | Pointer to **[]string** | Categories of news to filter on | [optional] [default to [All]]
**DocStartDelimiter** | Pointer to **string** | Document start delimiter for string return. | [optional] [default to "<doc>"]
**DocEndDelimiter** | Pointer to **string** | Document end delimiter for string return. | [optional] [default to "</doc>"]
**Provocative** | Pointer to **string** | Filter articles based on how provocative they are deemed based on the use of provocative language and emotional vocabulary. | [optional] [default to "all"]
**ReportingVoice** | Pointer to [**ReportingVoice2**](ReportingVoice2.md) |  | [optional] [default to [all]]
**DomainUrl** | Pointer to [**NullableDomainUrl1**](DomainUrl1.md) |  | [optional] 
**BadDomainUrl** | Pointer to [**NullableBadDomainUrl2**](BadDomainUrl2.md) |  | [optional] 
**PageRank** | Pointer to **int32** |  | [optional] 
**DiversifySources** | Pointer to **bool** | Ensure that the return set of articles are selected from diverse sources. This adds latency to the search, but attempts to balance the representation of sources by country and source origins. In summary, a net is cast around your search, then the diversity of sources is analyzed, and your final result matches the large net diversity distribution. This means that your search accuracy is reduced, but you gain more diverse perspectives. | [optional] [default to false]
**Strategy** | Pointer to **string** | Strategy to use for searching. &#39;latest news&#39; automatically setsmethod&#x3D;&#39;nl&#39;, historical&#x3D;False, and looks within the past 24 hours. &#39;news knowledge&#39; automatically sets method&#x3D;&#39;kw&#39;, historical&#x3D;True, and looks within the past 60 days. &#39;news knowledge&#39; will increase latency due to the  larger search space in the archive. Use &#39;default&#39; if you want to control  start_timestamp, end_timestamp, historical, and method. | [optional] [default to "default"]
**HoursBack** | Pointer to **int32** | Can be set to easily control the look back on the search. This is the same as controlling the &#39;start_timestamp&#39; parameter. The difference is that this is not a timestamp, it is the number of hours back to look from the current time. Defaults to 24 hours. | [optional] [default to 24]
**StringGuarantee** | Pointer to **[]string** |  | [optional] 
**StringGuaranteeOp** | Pointer to **string** | Operator to use for string guarantee list. | [optional] [default to "AND"]
**ReverseStringGuarantee** | Pointer to **[]string** |  | [optional] 
**EntityGuarantee** | Pointer to **[]string** |  | [optional] 
**ReverseEntityGuarantee** | Pointer to **[]string** |  | [optional] 
**EntityGuaranteeOp** | Pointer to **string** | Operator to use for entity guarantee list. | [optional] [default to "OR"]
**ReturnGraphs** | Pointer to **bool** | Return graphs for the articles. Only available to Analyst tier and above. | [optional] [default to false]
**ReturnGeo** | Pointer to **bool** | Return GeoCoordinates associated with locations discussed  inside the articles. Only available to Analyst tier and above. | [optional] [default to false]
**Languages** | Pointer to **[]string** |  | [optional] 
**Countries** | Pointer to **[]string** |  | [optional] 
**CountriesBlacklist** | Pointer to **[]string** |  | [optional] 
**Continents** | Pointer to **[]string** |  | [optional] 
**Sentiment** | Pointer to **string** |  | [optional] 
**Premium** | Pointer to **bool** | Include premium sources. | [optional] [default to false]

## Methods

### NewCreateDeepNewsRequestFilterParams

`func NewCreateDeepNewsRequestFilterParams() *CreateDeepNewsRequestFilterParams`

NewCreateDeepNewsRequestFilterParams instantiates a new CreateDeepNewsRequestFilterParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDeepNewsRequestFilterParamsWithDefaults

`func NewCreateDeepNewsRequestFilterParamsWithDefaults() *CreateDeepNewsRequestFilterParams`

NewCreateDeepNewsRequestFilterParamsWithDefaults instantiates a new CreateDeepNewsRequestFilterParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuery

`func (o *CreateDeepNewsRequestFilterParams) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *CreateDeepNewsRequestFilterParams) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *CreateDeepNewsRequestFilterParams) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *CreateDeepNewsRequestFilterParams) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### GetNArticles

`func (o *CreateDeepNewsRequestFilterParams) GetNArticles() int32`

GetNArticles returns the NArticles field if non-nil, zero value otherwise.

### GetNArticlesOk

`func (o *CreateDeepNewsRequestFilterParams) GetNArticlesOk() (*int32, bool)`

GetNArticlesOk returns a tuple with the NArticles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNArticles

`func (o *CreateDeepNewsRequestFilterParams) SetNArticles(v int32)`

SetNArticles sets NArticles field to given value.

### HasNArticles

`func (o *CreateDeepNewsRequestFilterParams) HasNArticles() bool`

HasNArticles returns a boolean if a field has been set.

### GetStartTimestamp

`func (o *CreateDeepNewsRequestFilterParams) GetStartTimestamp() int32`

GetStartTimestamp returns the StartTimestamp field if non-nil, zero value otherwise.

### GetStartTimestampOk

`func (o *CreateDeepNewsRequestFilterParams) GetStartTimestampOk() (*int32, bool)`

GetStartTimestampOk returns a tuple with the StartTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTimestamp

`func (o *CreateDeepNewsRequestFilterParams) SetStartTimestamp(v int32)`

SetStartTimestamp sets StartTimestamp field to given value.

### HasStartTimestamp

`func (o *CreateDeepNewsRequestFilterParams) HasStartTimestamp() bool`

HasStartTimestamp returns a boolean if a field has been set.

### GetEndTimestamp

`func (o *CreateDeepNewsRequestFilterParams) GetEndTimestamp() int32`

GetEndTimestamp returns the EndTimestamp field if non-nil, zero value otherwise.

### GetEndTimestampOk

`func (o *CreateDeepNewsRequestFilterParams) GetEndTimestampOk() (*int32, bool)`

GetEndTimestampOk returns a tuple with the EndTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTimestamp

`func (o *CreateDeepNewsRequestFilterParams) SetEndTimestamp(v int32)`

SetEndTimestamp sets EndTimestamp field to given value.

### HasEndTimestamp

`func (o *CreateDeepNewsRequestFilterParams) HasEndTimestamp() bool`

HasEndTimestamp returns a boolean if a field has been set.

### GetTimeFilter

`func (o *CreateDeepNewsRequestFilterParams) GetTimeFilter() string`

GetTimeFilter returns the TimeFilter field if non-nil, zero value otherwise.

### GetTimeFilterOk

`func (o *CreateDeepNewsRequestFilterParams) GetTimeFilterOk() (*string, bool)`

GetTimeFilterOk returns a tuple with the TimeFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeFilter

`func (o *CreateDeepNewsRequestFilterParams) SetTimeFilter(v string)`

SetTimeFilter sets TimeFilter field to given value.

### HasTimeFilter

`func (o *CreateDeepNewsRequestFilterParams) HasTimeFilter() bool`

HasTimeFilter returns a boolean if a field has been set.

### GetReturnType

`func (o *CreateDeepNewsRequestFilterParams) GetReturnType() string`

GetReturnType returns the ReturnType field if non-nil, zero value otherwise.

### GetReturnTypeOk

`func (o *CreateDeepNewsRequestFilterParams) GetReturnTypeOk() (*string, bool)`

GetReturnTypeOk returns a tuple with the ReturnType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnType

`func (o *CreateDeepNewsRequestFilterParams) SetReturnType(v string)`

SetReturnType sets ReturnType field to given value.

### HasReturnType

`func (o *CreateDeepNewsRequestFilterParams) HasReturnType() bool`

HasReturnType returns a boolean if a field has been set.

### GetHistorical

`func (o *CreateDeepNewsRequestFilterParams) GetHistorical() bool`

GetHistorical returns the Historical field if non-nil, zero value otherwise.

### GetHistoricalOk

`func (o *CreateDeepNewsRequestFilterParams) GetHistoricalOk() (*bool, bool)`

GetHistoricalOk returns a tuple with the Historical field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistorical

`func (o *CreateDeepNewsRequestFilterParams) SetHistorical(v bool)`

SetHistorical sets Historical field to given value.

### HasHistorical

`func (o *CreateDeepNewsRequestFilterParams) HasHistorical() bool`

HasHistorical returns a boolean if a field has been set.

### GetMethod

`func (o *CreateDeepNewsRequestFilterParams) GetMethod() string`

GetMethod returns the Method field if non-nil, zero value otherwise.

### GetMethodOk

`func (o *CreateDeepNewsRequestFilterParams) GetMethodOk() (*string, bool)`

GetMethodOk returns a tuple with the Method field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethod

`func (o *CreateDeepNewsRequestFilterParams) SetMethod(v string)`

SetMethod sets Method field to given value.

### HasMethod

`func (o *CreateDeepNewsRequestFilterParams) HasMethod() bool`

HasMethod returns a boolean if a field has been set.

### GetSimilarityScoreThreshold

`func (o *CreateDeepNewsRequestFilterParams) GetSimilarityScoreThreshold() float32`

GetSimilarityScoreThreshold returns the SimilarityScoreThreshold field if non-nil, zero value otherwise.

### GetSimilarityScoreThresholdOk

`func (o *CreateDeepNewsRequestFilterParams) GetSimilarityScoreThresholdOk() (*float32, bool)`

GetSimilarityScoreThresholdOk returns a tuple with the SimilarityScoreThreshold field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSimilarityScoreThreshold

`func (o *CreateDeepNewsRequestFilterParams) SetSimilarityScoreThreshold(v float32)`

SetSimilarityScoreThreshold sets SimilarityScoreThreshold field to given value.

### HasSimilarityScoreThreshold

`func (o *CreateDeepNewsRequestFilterParams) HasSimilarityScoreThreshold() bool`

HasSimilarityScoreThreshold returns a boolean if a field has been set.

### GetOffset

`func (o *CreateDeepNewsRequestFilterParams) GetOffset() Offset2`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *CreateDeepNewsRequestFilterParams) GetOffsetOk() (*Offset2, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *CreateDeepNewsRequestFilterParams) SetOffset(v Offset2)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *CreateDeepNewsRequestFilterParams) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### GetCategories

`func (o *CreateDeepNewsRequestFilterParams) GetCategories() []string`

GetCategories returns the Categories field if non-nil, zero value otherwise.

### GetCategoriesOk

`func (o *CreateDeepNewsRequestFilterParams) GetCategoriesOk() (*[]string, bool)`

GetCategoriesOk returns a tuple with the Categories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategories

`func (o *CreateDeepNewsRequestFilterParams) SetCategories(v []string)`

SetCategories sets Categories field to given value.

### HasCategories

`func (o *CreateDeepNewsRequestFilterParams) HasCategories() bool`

HasCategories returns a boolean if a field has been set.

### GetDocStartDelimiter

`func (o *CreateDeepNewsRequestFilterParams) GetDocStartDelimiter() string`

GetDocStartDelimiter returns the DocStartDelimiter field if non-nil, zero value otherwise.

### GetDocStartDelimiterOk

`func (o *CreateDeepNewsRequestFilterParams) GetDocStartDelimiterOk() (*string, bool)`

GetDocStartDelimiterOk returns a tuple with the DocStartDelimiter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocStartDelimiter

`func (o *CreateDeepNewsRequestFilterParams) SetDocStartDelimiter(v string)`

SetDocStartDelimiter sets DocStartDelimiter field to given value.

### HasDocStartDelimiter

`func (o *CreateDeepNewsRequestFilterParams) HasDocStartDelimiter() bool`

HasDocStartDelimiter returns a boolean if a field has been set.

### GetDocEndDelimiter

`func (o *CreateDeepNewsRequestFilterParams) GetDocEndDelimiter() string`

GetDocEndDelimiter returns the DocEndDelimiter field if non-nil, zero value otherwise.

### GetDocEndDelimiterOk

`func (o *CreateDeepNewsRequestFilterParams) GetDocEndDelimiterOk() (*string, bool)`

GetDocEndDelimiterOk returns a tuple with the DocEndDelimiter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocEndDelimiter

`func (o *CreateDeepNewsRequestFilterParams) SetDocEndDelimiter(v string)`

SetDocEndDelimiter sets DocEndDelimiter field to given value.

### HasDocEndDelimiter

`func (o *CreateDeepNewsRequestFilterParams) HasDocEndDelimiter() bool`

HasDocEndDelimiter returns a boolean if a field has been set.

### GetProvocative

`func (o *CreateDeepNewsRequestFilterParams) GetProvocative() string`

GetProvocative returns the Provocative field if non-nil, zero value otherwise.

### GetProvocativeOk

`func (o *CreateDeepNewsRequestFilterParams) GetProvocativeOk() (*string, bool)`

GetProvocativeOk returns a tuple with the Provocative field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvocative

`func (o *CreateDeepNewsRequestFilterParams) SetProvocative(v string)`

SetProvocative sets Provocative field to given value.

### HasProvocative

`func (o *CreateDeepNewsRequestFilterParams) HasProvocative() bool`

HasProvocative returns a boolean if a field has been set.

### GetReportingVoice

`func (o *CreateDeepNewsRequestFilterParams) GetReportingVoice() ReportingVoice2`

GetReportingVoice returns the ReportingVoice field if non-nil, zero value otherwise.

### GetReportingVoiceOk

`func (o *CreateDeepNewsRequestFilterParams) GetReportingVoiceOk() (*ReportingVoice2, bool)`

GetReportingVoiceOk returns a tuple with the ReportingVoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportingVoice

`func (o *CreateDeepNewsRequestFilterParams) SetReportingVoice(v ReportingVoice2)`

SetReportingVoice sets ReportingVoice field to given value.

### HasReportingVoice

`func (o *CreateDeepNewsRequestFilterParams) HasReportingVoice() bool`

HasReportingVoice returns a boolean if a field has been set.

### GetDomainUrl

`func (o *CreateDeepNewsRequestFilterParams) GetDomainUrl() DomainUrl1`

GetDomainUrl returns the DomainUrl field if non-nil, zero value otherwise.

### GetDomainUrlOk

`func (o *CreateDeepNewsRequestFilterParams) GetDomainUrlOk() (*DomainUrl1, bool)`

GetDomainUrlOk returns a tuple with the DomainUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainUrl

`func (o *CreateDeepNewsRequestFilterParams) SetDomainUrl(v DomainUrl1)`

SetDomainUrl sets DomainUrl field to given value.

### HasDomainUrl

`func (o *CreateDeepNewsRequestFilterParams) HasDomainUrl() bool`

HasDomainUrl returns a boolean if a field has been set.

### SetDomainUrlNil

`func (o *CreateDeepNewsRequestFilterParams) SetDomainUrlNil(b bool)`

 SetDomainUrlNil sets the value for DomainUrl to be an explicit nil

### UnsetDomainUrl
`func (o *CreateDeepNewsRequestFilterParams) UnsetDomainUrl()`

UnsetDomainUrl ensures that no value is present for DomainUrl, not even an explicit nil
### GetBadDomainUrl

`func (o *CreateDeepNewsRequestFilterParams) GetBadDomainUrl() BadDomainUrl2`

GetBadDomainUrl returns the BadDomainUrl field if non-nil, zero value otherwise.

### GetBadDomainUrlOk

`func (o *CreateDeepNewsRequestFilterParams) GetBadDomainUrlOk() (*BadDomainUrl2, bool)`

GetBadDomainUrlOk returns a tuple with the BadDomainUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBadDomainUrl

`func (o *CreateDeepNewsRequestFilterParams) SetBadDomainUrl(v BadDomainUrl2)`

SetBadDomainUrl sets BadDomainUrl field to given value.

### HasBadDomainUrl

`func (o *CreateDeepNewsRequestFilterParams) HasBadDomainUrl() bool`

HasBadDomainUrl returns a boolean if a field has been set.

### SetBadDomainUrlNil

`func (o *CreateDeepNewsRequestFilterParams) SetBadDomainUrlNil(b bool)`

 SetBadDomainUrlNil sets the value for BadDomainUrl to be an explicit nil

### UnsetBadDomainUrl
`func (o *CreateDeepNewsRequestFilterParams) UnsetBadDomainUrl()`

UnsetBadDomainUrl ensures that no value is present for BadDomainUrl, not even an explicit nil
### GetPageRank

`func (o *CreateDeepNewsRequestFilterParams) GetPageRank() int32`

GetPageRank returns the PageRank field if non-nil, zero value otherwise.

### GetPageRankOk

`func (o *CreateDeepNewsRequestFilterParams) GetPageRankOk() (*int32, bool)`

GetPageRankOk returns a tuple with the PageRank field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageRank

`func (o *CreateDeepNewsRequestFilterParams) SetPageRank(v int32)`

SetPageRank sets PageRank field to given value.

### HasPageRank

`func (o *CreateDeepNewsRequestFilterParams) HasPageRank() bool`

HasPageRank returns a boolean if a field has been set.

### GetDiversifySources

`func (o *CreateDeepNewsRequestFilterParams) GetDiversifySources() bool`

GetDiversifySources returns the DiversifySources field if non-nil, zero value otherwise.

### GetDiversifySourcesOk

`func (o *CreateDeepNewsRequestFilterParams) GetDiversifySourcesOk() (*bool, bool)`

GetDiversifySourcesOk returns a tuple with the DiversifySources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiversifySources

`func (o *CreateDeepNewsRequestFilterParams) SetDiversifySources(v bool)`

SetDiversifySources sets DiversifySources field to given value.

### HasDiversifySources

`func (o *CreateDeepNewsRequestFilterParams) HasDiversifySources() bool`

HasDiversifySources returns a boolean if a field has been set.

### GetStrategy

`func (o *CreateDeepNewsRequestFilterParams) GetStrategy() string`

GetStrategy returns the Strategy field if non-nil, zero value otherwise.

### GetStrategyOk

`func (o *CreateDeepNewsRequestFilterParams) GetStrategyOk() (*string, bool)`

GetStrategyOk returns a tuple with the Strategy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStrategy

`func (o *CreateDeepNewsRequestFilterParams) SetStrategy(v string)`

SetStrategy sets Strategy field to given value.

### HasStrategy

`func (o *CreateDeepNewsRequestFilterParams) HasStrategy() bool`

HasStrategy returns a boolean if a field has been set.

### GetHoursBack

`func (o *CreateDeepNewsRequestFilterParams) GetHoursBack() int32`

GetHoursBack returns the HoursBack field if non-nil, zero value otherwise.

### GetHoursBackOk

`func (o *CreateDeepNewsRequestFilterParams) GetHoursBackOk() (*int32, bool)`

GetHoursBackOk returns a tuple with the HoursBack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHoursBack

`func (o *CreateDeepNewsRequestFilterParams) SetHoursBack(v int32)`

SetHoursBack sets HoursBack field to given value.

### HasHoursBack

`func (o *CreateDeepNewsRequestFilterParams) HasHoursBack() bool`

HasHoursBack returns a boolean if a field has been set.

### GetStringGuarantee

`func (o *CreateDeepNewsRequestFilterParams) GetStringGuarantee() []string`

GetStringGuarantee returns the StringGuarantee field if non-nil, zero value otherwise.

### GetStringGuaranteeOk

`func (o *CreateDeepNewsRequestFilterParams) GetStringGuaranteeOk() (*[]string, bool)`

GetStringGuaranteeOk returns a tuple with the StringGuarantee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStringGuarantee

`func (o *CreateDeepNewsRequestFilterParams) SetStringGuarantee(v []string)`

SetStringGuarantee sets StringGuarantee field to given value.

### HasStringGuarantee

`func (o *CreateDeepNewsRequestFilterParams) HasStringGuarantee() bool`

HasStringGuarantee returns a boolean if a field has been set.

### GetStringGuaranteeOp

`func (o *CreateDeepNewsRequestFilterParams) GetStringGuaranteeOp() string`

GetStringGuaranteeOp returns the StringGuaranteeOp field if non-nil, zero value otherwise.

### GetStringGuaranteeOpOk

`func (o *CreateDeepNewsRequestFilterParams) GetStringGuaranteeOpOk() (*string, bool)`

GetStringGuaranteeOpOk returns a tuple with the StringGuaranteeOp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStringGuaranteeOp

`func (o *CreateDeepNewsRequestFilterParams) SetStringGuaranteeOp(v string)`

SetStringGuaranteeOp sets StringGuaranteeOp field to given value.

### HasStringGuaranteeOp

`func (o *CreateDeepNewsRequestFilterParams) HasStringGuaranteeOp() bool`

HasStringGuaranteeOp returns a boolean if a field has been set.

### GetReverseStringGuarantee

`func (o *CreateDeepNewsRequestFilterParams) GetReverseStringGuarantee() []string`

GetReverseStringGuarantee returns the ReverseStringGuarantee field if non-nil, zero value otherwise.

### GetReverseStringGuaranteeOk

`func (o *CreateDeepNewsRequestFilterParams) GetReverseStringGuaranteeOk() (*[]string, bool)`

GetReverseStringGuaranteeOk returns a tuple with the ReverseStringGuarantee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReverseStringGuarantee

`func (o *CreateDeepNewsRequestFilterParams) SetReverseStringGuarantee(v []string)`

SetReverseStringGuarantee sets ReverseStringGuarantee field to given value.

### HasReverseStringGuarantee

`func (o *CreateDeepNewsRequestFilterParams) HasReverseStringGuarantee() bool`

HasReverseStringGuarantee returns a boolean if a field has been set.

### GetEntityGuarantee

`func (o *CreateDeepNewsRequestFilterParams) GetEntityGuarantee() []string`

GetEntityGuarantee returns the EntityGuarantee field if non-nil, zero value otherwise.

### GetEntityGuaranteeOk

`func (o *CreateDeepNewsRequestFilterParams) GetEntityGuaranteeOk() (*[]string, bool)`

GetEntityGuaranteeOk returns a tuple with the EntityGuarantee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityGuarantee

`func (o *CreateDeepNewsRequestFilterParams) SetEntityGuarantee(v []string)`

SetEntityGuarantee sets EntityGuarantee field to given value.

### HasEntityGuarantee

`func (o *CreateDeepNewsRequestFilterParams) HasEntityGuarantee() bool`

HasEntityGuarantee returns a boolean if a field has been set.

### GetReverseEntityGuarantee

`func (o *CreateDeepNewsRequestFilterParams) GetReverseEntityGuarantee() []string`

GetReverseEntityGuarantee returns the ReverseEntityGuarantee field if non-nil, zero value otherwise.

### GetReverseEntityGuaranteeOk

`func (o *CreateDeepNewsRequestFilterParams) GetReverseEntityGuaranteeOk() (*[]string, bool)`

GetReverseEntityGuaranteeOk returns a tuple with the ReverseEntityGuarantee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReverseEntityGuarantee

`func (o *CreateDeepNewsRequestFilterParams) SetReverseEntityGuarantee(v []string)`

SetReverseEntityGuarantee sets ReverseEntityGuarantee field to given value.

### HasReverseEntityGuarantee

`func (o *CreateDeepNewsRequestFilterParams) HasReverseEntityGuarantee() bool`

HasReverseEntityGuarantee returns a boolean if a field has been set.

### GetEntityGuaranteeOp

`func (o *CreateDeepNewsRequestFilterParams) GetEntityGuaranteeOp() string`

GetEntityGuaranteeOp returns the EntityGuaranteeOp field if non-nil, zero value otherwise.

### GetEntityGuaranteeOpOk

`func (o *CreateDeepNewsRequestFilterParams) GetEntityGuaranteeOpOk() (*string, bool)`

GetEntityGuaranteeOpOk returns a tuple with the EntityGuaranteeOp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityGuaranteeOp

`func (o *CreateDeepNewsRequestFilterParams) SetEntityGuaranteeOp(v string)`

SetEntityGuaranteeOp sets EntityGuaranteeOp field to given value.

### HasEntityGuaranteeOp

`func (o *CreateDeepNewsRequestFilterParams) HasEntityGuaranteeOp() bool`

HasEntityGuaranteeOp returns a boolean if a field has been set.

### GetReturnGraphs

`func (o *CreateDeepNewsRequestFilterParams) GetReturnGraphs() bool`

GetReturnGraphs returns the ReturnGraphs field if non-nil, zero value otherwise.

### GetReturnGraphsOk

`func (o *CreateDeepNewsRequestFilterParams) GetReturnGraphsOk() (*bool, bool)`

GetReturnGraphsOk returns a tuple with the ReturnGraphs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnGraphs

`func (o *CreateDeepNewsRequestFilterParams) SetReturnGraphs(v bool)`

SetReturnGraphs sets ReturnGraphs field to given value.

### HasReturnGraphs

`func (o *CreateDeepNewsRequestFilterParams) HasReturnGraphs() bool`

HasReturnGraphs returns a boolean if a field has been set.

### GetReturnGeo

`func (o *CreateDeepNewsRequestFilterParams) GetReturnGeo() bool`

GetReturnGeo returns the ReturnGeo field if non-nil, zero value otherwise.

### GetReturnGeoOk

`func (o *CreateDeepNewsRequestFilterParams) GetReturnGeoOk() (*bool, bool)`

GetReturnGeoOk returns a tuple with the ReturnGeo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnGeo

`func (o *CreateDeepNewsRequestFilterParams) SetReturnGeo(v bool)`

SetReturnGeo sets ReturnGeo field to given value.

### HasReturnGeo

`func (o *CreateDeepNewsRequestFilterParams) HasReturnGeo() bool`

HasReturnGeo returns a boolean if a field has been set.

### GetLanguages

`func (o *CreateDeepNewsRequestFilterParams) GetLanguages() []string`

GetLanguages returns the Languages field if non-nil, zero value otherwise.

### GetLanguagesOk

`func (o *CreateDeepNewsRequestFilterParams) GetLanguagesOk() (*[]string, bool)`

GetLanguagesOk returns a tuple with the Languages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguages

`func (o *CreateDeepNewsRequestFilterParams) SetLanguages(v []string)`

SetLanguages sets Languages field to given value.

### HasLanguages

`func (o *CreateDeepNewsRequestFilterParams) HasLanguages() bool`

HasLanguages returns a boolean if a field has been set.

### GetCountries

`func (o *CreateDeepNewsRequestFilterParams) GetCountries() []string`

GetCountries returns the Countries field if non-nil, zero value otherwise.

### GetCountriesOk

`func (o *CreateDeepNewsRequestFilterParams) GetCountriesOk() (*[]string, bool)`

GetCountriesOk returns a tuple with the Countries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountries

`func (o *CreateDeepNewsRequestFilterParams) SetCountries(v []string)`

SetCountries sets Countries field to given value.

### HasCountries

`func (o *CreateDeepNewsRequestFilterParams) HasCountries() bool`

HasCountries returns a boolean if a field has been set.

### GetCountriesBlacklist

`func (o *CreateDeepNewsRequestFilterParams) GetCountriesBlacklist() []string`

GetCountriesBlacklist returns the CountriesBlacklist field if non-nil, zero value otherwise.

### GetCountriesBlacklistOk

`func (o *CreateDeepNewsRequestFilterParams) GetCountriesBlacklistOk() (*[]string, bool)`

GetCountriesBlacklistOk returns a tuple with the CountriesBlacklist field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountriesBlacklist

`func (o *CreateDeepNewsRequestFilterParams) SetCountriesBlacklist(v []string)`

SetCountriesBlacklist sets CountriesBlacklist field to given value.

### HasCountriesBlacklist

`func (o *CreateDeepNewsRequestFilterParams) HasCountriesBlacklist() bool`

HasCountriesBlacklist returns a boolean if a field has been set.

### GetContinents

`func (o *CreateDeepNewsRequestFilterParams) GetContinents() []string`

GetContinents returns the Continents field if non-nil, zero value otherwise.

### GetContinentsOk

`func (o *CreateDeepNewsRequestFilterParams) GetContinentsOk() (*[]string, bool)`

GetContinentsOk returns a tuple with the Continents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContinents

`func (o *CreateDeepNewsRequestFilterParams) SetContinents(v []string)`

SetContinents sets Continents field to given value.

### HasContinents

`func (o *CreateDeepNewsRequestFilterParams) HasContinents() bool`

HasContinents returns a boolean if a field has been set.

### GetSentiment

`func (o *CreateDeepNewsRequestFilterParams) GetSentiment() string`

GetSentiment returns the Sentiment field if non-nil, zero value otherwise.

### GetSentimentOk

`func (o *CreateDeepNewsRequestFilterParams) GetSentimentOk() (*string, bool)`

GetSentimentOk returns a tuple with the Sentiment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentiment

`func (o *CreateDeepNewsRequestFilterParams) SetSentiment(v string)`

SetSentiment sets Sentiment field to given value.

### HasSentiment

`func (o *CreateDeepNewsRequestFilterParams) HasSentiment() bool`

HasSentiment returns a boolean if a field has been set.

### GetPremium

`func (o *CreateDeepNewsRequestFilterParams) GetPremium() bool`

GetPremium returns the Premium field if non-nil, zero value otherwise.

### GetPremiumOk

`func (o *CreateDeepNewsRequestFilterParams) GetPremiumOk() (*bool, bool)`

GetPremiumOk returns a tuple with the Premium field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPremium

`func (o *CreateDeepNewsRequestFilterParams) SetPremium(v bool)`

SetPremium sets Premium field to given value.

### HasPremium

`func (o *CreateDeepNewsRequestFilterParams) HasPremium() bool`

HasPremium returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


