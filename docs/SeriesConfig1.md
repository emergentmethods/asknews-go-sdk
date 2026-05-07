# SeriesConfig1

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

### NewSeriesConfig1

`func NewSeriesConfig1(name string, startDatetime time.Time, endDatetime time.Time, ) *SeriesConfig1`

NewSeriesConfig1 instantiates a new SeriesConfig1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSeriesConfig1WithDefaults

`func NewSeriesConfig1WithDefaults() *SeriesConfig1`

NewSeriesConfig1WithDefaults instantiates a new SeriesConfig1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *SeriesConfig1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SeriesConfig1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SeriesConfig1) SetName(v string)`

SetName sets Name field to given value.


### GetStartDatetime

`func (o *SeriesConfig1) GetStartDatetime() time.Time`

GetStartDatetime returns the StartDatetime field if non-nil, zero value otherwise.

### GetStartDatetimeOk

`func (o *SeriesConfig1) GetStartDatetimeOk() (*time.Time, bool)`

GetStartDatetimeOk returns a tuple with the StartDatetime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDatetime

`func (o *SeriesConfig1) SetStartDatetime(v time.Time)`

SetStartDatetime sets StartDatetime field to given value.


### GetEndDatetime

`func (o *SeriesConfig1) GetEndDatetime() time.Time`

GetEndDatetime returns the EndDatetime field if non-nil, zero value otherwise.

### GetEndDatetimeOk

`func (o *SeriesConfig1) GetEndDatetimeOk() (*time.Time, bool)`

GetEndDatetimeOk returns a tuple with the EndDatetime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDatetime

`func (o *SeriesConfig1) SetEndDatetime(v time.Time)`

SetEndDatetime sets EndDatetime field to given value.


### GetSampling

`func (o *SeriesConfig1) GetSampling() string`

GetSampling returns the Sampling field if non-nil, zero value otherwise.

### GetSamplingOk

`func (o *SeriesConfig1) GetSamplingOk() (*string, bool)`

GetSamplingOk returns a tuple with the Sampling field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSampling

`func (o *SeriesConfig1) SetSampling(v string)`

SetSampling sets Sampling field to given value.

### HasSampling

`func (o *SeriesConfig1) HasSampling() bool`

HasSampling returns a boolean if a field has been set.

### SetSamplingNil

`func (o *SeriesConfig1) SetSamplingNil(b bool)`

 SetSamplingNil sets the value for Sampling to be an explicit nil

### UnsetSampling
`func (o *SeriesConfig1) UnsetSampling()`

UnsetSampling ensures that no value is present for Sampling, not even an explicit nil
### GetTimeFilter

`func (o *SeriesConfig1) GetTimeFilter() string`

GetTimeFilter returns the TimeFilter field if non-nil, zero value otherwise.

### GetTimeFilterOk

`func (o *SeriesConfig1) GetTimeFilterOk() (*string, bool)`

GetTimeFilterOk returns a tuple with the TimeFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeFilter

`func (o *SeriesConfig1) SetTimeFilter(v string)`

SetTimeFilter sets TimeFilter field to given value.

### HasTimeFilter

`func (o *SeriesConfig1) HasTimeFilter() bool`

HasTimeFilter returns a boolean if a field has been set.

### SetTimeFilterNil

`func (o *SeriesConfig1) SetTimeFilterNil(b bool)`

 SetTimeFilterNil sets the value for TimeFilter to be an explicit nil

### UnsetTimeFilter
`func (o *SeriesConfig1) UnsetTimeFilter()`

UnsetTimeFilter ensures that no value is present for TimeFilter, not even an explicit nil
### GetCategories

`func (o *SeriesConfig1) GetCategories() []string`

GetCategories returns the Categories field if non-nil, zero value otherwise.

### GetCategoriesOk

`func (o *SeriesConfig1) GetCategoriesOk() (*[]string, bool)`

GetCategoriesOk returns a tuple with the Categories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategories

`func (o *SeriesConfig1) SetCategories(v []string)`

SetCategories sets Categories field to given value.

### HasCategories

`func (o *SeriesConfig1) HasCategories() bool`

HasCategories returns a boolean if a field has been set.

### SetCategoriesNil

`func (o *SeriesConfig1) SetCategoriesNil(b bool)`

 SetCategoriesNil sets the value for Categories to be an explicit nil

### UnsetCategories
`func (o *SeriesConfig1) UnsetCategories()`

UnsetCategories ensures that no value is present for Categories, not even an explicit nil
### GetDomains

`func (o *SeriesConfig1) GetDomains() []string`

GetDomains returns the Domains field if non-nil, zero value otherwise.

### GetDomainsOk

`func (o *SeriesConfig1) GetDomainsOk() (*[]string, bool)`

GetDomainsOk returns a tuple with the Domains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomains

`func (o *SeriesConfig1) SetDomains(v []string)`

SetDomains sets Domains field to given value.

### HasDomains

`func (o *SeriesConfig1) HasDomains() bool`

HasDomains returns a boolean if a field has been set.

### SetDomainsNil

`func (o *SeriesConfig1) SetDomainsNil(b bool)`

 SetDomainsNil sets the value for Domains to be an explicit nil

### UnsetDomains
`func (o *SeriesConfig1) UnsetDomains()`

UnsetDomains ensures that no value is present for Domains, not even an explicit nil
### GetBadDomainUrl

`func (o *SeriesConfig1) GetBadDomainUrl() []string`

GetBadDomainUrl returns the BadDomainUrl field if non-nil, zero value otherwise.

### GetBadDomainUrlOk

`func (o *SeriesConfig1) GetBadDomainUrlOk() (*[]string, bool)`

GetBadDomainUrlOk returns a tuple with the BadDomainUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBadDomainUrl

`func (o *SeriesConfig1) SetBadDomainUrl(v []string)`

SetBadDomainUrl sets BadDomainUrl field to given value.

### HasBadDomainUrl

`func (o *SeriesConfig1) HasBadDomainUrl() bool`

HasBadDomainUrl returns a boolean if a field has been set.

### SetBadDomainUrlNil

`func (o *SeriesConfig1) SetBadDomainUrlNil(b bool)`

 SetBadDomainUrlNil sets the value for BadDomainUrl to be an explicit nil

### UnsetBadDomainUrl
`func (o *SeriesConfig1) UnsetBadDomainUrl()`

UnsetBadDomainUrl ensures that no value is present for BadDomainUrl, not even an explicit nil
### GetPageRank

`func (o *SeriesConfig1) GetPageRank() int32`

GetPageRank returns the PageRank field if non-nil, zero value otherwise.

### GetPageRankOk

`func (o *SeriesConfig1) GetPageRankOk() (*int32, bool)`

GetPageRankOk returns a tuple with the PageRank field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageRank

`func (o *SeriesConfig1) SetPageRank(v int32)`

SetPageRank sets PageRank field to given value.

### HasPageRank

`func (o *SeriesConfig1) HasPageRank() bool`

HasPageRank returns a boolean if a field has been set.

### SetPageRankNil

`func (o *SeriesConfig1) SetPageRankNil(b bool)`

 SetPageRankNil sets the value for PageRank to be an explicit nil

### UnsetPageRank
`func (o *SeriesConfig1) UnsetPageRank()`

UnsetPageRank ensures that no value is present for PageRank, not even an explicit nil
### GetStringGuarantee

`func (o *SeriesConfig1) GetStringGuarantee() []string`

GetStringGuarantee returns the StringGuarantee field if non-nil, zero value otherwise.

### GetStringGuaranteeOk

`func (o *SeriesConfig1) GetStringGuaranteeOk() (*[]string, bool)`

GetStringGuaranteeOk returns a tuple with the StringGuarantee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStringGuarantee

`func (o *SeriesConfig1) SetStringGuarantee(v []string)`

SetStringGuarantee sets StringGuarantee field to given value.

### HasStringGuarantee

`func (o *SeriesConfig1) HasStringGuarantee() bool`

HasStringGuarantee returns a boolean if a field has been set.

### SetStringGuaranteeNil

`func (o *SeriesConfig1) SetStringGuaranteeNil(b bool)`

 SetStringGuaranteeNil sets the value for StringGuarantee to be an explicit nil

### UnsetStringGuarantee
`func (o *SeriesConfig1) UnsetStringGuarantee()`

UnsetStringGuarantee ensures that no value is present for StringGuarantee, not even an explicit nil
### GetStringGuaranteeOp

`func (o *SeriesConfig1) GetStringGuaranteeOp() string`

GetStringGuaranteeOp returns the StringGuaranteeOp field if non-nil, zero value otherwise.

### GetStringGuaranteeOpOk

`func (o *SeriesConfig1) GetStringGuaranteeOpOk() (*string, bool)`

GetStringGuaranteeOpOk returns a tuple with the StringGuaranteeOp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStringGuaranteeOp

`func (o *SeriesConfig1) SetStringGuaranteeOp(v string)`

SetStringGuaranteeOp sets StringGuaranteeOp field to given value.

### HasStringGuaranteeOp

`func (o *SeriesConfig1) HasStringGuaranteeOp() bool`

HasStringGuaranteeOp returns a boolean if a field has been set.

### SetStringGuaranteeOpNil

`func (o *SeriesConfig1) SetStringGuaranteeOpNil(b bool)`

 SetStringGuaranteeOpNil sets the value for StringGuaranteeOp to be an explicit nil

### UnsetStringGuaranteeOp
`func (o *SeriesConfig1) UnsetStringGuaranteeOp()`

UnsetStringGuaranteeOp ensures that no value is present for StringGuaranteeOp, not even an explicit nil
### GetReverseStringGuarantee

`func (o *SeriesConfig1) GetReverseStringGuarantee() []string`

GetReverseStringGuarantee returns the ReverseStringGuarantee field if non-nil, zero value otherwise.

### GetReverseStringGuaranteeOk

`func (o *SeriesConfig1) GetReverseStringGuaranteeOk() (*[]string, bool)`

GetReverseStringGuaranteeOk returns a tuple with the ReverseStringGuarantee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReverseStringGuarantee

`func (o *SeriesConfig1) SetReverseStringGuarantee(v []string)`

SetReverseStringGuarantee sets ReverseStringGuarantee field to given value.

### HasReverseStringGuarantee

`func (o *SeriesConfig1) HasReverseStringGuarantee() bool`

HasReverseStringGuarantee returns a boolean if a field has been set.

### SetReverseStringGuaranteeNil

`func (o *SeriesConfig1) SetReverseStringGuaranteeNil(b bool)`

 SetReverseStringGuaranteeNil sets the value for ReverseStringGuarantee to be an explicit nil

### UnsetReverseStringGuarantee
`func (o *SeriesConfig1) UnsetReverseStringGuarantee()`

UnsetReverseStringGuarantee ensures that no value is present for ReverseStringGuarantee, not even an explicit nil
### GetEntityGuarantee

`func (o *SeriesConfig1) GetEntityGuarantee() []string`

GetEntityGuarantee returns the EntityGuarantee field if non-nil, zero value otherwise.

### GetEntityGuaranteeOk

`func (o *SeriesConfig1) GetEntityGuaranteeOk() (*[]string, bool)`

GetEntityGuaranteeOk returns a tuple with the EntityGuarantee field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityGuarantee

`func (o *SeriesConfig1) SetEntityGuarantee(v []string)`

SetEntityGuarantee sets EntityGuarantee field to given value.

### HasEntityGuarantee

`func (o *SeriesConfig1) HasEntityGuarantee() bool`

HasEntityGuarantee returns a boolean if a field has been set.

### SetEntityGuaranteeNil

`func (o *SeriesConfig1) SetEntityGuaranteeNil(b bool)`

 SetEntityGuaranteeNil sets the value for EntityGuarantee to be an explicit nil

### UnsetEntityGuarantee
`func (o *SeriesConfig1) UnsetEntityGuarantee()`

UnsetEntityGuarantee ensures that no value is present for EntityGuarantee, not even an explicit nil
### GetEntityGuaranteeOp

`func (o *SeriesConfig1) GetEntityGuaranteeOp() string`

GetEntityGuaranteeOp returns the EntityGuaranteeOp field if non-nil, zero value otherwise.

### GetEntityGuaranteeOpOk

`func (o *SeriesConfig1) GetEntityGuaranteeOpOk() (*string, bool)`

GetEntityGuaranteeOpOk returns a tuple with the EntityGuaranteeOp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityGuaranteeOp

`func (o *SeriesConfig1) SetEntityGuaranteeOp(v string)`

SetEntityGuaranteeOp sets EntityGuaranteeOp field to given value.

### HasEntityGuaranteeOp

`func (o *SeriesConfig1) HasEntityGuaranteeOp() bool`

HasEntityGuaranteeOp returns a boolean if a field has been set.

### SetEntityGuaranteeOpNil

`func (o *SeriesConfig1) SetEntityGuaranteeOpNil(b bool)`

 SetEntityGuaranteeOpNil sets the value for EntityGuaranteeOp to be an explicit nil

### UnsetEntityGuaranteeOp
`func (o *SeriesConfig1) UnsetEntityGuaranteeOp()`

UnsetEntityGuaranteeOp ensures that no value is present for EntityGuaranteeOp, not even an explicit nil
### GetCountries

`func (o *SeriesConfig1) GetCountries() []string`

GetCountries returns the Countries field if non-nil, zero value otherwise.

### GetCountriesOk

`func (o *SeriesConfig1) GetCountriesOk() (*[]string, bool)`

GetCountriesOk returns a tuple with the Countries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountries

`func (o *SeriesConfig1) SetCountries(v []string)`

SetCountries sets Countries field to given value.

### HasCountries

`func (o *SeriesConfig1) HasCountries() bool`

HasCountries returns a boolean if a field has been set.

### SetCountriesNil

`func (o *SeriesConfig1) SetCountriesNil(b bool)`

 SetCountriesNil sets the value for Countries to be an explicit nil

### UnsetCountries
`func (o *SeriesConfig1) UnsetCountries()`

UnsetCountries ensures that no value is present for Countries, not even an explicit nil
### GetCountriesBlacklist

`func (o *SeriesConfig1) GetCountriesBlacklist() []string`

GetCountriesBlacklist returns the CountriesBlacklist field if non-nil, zero value otherwise.

### GetCountriesBlacklistOk

`func (o *SeriesConfig1) GetCountriesBlacklistOk() (*[]string, bool)`

GetCountriesBlacklistOk returns a tuple with the CountriesBlacklist field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountriesBlacklist

`func (o *SeriesConfig1) SetCountriesBlacklist(v []string)`

SetCountriesBlacklist sets CountriesBlacklist field to given value.

### HasCountriesBlacklist

`func (o *SeriesConfig1) HasCountriesBlacklist() bool`

HasCountriesBlacklist returns a boolean if a field has been set.

### SetCountriesBlacklistNil

`func (o *SeriesConfig1) SetCountriesBlacklistNil(b bool)`

 SetCountriesBlacklistNil sets the value for CountriesBlacklist to be an explicit nil

### UnsetCountriesBlacklist
`func (o *SeriesConfig1) UnsetCountriesBlacklist()`

UnsetCountriesBlacklist ensures that no value is present for CountriesBlacklist, not even an explicit nil
### GetContinents

`func (o *SeriesConfig1) GetContinents() []string`

GetContinents returns the Continents field if non-nil, zero value otherwise.

### GetContinentsOk

`func (o *SeriesConfig1) GetContinentsOk() (*[]string, bool)`

GetContinentsOk returns a tuple with the Continents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContinents

`func (o *SeriesConfig1) SetContinents(v []string)`

SetContinents sets Continents field to given value.

### HasContinents

`func (o *SeriesConfig1) HasContinents() bool`

HasContinents returns a boolean if a field has been set.

### SetContinentsNil

`func (o *SeriesConfig1) SetContinentsNil(b bool)`

 SetContinentsNil sets the value for Continents to be an explicit nil

### UnsetContinents
`func (o *SeriesConfig1) UnsetContinents()`

UnsetContinents ensures that no value is present for Continents, not even an explicit nil
### GetLanguages

`func (o *SeriesConfig1) GetLanguages() []string`

GetLanguages returns the Languages field if non-nil, zero value otherwise.

### GetLanguagesOk

`func (o *SeriesConfig1) GetLanguagesOk() (*[]string, bool)`

GetLanguagesOk returns a tuple with the Languages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguages

`func (o *SeriesConfig1) SetLanguages(v []string)`

SetLanguages sets Languages field to given value.

### HasLanguages

`func (o *SeriesConfig1) HasLanguages() bool`

HasLanguages returns a boolean if a field has been set.

### SetLanguagesNil

`func (o *SeriesConfig1) SetLanguagesNil(b bool)`

 SetLanguagesNil sets the value for Languages to be an explicit nil

### UnsetLanguages
`func (o *SeriesConfig1) UnsetLanguages()`

UnsetLanguages ensures that no value is present for Languages, not even an explicit nil
### GetSentiment

`func (o *SeriesConfig1) GetSentiment() string`

GetSentiment returns the Sentiment field if non-nil, zero value otherwise.

### GetSentimentOk

`func (o *SeriesConfig1) GetSentimentOk() (*string, bool)`

GetSentimentOk returns a tuple with the Sentiment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentiment

`func (o *SeriesConfig1) SetSentiment(v string)`

SetSentiment sets Sentiment field to given value.

### HasSentiment

`func (o *SeriesConfig1) HasSentiment() bool`

HasSentiment returns a boolean if a field has been set.

### SetSentimentNil

`func (o *SeriesConfig1) SetSentimentNil(b bool)`

 SetSentimentNil sets the value for Sentiment to be an explicit nil

### UnsetSentiment
`func (o *SeriesConfig1) UnsetSentiment()`

UnsetSentiment ensures that no value is present for Sentiment, not even an explicit nil
### GetReportingVoice

`func (o *SeriesConfig1) GetReportingVoice() []string`

GetReportingVoice returns the ReportingVoice field if non-nil, zero value otherwise.

### GetReportingVoiceOk

`func (o *SeriesConfig1) GetReportingVoiceOk() (*[]string, bool)`

GetReportingVoiceOk returns a tuple with the ReportingVoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportingVoice

`func (o *SeriesConfig1) SetReportingVoice(v []string)`

SetReportingVoice sets ReportingVoice field to given value.

### HasReportingVoice

`func (o *SeriesConfig1) HasReportingVoice() bool`

HasReportingVoice returns a boolean if a field has been set.

### SetReportingVoiceNil

`func (o *SeriesConfig1) SetReportingVoiceNil(b bool)`

 SetReportingVoiceNil sets the value for ReportingVoice to be an explicit nil

### UnsetReportingVoice
`func (o *SeriesConfig1) UnsetReportingVoice()`

UnsetReportingVoice ensures that no value is present for ReportingVoice, not even an explicit nil
### GetProvocative

`func (o *SeriesConfig1) GetProvocative() string`

GetProvocative returns the Provocative field if non-nil, zero value otherwise.

### GetProvocativeOk

`func (o *SeriesConfig1) GetProvocativeOk() (*string, bool)`

GetProvocativeOk returns a tuple with the Provocative field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvocative

`func (o *SeriesConfig1) SetProvocative(v string)`

SetProvocative sets Provocative field to given value.

### HasProvocative

`func (o *SeriesConfig1) HasProvocative() bool`

HasProvocative returns a boolean if a field has been set.

### SetProvocativeNil

`func (o *SeriesConfig1) SetProvocativeNil(b bool)`

 SetProvocativeNil sets the value for Provocative to be an explicit nil

### UnsetProvocative
`func (o *SeriesConfig1) UnsetProvocative()`

UnsetProvocative ensures that no value is present for Provocative, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


