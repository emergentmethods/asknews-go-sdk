# CreateDeepNewsResponseStreamSource

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Created** | **int32** |  | 
**Object** | Pointer to **string** |  | [optional] [default to "chat.completion.source"]
**Source** | [**Source**](Source.md) |  | 

## Methods

### NewCreateDeepNewsResponseStreamSource

`func NewCreateDeepNewsResponseStreamSource(id string, created int32, source Source, ) *CreateDeepNewsResponseStreamSource`

NewCreateDeepNewsResponseStreamSource instantiates a new CreateDeepNewsResponseStreamSource object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDeepNewsResponseStreamSourceWithDefaults

`func NewCreateDeepNewsResponseStreamSourceWithDefaults() *CreateDeepNewsResponseStreamSource`

NewCreateDeepNewsResponseStreamSourceWithDefaults instantiates a new CreateDeepNewsResponseStreamSource object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateDeepNewsResponseStreamSource) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateDeepNewsResponseStreamSource) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateDeepNewsResponseStreamSource) SetId(v string)`

SetId sets Id field to given value.


### GetCreated

`func (o *CreateDeepNewsResponseStreamSource) GetCreated() int32`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *CreateDeepNewsResponseStreamSource) GetCreatedOk() (*int32, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *CreateDeepNewsResponseStreamSource) SetCreated(v int32)`

SetCreated sets Created field to given value.


### GetObject

`func (o *CreateDeepNewsResponseStreamSource) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *CreateDeepNewsResponseStreamSource) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *CreateDeepNewsResponseStreamSource) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *CreateDeepNewsResponseStreamSource) HasObject() bool`

HasObject returns a boolean if a field has been set.

### GetSource

`func (o *CreateDeepNewsResponseStreamSource) GetSource() Source`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *CreateDeepNewsResponseStreamSource) GetSourceOk() (*Source, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *CreateDeepNewsResponseStreamSource) SetSource(v Source)`

SetSource sets Source field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


