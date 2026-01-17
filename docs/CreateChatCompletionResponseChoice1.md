# CreateChatCompletionResponseChoice1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Index** | **int32** |  | 
**Message** | [**CreateChatCompletionRequestMessage1**](CreateChatCompletionRequestMessage1.md) |  | 
**FinishReason** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCreateChatCompletionResponseChoice1

`func NewCreateChatCompletionResponseChoice1(index int32, message CreateChatCompletionRequestMessage1, ) *CreateChatCompletionResponseChoice1`

NewCreateChatCompletionResponseChoice1 instantiates a new CreateChatCompletionResponseChoice1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateChatCompletionResponseChoice1WithDefaults

`func NewCreateChatCompletionResponseChoice1WithDefaults() *CreateChatCompletionResponseChoice1`

NewCreateChatCompletionResponseChoice1WithDefaults instantiates a new CreateChatCompletionResponseChoice1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIndex

`func (o *CreateChatCompletionResponseChoice1) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *CreateChatCompletionResponseChoice1) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *CreateChatCompletionResponseChoice1) SetIndex(v int32)`

SetIndex sets Index field to given value.


### GetMessage

`func (o *CreateChatCompletionResponseChoice1) GetMessage() CreateChatCompletionRequestMessage1`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *CreateChatCompletionResponseChoice1) GetMessageOk() (*CreateChatCompletionRequestMessage1, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *CreateChatCompletionResponseChoice1) SetMessage(v CreateChatCompletionRequestMessage1)`

SetMessage sets Message field to given value.


### GetFinishReason

`func (o *CreateChatCompletionResponseChoice1) GetFinishReason() string`

GetFinishReason returns the FinishReason field if non-nil, zero value otherwise.

### GetFinishReasonOk

`func (o *CreateChatCompletionResponseChoice1) GetFinishReasonOk() (*string, bool)`

GetFinishReasonOk returns a tuple with the FinishReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishReason

`func (o *CreateChatCompletionResponseChoice1) SetFinishReason(v string)`

SetFinishReason sets FinishReason field to given value.

### HasFinishReason

`func (o *CreateChatCompletionResponseChoice1) HasFinishReason() bool`

HasFinishReason returns a boolean if a field has been set.

### SetFinishReasonNil

`func (o *CreateChatCompletionResponseChoice1) SetFinishReasonNil(b bool)`

 SetFinishReasonNil sets the value for FinishReason to be an explicit nil

### UnsetFinishReason
`func (o *CreateChatCompletionResponseChoice1) UnsetFinishReason()`

UnsetFinishReason ensures that no value is present for FinishReason, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


