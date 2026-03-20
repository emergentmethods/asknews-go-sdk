# DeepNewsSourceParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Sources** | Pointer to [**Sources2**](Sources2.md) |  | [optional] [default to [asknews, google, wiki, x]]
**FilterParams** | Pointer to [**NullableMCPFilterParams**](MCPFilterParams.md) |  | [optional] 
**IncludeEntities** | Pointer to **bool** | Whether to provide extracted entities to the agent. Defaults to True. | [optional] [default to true]
**IncludeGraphs** | Pointer to **bool** | Whether to provide knowledge graphs to the agent. Defaults to False. | [optional] [default to false]
**IncludeCoordinates** | Pointer to **bool** | Whether to provide geo coordinates to the agent. Defaults to False. | [optional] [default to false]
**Engine** | Pointer to **string** | Legacy vs new DeepNews engine | [optional] [default to "v1"]
**MaxParallelToolCalls** | Pointer to **int32** | The number of tool calls the agent can run in parallel. | [optional] [default to 1]
**Model** | Pointer to [**NullableDeepNewsModel**](DeepNewsModel.md) |  | [optional] 
**SearchDepth** | Pointer to **int32** | The search depth for deep research. Higher values mean more thorough research. Defaults to 1. | [optional] [default to 1]
**MaxDepth** | Pointer to **int32** | The maximum research depth allowed. Defaults to 4. | [optional] [default to 4]

## Methods

### NewDeepNewsSourceParams

`func NewDeepNewsSourceParams() *DeepNewsSourceParams`

NewDeepNewsSourceParams instantiates a new DeepNewsSourceParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeepNewsSourceParamsWithDefaults

`func NewDeepNewsSourceParamsWithDefaults() *DeepNewsSourceParams`

NewDeepNewsSourceParamsWithDefaults instantiates a new DeepNewsSourceParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSources

