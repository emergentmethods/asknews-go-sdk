# SeriesConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**StartDatetime** | **time.Time** |  | 
**EndDatetime** | **time.Time** |  | 
**Sampling** | Pointer to **NullableString** |  | [optional] 
**TimeFilter** | Pointer to **NullableString** |  | [optional] 
**Categories** | Pointer to **[]string** |  | [optional] 
**Domains** | Pointer to **[]string** |  | [optional] 
**BadDomainUrl** | Pointer to **[]string** |  | [optional] 
**PageRank** | Pointer to **NullableInt32** |  | [optional] 
**StringGuarantee** | Pointer to **[]string** |  | [optional] 
**StringGuaranteeOp** | Pointer to **NullableString** |  | [optional] 
**ReverseStringGuarantee** | Pointer to **[]string** |  | [optional] 
**EntityGuarantee** | Pointer to **[]string** |  | [optional] 
**EntityGuaranteeOp** | Pointer to **NullableString** |  | [optional] 
**Countries** | Pointer to **[]string** |  | [optional] 
**CountriesBlacklist** | Pointer to **[]string** |  | [optional] 
**Continents** | Pointer to **[]string** |  | [optional] 
**Languages** | Pointer to **[]string** |  | [optional] 
**Sentiment** | Pointer to **NullableString** |  | [optional] 
**ReportingVoice** | Pointer to **[]string** |  | [optional] 
**Provocative** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewSeriesConfig

`func NewSeriesConfig(name string, startDatetime time.Time, endDatetime time.Time, ) *SeriesConfig`

NewSeriesConfig instantiates a new SeriesConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSeriesConfigWithDefaults

`func NewSeriesConfigWithDefaults() *SeriesConfig`

