# CreateDeepNewsResponseStreamChunkChoice1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Index** | **int32** |  | 
**Delta** | [**CreateDeepNewsRequestMessage1**](CreateDeepNewsRequestMessage1.md) |  | 
**FinishReason** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCreateDeepNewsResponseStreamChunkChoice1

`func NewCreateDeepNewsResponseStreamChunkChoice1(index int32, delta CreateDeepNewsRequestMessage1, ) *CreateDeepNewsResponseStreamChunkChoice1`

NewCreateDeepNewsResponseStreamChunkChoice1 instantiates a new CreateDeepNewsResponseStreamChunkChoice1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDeepNewsResponseStreamChunkChoice1WithDefaults

`func NewCreateDeepNewsResponseStreamChunkChoice1WithDefaults() *CreateDeepNewsResponseStreamChunkChoice1`

NewCreateDeepNewsResponseStreamChunkChoice1WithDefaults instantiates a new CreateDeepNewsResponseStreamChunkChoice1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIndex

`func (o *CreateDeepNewsResponseStreamChunkChoice1) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *CreateDeepNewsResponseStreamChunkChoice1) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *CreateDeepNewsResponseStreamChunkChoice1) SetIndex(v int32)`

SetIndex sets Index field to given value.


### GetDelta

`func (o *CreateDeepNewsResponseStreamChunkChoice1) GetDelta() CreateDeepNewsRequestMessage1`

GetDelta returns the Delta field if non-nil, zero value otherwise.

### GetDeltaOk

`func (o *CreateDeepNewsResponseStreamChunkChoice1) GetDeltaOk() (*CreateDeepNewsRequestMessage1, bool)`

GetDeltaOk returns a tuple with the Delta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelta

`func (o *CreateDeepNewsResponseStreamChunkChoice1) SetDelta(v CreateDeepNewsRequestMessage1)`

SetDelta sets Delta field to given value.


### GetFinishReason

`func (o *CreateDeepNewsResponseStreamChunkChoice1) GetFinishReason() string`

GetFinishReason returns the FinishReason field if non-nil, zero value otherwise.

### GetFinishReasonOk

`func (o *CreateDeepNewsResponseStreamChunkChoice1) GetFinishReasonOk() (*string, bool)`

GetFinishReasonOk returns a tuple with the FinishReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishReason

`func (o *CreateDeepNewsResponseStreamChunkChoice1) SetFinishReason(v string)`

SetFinishReason sets FinishReason field to given value.

### HasFinishReason

`func (o *CreateDeepNewsResponseStreamChunkChoice1) HasFinishReason() bool`

HasFinishReason returns a boolean if a field has been set.

### SetFinishReasonNil

`func (o *CreateDeepNewsResponseStreamChunkChoice1) SetFinishReasonNil(b bool)`

 SetFinishReasonNil sets the value for FinishReason to be an explicit nil

### UnsetFinishReason
`func (o *CreateDeepNewsResponseStreamChunkChoice1) UnsetFinishReason()`

UnsetFinishReason ensures that no value is present for FinishReason, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


