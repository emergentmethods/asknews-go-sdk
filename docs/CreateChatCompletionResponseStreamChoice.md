# CreateChatCompletionResponseStreamChoice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Index** | **int32** |  | 
**Delta** | [**CreateChatCompletionRequestMessage**](CreateChatCompletionRequestMessage.md) |  | 
**FinishReason** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCreateChatCompletionResponseStreamChoice

`func NewCreateChatCompletionResponseStreamChoice(index int32, delta CreateChatCompletionRequestMessage, ) *CreateChatCompletionResponseStreamChoice`

NewCreateChatCompletionResponseStreamChoice instantiates a new CreateChatCompletionResponseStreamChoice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateChatCompletionResponseStreamChoiceWithDefaults

`func NewCreateChatCompletionResponseStreamChoiceWithDefaults() *CreateChatCompletionResponseStreamChoice`

NewCreateChatCompletionResponseStreamChoiceWithDefaults instantiates a new CreateChatCompletionResponseStreamChoice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIndex

`func (o *CreateChatCompletionResponseStreamChoice) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *CreateChatCompletionResponseStreamChoice) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *CreateChatCompletionResponseStreamChoice) SetIndex(v int32)`

SetIndex sets Index field to given value.


### GetDelta

`func (o *CreateChatCompletionResponseStreamChoice) GetDelta() CreateChatCompletionRequestMessage`

GetDelta returns the Delta field if non-nil, zero value otherwise.

### GetDeltaOk

`func (o *CreateChatCompletionResponseStreamChoice) GetDeltaOk() (*CreateChatCompletionRequestMessage, bool)`

GetDeltaOk returns a tuple with the Delta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelta

`func (o *CreateChatCompletionResponseStreamChoice) SetDelta(v CreateChatCompletionRequestMessage)`

SetDelta sets Delta field to given value.


### GetFinishReason

`func (o *CreateChatCompletionResponseStreamChoice) GetFinishReason() string`

GetFinishReason returns the FinishReason field if non-nil, zero value otherwise.

### GetFinishReasonOk

`func (o *CreateChatCompletionResponseStreamChoice) GetFinishReasonOk() (*string, bool)`

GetFinishReasonOk returns a tuple with the FinishReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishReason

`func (o *CreateChatCompletionResponseStreamChoice) SetFinishReason(v string)`

SetFinishReason sets FinishReason field to given value.

### HasFinishReason

`func (o *CreateChatCompletionResponseStreamChoice) HasFinishReason() bool`

HasFinishReason returns a boolean if a field has been set.

### SetFinishReasonNil

`func (o *CreateChatCompletionResponseStreamChoice) SetFinishReasonNil(b bool)`

 SetFinishReasonNil sets the value for FinishReason to be an explicit nil

### UnsetFinishReason
`func (o *CreateChatCompletionResponseStreamChoice) UnsetFinishReason()`

UnsetFinishReason ensures that no value is present for FinishReason, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


