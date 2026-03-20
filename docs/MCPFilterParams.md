# MCPFilterParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Query** | Pointer to **string** | Query string that can be any phrase, keyword, question, or paragraph. If method&#x3D;&#39;nl&#39;, then this will be used as a natural language query. If method&#x3D;&#39;kw&#39;, then this will be used as a direct keyword query. This is not required, if it is not passed, then the search is based on the remaining filters only. | [optional] [default to ""]
**NArticles** | Pointer to **int32** | Number of articles to return | [optional] [default to 10]
**StartTimestamp** | Pointer to **NullableInt32** |  | [optional] 
**EndTimestamp** | Pointer to **NullableInt32** |  | [optional] 
**TimeFilter** | Pointer to **string** | Control which date type to filter on. &#39;crawl_date&#39; is the date the article was crawled, &#39;pub_date&#39; is the date the article was published. | [optional] [default to "crawl_date"]
**Offset** | Pointer to [**Offset3**](Offset3.md) |  | [optional] [default to 0]
**Categories** | Pointer to **[]string** | Categories of news to filter on | [optional] [default to [All]]
**Provocative** | Pointer to **string** | Filter articles based on how provocative they are deemed based on the use of provocative language and emotional vocabulary. | [optional] [default to "all"]
**Authors** | Pointer to **[]string** |  | [optional] 
**ReportingVoice** | Pointer to [**ReportingVoice2**](ReportingVoice2.md) |  | [optional] [default to [all]]
**DomainUrl** | Pointer to [**NullableDomainUrl1**](DomainUrl1.md) |  | [optional] 
**BadDomainUrl** | Pointer to [**NullableBadDomainUrl2**](BadDomainUrl2.md) |  | [optional] 
**PageRank** | Pointer to **NullableInt32** |  | [optional] 
**HoursBack** | Pointer to **int32** | Can be set to easily control the look back on the search. This is the same as controlling the &#39;start_timestamp&#39; parameter. The difference is that this is not a timestamp, it is the number of hours back to look from the current time. Defaults to 24 hours. | [optional] [default to 24]
**StringGuarantee** | Pointer to **[]string** |  | [optional] 
**StringGuaranteeOp** | Pointer to **string** | Operator to use for string guarantee list. | [optional] [default to "AND"]
**ReverseStringGuarantee** | Pointer to **[]string** |  | [optional] 
**EntityGuarantee** | Pointer to **[]string** |  | [optional] 
**ReverseEntityGuarantee** | Pointer to **[]string** |  | [optional] 
**EntityGuaranteeOp** | Pointer to **string** | Operator to use for entity guarantee list. | [optional] [default to "OR"]
**Languages** | Pointer to **[]string** |  | [optional] 
**Countries** | Pointer to **[]string** |  | [optional] 
**CountriesBlacklist** | Pointer to **[]string** |  | [optional] 
**Continents** | Pointer to **[]string** |  | [optional] 
**Sentiment** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewMCPFilterParams

`func NewMCPFilterParams() *MCPFilterParams`

NewMCPFilterParams instantiates a new MCPFilterParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMCPFilterParamsWithDefaults

`func NewMCPFilterParamsWithDefaults() *MCPFilterParams`

NewMCPFilterParamsWithDefaults instantiates a new MCPFilterParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuery

