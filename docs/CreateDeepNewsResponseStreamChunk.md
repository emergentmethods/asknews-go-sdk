# CreateDeepNewsResponseStreamChunk

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Created** | **int32** |  | 
**Object** | Pointer to **string** |  | [optional] [default to "chat.completion.chunk"]
**Model** | Pointer to **string** |  | [optional] [default to "deepseek"]
**Usage** | [**CreateDeepNewsResponseUsage**](CreateDeepNewsResponseUsage.md) |  | 
**Choices** | [**[]CreateDeepNewsResponseStreamChunkChoice**](CreateDeepNewsResponseStreamChunkChoice.md) |  | 

## Methods

### NewCreateDeepNewsResponseStreamChunk

`func NewCreateDeepNewsResponseStreamChunk(id string, created int32, usage CreateDeepNewsResponseUsage, choices []CreateDeepNewsResponseStreamChunkChoice, ) *CreateDeepNewsResponseStreamChunk`

NewCreateDeepNewsResponseStreamChunk instantiates a new CreateDeepNewsResponseStreamChunk object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDeepNewsResponseStreamChunkWithDefaults

`func NewCreateDeepNewsResponseStreamChunkWithDefaults() *CreateDeepNewsResponseStreamChunk`

NewCreateDeepNewsResponseStreamChunkWithDefaults instantiates a new CreateDeepNewsResponseStreamChunk object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateDeepNewsResponseStreamChunk) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateDeepNewsResponseStreamChunk) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateDeepNewsResponseStreamChunk) SetId(v string)`

SetId sets Id field to given value.


### GetCreated

`func (o *CreateDeepNewsResponseStreamChunk) GetCreated() int32`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *CreateDeepNewsResponseStreamChunk) GetCreatedOk() (*int32, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *CreateDeepNewsResponseStreamChunk) SetCreated(v int32)`

SetCreated sets Created field to given value.


### GetObject

`func (o *CreateDeepNewsResponseStreamChunk) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *CreateDeepNewsResponseStreamChunk) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *CreateDeepNewsResponseStreamChunk) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *CreateDeepNewsResponseStreamChunk) HasObject() bool`

HasObject returns a boolean if a field has been set.

### GetModel

`func (o *CreateDeepNewsResponseStreamChunk) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *CreateDeepNewsResponseStreamChunk) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *CreateDeepNewsResponseStreamChunk) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *CreateDeepNewsResponseStreamChunk) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetUsage

`func (o *CreateDeepNewsResponseStreamChunk) GetUsage() CreateDeepNewsResponseUsage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *CreateDeepNewsResponseStreamChunk) GetUsageOk() (*CreateDeepNewsResponseUsage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *CreateDeepNewsResponseStreamChunk) SetUsage(v CreateDeepNewsResponseUsage)`

SetUsage sets Usage field to given value.


### GetChoices

`func (o *CreateDeepNewsResponseStreamChunk) GetChoices() []CreateDeepNewsResponseStreamChunkChoice`

GetChoices returns the Choices field if non-nil, zero value otherwise.

### GetChoicesOk

`func (o *CreateDeepNewsResponseStreamChunk) GetChoicesOk() (*[]CreateDeepNewsResponseStreamChunkChoice, bool)`

GetChoicesOk returns a tuple with the Choices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChoices

`func (o *CreateDeepNewsResponseStreamChunk) SetChoices(v []CreateDeepNewsResponseStreamChunkChoice)`

SetChoices sets Choices field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


