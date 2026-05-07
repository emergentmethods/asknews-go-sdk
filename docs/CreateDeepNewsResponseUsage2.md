# CreateDeepNewsResponseUsage2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PromptTokens** | **int32** |  | 
**CompletionTokens** | **int32** |  | 
**TotalTokens** | **int32** |  | 
**ToolUsage** | Pointer to **map[string]int32** |  | [optional] 

## Methods

### NewCreateDeepNewsResponseUsage2

`func NewCreateDeepNewsResponseUsage2(promptTokens int32, completionTokens int32, totalTokens int32, ) *CreateDeepNewsResponseUsage2`

NewCreateDeepNewsResponseUsage2 instantiates a new CreateDeepNewsResponseUsage2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateDeepNewsResponseUsage2WithDefaults

`func NewCreateDeepNewsResponseUsage2WithDefaults() *CreateDeepNewsResponseUsage2`

NewCreateDeepNewsResponseUsage2WithDefaults instantiates a new CreateDeepNewsResponseUsage2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPromptTokens

`func (o *CreateDeepNewsResponseUsage2) GetPromptTokens() int32`

GetPromptTokens returns the PromptTokens field if non-nil, zero value otherwise.

### GetPromptTokensOk

`func (o *CreateDeepNewsResponseUsage2) GetPromptTokensOk() (*int32, bool)`

GetPromptTokensOk returns a tuple with the PromptTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptTokens

`func (o *CreateDeepNewsResponseUsage2) SetPromptTokens(v int32)`

SetPromptTokens sets PromptTokens field to given value.


### GetCompletionTokens

`func (o *CreateDeepNewsResponseUsage2) GetCompletionTokens() int32`

GetCompletionTokens returns the CompletionTokens field if non-nil, zero value otherwise.

### GetCompletionTokensOk

`func (o *CreateDeepNewsResponseUsage2) GetCompletionTokensOk() (*int32, bool)`

GetCompletionTokensOk returns a tuple with the CompletionTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletionTokens

`func (o *CreateDeepNewsResponseUsage2) SetCompletionTokens(v int32)`

SetCompletionTokens sets CompletionTokens field to given value.


### GetTotalTokens

`func (o *CreateDeepNewsResponseUsage2) GetTotalTokens() int32`

GetTotalTokens returns the TotalTokens field if non-nil, zero value otherwise.

### GetTotalTokensOk

`func (o *CreateDeepNewsResponseUsage2) GetTotalTokensOk() (*int32, bool)`

GetTotalTokensOk returns a tuple with the TotalTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalTokens

`func (o *CreateDeepNewsResponseUsage2) SetTotalTokens(v int32)`

SetTotalTokens sets TotalTokens field to given value.


### GetToolUsage

`func (o *CreateDeepNewsResponseUsage2) GetToolUsage() map[string]int32`

GetToolUsage returns the ToolUsage field if non-nil, zero value otherwise.

### GetToolUsageOk

`func (o *CreateDeepNewsResponseUsage2) GetToolUsageOk() (*map[string]int32, bool)`

GetToolUsageOk returns a tuple with the ToolUsage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolUsage

`func (o *CreateDeepNewsResponseUsage2) SetToolUsage(v map[string]int32)`

SetToolUsage sets ToolUsage field to given value.

### HasToolUsage

`func (o *CreateDeepNewsResponseUsage2) HasToolUsage() bool`

HasToolUsage returns a boolean if a field has been set.

### SetToolUsageNil

`func (o *CreateDeepNewsResponseUsage2) SetToolUsageNil(b bool)`

 SetToolUsageNil sets the value for ToolUsage to be an explicit nil

### UnsetToolUsage
`func (o *CreateDeepNewsResponseUsage2) UnsetToolUsage()`

UnsetToolUsage ensures that no value is present for ToolUsage, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


