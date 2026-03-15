# DeepNewsReportParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Sources** | Pointer to [**Sources2**](Sources2.md) |  | [optional] [default to [asknews, google, wiki, x]]
**FilterParams** | Pointer to [**NullableFilterParams**](FilterParams.md) |  | [optional] 
**IncludeEntities** | Pointer to **bool** | Whether to provide extracted entities to the agent. Defaults to True. | [optional] [default to true]
**IncludeGraphs** | Pointer to **bool** | Whether to provide knowledge graphs to the agent. Defaults to False. | [optional] [default to false]
**IncludeCoordinates** | Pointer to **bool** | Whether to provide geo coordinates to the agent. Defaults to False. | [optional] [default to false]
**Model** | Pointer to [**NullableDeepNewsModel**](DeepNewsModel.md) |  | [optional] 
**SearchDepth** | Pointer to **int32** | The search depth for deep research. Higher values mean more thorough research. Defaults to 2. | [optional] [default to 2]
**MaxDepth** | Pointer to **int32** | The maximum research depth allowed. Defaults to 4. | [optional] [default to 4]
**StartCitationNumber** | Pointer to **int32** | Starting number for inline citations. Offsets fetched source citation keys. Useful if you are providing the agent outside sources with numbered citation keys. Defaults to 1. | [optional] [default to 1]
**JournalistMode** | Pointer to **bool** | Whether to use journalist mode for more factual reporting. Defaults to True. | [optional] [default to true]

## Methods

### NewDeepNewsReportParams

`func NewDeepNewsReportParams() *DeepNewsReportParams`

NewDeepNewsReportParams instantiates a new DeepNewsReportParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeepNewsReportParamsWithDefaults

`func NewDeepNewsReportParamsWithDefaults() *DeepNewsReportParams`

NewDeepNewsReportParamsWithDefaults instantiates a new DeepNewsReportParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSources

`func (o *DeepNewsReportParams) GetSources() Sources2`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *DeepNewsReportParams) GetSourcesOk() (*Sources2, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *DeepNewsReportParams) SetSources(v Sources2)`

SetSources sets Sources field to given value.

### HasSources

`func (o *DeepNewsReportParams) HasSources() bool`

HasSources returns a boolean if a field has been set.

### GetFilterParams

`func (o *DeepNewsReportParams) GetFilterParams() FilterParams`

GetFilterParams returns the FilterParams field if non-nil, zero value otherwise.

### GetFilterParamsOk

`func (o *DeepNewsReportParams) GetFilterParamsOk() (*FilterParams, bool)`

GetFilterParamsOk returns a tuple with the FilterParams field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilterParams

`func (o *DeepNewsReportParams) SetFilterParams(v FilterParams)`

SetFilterParams sets FilterParams field to given value.

### HasFilterParams

`func (o *DeepNewsReportParams) HasFilterParams() bool`

HasFilterParams returns a boolean if a field has been set.

### SetFilterParamsNil

`func (o *DeepNewsReportParams) SetFilterParamsNil(b bool)`

 SetFilterParamsNil sets the value for FilterParams to be an explicit nil

### UnsetFilterParams
`func (o *DeepNewsReportParams) UnsetFilterParams()`

UnsetFilterParams ensures that no value is present for FilterParams, not even an explicit nil
### GetIncludeEntities

`func (o *DeepNewsReportParams) GetIncludeEntities() bool`

GetIncludeEntities returns the IncludeEntities field if non-nil, zero value otherwise.

### GetIncludeEntitiesOk

`func (o *DeepNewsReportParams) GetIncludeEntitiesOk() (*bool, bool)`

GetIncludeEntitiesOk returns a tuple with the IncludeEntities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeEntities

`func (o *DeepNewsReportParams) SetIncludeEntities(v bool)`

SetIncludeEntities sets IncludeEntities field to given value.

### HasIncludeEntities

`func (o *DeepNewsReportParams) HasIncludeEntities() bool`

HasIncludeEntities returns a boolean if a field has been set.

### GetIncludeGraphs

`func (o *DeepNewsReportParams) GetIncludeGraphs() bool`

GetIncludeGraphs returns the IncludeGraphs field if non-nil, zero value otherwise.

### GetIncludeGraphsOk

`func (o *DeepNewsReportParams) GetIncludeGraphsOk() (*bool, bool)`

GetIncludeGraphsOk returns a tuple with the IncludeGraphs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeGraphs

`func (o *DeepNewsReportParams) SetIncludeGraphs(v bool)`

SetIncludeGraphs sets IncludeGraphs field to given value.

### HasIncludeGraphs

`func (o *DeepNewsReportParams) HasIncludeGraphs() bool`

HasIncludeGraphs returns a boolean if a field has been set.

### GetIncludeCoordinates

`func (o *DeepNewsReportParams) GetIncludeCoordinates() bool`

GetIncludeCoordinates returns the IncludeCoordinates field if non-nil, zero value otherwise.

### GetIncludeCoordinatesOk

`func (o *DeepNewsReportParams) GetIncludeCoordinatesOk() (*bool, bool)`

GetIncludeCoordinatesOk returns a tuple with the IncludeCoordinates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeCoordinates

`func (o *DeepNewsReportParams) SetIncludeCoordinates(v bool)`

SetIncludeCoordinates sets IncludeCoordinates field to given value.

### HasIncludeCoordinates

`func (o *DeepNewsReportParams) HasIncludeCoordinates() bool`

HasIncludeCoordinates returns a boolean if a field has been set.

### GetModel

`func (o *DeepNewsReportParams) GetModel() DeepNewsModel`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *DeepNewsReportParams) GetModelOk() (*DeepNewsModel, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *DeepNewsReportParams) SetModel(v DeepNewsModel)`

