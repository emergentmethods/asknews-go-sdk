# CreateDeepNewsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Model** | Pointer to [**DeepNewsModel**](DeepNewsModel.md) |  | [optional] 
**Messages** | [**[]CreateDeepNewsRequestMessage**](CreateDeepNewsRequestMessage.md) |  | 
**Temperature** | Pointer to **float32** |  | [optional] [default to 0.9]
**TopP** | Pointer to **float32** |  | [optional] [default to 1.0]
**N** | Pointer to **int32** |  | [optional] [default to 1]
**Stream** | Pointer to **bool** |  | [optional] [default to false]
**Stop** | Pointer to [**Stop**](Stop.md) |  | [optional] 
**MaxTokens** | Pointer to **int32** |  | [optional] [default to 9999]
**PresencePenalty** | Pointer to **int32** |  | [optional] [default to 0]
**FrequencyPenalty** | Pointer to **int32** |  | [optional] [default to 0]
**User** | Pointer to [**User**](User.md) |  | [optional] 
**ThreadId** | Pointer to [**ThreadId1**](ThreadId1.md) |  | [optional] 
**InlineCitations** | Pointer to **string** |  | [optional] [default to "markdown_link"]
**AppendReferences** | Pointer to **bool** |  | [optional] [default to true]
**JournalistMode** | Pointer to **bool** |  | [optional] [default to true]
**AsknewsWatermark** | Pointer to **bool** |  | [optional] [default to true]
**ConversationalAwareness** | Pointer to **bool** |  | [optional] [default to true]
**FilterParams** | Pointer to [**FilterParams1**](FilterParams1.md) |  | [optional] 
**SearchDepth** | Pointer to **int32** |  | [optional] [default to 2]
**MaxDepth** | Pointer to **int32** |  | [optional] [default to 4]
**Sources** | Pointer to [**Sources1**](Sources1.md) |  | [optional] [default to asknews]
**ReturnSources** | Pointer to **bool** |  | [optional] [default to true]
**IncludeCoordinates** | Pointer to **bool** |  | [optional] [default to false]
**IncludeEntities** | Pointer to **bool** |  | [optional] [default to true]
**IncludeGraphs** | Pointer to **bool** |  | [optional] [default to false]

## Methods

### NewCreateDeepNewsRequest

`func NewCreateDeepNewsRequest(messages []CreateDeepNewsRequestMessage, ) *CreateDeepNewsRequest`

NewCreateDeepNewsRequest instantiates a new CreateDeepNewsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDeepNewsRequestWithDefaults

`func NewCreateDeepNewsRequestWithDefaults() *CreateDeepNewsRequest`

NewCreateDeepNewsRequestWithDefaults instantiates a new CreateDeepNewsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModel

`func (o *CreateDeepNewsRequest) GetModel() DeepNewsModel`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *CreateDeepNewsRequest) GetModelOk() (*DeepNewsModel, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *CreateDeepNewsRequest) SetModel(v DeepNewsModel)`

SetModel sets Model field to given value.

### HasModel

`func (o *CreateDeepNewsRequest) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetMessages

