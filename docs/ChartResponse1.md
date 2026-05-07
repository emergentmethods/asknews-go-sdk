# ChartResponse1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**ChartJson** | **map[string]interface{}** | The plotly fig.to_json() JSON representation of the chart | 
**Query** | Pointer to **NullableString** |  | [optional] 
**Reasoning** | Pointer to **NullableString** |  | [optional] 
**Parameters** | Pointer to [**NullableChartParameters1**](ChartParameters1.md) |  | [optional] 
**Context** | Pointer to **map[string]interface{}** |  | [optional] 
**IterationsUsed** | Pointer to **NullableInt32** |  | [optional] 
**LastReasoning** | Pointer to **NullableString** |  | [optional] 
**LastParameters** | Pointer to [**NullableChartParameters1**](ChartParameters1.md) |  | [optional] 
**PngData** | Pointer to **NullableString** |  | [optional] 
**PngUrl** | Pointer to **NullableString** |  | [optional] 
**ChartUrl** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewChartResponse1

`func NewChartResponse1(success bool, chartJson map[string]interface{}, ) *ChartResponse1`

NewChartResponse1 instantiates a new ChartResponse1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChartResponse1WithDefaults

`func NewChartResponse1WithDefaults() *ChartResponse1`

NewChartResponse1WithDefaults instantiates a new ChartResponse1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *ChartResponse1) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ChartResponse1) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ChartResponse1) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetChartJson

`func (o *ChartResponse1) GetChartJson() map[string]interface{}`

GetChartJson returns the ChartJson field if non-nil, zero value otherwise.

### GetChartJsonOk

`func (o *ChartResponse1) GetChartJsonOk() (*map[string]interface{}, bool)`

GetChartJsonOk returns a tuple with the ChartJson field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChartJson

`func (o *ChartResponse1) SetChartJson(v map[string]interface{})`

SetChartJson sets ChartJson field to given value.


### GetQuery

`func (o *ChartResponse1) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *ChartResponse1) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *ChartResponse1) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *ChartResponse1) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### SetQueryNil

`func (o *ChartResponse1) SetQueryNil(b bool)`

 SetQueryNil sets the value for Query to be an explicit nil

### UnsetQuery
`func (o *ChartResponse1) UnsetQuery()`

UnsetQuery ensures that no value is present for Query, not even an explicit nil
### GetReasoning

`func (o *ChartResponse1) GetReasoning() string`

GetReasoning returns the Reasoning field if non-nil, zero value otherwise.

### GetReasoningOk

`func (o *ChartResponse1) GetReasoningOk() (*string, bool)`

GetReasoningOk returns a tuple with the Reasoning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasoning

`func (o *ChartResponse1) SetReasoning(v string)`

SetReasoning sets Reasoning field to given value.

### HasReasoning

`func (o *ChartResponse1) HasReasoning() bool`

HasReasoning returns a boolean if a field has been set.

### SetReasoningNil

`func (o *ChartResponse1) SetReasoningNil(b bool)`

 SetReasoningNil sets the value for Reasoning to be an explicit nil

### UnsetReasoning
`func (o *ChartResponse1) UnsetReasoning()`

UnsetReasoning ensures that no value is present for Reasoning, not even an explicit nil
### GetParameters

`func (o *ChartResponse1) GetParameters() ChartParameters1`

GetParameters returns the Parameters field if non-nil, zero value otherwise.

### GetParametersOk

`func (o *ChartResponse1) GetParametersOk() (*ChartParameters1, bool)`

GetParametersOk returns a tuple with the Parameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParameters

`func (o *ChartResponse1) SetParameters(v ChartParameters1)`

SetParameters sets Parameters field to given value.

### HasParameters

`func (o *ChartResponse1) HasParameters() bool`

HasParameters returns a boolean if a field has been set.

### SetParametersNil

`func (o *ChartResponse1) SetParametersNil(b bool)`

 SetParametersNil sets the value for Parameters to be an explicit nil

### UnsetParameters
`func (o *ChartResponse1) UnsetParameters()`

UnsetParameters ensures that no value is present for Parameters, not even an explicit nil
### GetContext

`func (o *ChartResponse1) GetContext() map[string]interface{}`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *ChartResponse1) GetContextOk() (*map[string]interface{}, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *ChartResponse1) SetContext(v map[string]interface{})`

SetContext sets Context field to given value.

### HasContext

`func (o *ChartResponse1) HasContext() bool`

HasContext returns a boolean if a field has been set.

### SetContextNil

`func (o *ChartResponse1) SetContextNil(b bool)`

 SetContextNil sets the value for Context to be an explicit nil

### UnsetContext
`func (o *ChartResponse1) UnsetContext()`

UnsetContext ensures that no value is present for Context, not even an explicit nil
### GetIterationsUsed

`func (o *ChartResponse1) GetIterationsUsed() int32`

GetIterationsUsed returns the IterationsUsed field if non-nil, zero value otherwise.

### GetIterationsUsedOk

`func (o *ChartResponse1) GetIterationsUsedOk() (*int32, bool)`

GetIterationsUsedOk returns a tuple with the IterationsUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIterationsUsed

`func (o *ChartResponse1) SetIterationsUsed(v int32)`

SetIterationsUsed sets IterationsUsed field to given value.

