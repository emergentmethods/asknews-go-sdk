# ChartResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**ChartJson** | **map[string]interface{}** | The plotly fig.to_json() JSON representation of the chart | 
**Query** | Pointer to **string** |  | [optional] 
**Reasoning** | Pointer to **NullableString** |  | [optional] 
**Parameters** | Pointer to [**NullableChartParameters**](ChartParameters.md) |  | [optional] 
**Context** | Pointer to **map[string]interface{}** |  | [optional] 
**IterationsUsed** | Pointer to **NullableInt32** |  | [optional] 
**LastReasoning** | Pointer to **NullableString** |  | [optional] 
**LastParameters** | Pointer to [**NullableChartParameters**](ChartParameters.md) |  | [optional] 
**PngData** | Pointer to **NullableString** |  | [optional] 
**PngUrl** | Pointer to **NullableString** |  | [optional] 
**ChartUrl** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewChartResponse

`func NewChartResponse(success bool, chartJson map[string]interface{}, ) *ChartResponse`

NewChartResponse instantiates a new ChartResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChartResponseWithDefaults

`func NewChartResponseWithDefaults() *ChartResponse`

NewChartResponseWithDefaults instantiates a new ChartResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *ChartResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ChartResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ChartResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetChartJson

`func (o *ChartResponse) GetChartJson() map[string]interface{}`

GetChartJson returns the ChartJson field if non-nil, zero value otherwise.

### GetChartJsonOk

`func (o *ChartResponse) GetChartJsonOk() (*map[string]interface{}, bool)`

GetChartJsonOk returns a tuple with the ChartJson field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChartJson

`func (o *ChartResponse) SetChartJson(v map[string]interface{})`

SetChartJson sets ChartJson field to given value.


### GetQuery

`func (o *ChartResponse) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *ChartResponse) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *ChartResponse) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *ChartResponse) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### GetReasoning

`func (o *ChartResponse) GetReasoning() string`

GetReasoning returns the Reasoning field if non-nil, zero value otherwise.

### GetReasoningOk

`func (o *ChartResponse) GetReasoningOk() (*string, bool)`

GetReasoningOk returns a tuple with the Reasoning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasoning

`func (o *ChartResponse) SetReasoning(v string)`

SetReasoning sets Reasoning field to given value.

### HasReasoning

`func (o *ChartResponse) HasReasoning() bool`

HasReasoning returns a boolean if a field has been set.

### SetReasoningNil

`func (o *ChartResponse) SetReasoningNil(b bool)`

 SetReasoningNil sets the value for Reasoning to be an explicit nil

### UnsetReasoning
`func (o *ChartResponse) UnsetReasoning()`

UnsetReasoning ensures that no value is present for Reasoning, not even an explicit nil
### GetParameters

`func (o *ChartResponse) GetParameters() ChartParameters`

GetParameters returns the Parameters field if non-nil, zero value otherwise.

### GetParametersOk

`func (o *ChartResponse) GetParametersOk() (*ChartParameters, bool)`

GetParametersOk returns a tuple with the Parameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParameters

`func (o *ChartResponse) SetParameters(v ChartParameters)`

SetParameters sets Parameters field to given value.

### HasParameters

`func (o *ChartResponse) HasParameters() bool`

HasParameters returns a boolean if a field has been set.

### SetParametersNil

`func (o *ChartResponse) SetParametersNil(b bool)`

 SetParametersNil sets the value for Parameters to be an explicit nil

### UnsetParameters
`func (o *ChartResponse) UnsetParameters()`

UnsetParameters ensures that no value is present for Parameters, not even an explicit nil
### GetContext

`func (o *ChartResponse) GetContext() map[string]interface{}`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *ChartResponse) GetContextOk() (*map[string]interface{}, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *ChartResponse) SetContext(v map[string]interface{})`

SetContext sets Context field to given value.

### HasContext

`func (o *ChartResponse) HasContext() bool`

HasContext returns a boolean if a field has been set.

### SetContextNil

`func (o *ChartResponse) SetContextNil(b bool)`

 SetContextNil sets the value for Context to be an explicit nil

### UnsetContext
`func (o *ChartResponse) UnsetContext()`

UnsetContext ensures that no value is present for Context, not even an explicit nil
### GetIterationsUsed

`func (o *ChartResponse) GetIterationsUsed() int32`

GetIterationsUsed returns the IterationsUsed field if non-nil, zero value otherwise.

### GetIterationsUsedOk

`func (o *ChartResponse) GetIterationsUsedOk() (*int32, bool)`

GetIterationsUsedOk returns a tuple with the IterationsUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIterationsUsed

`func (o *ChartResponse) SetIterationsUsed(v int32)`

SetIterationsUsed sets IterationsUsed field to given value.

### HasIterationsUsed

`func (o *ChartResponse) HasIterationsUsed() bool`

HasIterationsUsed returns a boolean if a field has been set.

### SetIterationsUsedNil