NewSeriesConfigWithDefaults instantiates a new SeriesConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *SeriesConfig) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SeriesConfig) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SeriesConfig) SetName(v string)`

SetName sets Name field to given value.


### GetStartDatetime

`func (o *SeriesConfig) GetStartDatetime() time.Time`

GetStartDatetime returns the StartDatetime field if non-nil, zero value otherwise.

### GetStartDatetimeOk

`func (o *SeriesConfig) GetStartDatetimeOk() (*time.Time, bool)`

GetStartDatetimeOk returns a tuple with the StartDatetime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDatetime

`func (o *SeriesConfig) SetStartDatetime(v time.Time)`

SetStartDatetime sets StartDatetime field to given value.


### GetEndDatetime

`func (o *SeriesConfig) GetEndDatetime() time.Time`

GetEndDatetime returns the EndDatetime field if non-nil, zero value otherwise.

### GetEndDatetimeOk

`func (o *SeriesConfig) GetEndDatetimeOk() (*time.Time, bool)`

GetEndDatetimeOk returns a tuple with the EndDatetime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDatetime

`func (o *SeriesConfig) SetEndDatetime(v time.Time)`

SetEndDatetime sets EndDatetime field to given value.


### GetSampling

`func (o *SeriesConfig) GetSampling() string`

GetSampling returns the Sampling field if non-nil, zero value otherwise.

### GetSamplingOk

`func (o *SeriesConfig) GetSamplingOk() (*string, bool)`

GetSamplingOk returns a tuple with the Sampling field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSampling

`func (o *SeriesConfig) SetSampling(v string)`

SetSampling sets Sampling field to given value.

### HasSampling

`func (o *SeriesConfig) HasSampling() bool`

HasSampling returns a boolean if a field has been set.

### SetSamplingNil

`func (o *SeriesConfig) SetSamplingNil(b bool)`

 SetSamplingNil sets the value for Sampling to be an explicit nil

### UnsetSampling
`func (o *SeriesConfig) UnsetSampling()`

UnsetSampling ensures that no value is present for Sampling, not even an explicit nil
### GetTimeFilter

`func (o *SeriesConfig) GetTimeFilter() string`

GetTimeFilter returns the TimeFilter field if non-nil, zero value otherwise.

### GetTimeFilterOk

`func (o *SeriesConfig) GetTimeFilterOk() (*string, bool)`

GetTimeFilterOk returns a tuple with the TimeFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeFilter

`func (o *SeriesConfig) SetTimeFilter(v string)`

SetTimeFilter sets TimeFilter field to given value.

### HasTimeFilter

`func (o *SeriesConfig) HasTimeFilter() bool`

HasTimeFilter returns a boolean if a field has been set.

### SetTimeFilterNil

`func (o *SeriesConfig) SetTimeFilterNil(b bool)`

 SetTimeFilterNil sets the value for TimeFilter to be an explicit nil

### UnsetTimeFilter
`func (o *SeriesConfig) UnsetTimeFilter()`

UnsetTimeFilter ensures that no value is present for TimeFilter, not even an explicit nil
### GetCategories

`func (o *SeriesConfig) GetCategories() []string`

GetCategories returns the Categories field if non-nil, zero value otherwise.

### GetCategoriesOk

`func (o *SeriesConfig) GetCategoriesOk() (*[]string, bool)`

GetCategoriesOk returns a tuple with the Categories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategories

`func (o *SeriesConfig) SetCategories(v []string)`

SetCategories sets Categories field to given value.

### HasCategories

`func (o *SeriesConfig) HasCategories() bool`

HasCategories returns a boolean if a field has been set.

### SetCategoriesNil

`func (o *SeriesConfig) SetCategoriesNil(b bool)`

 SetCategoriesNil sets the value for Categories to be an explicit nil

### UnsetCategories
`func (o *SeriesConfig) UnsetCategories()`

UnsetCategories ensures that no value is present for Categories, not even an explicit nil
### GetDomains

`func (o *SeriesConfig) GetDomains() []string`

GetDomains returns the Domains field if non-nil, zero value otherwise.

### GetDomainsOk

`func (o *SeriesConfig) GetDomainsOk() (*[]string, bool)`

GetDomainsOk returns a tuple with the Domains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomains

`func (o *SeriesConfig) SetDomains(v []string)`

SetDomains sets Domains field to given value.

### HasDomains

`func (o *SeriesConfig) HasDomains() bool`

HasDomains returns a boolean if a field has been set.

### SetDomainsNil

`func (o *SeriesConfig) SetDomainsNil(b bool)`

 SetDomainsNil sets the value for Domains to be an explicit nil

### UnsetDomains
`func (o *SeriesConfig) UnsetDomains()`

UnsetDomains ensures that no value is present for Domains, not even an explicit nil
### GetBadDomainUrl

`func (o *SeriesConfig) GetBadDomainUrl() []string`

GetBadDomainUrl returns the BadDomainUrl field if non-nil, zero value otherwise.

### GetBadDomainUrlOk

`func (o *SeriesConfig) GetBadDomainUrlOk() (*[]string, bool)`

GetBadDomainUrlOk returns a tuple with the BadDomainUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBadDomainUrl

`func (o *SeriesConfig) SetBadDomainUrl(v []string)`

SetBadDomainUrl sets BadDomainUrl field to given value.

### HasBadDomainUrl

`func (o *SeriesConfig) HasBadDomainUrl() bool`

HasBadDomainUrl returns a boolean if a field has been set.

### SetBadDomainUrlNil

`func (o *SeriesConfig) SetBadDomainUrlNil(b bool)`

 SetBadDomainUrlNil sets the value for BadDomainUrl to be an explicit nil

### UnsetBadDomainUrl
`func (o *SeriesConfig) UnsetBadDomainUrl()`

UnsetBadDomainUrl ensures that no value is present for BadDomainUrl, not even an explicit nil
### GetPageRank

`func (o *SeriesConfig) GetPageRank() int32`

GetPageRank returns the PageRank field if non-nil, zero value otherwise.

### GetPageRankOk

`func (o *SeriesConfig) GetPageRankOk() (*int32, bool)`

GetPageRankOk returns a tuple with the PageRank field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageRank

`func (o *SeriesConfig) SetPageRank(v int32)`

SetPageRank sets PageRank field to given value.

### HasPageRank

`func (o *SeriesConfig) HasPageRank() bool`

HasPageRank returns a boolean if a field has been set.

### SetPageRankNil

`func (o *SeriesConfig) SetPageRankNil(b bool)`

 SetPageRankNil sets the value for PageRank to be an explicit nil

### UnsetPageRank
`func (o *SeriesConfig) UnsetPageRank()`

UnsetPageRank ensures that no value is present for PageRank, not even an explicit nil
### GetStringGuarantee

`func (o *SeriesConfig) GetStringGuarantee() []string`

GetStringGuarantee returns the StringGuarantee field if non-nil, zero value otherwise.

### GetStringGuaranteeOk

`func (o *SeriesConfig) GetStringGuaranteeOk() (*[]string, bool)`

GetStringGuaranteeOk returns a tuple with the StringGuarantee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStringGuarantee

`func (o *SeriesConfig) SetStringGuarantee(v []string)`

SetStringGuarantee sets StringGuarantee field to given value.

### HasStringGuarantee

`func (o *SeriesConfig) HasStringGuarantee() bool`

HasStringGuarantee returns a boolean if a field has been set.

### SetStringGuaranteeNil

`func (o *SeriesConfig) SetStringGuaranteeNil(b bool)`

 SetStringGuaranteeNil sets the value for StringGuarantee to be an explicit nil

### UnsetStringGuarantee
`func (o *SeriesConfig) UnsetStringGuarantee()`

UnsetStringGuarantee ensures that no value is present for StringGuarantee, not even an explicit nil
### GetStringGuaranteeOp

`func (o *SeriesConfig) GetStringGuaranteeOp() string`

GetStringGuaranteeOp returns the StringGuaranteeOp field if non-nil, zero value otherwise.

### GetStringGuaranteeOpOk

`func (o *SeriesConfig) GetStringGuaranteeOpOk() (*string, bool)`

GetStringGuaranteeOpOk returns a tuple with the StringGuaranteeOp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStringGuaranteeOp

`func (o *SeriesConfig) SetStringGuaranteeOp(v string)`

SetStringGuaranteeOp sets StringGuaranteeOp field to given value.

### HasStringGuaranteeOp

`func (o *SeriesConfig) HasStringGuaranteeOp() bool`

HasStringGuaranteeOp returns a boolean if a field has been set.

### SetStringGuaranteeOpNil

`func (o *SeriesConfig) SetStringGuaranteeOpNil(b bool)`

 SetStringGuaranteeOpNil sets the value for StringGuaranteeOp to be an explicit nil

### UnsetStringGuaranteeOp
`func (o *SeriesConfig) UnsetStringGuaranteeOp()`

UnsetStringGuaranteeOp ensures that no value is present for StringGuaranteeOp, not even an explicit nil
### GetReverseStringGuarantee

`func (o *SeriesConfig) GetReverseStringGuarantee() []string`

GetReverseStringGuarantee returns the ReverseStringGuarantee field if non-nil, zero value otherwise.

### GetReverseStringGuaranteeOk

`func (o *SeriesConfig) GetReverseStringGuaranteeOk() (*[]string, bool)`

GetReverseStringGuaranteeOk returns a tuple with the ReverseStringGuarantee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReverseStringGuarantee

`func (o *SeriesConfig) SetReverseStringGuarantee(v []string)`

SetReverseStringGuarantee sets ReverseStringGuarantee field to given value.

### HasReverseStringGuarantee

`func (o *SeriesConfig) HasReverseStringGuarantee() bool`

HasReverseStringGuarantee returns a boolean if a field has been set.

### SetReverseStringGuaranteeNil

`func (o *SeriesConfig) SetReverseStringGuaranteeNil(b bool)`

 SetReverseStringGuaranteeNil sets the value for ReverseStringGuarantee to be an explicit nil

### UnsetReverseStringGuarantee
`func (o *SeriesConfig) UnsetReverseStringGuarantee()`

UnsetReverseStringGuarantee ensures that no value is present for ReverseStringGuarantee, not even an explicit nil
### GetEntityGuarantee

`func (o *SeriesConfig) GetEntityGuarantee() []string`

GetEntityGuarantee returns the EntityGuarantee field if non-nil, zero value otherwise.

### GetEntityGuaranteeOk

`func (o *SeriesConfig) GetEntityGuaranteeOk() (*[]string, bool)`

GetEntityGuaranteeOk returns a tuple with the EntityGuarantee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityGuarantee

`func (o *SeriesConfig) SetEntityGuarantee(v []string)`

SetEntityGuarantee sets EntityGuarantee field to given value.

### HasEntityGuarantee

`func (o *SeriesConfig) HasEntityGuarantee() bool`

HasEntityGuarantee returns a boolean if a field has been set.

### SetEntityGuaranteeNil

`func (o *SeriesConfig) SetEntityGuaranteeNil(b bool)`

 SetEntityGuaranteeNil sets the value for EntityGuarantee to be an explicit nil

### UnsetEntityGuarantee
`func (o *SeriesConfig) UnsetEntityGuarantee()`

UnsetEntityGuarantee ensures that no value is present for EntityGuarantee, not even an explicit nil
### GetEntityGuaranteeOp

`func (o *SeriesConfig) GetEntityGuaranteeOp() string`

GetEntityGuaranteeOp returns the EntityGuaranteeOp field if non-nil, zero value otherwise.

### GetEntityGuaranteeOpOk

`func (o *SeriesConfig) GetEntityGuaranteeOpOk() (*string, bool)`

GetEntityGuaranteeOpOk returns a tuple with the EntityGuaranteeOp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityGuaranteeOp

`func (o *SeriesConfig) SetEntityGuaranteeOp(v string)`

SetEntityGuaranteeOp sets EntityGuaranteeOp field to given value.

### HasEntityGuaranteeOp

`func (o *SeriesConfig) HasEntityGuaranteeOp() bool`

HasEntityGuaranteeOp returns a boolean if a field has been set.

### SetEntityGuaranteeOpNil

`func (o *SeriesConfig) SetEntityGuaranteeOpNil(b bool)`

 SetEntityGuaranteeOpNil sets the value for EntityGuaranteeOp to be an explicit nil

### UnsetEntityGuaranteeOp
`func (o *SeriesConfig) UnsetEntityGuaranteeOp()`

UnsetEntityGuaranteeOp ensures that no value is present for EntityGuaranteeOp, not even an explicit nil
### GetCountries

`func (o *SeriesConfig) GetCountries() []string`

GetCountries returns the Countries field if non-nil, zero value otherwise.

### GetCountriesOk

`func (o *SeriesConfig) GetCountriesOk() (*[]string, bool)`

GetCountriesOk returns a tuple with the Countries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountries

`func (o *SeriesConfig) SetCountries(v []string)`

SetCountries sets Countries field to given value.

### HasCountries

`func (o *SeriesConfig) HasCountries() bool`

HasCountries returns a boolean if a field has been set.

### SetCountriesNil

`func (o *SeriesConfig) SetCountriesNil(b bool)`

 SetCountriesNil sets the value for Countries to be an explicit nil

### UnsetCountries
`func (o *SeriesConfig) UnsetCountries()`

UnsetCountries ensures that no value is present for Countries, not even an explicit nil
### GetCountriesBlacklist

`func (o *SeriesConfig) GetCountriesBlacklist() []string`

GetCountriesBlacklist returns the CountriesBlacklist field if non-nil, zero value otherwise.

### GetCountriesBlacklistOk

`func (o *SeriesConfig) GetCountriesBlacklistOk() (*[]string, bool)`

GetCountriesBlacklistOk returns a tuple with the CountriesBlacklist field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountriesBlacklist

`func (o *SeriesConfig) SetCountriesBlacklist(v []string)`

SetCountriesBlacklist sets CountriesBlacklist field to given value.

### HasCountriesBlacklist

`func (o *SeriesConfig) HasCountriesBlacklist() bool`

HasCountriesBlacklist returns a boolean if a field has been set.

### SetCountriesBlacklistNil

`func (o *SeriesConfig) SetCountriesBlacklistNil(b bool)`

 SetCountriesBlacklistNil sets the value for CountriesBlacklist to be an explicit nil

### UnsetCountriesBlacklist
`func (o *SeriesConfig) UnsetCountriesBlacklist()`

UnsetCountriesBlacklist ensures that no value is present for CountriesBlacklist, not even an explicit nil
### GetContinents

`func (o *SeriesConfig) GetContinents() []string`

GetContinents returns the Continents field if non-nil, zero value otherwise.

### GetContinentsOk

`func (o *SeriesConfig) GetContinentsOk() (*[]string, bool)`

GetContinentsOk returns a tuple with the Continents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContinents

`func (o *SeriesConfig) SetContinents(v []string)`

SetContinents sets Continents field to given value.

### HasContinents

`func (o *SeriesConfig) HasContinents() bool`

HasContinents returns a boolean if a field has been set.

### SetContinentsNil

`func (o *SeriesConfig) SetContinentsNil(b bool)`

 SetContinentsNil sets the value for Continents to be an explicit nil

### UnsetContinents
`func (o *SeriesConfig) UnsetContinents()`

UnsetContinents ensures that no value is present for Continents, not even an explicit nil
### GetLanguages

`func (o *SeriesConfig) GetLanguages() []string`

GetLanguages returns the Languages field if non-nil, zero value otherwise.

### GetLanguagesOk

`func (o *SeriesConfig) GetLanguagesOk() (*[]string, bool)`

GetLanguagesOk returns a tuple with the Languages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguages

`func (o *SeriesConfig) SetLanguages(v []string)`

SetLanguages sets Languages field to given value.

### HasLanguages

`func (o *SeriesConfig) HasLanguages() bool`

HasLanguages returns a boolean if a field has been set.

### SetLanguagesNil

`func (o *SeriesConfig) SetLanguagesNil(b bool)`

 SetLanguagesNil sets the value for Languages to be an explicit nil

### UnsetLanguages
`func (o *SeriesConfig) UnsetLanguages()`

UnsetLanguages ensures that no value is present for Languages, not even an explicit nil
### GetSentiment

`func (o *SeriesConfig) GetSentiment() string`

GetSentiment returns the Sentiment field if non-nil, zero value otherwise.

### GetSentimentOk

`func (o *SeriesConfig) GetSentimentOk() (*string, bool)`

GetSentimentOk returns a tuple with the Sentiment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentiment

`func (o *SeriesConfig) SetSentiment(v string)`

SetSentiment sets Sentiment field to given value.

### HasSentiment

`func (o *SeriesConfig) HasSentiment() bool`

HasSentiment returns a boolean if a field has been set.

### SetSentimentNil

`func (o *SeriesConfig) SetSentimentNil(b bool)`

 SetSentimentNil sets the value for Sentiment to be an explicit nil

### UnsetSentiment
`func (o *SeriesConfig) UnsetSentiment()`

UnsetSentiment ensures that no value is present for Sentiment, not even an explicit nil
### GetReportingVoice

`func (o *SeriesConfig) GetReportingVoice() []string`

GetReportingVoice returns the ReportingVoice field if non-nil, zero value otherwise.

### GetReportingVoiceOk

`func (o *SeriesConfig) GetReportingVoiceOk() (*[]string, bool)`

GetReportingVoiceOk returns a tuple with the ReportingVoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportingVoice

`func (o *SeriesConfig) SetReportingVoice(v []string)`

SetReportingVoice sets ReportingVoice field to given value.

### HasReportingVoice

`func (o *SeriesConfig) HasReportingVoice() bool`

HasReportingVoice returns a boolean if a field has been set.

### SetReportingVoiceNil

`func (o *SeriesConfig) SetReportingVoiceNil(b bool)`

 SetReportingVoiceNil sets the value for ReportingVoice to be an explicit nil

### UnsetReportingVoice
`func (o *SeriesConfig) UnsetReportingVoice()`

UnsetReportingVoice ensures that no value is present for ReportingVoice, not even an explicit nil
### GetProvocative

`func (o *SeriesConfig) GetProvocative() string`

GetProvocative returns the Provocative field if non-nil, zero value otherwise.

### GetProvocativeOk

`func (o *SeriesConfig) GetProvocativeOk() (*string, bool)`

GetProvocativeOk returns a tuple with the Provocative field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvocative

`func (o *SeriesConfig) SetProvocative(v string)`

SetProvocative sets Provocative field to given value.

### HasProvocative

`func (o *SeriesConfig) HasProvocative() bool`

HasProvocative returns a boolean if a field has been set.

### SetProvocativeNil

`func (o *SeriesConfig) SetProvocativeNil(b bool)`

 SetProvocativeNil sets the value for Provocative to be an explicit nil

### UnsetProvocative
`func (o *SeriesConfig) UnsetProvocative()`

UnsetProvocative ensures that no value is present for Provocative, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