### HasIterationsUsed

`func (o *ChartResponse1) HasIterationsUsed() bool`

HasIterationsUsed returns a boolean if a field has been set.

### SetIterationsUsedNil

`func (o *ChartResponse1) SetIterationsUsedNil(b bool)`

 SetIterationsUsedNil sets the value for IterationsUsed to be an explicit nil

### UnsetIterationsUsed
`func (o *ChartResponse1) UnsetIterationsUsed()`

UnsetIterationsUsed ensures that no value is present for IterationsUsed, not even an explicit nil
### GetLastReasoning

`func (o *ChartResponse1) GetLastReasoning() string`

GetLastReasoning returns the LastReasoning field if non-nil, zero value otherwise.

### GetLastReasoningOk

`func (o *ChartResponse1) GetLastReasoningOk() (*string, bool)`

GetLastReasoningOk returns a tuple with the LastReasoning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastReasoning

`func (o *ChartResponse1) SetLastReasoning(v string)`

SetLastReasoning sets LastReasoning field to given value.

### HasLastReasoning

`func (o *ChartResponse1) HasLastReasoning() bool`

HasLastReasoning returns a boolean if a field has been set.

### SetLastReasoningNil

`func (o *ChartResponse1) SetLastReasoningNil(b bool)`

 SetLastReasoningNil sets the value for LastReasoning to be an explicit nil

### UnsetLastReasoning
`func (o *ChartResponse1) UnsetLastReasoning()`

UnsetLastReasoning ensures that no value is present for LastReasoning, not even an explicit nil
### GetLastParameters

`func (o *ChartResponse1) GetLastParameters() ChartParameters1`

GetLastParameters returns the LastParameters field if non-nil, zero value otherwise.

### GetLastParametersOk

`func (o *ChartResponse1) GetLastParametersOk() (*ChartParameters1, bool)`

GetLastParametersOk returns a tuple with the LastParameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastParameters

`func (o *ChartResponse1) SetLastParameters(v ChartParameters1)`

SetLastParameters sets LastParameters field to given value.

### HasLastParameters

`func (o *ChartResponse1) HasLastParameters() bool`

HasLastParameters returns a boolean if a field has been set.

### SetLastParametersNil

`func (o *ChartResponse1) SetLastParametersNil(b bool)`

 SetLastParametersNil sets the value for LastParameters to be an explicit nil

### UnsetLastParameters
`func (o *ChartResponse1) UnsetLastParameters()`

UnsetLastParameters ensures that no value is present for LastParameters, not even an explicit nil
### GetPngData

`func (o *ChartResponse1) GetPngData() string`

GetPngData returns the PngData field if non-nil, zero value otherwise.

### GetPngDataOk

`func (o *ChartResponse1) GetPngDataOk() (*string, bool)`

GetPngDataOk returns a tuple with the PngData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPngData

`func (o *ChartResponse1) SetPngData(v string)`

SetPngData sets PngData field to given value.

### HasPngData

`func (o *ChartResponse1) HasPngData() bool`

HasPngData returns a boolean if a field has been set.

### SetPngDataNil

`func (o *ChartResponse1) SetPngDataNil(b bool)`

 SetPngDataNil sets the value for PngData to be an explicit nil

### UnsetPngData
`func (o *ChartResponse1) UnsetPngData()`

UnsetPngData ensures that no value is present for PngData, not even an explicit nil
### GetPngUrl

`func (o *ChartResponse1) GetPngUrl() string`

GetPngUrl returns the PngUrl field if non-nil, zero value otherwise.

### GetPngUrlOk

`func (o *ChartResponse1) GetPngUrlOk() (*string, bool)`

GetPngUrlOk returns a tuple with the PngUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPngUrl

`func (o *ChartResponse1) SetPngUrl(v string)`

SetPngUrl sets PngUrl field to given value.

### HasPngUrl

`func (o *ChartResponse1) HasPngUrl() bool`

HasPngUrl returns a boolean if a field has been set.

### SetPngUrlNil

`func (o *ChartResponse1) SetPngUrlNil(b bool)`

 SetPngUrlNil sets the value for PngUrl to be an explicit nil

### UnsetPngUrl
`func (o *ChartResponse1) UnsetPngUrl()`

UnsetPngUrl ensures that no value is present for PngUrl, not even an explicit nil
### GetChartUrl

`func (o *ChartResponse1) GetChartUrl() string`

GetChartUrl returns the ChartUrl field if non-nil, zero value otherwise.

### GetChartUrlOk

`func (o *ChartResponse1) GetChartUrlOk() (*string, bool)`

GetChartUrlOk returns a tuple with the ChartUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChartUrl

`func (o *ChartResponse1) SetChartUrl(v string)`

SetChartUrl sets ChartUrl field to given value.

### HasChartUrl

`func (o *ChartResponse1) HasChartUrl() bool`

HasChartUrl returns a boolean if a field has been set.

### SetChartUrlNil

`func (o *ChartResponse1) SetChartUrlNil(b bool)`

 SetChartUrlNil sets the value for ChartUrl to be an explicit nil

### UnsetChartUrl
`func (o *ChartResponse1) UnsetChartUrl()`

UnsetChartUrl ensures that no value is present for ChartUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


