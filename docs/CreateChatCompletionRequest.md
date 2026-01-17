# CreateChatCompletionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Model** | Pointer to **string** |  | [optional] [default to "gpt-4o-mini"]
**Messages** | [**[]CreateChatCompletionRequestMessage**](CreateChatCompletionRequestMessage.md) |  | 
**Temperature** | Pointer to **float32** |  | [optional] [default to 0.9]
**TopP** | Pointer to **float32** |  | [optional] [default to 1.0]
**N** | Pointer to **int32** |  | [optional] [default to 1]
**Stream** | Pointer to **bool** |  | [optional] [default to false]
**Stop** | Pointer to [**Stop**](Stop.md) |  | [optional] 
**MaxTokens** | Pointer to **int32** |  | [optional] [default to 9999]
**PresencePenalty** | Pointer to **int32** |  | [optional] [default to 0]
**FrequencyPenalty** | Pointer to **int32** |  | [optional] [default to 0]
**ThreadId** | Pointer to [**ThreadId**](ThreadId.md) |  | [optional] 
**User** | Pointer to [**User**](User.md) |  | [optional] 
**InlineCitations** | Pointer to **string** |  | [optional] [default to "markdown_link"]
**AppendReferences** | Pointer to **bool** |  | [optional] [default to true]
**JournalistMode** | Pointer to **bool** |  | [optional] [default to true]
**AsknewsWatermark** | Pointer to **bool** |  | [optional] [default to true]
**ConversationalAwareness** | Pointer to **bool** |  | [optional] [default to true]
**FilterParams** | Pointer to [**FilterParams**](FilterParams.md) |  | [optional] 

## Methods

### NewCreateChatCompletionRequest

`func NewCreateChatCompletionRequest(messages []CreateChatCompletionRequestMessage, ) *CreateChatCompletionRequest`

NewCreateChatCompletionRequest instantiates a new CreateChatCompletionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateChatCompletionRequestWithDefaults

`func NewCreateChatCompletionRequestWithDefaults() *CreateChatCompletionRequest`

NewCreateChatCompletionRequestWithDefaults instantiates a new CreateChatCompletionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModel

`func (o *CreateChatCompletionRequest) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *CreateChatCompletionRequest) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *CreateChatCompletionRequest) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *CreateChatCompletionRequest) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetMessages

`func (o *CreateChatCompletionRequest) GetMessages() []CreateChatCompletionRequestMessage`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *CreateChatCompletionRequest) GetMessagesOk() (*[]CreateChatCompletionRequestMessage, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *CreateChatCompletionRequest) SetMessages(v []CreateChatCompletionRequestMessage)`

SetMessages sets Messages field to given value.


### GetTemperature

`func (o *CreateChatCompletionRequest) GetTemperature() float32`

GetTemperature returns the Temperature field if non-nil, zero value otherwise.

### GetTemperatureOk

`func (o *CreateChatCompletionRequest) GetTemperatureOk() (*float32, bool)`

GetTemperatureOk returns a tuple with the Temperature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemperature

`func (o *CreateChatCompletionRequest) SetTemperature(v float32)`

SetTemperature sets Temperature field to given value.

### HasTemperature

`func (o *CreateChatCompletionRequest) HasTemperature() bool`

HasTemperature returns a boolean if a field has been set.

### GetTopP

`func (o *CreateChatCompletionRequest) GetTopP() float32`

GetTopP returns the TopP field if non-nil, zero value otherwise.

### GetTopPOk

`func (o *CreateChatCompletionRequest) GetTopPOk() (*float32, bool)`

GetTopPOk returns a tuple with the TopP field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopP

`func (o *CreateChatCompletionRequest) SetTopP(v float32)`

SetTopP sets TopP field to given value.

### HasTopP

`func (o *CreateChatCompletionRequest) HasTopP() bool`

HasTopP returns a boolean if a field has been set.

### GetN

`func (o *CreateChatCompletionRequest) GetN() int32`

GetN returns the N field if non-nil, zero value otherwise.

### GetNOk

`func (o *CreateChatCompletionRequest) GetNOk() (*int32, bool)`

GetNOk returns a tuple with the N field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetN

`func (o *CreateChatCompletionRequest) SetN(v int32)`

SetN sets N field to given value.

### HasN

`func (o *CreateChatCompletionRequest) HasN() bool`

HasN returns a boolean if a field has been set.

