# ContentBlockStopEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "content_block_stop"]
**Index** | **int32** |  | 

## Methods

### NewContentBlockStopEvent

`func NewContentBlockStopEvent(index int32, ) *ContentBlockStopEvent`

NewContentBlockStopEvent instantiates a new ContentBlockStopEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContentBlockStopEventWithDefaults

`func NewContentBlockStopEventWithDefaults() *ContentBlockStopEvent`

NewContentBlockStopEventWithDefaults instantiates a new ContentBlockStopEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ContentBlockStopEvent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContentBlockStopEvent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContentBlockStopEvent) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ContentBlockStopEvent) HasType() bool`

HasType returns a boolean if a field has been set.

### GetIndex

`func (o *ContentBlockStopEvent) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *ContentBlockStopEvent) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *ContentBlockStopEvent) SetIndex(v int32)`

SetIndex sets Index field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


