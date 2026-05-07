# CreateDeepNewsResponseStreamSource1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Created** | **int32** |  | 
**Object** | Pointer to **string** |  | [optional] [default to "chat.completion.source"]
**Source** | [**Source**](Source.md) |  | 

## Methods

### NewCreateDeepNewsResponseStreamSource1

`func NewCreateDeepNewsResponseStreamSource1(id string, created int32, source Source, ) *CreateDeepNewsResponseStreamSource1`

NewCreateDeepNewsResponseStreamSource1 instantiates a new CreateDeepNewsResponseStreamSource1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDeepNewsResponseStreamSource1WithDefaults

`func NewCreateDeepNewsResponseStreamSource1WithDefaults() *CreateDeepNewsResponseStreamSource1`

NewCreateDeepNewsResponseStreamSource1WithDefaults instantiates a new CreateDeepNewsResponseStreamSource1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateDeepNewsResponseStreamSource1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateDeepNewsResponseStreamSource1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateDeepNewsResponseStreamSource1) SetId(v string)`

SetId sets Id field to given value.


### GetCreated

`func (o *CreateDeepNewsResponseStreamSource1) GetCreated() int32`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *CreateDeepNewsResponseStreamSource1) GetCreatedOk() (*int32, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *CreateDeepNewsResponseStreamSource1) SetCreated(v int32)`

SetCreated sets Created field to given value.


### GetObject

`func (o *CreateDeepNewsResponseStreamSource1) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *CreateDeepNewsResponseStreamSource1) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *CreateDeepNewsResponseStreamSource1) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *CreateDeepNewsResponseStreamSource1) HasObject() bool`

HasObject returns a boolean if a field has been set.

### GetSource

`func (o *CreateDeepNewsResponseStreamSource1) GetSource() Source`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *CreateDeepNewsResponseStreamSource1) GetSourceOk() (*Source, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *CreateDeepNewsResponseStreamSource1) SetSource(v Source)`

SetSource sets Source field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