### GetStream

`func (o *CreateChatCompletionRequest) GetStream() bool`

GetStream returns the Stream field if non-nil, zero value otherwise.

### GetStreamOk

`func (o *CreateChatCompletionRequest) GetStreamOk() (*bool, bool)`

GetStreamOk returns a tuple with the Stream field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStream

`func (o *CreateChatCompletionRequest) SetStream(v bool)`

SetStream sets Stream field to given value.

### HasStream

`func (o *CreateChatCompletionRequest) HasStream() bool`

HasStream returns a boolean if a field has been set.

### GetStop

`func (o *CreateChatCompletionRequest) GetStop() Stop`

GetStop returns the Stop field if non-nil, zero value otherwise.

### GetStopOk

`func (o *CreateChatCompletionRequest) GetStopOk() (*Stop, bool)`

GetStopOk returns a tuple with the Stop field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStop

`func (o *CreateChatCompletionRequest) SetStop(v Stop)`

SetStop sets Stop field to given value.

### HasStop

`func (o *CreateChatCompletionRequest) HasStop() bool`

HasStop returns a boolean if a field has been set.

### GetMaxTokens

`func (o *CreateChatCompletionRequest) GetMaxTokens() int32`

GetMaxTokens returns the MaxTokens field if non-nil, zero value otherwise.

### GetMaxTokensOk

`func (o *CreateChatCompletionRequest) GetMaxTokensOk() (*int32, bool)`

GetMaxTokensOk returns a tuple with the MaxTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxTokens

`func (o *CreateChatCompletionRequest) SetMaxTokens(v int32)`

SetMaxTokens sets MaxTokens field to given value.

### HasMaxTokens

`func (o *CreateChatCompletionRequest) HasMaxTokens() bool`

HasMaxTokens returns a boolean if a field has been set.

### GetPresencePenalty

`func (o *CreateChatCompletionRequest) GetPresencePenalty() int32`

GetPresencePenalty returns the PresencePenalty field if non-nil, zero value otherwise.

### GetPresencePenaltyOk

`func (o *CreateChatCompletionRequest) GetPresencePenaltyOk() (*int32, bool)`

GetPresencePenaltyOk returns a tuple with the PresencePenalty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPresencePenalty

`func (o *CreateChatCompletionRequest) SetPresencePenalty(v int32)`

SetPresencePenalty sets PresencePenalty field to given value.

### HasPresencePenalty

`func (o *CreateChatCompletionRequest) HasPresencePenalty() bool`

HasPresencePenalty returns a boolean if a field has been set.

### GetFrequencyPenalty

`func (o *CreateChatCompletionRequest) GetFrequencyPenalty() int32`

GetFrequencyPenalty returns the FrequencyPenalty field if non-nil, zero value otherwise.

### GetFrequencyPenaltyOk

`func (o *CreateChatCompletionRequest) GetFrequencyPenaltyOk() (*int32, bool)`

GetFrequencyPenaltyOk returns a tuple with the FrequencyPenalty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrequencyPenalty

`func (o *CreateChatCompletionRequest) SetFrequencyPenalty(v int32)`

SetFrequencyPenalty sets FrequencyPenalty field to given value.

### HasFrequencyPenalty

`func (o *CreateChatCompletionRequest) HasFrequencyPenalty() bool`

HasFrequencyPenalty returns a boolean if a field has been set.

### GetThreadId

`func (o *CreateChatCompletionRequest) GetThreadId() ThreadId`

GetThreadId returns the ThreadId field if non-nil, zero value otherwise.

### GetThreadIdOk

`func (o *CreateChatCompletionRequest) GetThreadIdOk() (*ThreadId, bool)`

GetThreadIdOk returns a tuple with the ThreadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreadId

`func (o *CreateChatCompletionRequest) SetThreadId(v ThreadId)`

SetThreadId sets ThreadId field to given value.

### HasThreadId

`func (o *CreateChatCompletionRequest) HasThreadId() bool`

HasThreadId returns a boolean if a field has been set.

### GetUser

