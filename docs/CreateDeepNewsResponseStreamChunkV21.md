# CreateDeepNewsResponseStreamChunkV21

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Created** | **int32** |  | 
**Object** | Pointer to **string** |  | [optional] [default to "chat.completion.chunk"]
**Model** | Pointer to **string** |  | [optional] [default to "claude-sonnet-4-6"]
**Usage** | [**CreateDeepNewsResponseUsage2**](CreateDeepNewsResponseUsage2.md) |  | 
**Choices** | [**[]CreateDeepNewsResponseStreamChunkChoiceV21**](CreateDeepNewsResponseStreamChunkChoiceV21.md) |  | 

## Methods

### NewCreateDeepNewsResponseStreamChunkV21

`func NewCreateDeepNewsResponseStreamChunkV21(id string, created int32, usage CreateDeepNewsResponseUsage2, choices []CreateDeepNewsResponseStreamChunkChoiceV21, ) *CreateDeepNewsResponseStreamChunkV21`

NewCreateDeepNewsResponseStreamChunkV21 instantiates a new CreateDeepNewsResponseStreamChunkV21 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDeepNewsResponseStreamChunkV21WithDefaults

`func NewCreateDeepNewsResponseStreamChunkV21WithDefaults() *CreateDeepNewsResponseStreamChunkV21`

NewCreateDeepNewsResponseStreamChunkV21WithDefaults instantiates a new CreateDeepNewsResponseStreamChunkV21 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateDeepNewsResponseStreamChunkV21) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateDeepNewsResponseStreamChunkV21) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateDeepNewsResponseStreamChunkV21) SetId(v string)`

SetId sets Id field to given value.


### GetCreated

`func (o *CreateDeepNewsResponseStreamChunkV21) GetCreated() int32`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *CreateDeepNewsResponseStreamChunkV21) GetCreatedOk() (*int32, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *CreateDeepNewsResponseStreamChunkV21) SetCreated(v int32)`

SetCreated sets Created field to given value.


### GetObject

`func (o *CreateDeepNewsResponseStreamChunkV21) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *CreateDeepNewsResponseStreamChunkV21) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *CreateDeepNewsResponseStreamChunkV21) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *CreateDeepNewsResponseStreamChunkV21) HasObject() bool`

HasObject returns a boolean if a field has been set.

### GetModel

`func (o *CreateDeepNewsResponseStreamChunkV21) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *CreateDeepNewsResponseStreamChunkV21) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *CreateDeepNewsResponseStreamChunkV21) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *CreateDeepNewsResponseStreamChunkV21) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetUsage

`func (o *CreateDeepNewsResponseStreamChunkV21) GetUsage() CreateDeepNewsResponseUsage2`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *CreateDeepNewsResponseStreamChunkV21) GetUsageOk() (*CreateDeepNewsResponseUsage2, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *CreateDeepNewsResponseStreamChunkV21) SetUsage(v CreateDeepNewsResponseUsage2)`

SetUsage sets Usage field to given value.


### GetChoices

`func (o *CreateDeepNewsResponseStreamChunkV21) GetChoices() []CreateDeepNewsResponseStreamChunkChoiceV21`

GetChoices returns the Choices field if non-nil, zero value otherwise.

### GetChoicesOk

`func (o *CreateDeepNewsResponseStreamChunkV21) GetChoicesOk() (*[]CreateDeepNewsResponseStreamChunkChoiceV21, bool)`

GetChoicesOk returns a tuple with the Choices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChoices

`func (o *CreateDeepNewsResponseStreamChunkV21) SetChoices(v []CreateDeepNewsResponseStreamChunkChoiceV21)`

SetChoices sets Choices field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


