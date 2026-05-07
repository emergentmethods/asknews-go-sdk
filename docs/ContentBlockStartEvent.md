# ContentBlockStartEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "content_block_start"]
**Index** | **int32** |  | 
**ContentBlock** | [**ContentBlock1**](ContentBlock1.md) |  | 

## Methods

### NewContentBlockStartEvent

`func NewContentBlockStartEvent(index int32, contentBlock ContentBlock1, ) *ContentBlockStartEvent`

NewContentBlockStartEvent instantiates a new ContentBlockStartEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContentBlockStartEventWithDefaults

`func NewContentBlockStartEventWithDefaults() *ContentBlockStartEvent`

NewContentBlockStartEventWithDefaults instantiates a new ContentBlockStartEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ContentBlockStartEvent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContentBlockStartEvent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContentBlockStartEvent) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ContentBlockStartEvent) HasType() bool`

HasType returns a boolean if a field has been set.

### GetIndex

`func (o *ContentBlockStartEvent) GetIndex() int32`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *ContentBlockStartEvent) GetIndexOk() (*int32, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *ContentBlockStartEvent) SetIndex(v int32)`

SetIndex sets Index field to given value.


### GetContentBlock

`func (o *ContentBlockStartEvent) GetContentBlock() ContentBlock1`

GetContentBlock returns the ContentBlock field if non-nil, zero value otherwise.

### GetContentBlockOk

`func (o *ContentBlockStartEvent) GetContentBlockOk() (*ContentBlock1, bool)`

GetContentBlockOk returns a tuple with the ContentBlock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentBlock

`func (o *ContentBlockStartEvent) SetContentBlock(v ContentBlock1)`

SetContentBlock sets ContentBlock field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