`func (o *CreateDeepNewsRequest) GetMessages() []CreateDeepNewsRequestMessage`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *CreateDeepNewsRequest) GetMessagesOk() (*[]CreateDeepNewsRequestMessage, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *CreateDeepNewsRequest) SetMessages(v []CreateDeepNewsRequestMessage)`

SetMessages sets Messages field to given value.


### GetTemperature

`func (o *CreateDeepNewsRequest) GetTemperature() float32`

GetTemperature returns the Temperature field if non-nil, zero value otherwise.

### GetTemperatureOk

`func (o *CreateDeepNewsRequest) GetTemperatureOk() (*float32, bool)`

GetTemperatureOk returns a tuple with the Temperature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemperature

`func (o *CreateDeepNewsRequest) SetTemperature(v float32)`

SetTemperature sets Temperature field to given value.

### HasTemperature

`func (o *CreateDeepNewsRequest) HasTemperature() bool`

HasTemperature returns a boolean if a field has been set.

### GetTopP

`func (o *CreateDeepNewsRequest) GetTopP() float32`

GetTopP returns the TopP field if non-nil, zero value otherwise.

### GetTopPOk

`func (o *CreateDeepNewsRequest) GetTopPOk() (*float32, bool)`

GetTopPOk returns a tuple with the TopP field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopP

`func (o *CreateDeepNewsRequest) SetTopP(v float32)`

SetTopP sets TopP field to given value.

### HasTopP

`func (o *CreateDeepNewsRequest) HasTopP() bool`

HasTopP returns a boolean if a field has been set.

### GetN

`func (o *CreateDeepNewsRequest) GetN() int32`

GetN returns the N field if non-nil, zero value otherwise.

### GetNOk

`func (o *CreateDeepNewsRequest) GetNOk() (*int32, bool)`

GetNOk returns a tuple with the N field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetN

`func (o *CreateDeepNewsRequest) SetN(v int32)`

SetN sets N field to given value.

### HasN

`func (o *CreateDeepNewsRequest) HasN() bool`

HasN returns a boolean if a field has been set.

### GetStream

`func (o *CreateDeepNewsRequest) GetStream() bool`

GetStream returns the Stream field if non-nil, zero value otherwise.

### GetStreamOk

`func (o *CreateDeepNewsRequest) GetStreamOk() (*bool, bool)`

GetStreamOk returns a tuple with the Stream field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStream

`func (o *CreateDeepNewsRequest) SetStream(v bool)`

SetStream sets Stream field to given value.

### HasStream

`func (o *CreateDeepNewsRequest) HasStream() bool`

HasStream returns a boolean if a field has been set.

### GetStop

`func (o *CreateDeepNewsRequest) GetStop() Stop`

GetStop returns the Stop field if non-nil, zero value otherwise.

### GetStopOk

`func (o *CreateDeepNewsRequest) GetStopOk() (*Stop, bool)`

GetStopOk returns a tuple with the Stop field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStop

`func (o *CreateDeepNewsRequest) SetStop(v Stop)`

SetStop sets Stop field to given value.

### HasStop

`func (o *CreateDeepNewsRequest) HasStop() bool`

HasStop returns a boolean if a field has been set.

### GetMaxTokens

`func (o *CreateDeepNewsRequest) GetMaxTokens() int32`

GetMaxTokens returns the MaxTokens field if non-nil, zero value otherwise.

### GetMaxTokensOk

`func (o *CreateDeepNewsRequest) GetMaxTokensOk() (*int32, bool)`

GetMaxTokensOk returns a tuple with the MaxTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxTokens

`func (o *CreateDeepNewsRequest) SetMaxTokens(v int32)`

SetMaxTokens sets MaxTokens field to given value.

### HasMaxTokens

`func (o *CreateDeepNewsRequest) HasMaxTokens() bool`

HasMaxTokens returns a boolean if a field has been set.

### GetPresencePenalty

`func (o *CreateDeepNewsRequest) GetPresencePenalty() int32`

GetPresencePenalty returns the PresencePenalty field if non-nil, zero value otherwise.

### GetPresencePenaltyOk

`func (o *CreateDeepNewsRequest) GetPresencePenaltyOk() (*int32, bool)`

GetPresencePenaltyOk returns a tuple with the PresencePenalty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPresencePenalty

`func (o *CreateDeepNewsRequest) SetPresencePenalty(v int32)`

SetPresencePenalty sets PresencePenalty field to given value.

### HasPresencePenalty

`func (o *CreateDeepNewsRequest) HasPresencePenalty() bool`

HasPresencePenalty returns a boolean if a field has been set.

### GetFrequencyPenalty

`func (o *CreateDeepNewsRequest) GetFrequencyPenalty() int32`

GetFrequencyPenalty returns the FrequencyPenalty field if non-nil, zero value otherwise.

### GetFrequencyPenaltyOk

`func (o *CreateDeepNewsRequest) GetFrequencyPenaltyOk() (*int32, bool)`

GetFrequencyPenaltyOk returns a tuple with the FrequencyPenalty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrequencyPenalty

`func (o *CreateDeepNewsRequest) SetFrequencyPenalty(v int32)`

SetFrequencyPenalty sets FrequencyPenalty field to given value.

### HasFrequencyPenalty

`func (o *CreateDeepNewsRequest) HasFrequencyPenalty() bool`

HasFrequencyPenalty returns a boolean if a field has been set.

### GetUser

`func (o *CreateDeepNewsRequest) GetUser() User`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *CreateDeepNewsRequest) GetUserOk() (*User, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *CreateDeepNewsRequest) SetUser(v User)`

SetUser sets User field to given value.

### HasUser

`func (o *CreateDeepNewsRequest) HasUser() bool`

HasUser returns a boolean if a field has been set.

### GetThreadId

`func (o *CreateDeepNewsRequest) GetThreadId() ThreadId1`

GetThreadId returns the ThreadId field if non-nil, zero value otherwise.

### GetThreadIdOk

`func (o *CreateDeepNewsRequest) GetThreadIdOk() (*ThreadId1, bool)`

GetThreadIdOk returns a tuple with the ThreadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreadId

`func (o *CreateDeepNewsRequest) SetThreadId(v ThreadId1)`

