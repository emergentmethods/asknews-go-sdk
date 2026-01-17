# CreateChatCompletionResponse1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Created** | **int32** |  | 
**Object** | Pointer to **string** |  | [optional] [default to "chat.completion"]
**Model** | Pointer to **string** |  | [optional] [default to "gpt-4o-mini"]
**Usage** | [**CreateChatCompletionResponseUsage1**](CreateChatCompletionResponseUsage1.md) |  | 
**Choices** | [**[]CreateChatCompletionResponseChoice1**](CreateChatCompletionResponseChoice1.md) |  | 

## Methods

### NewCreateChatCompletionResponse1

`func NewCreateChatCompletionResponse1(id string, created int32, usage CreateChatCompletionResponseUsage1, choices []CreateChatCompletionResponseChoice1, ) *CreateChatCompletionResponse1`

NewCreateChatCompletionResponse1 instantiates a new CreateChatCompletionResponse1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateChatCompletionResponse1WithDefaults

`func NewCreateChatCompletionResponse1WithDefaults() *CreateChatCompletionResponse1`

NewCreateChatCompletionResponse1WithDefaults instantiates a new CreateChatCompletionResponse1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateChatCompletionResponse1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateChatCompletionResponse1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateChatCompletionResponse1) SetId(v string)`

SetId sets Id field to given value.


### GetCreated

`func (o *CreateChatCompletionResponse1) GetCreated() int32`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *CreateChatCompletionResponse1) GetCreatedOk() (*int32, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *CreateChatCompletionResponse1) SetCreated(v int32)`

SetCreated sets Created field to given value.


### GetObject

`func (o *CreateChatCompletionResponse1) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *CreateChatCompletionResponse1) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *CreateChatCompletionResponse1) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *CreateChatCompletionResponse1) HasObject() bool`

HasObject returns a boolean if a field has been set.

### GetModel

`func (o *CreateChatCompletionResponse1) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *CreateChatCompletionResponse1) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *CreateChatCompletionResponse1) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *CreateChatCompletionResponse1) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetUsage

`func (o *CreateChatCompletionResponse1) GetUsage() CreateChatCompletionResponseUsage1`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *CreateChatCompletionResponse1) GetUsageOk() (*CreateChatCompletionResponseUsage1, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *CreateChatCompletionResponse1) SetUsage(v CreateChatCompletionResponseUsage1)`

SetUsage sets Usage field to given value.


### GetChoices

`func (o *CreateChatCompletionResponse1) GetChoices() []CreateChatCompletionResponseChoice1`

GetChoices returns the Choices field if non-nil, zero value otherwise.

### GetChoicesOk

`func (o *CreateChatCompletionResponse1) GetChoicesOk() (*[]CreateChatCompletionResponseChoice1, bool)`

GetChoicesOk returns a tuple with the Choices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChoices

`func (o *CreateChatCompletionResponse1) SetChoices(v []CreateChatCompletionResponseChoice1)`

SetChoices sets Choices field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


