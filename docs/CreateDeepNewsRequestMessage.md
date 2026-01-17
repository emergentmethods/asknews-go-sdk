# CreateDeepNewsRequestMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Role** | **string** |  | 
**Content** | **string** |  | 
**Name** | Pointer to **NullableString** |  | [optional] 
**FunctionCall** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewCreateDeepNewsRequestMessage

`func NewCreateDeepNewsRequestMessage(role string, content string, ) *CreateDeepNewsRequestMessage`

NewCreateDeepNewsRequestMessage instantiates a new CreateDeepNewsRequestMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDeepNewsRequestMessageWithDefaults

`func NewCreateDeepNewsRequestMessageWithDefaults() *CreateDeepNewsRequestMessage`

NewCreateDeepNewsRequestMessageWithDefaults instantiates a new CreateDeepNewsRequestMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRole

`func (o *CreateDeepNewsRequestMessage) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *CreateDeepNewsRequestMessage) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *CreateDeepNewsRequestMessage) SetRole(v string)`

SetRole sets Role field to given value.


### GetContent

`func (o *CreateDeepNewsRequestMessage) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *CreateDeepNewsRequestMessage) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *CreateDeepNewsRequestMessage) SetContent(v string)`

SetContent sets Content field to given value.


### GetName

`func (o *CreateDeepNewsRequestMessage) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateDeepNewsRequestMessage) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateDeepNewsRequestMessage) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateDeepNewsRequestMessage) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *CreateDeepNewsRequestMessage) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *CreateDeepNewsRequestMessage) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetFunctionCall

`func (o *CreateDeepNewsRequestMessage) GetFunctionCall() map[string]interface{}`

GetFunctionCall returns the FunctionCall field if non-nil, zero value otherwise.

### GetFunctionCallOk

`func (o *CreateDeepNewsRequestMessage) GetFunctionCallOk() (*map[string]interface{}, bool)`

GetFunctionCallOk returns a tuple with the FunctionCall field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFunctionCall

`func (o *CreateDeepNewsRequestMessage) SetFunctionCall(v map[string]interface{})`

SetFunctionCall sets FunctionCall field to given value.

### HasFunctionCall

`func (o *CreateDeepNewsRequestMessage) HasFunctionCall() bool`

HasFunctionCall returns a boolean if a field has been set.

### SetFunctionCallNil

`func (o *CreateDeepNewsRequestMessage) SetFunctionCallNil(b bool)`

 SetFunctionCallNil sets the value for FunctionCall to be an explicit nil

### UnsetFunctionCall
`func (o *CreateDeepNewsRequestMessage) UnsetFunctionCall()`

UnsetFunctionCall ensures that no value is present for FunctionCall, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


