# CreateDeepNewsResponseChoice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Index** | **int32** |  | 
**Message** | [**CreateDeepNewsRequestMessage**](CreateDeepNewsRequestMessage.md) |  | 
**FinishReason** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCreateDeepNewsResponseChoice

`func NewCreateDeepNewsResponseChoice(index int32, message CreateDeepNewsRequestMessage, ) *CreateDeepNewsResponseChoice`

NewCreateDeepNewsResponseChoice instantiates a new CreateDeepNewsResponseChoice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDeepNewsResponseChoiceWithDefaults

`func NewCreateDeepNewsResponseChoiceWithDefaults() *CreateDeepNewsResponseChoice`

NewCreateDeepNewsResponseChoiceWithDefaults instantiates a new CreateDeepNewsResponseChoice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIndex

`func (o *CreateDeepNewsResponseChoice) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *CreateDeepNewsResponseChoice) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *CreateDeepNewsResponseChoice) SetIndex(v int32)`

SetIndex sets Index field to given value.


### GetMessage

`func (o *CreateDeepNewsResponseChoice) GetMessage() CreateDeepNewsRequestMessage`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *CreateDeepNewsResponseChoice) GetMessageOk() (*CreateDeepNewsRequestMessage, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *CreateDeepNewsResponseChoice) SetMessage(v CreateDeepNewsRequestMessage)`

SetMessage sets Message field to given value.


### GetFinishReason

`func (o *CreateDeepNewsResponseChoice) GetFinishReason() string`

GetFinishReason returns the FinishReason field if non-nil, zero value otherwise.

### GetFinishReasonOk

`func (o *CreateDeepNewsResponseChoice) GetFinishReasonOk() (*string, bool)`

GetFinishReasonOk returns a tuple with the FinishReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishReason

`func (o *CreateDeepNewsResponseChoice) SetFinishReason(v string)`

SetFinishReason sets FinishReason field to given value.

### HasFinishReason

`func (o *CreateDeepNewsResponseChoice) HasFinishReason() bool`

HasFinishReason returns a boolean if a field has been set.

### SetFinishReasonNil

`func (o *CreateDeepNewsResponseChoice) SetFinishReasonNil(b bool)`

 SetFinishReasonNil sets the value for FinishReason to be an explicit nil

### UnsetFinishReason
`func (o *CreateDeepNewsResponseChoice) UnsetFinishReason()`

UnsetFinishReason ensures that no value is present for FinishReason, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


