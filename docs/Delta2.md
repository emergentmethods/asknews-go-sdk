# Delta2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "message_start"]
**Role** | Pointer to **string** |  | [optional] [default to "assistant"]
**Index** | **int32** |  | 
**ContentBlock** | [**ContentBlock1**](ContentBlock1.md) |  | 
**Delta** | [**Delta1**](Delta1.md) |  | 

## Methods

### NewDelta2

`func NewDelta2(index int32, contentBlock ContentBlock1, delta Delta1, ) *Delta2`

NewDelta2 instantiates a new Delta2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDelta2WithDefaults

`func NewDelta2WithDefaults() *Delta2`

NewDelta2WithDefaults instantiates a new Delta2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *Delta2) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Delta2) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Delta2) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *Delta2) HasType() bool`

HasType returns a boolean if a field has been set.

### GetRole

`func (o *Delta2) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *Delta2) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *Delta2) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *Delta2) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetIndex

`func (o *Delta2) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *Delta2) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *Delta2) SetIndex(v int32)`

SetIndex sets Index field to given value.


### GetContentBlock

`func (o *Delta2) GetContentBlock() ContentBlock1`

GetContentBlock returns the ContentBlock field if non-nil, zero value otherwise.

### GetContentBlockOk

`func (o *Delta2) GetContentBlockOk() (*ContentBlock1, bool)`

GetContentBlockOk returns a tuple with the ContentBlock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentBlock

`func (o *Delta2) SetContentBlock(v ContentBlock1)`

SetContentBlock sets ContentBlock field to given value.


### GetDelta

`func (o *Delta2) GetDelta() Delta1`

GetDelta returns the Delta field if non-nil, zero value otherwise.

### GetDeltaOk

`func (o *Delta2) GetDeltaOk() (*Delta1, bool)`

GetDeltaOk returns a tuple with the Delta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelta

`func (o *Delta2) SetDelta(v Delta1)`

SetDelta sets Delta field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