`func (o *DeepNewsSourceParams) GetSources() Sources2`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *DeepNewsSourceParams) GetSourcesOk() (*Sources2, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *DeepNewsSourceParams) SetSources(v Sources2)`

SetSources sets Sources field to given value.

### HasSources

`func (o *DeepNewsSourceParams) HasSources() bool`

HasSources returns a boolean if a field has been set.

### GetFilterParams

`func (o *DeepNewsSourceParams) GetFilterParams() MCPFilterParams`

GetFilterParams returns the FilterParams field if non-nil, zero value otherwise.

### GetFilterParamsOk

`func (o *DeepNewsSourceParams) GetFilterParamsOk() (*MCPFilterParams, bool)`

GetFilterParamsOk returns a tuple with the FilterParams field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilterParams

`func (o *DeepNewsSourceParams) SetFilterParams(v MCPFilterParams)`

SetFilterParams sets FilterParams field to given value.

### HasFilterParams

`func (o *DeepNewsSourceParams) HasFilterParams() bool`

HasFilterParams returns a boolean if a field has been set.

### SetFilterParamsNil

`func (o *DeepNewsSourceParams) SetFilterParamsNil(b bool)`

 SetFilterParamsNil sets the value for FilterParams to be an explicit nil

### UnsetFilterParams
`func (o *DeepNewsSourceParams) UnsetFilterParams()`

UnsetFilterParams ensures that no value is present for FilterParams, not even an explicit nil
### GetIncludeEntities

`func (o *DeepNewsSourceParams) GetIncludeEntities() bool`

GetIncludeEntities returns the IncludeEntities field if non-nil, zero value otherwise.

### GetIncludeEntitiesOk

`func (o *DeepNewsSourceParams) GetIncludeEntitiesOk() (*bool, bool)`

GetIncludeEntitiesOk returns a tuple with the IncludeEntities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeEntities

`func (o *DeepNewsSourceParams) SetIncludeEntities(v bool)`

SetIncludeEntities sets IncludeEntities field to given value.

### HasIncludeEntities

`func (o *DeepNewsSourceParams) HasIncludeEntities() bool`

HasIncludeEntities returns a boolean if a field has been set.

### GetIncludeGraphs

`func (o *DeepNewsSourceParams) GetIncludeGraphs() bool`

GetIncludeGraphs returns the IncludeGraphs field if non-nil, zero value otherwise.

### GetIncludeGraphsOk

`func (o *DeepNewsSourceParams) GetIncludeGraphsOk() (*bool, bool)`

GetIncludeGraphsOk returns a tuple with the IncludeGraphs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeGraphs

`func (o *DeepNewsSourceParams) SetIncludeGraphs(v bool)`

SetIncludeGraphs sets IncludeGraphs field to given value.

### HasIncludeGraphs

`func (o *DeepNewsSourceParams) HasIncludeGraphs() bool`

HasIncludeGraphs returns a boolean if a field has been set.

### GetIncludeCoordinates

`func (o *DeepNewsSourceParams) GetIncludeCoordinates() bool`

GetIncludeCoordinates returns the IncludeCoordinates field if non-nil, zero value otherwise.

### GetIncludeCoordinatesOk

`func (o *DeepNewsSourceParams) GetIncludeCoordinatesOk() (*bool, bool)`

GetIncludeCoordinatesOk returns a tuple with the IncludeCoordinates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeCoordinates

`func (o *DeepNewsSourceParams) SetIncludeCoordinates(v bool)`

SetIncludeCoordinates sets IncludeCoordinates field to given value.

### HasIncludeCoordinates

`func (o *DeepNewsSourceParams) HasIncludeCoordinates() bool`

HasIncludeCoordinates returns a boolean if a field has been set.

### GetEngine

`func (o *DeepNewsSourceParams) GetEngine() string`

GetEngine returns the Engine field if non-nil, zero value otherwise.

### GetEngineOk

`func (o *DeepNewsSourceParams) GetEngineOk() (*string, bool)`

GetEngineOk returns a tuple with the Engine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngine

`func (o *DeepNewsSourceParams) SetEngine(v string)`

SetEngine sets Engine field to given value.

### HasEngine

`func (o *DeepNewsSourceParams) HasEngine() bool`

HasEngine returns a boolean if a field has been set.

### GetMaxParallelToolCalls

`func (o *DeepNewsSourceParams) GetMaxParallelToolCalls() int32`

GetMaxParallelToolCalls returns the MaxParallelToolCalls field if non-nil, zero value otherwise.

### GetMaxParallelToolCallsOk

`func (o *DeepNewsSourceParams) GetMaxParallelToolCallsOk() (*int32, bool)`

GetMaxParallelToolCallsOk returns a tuple with the MaxParallelToolCalls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxParallelToolCalls

`func (o *DeepNewsSourceParams) SetMaxParallelToolCalls(v int32)`

SetMaxParallelToolCalls sets MaxParallelToolCalls field to given value.

### HasMaxParallelToolCalls

`func (o *DeepNewsSourceParams) HasMaxParallelToolCalls() bool`

HasMaxParallelToolCalls returns a boolean if a field has been set.

### GetModel

`func (o *DeepNewsSourceParams) GetModel() DeepNewsModel`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *DeepNewsSourceParams) GetModelOk() (*DeepNewsModel, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *DeepNewsSourceParams) SetModel(v DeepNewsModel)`

SetModel sets Model field to given value.

### HasModel

`func (o *DeepNewsSourceParams) HasModel() bool`

HasModel returns a boolean if a field has been set.

### SetModelNil

`func (o *DeepNewsSourceParams) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *DeepNewsSourceParams) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetSearchDepth

`func (o *DeepNewsSourceParams) GetSearchDepth() int32`

GetSearchDepth returns the SearchDepth field if non-nil, zero value otherwise.

### GetSearchDepthOk

`func (o *DeepNewsSourceParams) GetSearchDepthOk() (*int32, bool)`

GetSearchDepthOk returns a tuple with the SearchDepth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearchDepth

`func (o *DeepNewsSourceParams) SetSearchDepth(v int32)`

SetSearchDepth sets SearchDepth field to given value.

### HasSearchDepth

`func (o *DeepNewsSourceParams) HasSearchDepth() bool`

HasSearchDepth returns a boolean if a field has been set.

### GetMaxDepth

`func (o *DeepNewsSourceParams) GetMaxDepth() int32`

GetMaxDepth returns the MaxDepth field if non-nil, zero value otherwise.

### GetMaxDepthOk

`func (o *DeepNewsSourceParams) GetMaxDepthOk() (*int32, bool)`

GetMaxDepthOk returns a tuple with the MaxDepth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxDepth

`func (o *DeepNewsSourceParams) SetMaxDepth(v int32)`

SetMaxDepth sets MaxDepth field to given value.

### HasMaxDepth

`func (o *DeepNewsSourceParams) HasMaxDepth() bool`

HasMaxDepth returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


