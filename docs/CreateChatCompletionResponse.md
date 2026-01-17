# CreateChatCompletionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Created** | **int32** |  | 
**Object** | Pointer to **string** |  | [optional] [default to "chat.completion"]
**Model** | Pointer to **string** |  | [optional] [default to "gpt-4o-mini"]
**Usage** | [**CreateChatCompletionResponseUsage**](CreateChatCompletionResponseUsage.md) |  | 
**Choices** | [**[]CreateChatCompletionResponseChoice**](CreateChatCompletionResponseChoice.md) |  | 

## Methods

### NewCreateChatCompletionResponse

`func NewCreateChatCompletionResponse(id string, created int32, usage CreateChatCompletionResponseUsage, choices []CreateChatCompletionResponseChoice, ) *CreateChatCompletionResponse`

NewCreateChatCompletionResponse instantiates a new CreateChatCompletionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateChatCompletionResponseWithDefaults

`func NewCreateChatCompletionResponseWithDefaults() *CreateChatCompletionResponse`

NewCreateChatCompletionResponseWithDefaults instantiates a new CreateChatCompletionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateChatCompletionResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateChatCompletionResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateChatCompletionResponse) SetId(v string)`

SetId sets Id field to given value.


### GetCreated

`func (o *CreateChatCompletionResponse) GetCreated() int32`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *CreateChatCompletionResponse) GetCreatedOk() (*int32, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *CreateChatCompletionResponse) SetCreated(v int32)`

SetCreated sets Created field to given value.


### GetObject

`func (o *CreateChatCompletionResponse) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *CreateChatCompletionResponse) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *CreateChatCompletionResponse) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *CreateChatCompletionResponse) HasObject() bool`

HasObject returns a boolean if a field has been set.

### GetModel

`func (o *CreateChatCompletionResponse) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *CreateChatCompletionResponse) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *CreateChatCompletionResponse) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *CreateChatCompletionResponse) HasModel() bool`

HasModel returns a boolean if a field has been set.

### GetUsage

`func (o *CreateChatCompletionResponse) GetUsage() CreateChatCompletionResponseUsage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *CreateChatCompletionResponse) GetUsageOk() (*CreateChatCompletionResponseUsage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *CreateChatCompletionResponse) SetUsage(v CreateChatCompletionResponseUsage)`

SetUsage sets Usage field to given value.


### GetChoices

`func (o *CreateChatCompletionResponse) GetChoices() []CreateChatCompletionResponseChoice`

GetChoices returns the Choices field if non-nil, zero value otherwise.

### GetChoicesOk

`func (o *CreateChatCompletionResponse) GetChoicesOk() (*[]CreateChatCompletionResponseChoice, bool)`

GetChoicesOk returns a tuple with the Choices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChoices

`func (o *CreateChatCompletionResponse) SetChoices(v []CreateChatCompletionResponseChoice)`

SetChoices sets Choices field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