SetModel sets Model field to given value.

### HasModel

`func (o *DeepNewsReportParams) HasModel() bool`

HasModel returns a boolean if a field has been set.

### SetModelNil

`func (o *DeepNewsReportParams) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *DeepNewsReportParams) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetSearchDepth

`func (o *DeepNewsReportParams) GetSearchDepth() int32`

GetSearchDepth returns the SearchDepth field if non-nil, zero value otherwise.

### GetSearchDepthOk

`func (o *DeepNewsReportParams) GetSearchDepthOk() (*int32, bool)`

GetSearchDepthOk returns a tuple with the SearchDepth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearchDepth

`func (o *DeepNewsReportParams) SetSearchDepth(v int32)`

SetSearchDepth sets SearchDepth field to given value.

### HasSearchDepth

`func (o *DeepNewsReportParams) HasSearchDepth() bool`

HasSearchDepth returns a boolean if a field has been set.

### GetMaxDepth

`func (o *DeepNewsReportParams) GetMaxDepth() int32`

GetMaxDepth returns the MaxDepth field if non-nil, zero value otherwise.

### GetMaxDepthOk

`func (o *DeepNewsReportParams) GetMaxDepthOk() (*int32, bool)`

GetMaxDepthOk returns a tuple with the MaxDepth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxDepth

`func (o *DeepNewsReportParams) SetMaxDepth(v int32)`

SetMaxDepth sets MaxDepth field to given value.

### HasMaxDepth

`func (o *DeepNewsReportParams) HasMaxDepth() bool`

HasMaxDepth returns a boolean if a field has been set.

### GetStartCitationNumber

`func (o *DeepNewsReportParams) GetStartCitationNumber() int32`

GetStartCitationNumber returns the StartCitationNumber field if non-nil, zero value otherwise.

### GetStartCitationNumberOk

`func (o *DeepNewsReportParams) GetStartCitationNumberOk() (*int32, bool)`

GetStartCitationNumberOk returns a tuple with the StartCitationNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartCitationNumber

`func (o *DeepNewsReportParams) SetStartCitationNumber(v int32)`

SetStartCitationNumber sets StartCitationNumber field to given value.

### HasStartCitationNumber

`func (o *DeepNewsReportParams) HasStartCitationNumber() bool`

HasStartCitationNumber returns a boolean if a field has been set.

### GetJournalistMode

`func (o *DeepNewsReportParams) GetJournalistMode() bool`

GetJournalistMode returns the JournalistMode field if non-nil, zero value otherwise.

### GetJournalistModeOk

`func (o *DeepNewsReportParams) GetJournalistModeOk() (*bool, bool)`

GetJournalistModeOk returns a tuple with the JournalistMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJournalistMode

`func (o *DeepNewsReportParams) SetJournalistMode(v bool)`

SetJournalistMode sets JournalistMode field to given value.

### HasJournalistMode

`func (o *DeepNewsReportParams) HasJournalistMode() bool`

HasJournalistMode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


