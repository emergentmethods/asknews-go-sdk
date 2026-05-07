# CreateDeepNewsResponseStreamChunkChoiceV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Index** | **int32** |  | 
**Delta** | [**Delta2**](Delta2.md) |  | 
**FinishReason** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCreateDeepNewsResponseStreamChunkChoiceV2

`func NewCreateDeepNewsResponseStreamChunkChoiceV2(index int32, delta Delta2, ) *CreateDeepNewsResponseStreamChunkChoiceV2`

NewCreateDeepNewsResponseStreamChunkChoiceV2 instantiates a new CreateDeepNewsResponseStreamChunkChoiceV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDeepNewsResponseStreamChunkChoiceV2WithDefaults

`func NewCreateDeepNewsResponseStreamChunkChoiceV2WithDefaults() *CreateDeepNewsResponseStreamChunkChoiceV2`

NewCreateDeepNewsResponseStreamChunkChoiceV2WithDefaults instantiates a new CreateDeepNewsResponseStreamChunkChoiceV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIndex

`func (o *CreateDeepNewsResponseStreamChunkChoiceV2) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *CreateDeepNewsResponseStreamChunkChoiceV2) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *CreateDeepNewsResponseStreamChunkChoiceV2) SetIndex(v int32)`

SetIndex sets Index field to given value.


### GetDelta

`func (o *CreateDeepNewsResponseStreamChunkChoiceV2) GetDelta() Delta2`

GetDelta returns the Delta field if non-nil, zero value otherwise.

### GetDeltaOk

`func (o *CreateDeepNewsResponseStreamChunkChoiceV2) GetDeltaOk() (*Delta2, bool)`

GetDeltaOk returns a tuple with the Delta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelta

`func (o *CreateDeepNewsResponseStreamChunkChoiceV2) SetDelta(v Delta2)`

SetDelta sets Delta field to given value.


### GetFinishReason

`func (o *CreateDeepNewsResponseStreamChunkChoiceV2) GetFinishReason() string`

GetFinishReason returns the FinishReason field if non-nil, zero value otherwise.

### GetFinishReasonOk

`func (o *CreateDeepNewsResponseStreamChunkChoiceV2) GetFinishReasonOk() (*string, bool)`

GetFinishReasonOk returns a tuple with the FinishReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishReason

`func (o *CreateDeepNewsResponseStreamChunkChoiceV2) SetFinishReason(v string)`

SetFinishReason sets FinishReason field to given value.

### HasFinishReason

`func (o *CreateDeepNewsResponseStreamChunkChoiceV2) HasFinishReason() bool`

HasFinishReason returns a boolean if a field has been set.

### SetFinishReasonNil

`func (o *CreateDeepNewsResponseStreamChunkChoiceV2) SetFinishReasonNil(b bool)`

 SetFinishReasonNil sets the value for FinishReason to be an explicit nil

### UnsetFinishReason
`func (o *CreateDeepNewsResponseStreamChunkChoiceV2) UnsetFinishReason()`

UnsetFinishReason ensures that no value is present for FinishReason, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