SetThreadId sets ThreadId field to given value.

### HasThreadId

`func (o *CreateDeepNewsRequest) HasThreadId() bool`

HasThreadId returns a boolean if a field has been set.

### GetInlineCitations

`func (o *CreateDeepNewsRequest) GetInlineCitations() string`

GetInlineCitations returns the InlineCitations field if non-nil, zero value otherwise.

### GetInlineCitationsOk

`func (o *CreateDeepNewsRequest) GetInlineCitationsOk() (*string, bool)`

GetInlineCitationsOk returns a tuple with the InlineCitations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInlineCitations

`func (o *CreateDeepNewsRequest) SetInlineCitations(v string)`

SetInlineCitations sets InlineCitations field to given value.

### HasInlineCitations

`func (o *CreateDeepNewsRequest) HasInlineCitations() bool`

HasInlineCitations returns a boolean if a field has been set.

### GetAppendReferences

`func (o *CreateDeepNewsRequest) GetAppendReferences() bool`

GetAppendReferences returns the AppendReferences field if non-nil, zero value otherwise.

### GetAppendReferencesOk

`func (o *CreateDeepNewsRequest) GetAppendReferencesOk() (*bool, bool)`

GetAppendReferencesOk returns a tuple with the AppendReferences field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppendReferences

`func (o *CreateDeepNewsRequest) SetAppendReferences(v bool)`

SetAppendReferences sets AppendReferences field to given value.

### HasAppendReferences

`func (o *CreateDeepNewsRequest) HasAppendReferences() bool`

HasAppendReferences returns a boolean if a field has been set.

### GetJournalistMode

`func (o *CreateDeepNewsRequest) GetJournalistMode() bool`

GetJournalistMode returns the JournalistMode field if non-nil, zero value otherwise.

### GetJournalistModeOk

`func (o *CreateDeepNewsRequest) GetJournalistModeOk() (*bool, bool)`

GetJournalistModeOk returns a tuple with the JournalistMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJournalistMode

`func (o *CreateDeepNewsRequest) SetJournalistMode(v bool)`

SetJournalistMode sets JournalistMode field to given value.

### HasJournalistMode

`func (o *CreateDeepNewsRequest) HasJournalistMode() bool`

HasJournalistMode returns a boolean if a field has been set.

### GetAsknewsWatermark

`func (o *CreateDeepNewsRequest) GetAsknewsWatermark() bool`

GetAsknewsWatermark returns the AsknewsWatermark field if non-nil, zero value otherwise.

### GetAsknewsWatermarkOk

`func (o *CreateDeepNewsRequest) GetAsknewsWatermarkOk() (*bool, bool)`

GetAsknewsWatermarkOk returns a tuple with the AsknewsWatermark field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsknewsWatermark

`func (o *CreateDeepNewsRequest) SetAsknewsWatermark(v bool)`

SetAsknewsWatermark sets AsknewsWatermark field to given value.

### HasAsknewsWatermark

`func (o *CreateDeepNewsRequest) HasAsknewsWatermark() bool`

HasAsknewsWatermark returns a boolean if a field has been set.

### GetConversationalAwareness

`func (o *CreateDeepNewsRequest) GetConversationalAwareness() bool`

GetConversationalAwareness returns the ConversationalAwareness field if non-nil, zero value otherwise.

### GetConversationalAwarenessOk

`func (o *CreateDeepNewsRequest) GetConversationalAwarenessOk() (*bool, bool)`

GetConversationalAwarenessOk returns a tuple with the ConversationalAwareness field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConversationalAwareness

`func (o *CreateDeepNewsRequest) SetConversationalAwareness(v bool)`

SetConversationalAwareness sets ConversationalAwareness field to given value.

### HasConversationalAwareness

`func (o *CreateDeepNewsRequest) HasConversationalAwareness() bool`

HasConversationalAwareness returns a boolean if a field has been set.

### GetFilterParams

`func (o *CreateDeepNewsRequest) GetFilterParams() FilterParams1`

GetFilterParams returns the FilterParams field if non-nil, zero value otherwise.

### GetFilterParamsOk

`func (o *CreateDeepNewsRequest) GetFilterParamsOk() (*FilterParams1, bool)`

GetFilterParamsOk returns a tuple with the FilterParams field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilterParams

`func (o *CreateDeepNewsRequest) SetFilterParams(v FilterParams1)`

SetFilterParams sets FilterParams field to given value.

### HasFilterParams

`func (o *CreateDeepNewsRequest) HasFilterParams() bool`

HasFilterParams returns a boolean if a field has been set.

### GetSearchDepth

`func (o *CreateDeepNewsRequest) GetSearchDepth() int32`

