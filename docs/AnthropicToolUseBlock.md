# AnthropicToolUseBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "tool_use"]
**Id** | **string** |  | 
**Name** | **string** |  | 
**Input** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewAnthropicToolUseBlock

`func NewAnthropicToolUseBlock(id string, name string, ) *AnthropicToolUseBlock`

NewAnthropicToolUseBlock instantiates a new AnthropicToolUseBlock object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnthropicToolUseBlockWithDefaults

`func NewAnthropicToolUseBlockWithDefaults() *AnthropicToolUseBlock`

NewAnthropicToolUseBlockWithDefaults instantiates a new AnthropicToolUseBlock object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *AnthropicToolUseBlock) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AnthropicToolUseBlock) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AnthropicToolUseBlock) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *AnthropicToolUseBlock) HasType() bool`

HasType returns a boolean if a field has been set.

### GetId

`func (o *AnthropicToolUseBlock) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AnthropicToolUseBlock) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AnthropicToolUseBlock) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *AnthropicToolUseBlock) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AnthropicToolUseBlock) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AnthropicToolUseBlock) SetName(v string)`

SetName sets Name field to given value.


### GetInput

`func (o *AnthropicToolUseBlock) GetInput() map[string]interface{}`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *AnthropicToolUseBlock) GetInputOk() (*map[string]interface{}, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *AnthropicToolUseBlock) SetInput(v map[string]interface{})`

SetInput sets Input field to given value.

### HasInput

`func (o *AnthropicToolUseBlock) HasInput() bool`

HasInput returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