`func (o *MCPFilterParams) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *MCPFilterParams) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *MCPFilterParams) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *MCPFilterParams) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### GetNArticles

`func (o *MCPFilterParams) GetNArticles() int32`

GetNArticles returns the NArticles field if non-nil, zero value otherwise.

### GetNArticlesOk

`func (o *MCPFilterParams) GetNArticlesOk() (*int32, bool)`

GetNArticlesOk returns a tuple with the NArticles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNArticles

`func (o *MCPFilterParams) SetNArticles(v int32)`

SetNArticles sets NArticles field to given value.

### HasNArticles

`func (o *MCPFilterParams) HasNArticles() bool`

HasNArticles returns a boolean if a field has been set.

### GetStartTimestamp

`func (o *MCPFilterParams) GetStartTimestamp() int32`

GetStartTimestamp returns the StartTimestamp field if non-nil, zero value otherwise.

### GetStartTimestampOk

`func (o *MCPFilterParams) GetStartTimestampOk() (*int32, bool)`

GetStartTimestampOk returns a tuple with the StartTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTimestamp

`func (o *MCPFilterParams) SetStartTimestamp(v int32)`

SetStartTimestamp sets StartTimestamp field to given value.

### HasStartTimestamp

`func (o *MCPFilterParams) HasStartTimestamp() bool`

HasStartTimestamp returns a boolean if a field has been set.

### SetStartTimestampNil

`func (o *MCPFilterParams) SetStartTimestampNil(b bool)`

 SetStartTimestampNil sets the value for StartTimestamp to be an explicit nil

### UnsetStartTimestamp
`func (o *MCPFilterParams) UnsetStartTimestamp()`

UnsetStartTimestamp ensures that no value is present for StartTimestamp, not even an explicit nil
### GetEndTimestamp

`func (o *MCPFilterParams) GetEndTimestamp() int32`

GetEndTimestamp returns the EndTimestamp field if non-nil, zero value otherwise.

### GetEndTimestampOk

`func (o *MCPFilterParams) GetEndTimestampOk() (*int32, bool)`

GetEndTimestampOk returns a tuple with the EndTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTimestamp

`func (o *MCPFilterParams) SetEndTimestamp(v int32)`

SetEndTimestamp sets EndTimestamp field to given value.

### HasEndTimestamp

`func (o *MCPFilterParams) HasEndTimestamp() bool`

HasEndTimestamp returns a boolean if a field has been set.

### SetEndTimestampNil

`func (o *MCPFilterParams) SetEndTimestampNil(b bool)`

 SetEndTimestampNil sets the value for EndTimestamp to be an explicit nil

### UnsetEndTimestamp
`func (o *MCPFilterParams) UnsetEndTimestamp()`

UnsetEndTimestamp ensures that no value is present for EndTimestamp, not even an explicit nil
### GetTimeFilter

`func (o *MCPFilterParams) GetTimeFilter() string`

GetTimeFilter returns the TimeFilter field if non-nil, zero value otherwise.

### GetTimeFilterOk

`func (o *MCPFilterParams) GetTimeFilterOk() (*string, bool)`

GetTimeFilterOk returns a tuple with the TimeFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeFilter

`func (o *MCPFilterParams) SetTimeFilter(v string)`

SetTimeFilter sets TimeFilter field to given value.

### HasTimeFilter

`func (o *MCPFilterParams) HasTimeFilter() bool`

HasTimeFilter returns a boolean if a field has been set.

### GetOffset

`func (o *MCPFilterParams) GetOffset() Offset3`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *MCPFilterParams) GetOffsetOk() (*Offset3, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *MCPFilterParams) SetOffset(v Offset3)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *MCPFilterParams) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### GetCategories

`func (o *MCPFilterParams) GetCategories() []string`

GetCategories returns the Categories field if non-nil, zero value otherwise.

### GetCategoriesOk

`func (o *MCPFilterParams) GetCategoriesOk() (*[]string, bool)`

GetCategoriesOk returns a tuple with the Categories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategories

`func (o *MCPFilterParams) SetCategories(v []string)`

SetCategories sets Categories field to given value.

### HasCategories

`func (o *MCPFilterParams) HasCategories() bool`

HasCategories returns a boolean if a field has been set.

### GetProvocative

`func (o *MCPFilterParams) GetProvocative() string`

GetProvocative returns the Provocative field if non-nil, zero value otherwise.

### GetProvocativeOk

`func (o *MCPFilterParams) GetProvocativeOk() (*string, bool)`

GetProvocativeOk returns a tuple with the Provocative field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvocative

`func (o *MCPFilterParams) SetProvocative(v string)`

SetProvocative sets Provocative field to given value.

### HasProvocative

`func (o *MCPFilterParams) HasProvocative() bool`

HasProvocative returns a boolean if a field has been set.

### GetAuthors

`func (o *MCPFilterParams) GetAuthors() []string`

GetAuthors returns the Authors field if non-nil, zero value otherwise.

### GetAuthorsOk

`func (o *MCPFilterParams) GetAuthorsOk() (*[]string, bool)`

GetAuthorsOk returns a tuple with the Authors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthors

`func (o *MCPFilterParams) SetAuthors(v []string)`

SetAuthors sets Authors field to given value.

### HasAuthors

`func (o *MCPFilterParams) HasAuthors() bool`

HasAuthors returns a boolean if a field has been set.

### SetAuthorsNil

`func (o *MCPFilterParams) SetAuthorsNil(b bool)`

 SetAuthorsNil sets the value for Authors to be an explicit nil

### UnsetAuthors
`func (o *MCPFilterParams) UnsetAuthors()`

UnsetAuthors ensures that no value is present for Authors, not even an explicit nil
### GetReportingVoice

`func (o *MCPFilterParams) GetReportingVoice() ReportingVoice2`

GetReportingVoice returns the ReportingVoice field if non-nil, zero value otherwise.

### GetReportingVoiceOk

`func (o *MCPFilterParams) GetReportingVoiceOk() (*ReportingVoice2, bool)`

GetReportingVoiceOk returns a tuple with the ReportingVoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportingVoice

`func (o *MCPFilterParams) SetReportingVoice(v ReportingVoice2)`

SetReportingVoice sets ReportingVoice field to given value.

### HasReportingVoice

`func (o *MCPFilterParams) HasReportingVoice() bool`

HasReportingVoice returns a boolean if a field has been set.

### GetDomainUrl

`func (o *MCPFilterParams) GetDomainUrl() DomainUrl1`

GetDomainUrl returns the DomainUrl field if non-nil, zero value otherwise.

### GetDomainUrlOk

`func (o *MCPFilterParams) GetDomainUrlOk() (*DomainUrl1, bool)`

GetDomainUrlOk returns a tuple with the DomainUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainUrl

`func (o *MCPFilterParams) SetDomainUrl(v DomainUrl1)`

SetDomainUrl sets DomainUrl field to given value.

### HasDomainUrl

`func (o *MCPFilterParams) HasDomainUrl() bool`

HasDomainUrl returns a boolean if a field has been set.

### SetDomainUrlNil

`func (o *MCPFilterParams) SetDomainUrlNil(b bool)`

 SetDomainUrlNil sets the value for DomainUrl to be an explicit nil

### UnsetDomainUrl
`func (o *MCPFilterParams) UnsetDomainUrl()`

UnsetDomainUrl ensures that no value is present for DomainUrl, not even an explicit nil
### GetBadDomainUrl

`func (o *MCPFilterParams) GetBadDomainUrl() BadDomainUrl2`

GetBadDomainUrl returns the BadDomainUrl field if non-nil, zero value otherwise.

### GetBadDomainUrlOk

`func (o *MCPFilterParams) GetBadDomainUrlOk() (*BadDomainUrl2, bool)`

GetBadDomainUrlOk returns a tuple with the BadDomainUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBadDomainUrl

`func (o *MCPFilterParams) SetBadDomainUrl(v BadDomainUrl2)`

SetBadDomainUrl sets BadDomainUrl field to given value.

### HasBadDomainUrl

`func (o *MCPFilterParams) HasBadDomainUrl() bool`

HasBadDomainUrl returns a boolean if a field has been set.

### SetBadDomainUrlNil

`func (o *MCPFilterParams) SetBadDomainUrlNil(b bool)`

 SetBadDomainUrlNil sets the value for BadDomainUrl to be an explicit nil

### UnsetBadDomainUrl
`func (o *MCPFilterParams) UnsetBadDomainUrl()`

UnsetBadDomainUrl ensures that no value is present for BadDomainUrl, not even an explicit nil
### GetPageRank

`func (o *MCPFilterParams) GetPageRank() int32`

GetPageRank returns the PageRank field if non-nil, zero value otherwise.

### GetPageRankOk

`func (o *MCPFilterParams) GetPageRankOk() (*int32, bool)`

GetPageRankOk returns a tuple with the PageRank field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageRank

`func (o *MCPFilterParams) SetPageRank(v int32)`

SetPageRank sets PageRank field to given value.

### HasPageRank

`func (o *MCPFilterParams) HasPageRank() bool`

HasPageRank returns a boolean if a field has been set.

### SetPageRankNil

`func (o *MCPFilterParams) SetPageRankNil(b bool)`

 SetPageRankNil sets the value for PageRank to be an explicit nil

### UnsetPageRank
`func (o *MCPFilterParams) UnsetPageRank()`

UnsetPageRank ensures that no value is present for PageRank, not even an explicit nil
### GetHoursBack

`func (o *MCPFilterParams) GetHoursBack() int32`

GetHoursBack returns the HoursBack field if non-nil, zero value otherwise.

### GetHoursBackOk

`func (o *MCPFilterParams) GetHoursBackOk() (*int32, bool)`

GetHoursBackOk returns a tuple with the HoursBack field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHoursBack

`func (o *MCPFilterParams) SetHoursBack(v int32)`

SetHoursBack sets HoursBack field to given value.

### HasHoursBack

`func (o *MCPFilterParams) HasHoursBack() bool`

HasHoursBack returns a boolean if a field has been set.

### GetStringGuarantee

`func (o *MCPFilterParams) GetStringGuarantee() []string`

GetStringGuarantee returns the StringGuarantee field if non-nil, zero value otherwise.

### GetStringGuaranteeOk

`func (o *MCPFilterParams) GetStringGuaranteeOk() (*[]string, bool)`

GetStringGuaranteeOk returns a tuple with the StringGuarantee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStringGuarantee

`func (o *MCPFilterParams) SetStringGuarantee(v []string)`

SetStringGuarantee sets StringGuarantee field to given value.

### HasStringGuarantee

`func (o *MCPFilterParams) HasStringGuarantee() bool`

HasStringGuarantee returns a boolean if a field has been set.

### SetStringGuaranteeNil

`func (o *MCPFilterParams) SetStringGuaranteeNil(b bool)`

 SetStringGuaranteeNil sets the value for StringGuarantee to be an explicit nil

### UnsetStringGuarantee
`func (o *MCPFilterParams) UnsetStringGuarantee()`

UnsetStringGuarantee ensures that no value is present for StringGuarantee, not even an explicit nil
### GetStringGuaranteeOp

`func (o *MCPFilterParams) GetStringGuaranteeOp() string`

GetStringGuaranteeOp returns the StringGuaranteeOp field if non-nil, zero value otherwise.

### GetStringGuaranteeOpOk

`func (o *MCPFilterParams) GetStringGuaranteeOpOk() (*string, bool)`

GetStringGuaranteeOpOk returns a tuple with the StringGuaranteeOp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStringGuaranteeOp

`func (o *MCPFilterParams) SetStringGuaranteeOp(v string)`

SetStringGuaranteeOp sets StringGuaranteeOp field to given value.

### HasStringGuaranteeOp

`func (o *MCPFilterParams) HasStringGuaranteeOp() bool`

HasStringGuaranteeOp returns a boolean if a field has been set.

### GetReverseStringGuarantee

`func (o *MCPFilterParams) GetReverseStringGuarantee() []string`

GetReverseStringGuarantee returns the ReverseStringGuarantee field if non-nil, zero value otherwise.

### GetReverseStringGuaranteeOk

`func (o *MCPFilterParams) GetReverseStringGuaranteeOk() (*[]string, bool)`

GetReverseStringGuaranteeOk returns a tuple with the ReverseStringGuarantee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReverseStringGuarantee

`func (o *MCPFilterParams) SetReverseStringGuarantee(v []string)`

SetReverseStringGuarantee sets ReverseStringGuarantee field to given value.

### HasReverseStringGuarantee

`func (o *MCPFilterParams) HasReverseStringGuarantee() bool`

HasReverseStringGuarantee returns a boolean if a field has been set.

### SetReverseStringGuaranteeNil

`func (o *MCPFilterParams) SetReverseStringGuaranteeNil(b bool)`

 SetReverseStringGuaranteeNil sets the value for ReverseStringGuarantee to be an explicit nil

### UnsetReverseStringGuarantee
`func (o *MCPFilterParams) UnsetReverseStringGuarantee()`

UnsetReverseStringGuarantee ensures that no value is present for ReverseStringGuarantee, not even an explicit nil
### GetEntityGuarantee

`func (o *MCPFilterParams) GetEntityGuarantee() []string`

GetEntityGuarantee returns the EntityGuarantee field if non-nil, zero value otherwise.

### GetEntityGuaranteeOk

`func (o *MCPFilterParams) GetEntityGuaranteeOk() (*[]string, bool)`

GetEntityGuaranteeOk returns a tuple with the EntityGuarantee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityGuarantee

`func (o *MCPFilterParams) SetEntityGuarantee(v []string)`

SetEntityGuarantee sets EntityGuarantee field to given value.

### HasEntityGuarantee

`func (o *MCPFilterParams) HasEntityGuarantee() bool`

HasEntityGuarantee returns a boolean if a field has been set.

### SetEntityGuaranteeNil

`func (o *MCPFilterParams) SetEntityGuaranteeNil(b bool)`

 SetEntityGuaranteeNil sets the value for EntityGuarantee to be an explicit nil

### UnsetEntityGuarantee
`func (o *MCPFilterParams) UnsetEntityGuarantee()`

UnsetEntityGuarantee ensures that no value is present for EntityGuarantee, not even an explicit nil
### GetReverseEntityGuarantee

`func (o *MCPFilterParams) GetReverseEntityGuarantee() []string`

GetReverseEntityGuarantee returns the ReverseEntityGuarantee field if non-nil, zero value otherwise.

### GetReverseEntityGuaranteeOk

`func (o *MCPFilterParams) GetReverseEntityGuaranteeOk() (*[]string, bool)`

GetReverseEntityGuaranteeOk returns a tuple with the ReverseEntityGuarantee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReverseEntityGuarantee

`func (o *MCPFilterParams) SetReverseEntityGuarantee(v []string)`

SetReverseEntityGuarantee sets ReverseEntityGuarantee field to given value.

### HasReverseEntityGuarantee

`func (o *MCPFilterParams) HasReverseEntityGuarantee() bool`

HasReverseEntityGuarantee returns a boolean if a field has been set.

### SetReverseEntityGuaranteeNil

`func (o *MCPFilterParams) SetReverseEntityGuaranteeNil(b bool)`

 SetReverseEntityGuaranteeNil sets the value for ReverseEntityGuarantee to be an explicit nil

### UnsetReverseEntityGuarantee
`func (o *MCPFilterParams) UnsetReverseEntityGuarantee()`

UnsetReverseEntityGuarantee ensures that no value is present for ReverseEntityGuarantee, not even an explicit nil
### GetEntityGuaranteeOp

`func (o *MCPFilterParams) GetEntityGuaranteeOp() string`

GetEntityGuaranteeOp returns the EntityGuaranteeOp field if non-nil, zero value otherwise.

### GetEntityGuaranteeOpOk

`func (o *MCPFilterParams) GetEntityGuaranteeOpOk() (*string, bool)`

GetEntityGuaranteeOpOk returns a tuple with the EntityGuaranteeOp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityGuaranteeOp

`func (o *MCPFilterParams) SetEntityGuaranteeOp(v string)`

SetEntityGuaranteeOp sets EntityGuaranteeOp field to given value.

### HasEntityGuaranteeOp

`func (o *MCPFilterParams) HasEntityGuaranteeOp() bool`

HasEntityGuaranteeOp returns a boolean if a field has been set.

### GetLanguages

`func (o *MCPFilterParams) GetLanguages() []string`

GetLanguages returns the Languages field if non-nil, zero value otherwise.

### GetLanguagesOk

`func (o *MCPFilterParams) GetLanguagesOk() (*[]string, bool)`

GetLanguagesOk returns a tuple with the Languages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguages

`func (o *MCPFilterParams) SetLanguages(v []string)`

SetLanguages sets Languages field to given value.

### HasLanguages

`func (o *MCPFilterParams) HasLanguages() bool`

HasLanguages returns a boolean if a field has been set.

### SetLanguagesNil

`func (o *MCPFilterParams) SetLanguagesNil(b bool)`

 SetLanguagesNil sets the value for Languages to be an explicit nil

### UnsetLanguages
`func (o *MCPFilterParams) UnsetLanguages()`

UnsetLanguages ensures that no value is present for Languages, not even an explicit nil
### GetCountries

`func (o *MCPFilterParams) GetCountries() []string`

GetCountries returns the Countries field if non-nil, zero value otherwise.

### GetCountriesOk

`func (o *MCPFilterParams) GetCountriesOk() (*[]string, bool)`

GetCountriesOk returns a tuple with the Countries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountries

`func (o *MCPFilterParams) SetCountries(v []string)`

SetCountries sets Countries field to given value.

### HasCountries

`func (o *MCPFilterParams) HasCountries() bool`

HasCountries returns a boolean if a field has been set.

### SetCountriesNil

`func (o *MCPFilterParams) SetCountriesNil(b bool)`

 SetCountriesNil sets the value for Countries to be an explicit nil

### UnsetCountries
`func (o *MCPFilterParams) UnsetCountries()`

UnsetCountries ensures that no value is present for Countries, not even an explicit nil
### GetCountriesBlacklist

`func (o *MCPFilterParams) GetCountriesBlacklist() []string`

GetCountriesBlacklist returns the CountriesBlacklist field if non-nil, zero value otherwise.

### GetCountriesBlacklistOk

`func (o *MCPFilterParams) GetCountriesBlacklistOk() (*[]string, bool)`

GetCountriesBlacklistOk returns a tuple with the CountriesBlacklist field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountriesBlacklist

`func (o *MCPFilterParams) SetCountriesBlacklist(v []string)`

SetCountriesBlacklist sets CountriesBlacklist field to given value.

### HasCountriesBlacklist

`func (o *MCPFilterParams) HasCountriesBlacklist() bool`

HasCountriesBlacklist returns a boolean if a field has been set.

### SetCountriesBlacklistNil

`func (o *MCPFilterParams) SetCountriesBlacklistNil(b bool)`

 SetCountriesBlacklistNil sets the value for CountriesBlacklist to be an explicit nil

### UnsetCountriesBlacklist
`func (o *MCPFilterParams) UnsetCountriesBlacklist()`

UnsetCountriesBlacklist ensures that no value is present for CountriesBlacklist, not even an explicit nil
### GetContinents

`func (o *MCPFilterParams) GetContinents() []string`

GetContinents returns the Continents field if non-nil, zero value otherwise.

### GetContinentsOk

`func (o *MCPFilterParams) GetContinentsOk() (*[]string, bool)`

GetContinentsOk returns a tuple with the Continents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContinents

`func (o *MCPFilterParams) SetContinents(v []string)`

SetContinents sets Continents field to given value.

### HasContinents

`func (o *MCPFilterParams) HasContinents() bool`

HasContinents returns a boolean if a field has been set.

### SetContinentsNil

`func (o *MCPFilterParams) SetContinentsNil(b bool)`

 SetContinentsNil sets the value for Continents to be an explicit nil

### UnsetContinents
`func (o *MCPFilterParams) UnsetContinents()`

UnsetContinents ensures that no value is present for Continents, not even an explicit nil
### GetSentiment

`func (o *MCPFilterParams) GetSentiment() string`

GetSentiment returns the Sentiment field if non-nil, zero value otherwise.

### GetSentimentOk

`func (o *MCPFilterParams) GetSentimentOk() (*string, bool)`

GetSentimentOk returns a tuple with the Sentiment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentiment

`func (o *MCPFilterParams) SetSentiment(v string)`

SetSentiment sets Sentiment field to given value.

### HasSentiment

`func (o *MCPFilterParams) HasSentiment() bool`

HasSentiment returns a boolean if a field has been set.

### SetSentimentNil

`func (o *MCPFilterParams) SetSentimentNil(b bool)`

 SetSentimentNil sets the value for Sentiment to be an explicit nil

### UnsetSentiment
`func (o *MCPFilterParams) UnsetSentiment()`

UnsetSentiment ensures that no value is present for Sentiment, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