`func (o *CreateChatCompletionRequest) GetUser() User`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *CreateChatCompletionRequest) GetUserOk() (*User, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *CreateChatCompletionRequest) SetUser(v User)`

SetUser sets User field to given value.

### HasUser

`func (o *CreateChatCompletionRequest) HasUser() bool`

HasUser returns a boolean if a field has been set.

### GetInlineCitations

`func (o *CreateChatCompletionRequest) GetInlineCitations() string`

GetInlineCitations returns the InlineCitations field if non-nil, zero value otherwise.

### GetInlineCitationsOk

`func (o *CreateChatCompletionRequest) GetInlineCitationsOk() (*string, bool)`

GetInlineCitationsOk returns a tuple with the InlineCitations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInlineCitations

`func (o *CreateChatCompletionRequest) SetInlineCitations(v string)`

SetInlineCitations sets InlineCitations field to given value.

### HasInlineCitations

`func (o *CreateChatCompletionRequest) HasInlineCitations() bool`

HasInlineCitations returns a boolean if a field has been set.

### GetAppendReferences

`func (o *CreateChatCompletionRequest) GetAppendReferences() bool`

GetAppendReferences returns the AppendReferences field if non-nil, zero value otherwise.

### GetAppendReferencesOk

`func (o *CreateChatCompletionRequest) GetAppendReferencesOk() (*bool, bool)`

GetAppendReferencesOk returns a tuple with the AppendReferences field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppendReferences

`func (o *CreateChatCompletionRequest) SetAppendReferences(v bool)`

SetAppendReferences sets AppendReferences field to given value.

### HasAppendReferences

`func (o *CreateChatCompletionRequest) HasAppendReferences() bool`

HasAppendReferences returns a boolean if a field has been set.

### GetJournalistMode

`func (o *CreateChatCompletionRequest) GetJournalistMode() bool`

GetJournalistMode returns the JournalistMode field if non-nil, zero value otherwise.

### GetJournalistModeOk

`func (o *CreateChatCompletionRequest) GetJournalistModeOk() (*bool, bool)`

GetJournalistModeOk returns a tuple with the JournalistMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJournalistMode

`func (o *CreateChatCompletionRequest) SetJournalistMode(v bool)`

SetJournalistMode sets JournalistMode field to given value.

### HasJournalistMode

`func (o *CreateChatCompletionRequest) HasJournalistMode() bool`

HasJournalistMode returns a boolean if a field has been set.

### GetAsknewsWatermark

`func (o *CreateChatCompletionRequest) GetAsknewsWatermark() bool`

GetAsknewsWatermark returns the AsknewsWatermark field if non-nil, zero value otherwise.

### GetAsknewsWatermarkOk

`func (o *CreateChatCompletionRequest) GetAsknewsWatermarkOk() (*bool, bool)`

GetAsknewsWatermarkOk returns a tuple with the AsknewsWatermark field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsknewsWatermark

`func (o *CreateChatCompletionRequest) SetAsknewsWatermark(v bool)`

SetAsknewsWatermark sets AsknewsWatermark field to given value.

### HasAsknewsWatermark

`func (o *CreateChatCompletionRequest) HasAsknewsWatermark() bool`

HasAsknewsWatermark returns a boolean if a field has been set.

### GetConversationalAwareness

`func (o *CreateChatCompletionRequest) GetConversationalAwareness() bool`

GetConversationalAwareness returns the ConversationalAwareness field if non-nil, zero value otherwise.

### GetConversationalAwarenessOk

`func (o *CreateChatCompletionRequest) GetConversationalAwarenessOk() (*bool, bool)`

GetConversationalAwarenessOk returns a tuple with the ConversationalAwareness field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConversationalAwareness

`func (o *CreateChatCompletionRequest) SetConversationalAwareness(v bool)`

SetConversationalAwareness sets ConversationalAwareness field to given value.

### HasConversationalAwareness

`func (o *CreateChatCompletionRequest) HasConversationalAwareness() bool`

HasConversationalAwareness returns a boolean if a field has been set.

### GetFilterParams

`func (o *CreateChatCompletionRequest) GetFilterParams() FilterParams`

GetFilterParams returns the FilterParams field if non-nil, zero value otherwise.

### GetFilterParamsOk

`func (o *CreateChatCompletionRequest) GetFilterParamsOk() (*FilterParams, bool)`

GetFilterParamsOk returns a tuple with the FilterParams field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilterParams

`func (o *CreateChatCompletionRequest) SetFilterParams(v FilterParams)`

SetFilterParams sets FilterParams field to given value.

### HasFilterParams

`func (o *CreateChatCompletionRequest) HasFilterParams() bool`

HasFilterParams returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


