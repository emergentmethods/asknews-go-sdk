# CreateDeepNewsResponseStreamChunkChoiceV21

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Index** | **int32** |  | 
**Delta** | [**Delta**](Delta.md) |  | 
**FinishReason** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCreateDeepNewsResponseStreamChunkChoiceV21

`func NewCreateDeepNewsResponseStreamChunkChoiceV21(index int32, delta Delta, ) *CreateDeepNewsResponseStreamChunkChoiceV21`

NewCreateDeepNewsResponseStreamChunkChoiceV21 instantiates a new CreateDeepNewsResponseStreamChunkChoiceV21 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDeepNewsResponseStreamChunkChoiceV21WithDefaults

`func NewCreateDeepNewsResponseStreamChunkChoiceV21WithDefaults() *CreateDeepNewsResponseStreamChunkChoiceV21`

NewCreateDeepNewsResponseStreamChunkChoiceV21WithDefaults instantiates a new CreateDeepNewsResponseStreamChunkChoiceV21 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIndex

`func (o *CreateDeepNewsResponseStreamChunkChoiceV21) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *CreateDeepNewsResponseStreamChunkChoiceV21) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *CreateDeepNewsResponseStreamChunkChoiceV21) SetIndex(v int32)`

SetIndex sets Index field to given value.


### GetDelta

`func (o *CreateDeepNewsResponseStreamChunkChoiceV21) GetDelta() Delta`

GetDelta returns the Delta field if non-nil, zero value otherwise.

### GetDeltaOk

`func (o *CreateDeepNewsResponseStreamChunkChoiceV21) GetDeltaOk() (*Delta, bool)`

GetDeltaOk returns a tuple with the Delta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelta

`func (o *CreateDeepNewsResponseStreamChunkChoiceV21) SetDelta(v Delta)`

SetDelta sets Delta field to given value.


### GetFinishReason

`func (o *CreateDeepNewsResponseStreamChunkChoiceV21) GetFinishReason() string`

GetFinishReason returns the FinishReason field if non-nil, zero value otherwise.

### GetFinishReasonOk

`func (o *CreateDeepNewsResponseStreamChunkChoiceV21) GetFinishReasonOk() (*string, bool)`

GetFinishReasonOk returns a tuple with the FinishReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishReason

`func (o *CreateDeepNewsResponseStreamChunkChoiceV21) SetFinishReason(v string)`

SetFinishReason sets FinishReason field to given value.

### HasFinishReason

`func (o *CreateDeepNewsResponseStreamChunkChoiceV21) HasFinishReason() bool`

HasFinishReason returns a boolean if a field has been set.

### SetFinishReasonNil

`func (o *CreateDeepNewsResponseStreamChunkChoiceV21) SetFinishReasonNil(b bool)`

 SetFinishReasonNil sets the value for FinishReason to be an explicit nil

### UnsetFinishReason
`func (o *CreateDeepNewsResponseStreamChunkChoiceV21) UnsetFinishReason()`

UnsetFinishReason ensures that no value is present for FinishReason, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


