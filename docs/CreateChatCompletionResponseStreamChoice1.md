# CreateChatCompletionResponseStreamChoice1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Index** | **int32** |  | 
**Delta** | [**CreateChatCompletionRequestMessage1**](CreateChatCompletionRequestMessage1.md) |  | 
**FinishReason** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCreateChatCompletionResponseStreamChoice1

`func NewCreateChatCompletionResponseStreamChoice1(index int32, delta CreateChatCompletionRequestMessage1, ) *CreateChatCompletionResponseStreamChoice1`

NewCreateChatCompletionResponseStreamChoice1 instantiates a new CreateChatCompletionResponseStreamChoice1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateChatCompletionResponseStreamChoice1WithDefaults

`func NewCreateChatCompletionResponseStreamChoice1WithDefaults() *CreateChatCompletionResponseStreamChoice1`

NewCreateChatCompletionResponseStreamChoice1WithDefaults instantiates a new CreateChatCompletionResponseStreamChoice1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIndex

`func (o *CreateChatCompletionResponseStreamChoice1) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *CreateChatCompletionResponseStreamChoice1) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *CreateChatCompletionResponseStreamChoice1) SetIndex(v int32)`

SetIndex sets Index field to given value.


### GetDelta

`func (o *CreateChatCompletionResponseStreamChoice1) GetDelta() CreateChatCompletionRequestMessage1`

GetDelta returns the Delta field if non-nil, zero value otherwise.

### GetDeltaOk

`func (o *CreateChatCompletionResponseStreamChoice1) GetDeltaOk() (*CreateChatCompletionRequestMessage1, bool)`

GetDeltaOk returns a tuple with the Delta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelta

`func (o *CreateChatCompletionResponseStreamChoice1) SetDelta(v CreateChatCompletionRequestMessage1)`

SetDelta sets Delta field to given value.


### GetFinishReason

`func (o *CreateChatCompletionResponseStreamChoice1) GetFinishReason() string`

GetFinishReason returns the FinishReason field if non-nil, zero value otherwise.

### GetFinishReasonOk

`func (o *CreateChatCompletionResponseStreamChoice1) GetFinishReasonOk() (*string, bool)`

GetFinishReasonOk returns a tuple with the FinishReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishReason

`func (o *CreateChatCompletionResponseStreamChoice1) SetFinishReason(v string)`

SetFinishReason sets FinishReason field to given value.

### HasFinishReason

`func (o *CreateChatCompletionResponseStreamChoice1) HasFinishReason() bool`

HasFinishReason returns a boolean if a field has been set.

### SetFinishReasonNil

`func (o *CreateChatCompletionResponseStreamChoice1) SetFinishReasonNil(b bool)`

 SetFinishReasonNil sets the value for FinishReason to be an explicit nil

### UnsetFinishReason
`func (o *CreateChatCompletionResponseStreamChoice1) UnsetFinishReason()`

UnsetFinishReason ensures that no value is present for FinishReason, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


