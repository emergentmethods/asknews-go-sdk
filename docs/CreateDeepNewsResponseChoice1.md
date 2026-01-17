# CreateDeepNewsResponseChoice1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Index** | **int32** |  | 
**Message** | [**CreateDeepNewsRequestMessage1**](CreateDeepNewsRequestMessage1.md) |  | 
**FinishReason** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCreateDeepNewsResponseChoice1

`func NewCreateDeepNewsResponseChoice1(index int32, message CreateDeepNewsRequestMessage1, ) *CreateDeepNewsResponseChoice1`

NewCreateDeepNewsResponseChoice1 instantiates a new CreateDeepNewsResponseChoice1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDeepNewsResponseChoice1WithDefaults

`func NewCreateDeepNewsResponseChoice1WithDefaults() *CreateDeepNewsResponseChoice1`

NewCreateDeepNewsResponseChoice1WithDefaults instantiates a new CreateDeepNewsResponseChoice1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIndex

`func (o *CreateDeepNewsResponseChoice1) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *CreateDeepNewsResponseChoice1) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *CreateDeepNewsResponseChoice1) SetIndex(v int32)`

SetIndex sets Index field to given value.


### GetMessage

`func (o *CreateDeepNewsResponseChoice1) GetMessage() CreateDeepNewsRequestMessage1`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *CreateDeepNewsResponseChoice1) GetMessageOk() (*CreateDeepNewsRequestMessage1, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *CreateDeepNewsResponseChoice1) SetMessage(v CreateDeepNewsRequestMessage1)`

SetMessage sets Message field to given value.


### GetFinishReason

`func (o *CreateDeepNewsResponseChoice1) GetFinishReason() string`

GetFinishReason returns the FinishReason field if non-nil, zero value otherwise.

### GetFinishReasonOk

`func (o *CreateDeepNewsResponseChoice1) GetFinishReasonOk() (*string, bool)`

GetFinishReasonOk returns a tuple with the FinishReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishReason

`func (o *CreateDeepNewsResponseChoice1) SetFinishReason(v string)`

SetFinishReason sets FinishReason field to given value.

### HasFinishReason

`func (o *CreateDeepNewsResponseChoice1) HasFinishReason() bool`

HasFinishReason returns a boolean if a field has been set.

### SetFinishReasonNil

`func (o *CreateDeepNewsResponseChoice1) SetFinishReasonNil(b bool)`

 SetFinishReasonNil sets the value for FinishReason to be an explicit nil

### UnsetFinishReason
`func (o *CreateDeepNewsResponseChoice1) UnsetFinishReason()`

UnsetFinishReason ensures that no value is present for FinishReason, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


