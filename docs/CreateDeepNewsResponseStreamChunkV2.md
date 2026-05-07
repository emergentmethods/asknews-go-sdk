# CreateDeepNewsResponseStreamChunkV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Created** | **int32** |  | 
**Object** | Pointer to **string** |  | [optional] [default to "chat.completion.chunk"]
**Model** | Pointer to **string** |  | [optional] [default to "claude-sonnet-4-6"]
**Usage** | [**CreateDeepNewsResponseUsage**](CreateDeepNewsResponseUsage.md) |  | 
**Choices** | [**[]CreateDeepNewsResponseStreamChunkChoiceV2**](CreateDeepNewsResponseStreamChunkChoiceV2.md) |  | 

## Methods

### NewCreateDeepNewsResponseStreamChunkV2

`func NewCreateDeepNewsResponseStreamChunkV2(id string, created int32, usage CreateDeepNewsResponseUsage, choices []CreateDeepNewsResponseStreamChunkChoiceV2, ) *CreateDeepNewsResponseStreamChunkV2`

NewCreateDeepNewsResponseStreamChunkV2 instantiates a new CreateDeepNewsResponseStreamChunkV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDeepNewsResponseStreamChunkV2WithDefaults

`func NewCreateDeepNewsResponseStreamChunkV2WithDefaults() *CreateDeepNewsResponseStreamChunkV2`

NewCreateDeepNewsResponseStreamChunkV2WithDefaults instantiates a new CreateDeepNewsResponseStreamChunkV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateDeepNewsResponseStreamChunkV2) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateDeepNewsResponseStreamChunkV2) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateDeepNewsResponseStreamChunkV2) SetId(v string)`

SetId sets Id field to given value.


### GetCreated

`func (o *CreateDeepNewsResponseStreamChunkV2) GetCreated() int32`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *CreateDeepNewsResponseStreamChunkV2) GetCreatedOk() (*int32, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *CreateDeepNewsResponseStreamChunkV2) SetCreated(v int32)`

SetCreated sets Created field to given value.


### GetObject

`func (o *CreateDeepNewsResponseStreamChunkV2) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *CreateDeepNewsResponseStreamChunkV2) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *CreateDeepNewsResponseStreamChunkV2) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *CreateDeepNewsResponseStreamChunkV2) HasObject() bool`

HasObject returns a boolean if a field has been set.

### GetModel

`func (o *CreateDeepNewsResponseStreamChunkV2) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *CreateDeepNewsResponseStreamChunkV2) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *CreateDeepNewsResponseStreamChunkV2) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *CreateDeepNewsResponseStreamChunkV2) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetUsage

`func (o *CreateDeepNewsResponseStreamChunkV2) GetUsage() CreateDeepNewsResponseUsage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *CreateDeepNewsResponseStreamChunkV2) GetUsageOk() (*CreateDeepNewsResponseUsage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *CreateDeepNewsResponseStreamChunkV2) SetUsage(v CreateDeepNewsResponseUsage)`

SetUsage sets Usage field to given value.


### GetChoices

`func (o *CreateDeepNewsResponseStreamChunkV2) GetChoices() []CreateDeepNewsResponseStreamChunkChoiceV2`

GetChoices returns the Choices field if non-nil, zero value otherwise.

### GetChoicesOk

`func (o *CreateDeepNewsResponseStreamChunkV2) GetChoicesOk() (*[]CreateDeepNewsResponseStreamChunkChoiceV2, bool)`

GetChoicesOk returns a tuple with the Choices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChoices

`func (o *CreateDeepNewsResponseStreamChunkV2) SetChoices(v []CreateDeepNewsResponseStreamChunkChoiceV2)`

SetChoices sets Choices field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


