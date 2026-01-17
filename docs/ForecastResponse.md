# ForecastResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Forecast** | **string** |  | 
**ResolutionCriteria** | **string** |  | 
**Date** | **time.Time** |  | 
**Reasoning** | **string** |  | 
**Sources** | [**[]SearchResponseDictItem**](SearchResponseDictItem.md) |  | 
**Timeline** | **[]string** |  | 
**OppositeRequest** | **string** |  | 
**Confidence** | **float32** |  | 
**Choice** | [**Choice**](Choice.md) |  | 
**LlmConfidence** | **int32** |  | 
**ModelUsed** | **string** |  | 
**Likelihood** | **string** |  | 
**Probability** | **int32** |  | 
**WebSearchResults** | [**[]WebSearchResult**](WebSearchResult.md) |  | 
**Summary** | **string** |  | 
**KeyPeople** | [**[]KeyPerson**](KeyPerson.md) |  | 
**KeyFacets** | **[]string** |  | 
**ReconciledInformation** | **string** |  | 
**CandidateModels** | **[]string** |  | 
**UniqueInformation** | **string** |  | 
**ExpertInformation** | Pointer to **map[string]interface{}** |  | [optional] [default to {}]

## Methods

### NewForecastResponse

`func NewForecastResponse(forecast string, resolutionCriteria string, date time.Time, reasoning string, sources []SearchResponseDictItem, timeline []string, oppositeRequest string, confidence float32, choice Choice, llmConfidence int32, modelUsed string, likelihood string, probability int32, webSearchResults []WebSearchResult, summary string, keyPeople []KeyPerson, keyFacets []string, reconciledInformation string, candidateModels []string, uniqueInformation string, ) *ForecastResponse`

NewForecastResponse instantiates a new ForecastResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewForecastResponseWithDefaults

`func NewForecastResponseWithDefaults() *ForecastResponse`

NewForecastResponseWithDefaults instantiates a new ForecastResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetForecast

`func (o *ForecastResponse) GetForecast() string`

GetForecast returns the Forecast field if non-nil, zero value otherwise.

### GetForecastOk

`func (o *ForecastResponse) GetForecastOk() (*string, bool)`

GetForecastOk returns a tuple with the Forecast field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForecast

`func (o *ForecastResponse) SetForecast(v string)`

SetForecast sets Forecast field to given value.


### GetResolutionCriteria

`func (o *ForecastResponse) GetResolutionCriteria() string`

GetResolutionCriteria returns the ResolutionCriteria field if non-nil, zero value otherwise.

### GetResolutionCriteriaOk

`func (o *ForecastResponse) GetResolutionCriteriaOk() (*string, bool)`

GetResolutionCriteriaOk returns a tuple with the ResolutionCriteria field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolutionCriteria

`func (o *ForecastResponse) SetResolutionCriteria(v string)`

SetResolutionCriteria sets ResolutionCriteria field to given value.


### GetDate

`func (o *ForecastResponse) GetDate() time.Time`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *ForecastResponse) GetDateOk() (*time.Time, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *ForecastResponse) SetDate(v time.Time)`

SetDate sets Date field to given value.


### GetReasoning

`func (o *ForecastResponse) GetReasoning() string`

GetReasoning returns the Reasoning field if non-nil, zero value otherwise.

### GetReasoningOk

`func (o *ForecastResponse) GetReasoningOk() (*string, bool)`

GetReasoningOk returns a tuple with the Reasoning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasoning

`func (o *ForecastResponse) SetReasoning(v string)`

SetReasoning sets Reasoning field to given value.


### GetSources

`func (o *ForecastResponse) GetSources() []SearchResponseDictItem`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *ForecastResponse) GetSourcesOk() (*[]SearchResponseDictItem, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *ForecastResponse) SetSources(v []SearchResponseDictItem)`

SetSources sets Sources field to given value.


### GetTimeline

`func (o *ForecastResponse) GetTimeline() []string`

GetTimeline returns the Timeline field if non-nil, zero value otherwise.

### GetTimelineOk

`func (o *ForecastResponse) GetTimelineOk() (*[]string, bool)`

GetTimelineOk returns a tuple with the Timeline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeline

`func (o *ForecastResponse) SetTimeline(v []string)`

SetTimeline sets Timeline field to given value.


### GetOppositeRequest

`func (o *ForecastResponse) GetOppositeRequest() string`

GetOppositeRequest returns the OppositeRequest field if non-nil, zero value otherwise.

### GetOppositeRequestOk

`func (o *ForecastResponse) GetOppositeRequestOk() (*string, bool)`

GetOppositeRequestOk returns a tuple with the OppositeRequest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOppositeRequest

`func (o *ForecastResponse) SetOppositeRequest(v string)`

SetOppositeRequest sets OppositeRequest field to given value.


### GetConfidence

`func (o *ForecastResponse) GetConfidence() float32`

GetConfidence returns the Confidence field if non-nil, zero value otherwise.

### GetConfidenceOk

`func (o *ForecastResponse) GetConfidenceOk() (*float32, bool)`

GetConfidenceOk returns a tuple with the Confidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidence

`func (o *ForecastResponse) SetConfidence(v float32)`

SetConfidence sets Confidence field to given value.


### GetChoice

`func (o *ForecastResponse) GetChoice() Choice`

GetChoice returns the Choice field if non-nil, zero value otherwise.

### GetChoiceOk

`func (o *ForecastResponse) GetChoiceOk() (*Choice, bool)`

GetChoiceOk returns a tuple with the Choice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChoice

`func (o *ForecastResponse) SetChoice(v Choice)`

SetChoice sets Choice field to given value.


### GetLlmConfidence

`func (o *ForecastResponse) GetLlmConfidence() int32`

