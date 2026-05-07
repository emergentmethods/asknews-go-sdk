# Delta

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "message_start"]
**Role** | Pointer to **string** |  | [optional] [default to "assistant"]
**Index** | **int32** |  | 
**ContentBlock** | [**ContentBlock**](ContentBlock.md) |  | 
**Delta** | [**Delta**](Delta.md) |  | 

## Methods

### NewDelta

`func NewDelta(index int32, contentBlock ContentBlock, delta Delta, ) *Delta`

NewDelta instantiates a new Delta object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeltaWithDefaults

`func NewDeltaWithDefaults() *Delta`

NewDeltaWithDefaults instantiates a new Delta object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *Delta) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Delta) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Delta) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *Delta) HasType() bool`

HasType returns a boolean if a field has been set.

### GetRole

`func (o *Delta) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *Delta) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *Delta) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *Delta) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetIndex

`func (o *Delta) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *Delta) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *Delta) SetIndex(v int32)`

SetIndex sets Index field to given value.


### GetContentBlock

`func (o *Delta) GetContentBlock() ContentBlock`

GetContentBlock returns the ContentBlock field if non-nil, zero value otherwise.

### GetContentBlockOk

`func (o *Delta) GetContentBlockOk() (*ContentBlock, bool)`

GetContentBlockOk returns a tuple with the ContentBlock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentBlock

`func (o *Delta) SetContentBlock(v ContentBlock)`

SetContentBlock sets ContentBlock field to given value.


### GetDelta

`func (o *Delta) GetDelta() Delta`

GetDelta returns the Delta field if non-nil, zero value otherwise.

### GetDeltaOk

`func (o *Delta) GetDeltaOk() (*Delta, bool)`

GetDeltaOk returns a tuple with the Delta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelta

`func (o *Delta) SetDelta(v Delta)`

SetDelta sets Delta field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