`func (o *ChartResponse) SetIterationsUsedNil(b bool)`

 SetIterationsUsedNil sets the value for IterationsUsed to be an explicit nil

### UnsetIterationsUsed
`func (o *ChartResponse) UnsetIterationsUsed()`

UnsetIterationsUsed ensures that no value is present for IterationsUsed, not even an explicit nil
### GetLastReasoning

`func (o *ChartResponse) GetLastReasoning() string`

GetLastReasoning returns the LastReasoning field if non-nil, zero value otherwise.

### GetLastReasoningOk

`func (o *ChartResponse) GetLastReasoningOk() (*string, bool)`

GetLastReasoningOk returns a tuple with the LastReasoning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastReasoning

`func (o *ChartResponse) SetLastReasoning(v string)`

SetLastReasoning sets LastReasoning field to given value.

### HasLastReasoning

`func (o *ChartResponse) HasLastReasoning() bool`

HasLastReasoning returns a boolean if a field has been set.

### SetLastReasoningNil

`func (o *ChartResponse) SetLastReasoningNil(b bool)`

 SetLastReasoningNil sets the value for LastReasoning to be an explicit nil

### UnsetLastReasoning
`func (o *ChartResponse) UnsetLastReasoning()`

UnsetLastReasoning ensures that no value is present for LastReasoning, not even an explicit nil
### GetLastParameters

`func (o *ChartResponse) GetLastParameters() ChartParameters`

GetLastParameters returns the LastParameters field if non-nil, zero value otherwise.

### GetLastParametersOk

`func (o *ChartResponse) GetLastParametersOk() (*ChartParameters, bool)`

GetLastParametersOk returns a tuple with the LastParameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastParameters

`func (o *ChartResponse) SetLastParameters(v ChartParameters)`

SetLastParameters sets LastParameters field to given value.

### HasLastParameters

`func (o *ChartResponse) HasLastParameters() bool`

HasLastParameters returns a boolean if a field has been set.

### SetLastParametersNil

`func (o *ChartResponse) SetLastParametersNil(b bool)`

 SetLastParametersNil sets the value for LastParameters to be an explicit nil

### UnsetLastParameters
`func (o *ChartResponse) UnsetLastParameters()`

UnsetLastParameters ensures that no value is present for LastParameters, not even an explicit nil
### GetPngData

`func (o *ChartResponse) GetPngData() string`

GetPngData returns the PngData field if non-nil, zero value otherwise.

### GetPngDataOk

`func (o *ChartResponse) GetPngDataOk() (*string, bool)`

GetPngDataOk returns a tuple with the PngData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPngData

`func (o *ChartResponse) SetPngData(v string)`

SetPngData sets PngData field to given value.

### HasPngData

`func (o *ChartResponse) HasPngData() bool`

HasPngData returns a boolean if a field has been set.

### SetPngDataNil

`func (o *ChartResponse) SetPngDataNil(b bool)`

 SetPngDataNil sets the value for PngData to be an explicit nil

### UnsetPngData
`func (o *ChartResponse) UnsetPngData()`

UnsetPngData ensures that no value is present for PngData, not even an explicit nil
### GetPngUrl

`func (o *ChartResponse) GetPngUrl() string`

GetPngUrl returns the PngUrl field if non-nil, zero value otherwise.

### GetPngUrlOk

`func (o *ChartResponse) GetPngUrlOk() (*string, bool)`

GetPngUrlOk returns a tuple with the PngUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPngUrl

`func (o *ChartResponse) SetPngUrl(v string)`

SetPngUrl sets PngUrl field to given value.

### HasPngUrl

`func (o *ChartResponse) HasPngUrl() bool`

HasPngUrl returns a boolean if a field has been set.

### SetPngUrlNil

`func (o *ChartResponse) SetPngUrlNil(b bool)`

 SetPngUrlNil sets the value for PngUrl to be an explicit nil

### UnsetPngUrl
`func (o *ChartResponse) UnsetPngUrl()`

UnsetPngUrl ensures that no value is present for PngUrl, not even an explicit nil
### GetChartUrl

`func (o *ChartResponse) GetChartUrl() string`

GetChartUrl returns the ChartUrl field if non-nil, zero value otherwise.

### GetChartUrlOk

`func (o *ChartResponse) GetChartUrlOk() (*string, bool)`

GetChartUrlOk returns a tuple with the ChartUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChartUrl

`func (o *ChartResponse) SetChartUrl(v string)`

SetChartUrl sets ChartUrl field to given value.

### HasChartUrl

`func (o *ChartResponse) HasChartUrl() bool`

HasChartUrl returns a boolean if a field has been set.

### SetChartUrlNil

`func (o *ChartResponse) SetChartUrlNil(b bool)`

 SetChartUrlNil sets the value for ChartUrl to be an explicit nil

### UnsetChartUrl
`func (o *ChartResponse) UnsetChartUrl()`

UnsetChartUrl ensures that no value is present for ChartUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