GetLlmConfidence returns the LlmConfidence field if non-nil, zero value otherwise.

### GetLlmConfidenceOk

`func (o *ForecastResponse) GetLlmConfidenceOk() (*int32, bool)`

GetLlmConfidenceOk returns a tuple with the LlmConfidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLlmConfidence

`func (o *ForecastResponse) SetLlmConfidence(v int32)`

SetLlmConfidence sets LlmConfidence field to given value.


### GetModelUsed

`func (o *ForecastResponse) GetModelUsed() string`

GetModelUsed returns the ModelUsed field if non-nil, zero value otherwise.

### GetModelUsedOk

`func (o *ForecastResponse) GetModelUsedOk() (*string, bool)`

GetModelUsedOk returns a tuple with the ModelUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelUsed

`func (o *ForecastResponse) SetModelUsed(v string)`

SetModelUsed sets ModelUsed field to given value.


### GetLikelihood

`func (o *ForecastResponse) GetLikelihood() string`

GetLikelihood returns the Likelihood field if non-nil, zero value otherwise.

### GetLikelihoodOk

`func (o *ForecastResponse) GetLikelihoodOk() (*string, bool)`

GetLikelihoodOk returns a tuple with the Likelihood field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLikelihood

`func (o *ForecastResponse) SetLikelihood(v string)`

SetLikelihood sets Likelihood field to given value.


### GetProbability

`func (o *ForecastResponse) GetProbability() int32`

GetProbability returns the Probability field if non-nil, zero value otherwise.

### GetProbabilityOk

`func (o *ForecastResponse) GetProbabilityOk() (*int32, bool)`

GetProbabilityOk returns a tuple with the Probability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProbability

`func (o *ForecastResponse) SetProbability(v int32)`

SetProbability sets Probability field to given value.


### GetWebSearchResults

`func (o *ForecastResponse) GetWebSearchResults() []WebSearchResult`

GetWebSearchResults returns the WebSearchResults field if non-nil, zero value otherwise.

### GetWebSearchResultsOk

`func (o *ForecastResponse) GetWebSearchResultsOk() (*[]WebSearchResult, bool)`

GetWebSearchResultsOk returns a tuple with the WebSearchResults field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebSearchResults

`func (o *ForecastResponse) SetWebSearchResults(v []WebSearchResult)`

SetWebSearchResults sets WebSearchResults field to given value.


### GetSummary

`func (o *ForecastResponse) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *ForecastResponse) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *ForecastResponse) SetSummary(v string)`

SetSummary sets Summary field to given value.


### GetKeyPeople

`func (o *ForecastResponse) GetKeyPeople() []KeyPerson`

GetKeyPeople returns the KeyPeople field if non-nil, zero value otherwise.

### GetKeyPeopleOk

`func (o *ForecastResponse) GetKeyPeopleOk() (*[]KeyPerson, bool)`

GetKeyPeopleOk returns a tuple with the KeyPeople field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyPeople

`func (o *ForecastResponse) SetKeyPeople(v []KeyPerson)`

SetKeyPeople sets KeyPeople field to given value.


### GetKeyFacets

`func (o *ForecastResponse) GetKeyFacets() []string`

GetKeyFacets returns the KeyFacets field if non-nil, zero value otherwise.

### GetKeyFacetsOk

`func (o *ForecastResponse) GetKeyFacetsOk() (*[]string, bool)`

GetKeyFacetsOk returns a tuple with the KeyFacets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyFacets

`func (o *ForecastResponse) SetKeyFacets(v []string)`

SetKeyFacets sets KeyFacets field to given value.


### GetReconciledInformation

`func (o *ForecastResponse) GetReconciledInformation() string`

GetReconciledInformation returns the ReconciledInformation field if non-nil, zero value otherwise.

### GetReconciledInformationOk

`func (o *ForecastResponse) GetReconciledInformationOk() (*string, bool)`

GetReconciledInformationOk returns a tuple with the ReconciledInformation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReconciledInformation

`func (o *ForecastResponse) SetReconciledInformation(v string)`

SetReconciledInformation sets ReconciledInformation field to given value.


### GetCandidateModels

`func (o *ForecastResponse) GetCandidateModels() []string`

GetCandidateModels returns the CandidateModels field if non-nil, zero value otherwise.

### GetCandidateModelsOk

`func (o *ForecastResponse) GetCandidateModelsOk() (*[]string, bool)`

GetCandidateModelsOk returns a tuple with the CandidateModels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCandidateModels

`func (o *ForecastResponse) SetCandidateModels(v []string)`

SetCandidateModels sets CandidateModels field to given value.


### GetUniqueInformation

`func (o *ForecastResponse) GetUniqueInformation() string`

GetUniqueInformation returns the UniqueInformation field if non-nil, zero value otherwise.

### GetUniqueInformationOk

`func (o *ForecastResponse) GetUniqueInformationOk() (*string, bool)`

GetUniqueInformationOk returns a tuple with the UniqueInformation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUniqueInformation

`func (o *ForecastResponse) SetUniqueInformation(v string)`

SetUniqueInformation sets UniqueInformation field to given value.


### GetExpertInformation

`func (o *ForecastResponse) GetExpertInformation() map[string]interface{}`

GetExpertInformation returns the ExpertInformation field if non-nil, zero value otherwise.

### GetExpertInformationOk

`func (o *ForecastResponse) GetExpertInformationOk() (*map[string]interface{}, bool)`

GetExpertInformationOk returns a tuple with the ExpertInformation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpertInformation

`func (o *ForecastResponse) SetExpertInformation(v map[string]interface{})`

SetExpertInformation sets ExpertInformation field to given value.

### HasExpertInformation

`func (o *ForecastResponse) HasExpertInformation() bool`

HasExpertInformation returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


