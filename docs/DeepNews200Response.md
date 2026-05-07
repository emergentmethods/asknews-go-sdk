# DeepNews200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Created** | **int32** |  | 
**Object** | Pointer to **string** |  | [optional] [default to "chat.completion.source"]
**Model** | Pointer to **string** |  | [optional] [default to "claude-sonnet-4-6"]
**Usage** | [**CreateDeepNewsResponseUsage2**](CreateDeepNewsResponseUsage2.md) |  | 
**Choices** | [**[]CreateDeepNewsResponseStreamChunkChoiceV21**](CreateDeepNewsResponseStreamChunkChoiceV21.md) |  | 
**Source** | [**Source**](Source.md) |  | 

## Methods

### NewDeepNews200Response

`func NewDeepNews200Response(id string, created int32, usage CreateDeepNewsResponseUsage2, choices []CreateDeepNewsResponseStreamChunkChoiceV21, source Source, ) *DeepNews200Response`

NewDeepNews200Response instantiates a new DeepNews200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeepNews200ResponseWithDefaults

`func NewDeepNews200ResponseWithDefaults() *DeepNews200Response`

NewDeepNews200ResponseWithDefaults instantiates a new DeepNews200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DeepNews200Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DeepNews200Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DeepNews200Response) SetId(v string)`

SetId sets Id field to given value.


### GetCreated

`func (o *DeepNews200Response) GetCreated() int32`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *DeepNews200Response) GetCreatedOk() (*int32, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *DeepNews200Response) SetCreated(v int32)`

SetCreated sets Created field to given value.


### GetObject

`func (o *DeepNews200Response) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *DeepNews200Response) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *DeepNews200Response) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *DeepNews200Response) HasObject() bool`

HasObject returns a boolean if a field has been set.

### GetModel

`func (o *DeepNews200Response) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *DeepNews200Response) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *DeepNews200Response) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *DeepNews200Response) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetUsage

`func (o *DeepNews200Response) GetUsage() CreateDeepNewsResponseUsage2`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *DeepNews200Response) GetUsageOk() (*CreateDeepNewsResponseUsage2, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *DeepNews200Response) SetUsage(v CreateDeepNewsResponseUsage2)`

SetUsage sets Usage field to given value.


### GetChoices

`func (o *DeepNews200Response) GetChoices() []CreateDeepNewsResponseStreamChunkChoiceV21`

GetChoices returns the Choices field if non-nil, zero value otherwise.

### GetChoicesOk

`func (o *DeepNews200Response) GetChoicesOk() (*[]CreateDeepNewsResponseStreamChunkChoiceV21, bool)`

GetChoicesOk returns a tuple with the Choices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChoices

`func (o *DeepNews200Response) SetChoices(v []CreateDeepNewsResponseStreamChunkChoiceV21)`

SetChoices sets Choices field to given value.


### GetSource

`func (o *DeepNews200Response) GetSource() Source`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *DeepNews200Response) GetSourceOk() (*Source, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *DeepNews200Response) SetSource(v Source)`

SetSource sets Source field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


