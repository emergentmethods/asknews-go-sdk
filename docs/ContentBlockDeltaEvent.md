# ContentBlockDeltaEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "content_block_delta"]
**Index** | **int32** |  | 
**Delta** | [**Delta1**](Delta1.md) |  | 

## Methods

### NewContentBlockDeltaEvent

`func NewContentBlockDeltaEvent(index int32, delta Delta1, ) *ContentBlockDeltaEvent`

NewContentBlockDeltaEvent instantiates a new ContentBlockDeltaEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContentBlockDeltaEventWithDefaults

`func NewContentBlockDeltaEventWithDefaults() *ContentBlockDeltaEvent`

NewContentBlockDeltaEventWithDefaults instantiates a new ContentBlockDeltaEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ContentBlockDeltaEvent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContentBlockDeltaEvent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContentBlockDeltaEvent) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ContentBlockDeltaEvent) HasType() bool`

HasType returns a boolean if a field has been set.

### GetIndex

`func (o *ContentBlockDeltaEvent) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *ContentBlockDeltaEvent) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *ContentBlockDeltaEvent) SetIndex(v int32)`

SetIndex sets Index field to given value.


### GetDelta

`func (o *ContentBlockDeltaEvent) GetDelta() Delta1`

GetDelta returns the Delta field if non-nil, zero value otherwise.

### GetDeltaOk

`func (o *ContentBlockDeltaEvent) GetDeltaOk() (*Delta1, bool)`

GetDeltaOk returns a tuple with the Delta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelta

`func (o *ContentBlockDeltaEvent) SetDelta(v Delta1)`

SetDelta sets Delta field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


