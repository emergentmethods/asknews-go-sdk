# CreateChatCompletionResponseChoice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Index** | **int32** |  | 
**Message** | [**CreateChatCompletionRequestMessage**](CreateChatCompletionRequestMessage.md) |  | 
**FinishReason** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCreateChatCompletionResponseChoice

`func NewCreateChatCompletionResponseChoice(index int32, message CreateChatCompletionRequestMessage, ) *CreateChatCompletionResponseChoice`

NewCreateChatCompletionResponseChoice instantiates a new CreateChatCompletionResponseChoice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateChatCompletionResponseChoiceWithDefaults

`func NewCreateChatCompletionResponseChoiceWithDefaults() *CreateChatCompletionResponseChoice`

NewCreateChatCompletionResponseChoiceWithDefaults instantiates a new CreateChatCompletionResponseChoice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIndex

`func (o *CreateChatCompletionResponseChoice) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *CreateChatCompletionResponseChoice) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *CreateChatCompletionResponseChoice) SetIndex(v int32)`

SetIndex sets Index field to given value.


### GetMessage

`func (o *CreateChatCompletionResponseChoice) GetMessage() CreateChatCompletionRequestMessage`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *CreateChatCompletionResponseChoice) GetMessageOk() (*CreateChatCompletionRequestMessage, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *CreateChatCompletionResponseChoice) SetMessage(v CreateChatCompletionRequestMessage)`

SetMessage sets Message field to given value.


### GetFinishReason

`func (o *CreateChatCompletionResponseChoice) GetFinishReason() string`

GetFinishReason returns the FinishReason field if non-nil, zero value otherwise.

### GetFinishReasonOk

`func (o *CreateChatCompletionResponseChoice) GetFinishReasonOk() (*string, bool)`

GetFinishReasonOk returns a tuple with the FinishReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishReason

`func (o *CreateChatCompletionResponseChoice) SetFinishReason(v string)`

SetFinishReason sets FinishReason field to given value.

### HasFinishReason

`func (o *CreateChatCompletionResponseChoice) HasFinishReason() bool`

HasFinishReason returns a boolean if a field has been set.

### SetFinishReasonNil

`func (o *CreateChatCompletionResponseChoice) SetFinishReasonNil(b bool)`

 SetFinishReasonNil sets the value for FinishReason to be an explicit nil

### UnsetFinishReason
`func (o *CreateChatCompletionResponseChoice) UnsetFinishReason()`

UnsetFinishReason ensures that no value is present for FinishReason, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