GetSearchDepth returns the SearchDepth field if non-nil, zero value otherwise.

### GetSearchDepthOk

`func (o *CreateDeepNewsRequest) GetSearchDepthOk() (*int32, bool)`

GetSearchDepthOk returns a tuple with the SearchDepth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearchDepth

`func (o *CreateDeepNewsRequest) SetSearchDepth(v int32)`

SetSearchDepth sets SearchDepth field to given value.

### HasSearchDepth

`func (o *CreateDeepNewsRequest) HasSearchDepth() bool`

HasSearchDepth returns a boolean if a field has been set.

### GetMaxDepth

`func (o *CreateDeepNewsRequest) GetMaxDepth() int32`

GetMaxDepth returns the MaxDepth field if non-nil, zero value otherwise.

### GetMaxDepthOk

`func (o *CreateDeepNewsRequest) GetMaxDepthOk() (*int32, bool)`

GetMaxDepthOk returns a tuple with the MaxDepth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxDepth

`func (o *CreateDeepNewsRequest) SetMaxDepth(v int32)`

SetMaxDepth sets MaxDepth field to given value.

### HasMaxDepth

`func (o *CreateDeepNewsRequest) HasMaxDepth() bool`

HasMaxDepth returns a boolean if a field has been set.

### GetSources

`func (o *CreateDeepNewsRequest) GetSources() Sources1`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *CreateDeepNewsRequest) GetSourcesOk() (*Sources1, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *CreateDeepNewsRequest) SetSources(v Sources1)`

SetSources sets Sources field to given value.

### HasSources

`func (o *CreateDeepNewsRequest) HasSources() bool`

HasSources returns a boolean if a field has been set.

### GetReturnSources

`func (o *CreateDeepNewsRequest) GetReturnSources() bool`

GetReturnSources returns the ReturnSources field if non-nil, zero value otherwise.

### GetReturnSourcesOk

`func (o *CreateDeepNewsRequest) GetReturnSourcesOk() (*bool, bool)`

GetReturnSourcesOk returns a tuple with the ReturnSources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnSources

`func (o *CreateDeepNewsRequest) SetReturnSources(v bool)`

SetReturnSources sets ReturnSources field to given value.

### HasReturnSources

`func (o *CreateDeepNewsRequest) HasReturnSources() bool`

HasReturnSources returns a boolean if a field has been set.

### GetIncludeCoordinates

`func (o *CreateDeepNewsRequest) GetIncludeCoordinates() bool`

GetIncludeCoordinates returns the IncludeCoordinates field if non-nil, zero value otherwise.

### GetIncludeCoordinatesOk

`func (o *CreateDeepNewsRequest) GetIncludeCoordinatesOk() (*bool, bool)`

GetIncludeCoordinatesOk returns a tuple with the IncludeCoordinates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeCoordinates

`func (o *CreateDeepNewsRequest) SetIncludeCoordinates(v bool)`

SetIncludeCoordinates sets IncludeCoordinates field to given value.

### HasIncludeCoordinates

`func (o *CreateDeepNewsRequest) HasIncludeCoordinates() bool`

HasIncludeCoordinates returns a boolean if a field has been set.

### GetIncludeEntities

`func (o *CreateDeepNewsRequest) GetIncludeEntities() bool`

GetIncludeEntities returns the IncludeEntities field if non-nil, zero value otherwise.

### GetIncludeEntitiesOk

`func (o *CreateDeepNewsRequest) GetIncludeEntitiesOk() (*bool, bool)`

GetIncludeEntitiesOk returns a tuple with the IncludeEntities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeEntities

`func (o *CreateDeepNewsRequest) SetIncludeEntities(v bool)`

SetIncludeEntities sets IncludeEntities field to given value.

### HasIncludeEntities

`func (o *CreateDeepNewsRequest) HasIncludeEntities() bool`

HasIncludeEntities returns a boolean if a field has been set.

### GetIncludeGraphs

`func (o *CreateDeepNewsRequest) GetIncludeGraphs() bool`

GetIncludeGraphs returns the IncludeGraphs field if non-nil, zero value otherwise.

### GetIncludeGraphsOk

`func (o *CreateDeepNewsRequest) GetIncludeGraphsOk() (*bool, bool)`

GetIncludeGraphsOk returns a tuple with the IncludeGraphs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeGraphs

`func (o *CreateDeepNewsRequest) SetIncludeGraphs(v bool)`

SetIncludeGraphs sets IncludeGraphs field to given value.

### HasIncludeGraphs

`func (o *CreateDeepNewsRequest) HasIncludeGraphs() bool`

HasIncludeGraphs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


