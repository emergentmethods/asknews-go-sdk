# CreateChatCompletionRequestMessage1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Role** | **string** |  | 
**Content** | **string** |  | 
**Name** | Pointer to **NullableString** |  | [optional] 
**FunctionCall** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewCreateChatCompletionRequestMessage1

`func NewCreateChatCompletionRequestMessage1(role string, content string, ) *CreateChatCompletionRequestMessage1`

NewCreateChatCompletionRequestMessage1 instantiates a new CreateChatCompletionRequestMessage1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateChatCompletionRequestMessage1WithDefaults

`func NewCreateChatCompletionRequestMessage1WithDefaults() *CreateChatCompletionRequestMessage1`

NewCreateChatCompletionRequestMessage1WithDefaults instantiates a new CreateChatCompletionRequestMessage1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRole

`func (o *CreateChatCompletionRequestMessage1) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *CreateChatCompletionRequestMessage1) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *CreateChatCompletionRequestMessage1) SetRole(v string)`

SetRole sets Role field to given value.


### GetContent

`func (o *CreateChatCompletionRequestMessage1) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *CreateChatCompletionRequestMessage1) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *CreateChatCompletionRequestMessage1) SetContent(v string)`

SetContent sets Content field to given value.


### GetName

`func (o *CreateChatCompletionRequestMessage1) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateChatCompletionRequestMessage1) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateChatCompletionRequestMessage1) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateChatCompletionRequestMessage1) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *CreateChatCompletionRequestMessage1) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *CreateChatCompletionRequestMessage1) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetFunctionCall

`func (o *CreateChatCompletionRequestMessage1) GetFunctionCall() map[string]interface{}`

GetFunctionCall returns the FunctionCall field if non-nil, zero value otherwise.

### GetFunctionCallOk

`func (o *CreateChatCompletionRequestMessage1) GetFunctionCallOk() (*map[string]interface{}, bool)`

GetFunctionCallOk returns a tuple with the FunctionCall field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFunctionCall

`func (o *CreateChatCompletionRequestMessage1) SetFunctionCall(v map[string]interface{})`

SetFunctionCall sets FunctionCall field to given value.

### HasFunctionCall

`func (o *CreateChatCompletionRequestMessage1) HasFunctionCall() bool`

HasFunctionCall returns a boolean if a field has been set.

### SetFunctionCallNil

`func (o *CreateChatCompletionRequestMessage1) SetFunctionCallNil(b bool)`

 SetFunctionCallNil sets the value for FunctionCall to be an explicit nil

### UnsetFunctionCall
`func (o *CreateChatCompletionRequestMessage1) UnsetFunctionCall()`

UnsetFunctionCall ensures that no value is present for FunctionCall, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


