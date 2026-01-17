# CreateDeepNewsResponseStreamChunkChoice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Index** | **int32** |  | 
**Delta** | [**CreateDeepNewsRequestMessage**](CreateDeepNewsRequestMessage.md) |  | 
**FinishReason** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCreateDeepNewsResponseStreamChunkChoice

`func NewCreateDeepNewsResponseStreamChunkChoice(index int32, delta CreateDeepNewsRequestMessage, ) *CreateDeepNewsResponseStreamChunkChoice`

NewCreateDeepNewsResponseStreamChunkChoice instantiates a new CreateDeepNewsResponseStreamChunkChoice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDeepNewsResponseStreamChunkChoiceWithDefaults

`func NewCreateDeepNewsResponseStreamChunkChoiceWithDefaults() *CreateDeepNewsResponseStreamChunkChoice`

NewCreateDeepNewsResponseStreamChunkChoiceWithDefaults instantiates a new CreateDeepNewsResponseStreamChunkChoice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIndex

`func (o *CreateDeepNewsResponseStreamChunkChoice) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *CreateDeepNewsResponseStreamChunkChoice) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *CreateDeepNewsResponseStreamChunkChoice) SetIndex(v int32)`

SetIndex sets Index field to given value.


### GetDelta

`func (o *CreateDeepNewsResponseStreamChunkChoice) GetDelta() CreateDeepNewsRequestMessage`

GetDelta returns the Delta field if non-nil, zero value otherwise.

### GetDeltaOk

`func (o *CreateDeepNewsResponseStreamChunkChoice) GetDeltaOk() (*CreateDeepNewsRequestMessage, bool)`

GetDeltaOk returns a tuple with the Delta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelta

`func (o *CreateDeepNewsResponseStreamChunkChoice) SetDelta(v CreateDeepNewsRequestMessage)`

SetDelta sets Delta field to given value.


### GetFinishReason

`func (o *CreateDeepNewsResponseStreamChunkChoice) GetFinishReason() string`

GetFinishReason returns the FinishReason field if non-nil, zero value otherwise.

### GetFinishReasonOk

`func (o *CreateDeepNewsResponseStreamChunkChoice) GetFinishReasonOk() (*string, bool)`

GetFinishReasonOk returns a tuple with the FinishReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishReason

`func (o *CreateDeepNewsResponseStreamChunkChoice) SetFinishReason(v string)`

SetFinishReason sets FinishReason field to given value.

### HasFinishReason

`func (o *CreateDeepNewsResponseStreamChunkChoice) HasFinishReason() bool`

HasFinishReason returns a boolean if a field has been set.

### SetFinishReasonNil

`func (o *CreateDeepNewsResponseStreamChunkChoice) SetFinishReasonNil(b bool)`

 SetFinishReasonNil sets the value for FinishReason to be an explicit nil

### UnsetFinishReason
`func (o *CreateDeepNewsResponseStreamChunkChoice) UnsetFinishReason()`

UnsetFinishReason ensures that no value is present for FinishReason, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


