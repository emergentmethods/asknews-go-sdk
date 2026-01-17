# CreateDeepNewsResponse1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Created** | **int32** |  | 
**Object** | Pointer to **string** |  | [optional] [default to "chat.completion"]
**Model** | Pointer to **string** |  | [optional] [default to "deepseek"]
**Usage** | [**CreateDeepNewsResponseUsage1**](CreateDeepNewsResponseUsage1.md) |  | 
**Choices** | [**[]CreateDeepNewsResponseChoice1**](CreateDeepNewsResponseChoice1.md) |  | 
**Sources** | [**DeepNewsResponseSources1**](DeepNewsResponseSources1.md) |  | 

## Methods

### NewCreateDeepNewsResponse1

`func NewCreateDeepNewsResponse1(id string, created int32, usage CreateDeepNewsResponseUsage1, choices []CreateDeepNewsResponseChoice1, sources DeepNewsResponseSources1, ) *CreateDeepNewsResponse1`

NewCreateDeepNewsResponse1 instantiates a new CreateDeepNewsResponse1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDeepNewsResponse1WithDefaults

`func NewCreateDeepNewsResponse1WithDefaults() *CreateDeepNewsResponse1`

NewCreateDeepNewsResponse1WithDefaults instantiates a new CreateDeepNewsResponse1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateDeepNewsResponse1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateDeepNewsResponse1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateDeepNewsResponse1) SetId(v string)`

SetId sets Id field to given value.


### GetCreated

`func (o *CreateDeepNewsResponse1) GetCreated() int32`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *CreateDeepNewsResponse1) GetCreatedOk() (*int32, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *CreateDeepNewsResponse1) SetCreated(v int32)`

SetCreated sets Created field to given value.


### GetObject

`func (o *CreateDeepNewsResponse1) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *CreateDeepNewsResponse1) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *CreateDeepNewsResponse1) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *CreateDeepNewsResponse1) HasObject() bool`

HasObject returns a boolean if a field has been set.

### GetModel

`func (o *CreateDeepNewsResponse1) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *CreateDeepNewsResponse1) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *CreateDeepNewsResponse1) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *CreateDeepNewsResponse1) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetUsage

`func (o *CreateDeepNewsResponse1) GetUsage() CreateDeepNewsResponseUsage1`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *CreateDeepNewsResponse1) GetUsageOk() (*CreateDeepNewsResponseUsage1, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *CreateDeepNewsResponse1) SetUsage(v CreateDeepNewsResponseUsage1)`

SetUsage sets Usage field to given value.


### GetChoices

`func (o *CreateDeepNewsResponse1) GetChoices() []CreateDeepNewsResponseChoice1`

GetChoices returns the Choices field if non-nil, zero value otherwise.

### GetChoicesOk

`func (o *CreateDeepNewsResponse1) GetChoicesOk() (*[]CreateDeepNewsResponseChoice1, bool)`

GetChoicesOk returns a tuple with the Choices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChoices

`func (o *CreateDeepNewsResponse1) SetChoices(v []CreateDeepNewsResponseChoice1)`

SetChoices sets Choices field to given value.


### GetSources

`func (o *CreateDeepNewsResponse1) GetSources() DeepNewsResponseSources1`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *CreateDeepNewsResponse1) GetSourcesOk() (*DeepNewsResponseSources1, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *CreateDeepNewsResponse1) SetSources(v DeepNewsResponseSources1)`

SetSources sets Sources field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


