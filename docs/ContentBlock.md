# ContentBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "text"]
**Text** | Pointer to **string** |  | [optional] [default to ""]
**Thinking** | Pointer to **string** |  | [optional] [default to ""]
**Id** | **string** |  | 
**Name** | **string** |  | 
**Input** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewContentBlock

`func NewContentBlock(id string, name string, ) *ContentBlock`

NewContentBlock instantiates a new ContentBlock object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContentBlockWithDefaults

`func NewContentBlockWithDefaults() *ContentBlock`

NewContentBlockWithDefaults instantiates a new ContentBlock object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ContentBlock) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContentBlock) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContentBlock) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ContentBlock) HasType() bool`

HasType returns a boolean if a field has been set.

### GetText

`func (o *ContentBlock) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *ContentBlock) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *ContentBlock) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *ContentBlock) HasText() bool`

HasText returns a boolean if a field has been set.

### GetThinking

`func (o *ContentBlock) GetThinking() string`

GetThinking returns the Thinking field if non-nil, zero value otherwise.

### GetThinkingOk

`func (o *ContentBlock) GetThinkingOk() (*string, bool)`

GetThinkingOk returns a tuple with the Thinking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThinking

`func (o *ContentBlock) SetThinking(v string)`

SetThinking sets Thinking field to given value.

### HasThinking

`func (o *ContentBlock) HasThinking() bool`

HasThinking returns a boolean if a field has been set.

### GetId

`func (o *ContentBlock) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ContentBlock) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ContentBlock) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *ContentBlock) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ContentBlock) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ContentBlock) SetName(v string)`

SetName sets Name field to given value.


### GetInput

`func (o *ContentBlock) GetInput() map[string]interface{}`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *ContentBlock) GetInputOk() (*map[string]interface{}, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *ContentBlock) SetInput(v map[string]interface{})`

SetInput sets Input field to given value.

### HasInput

`func (o *ContentBlock) HasInput() bool`

HasInput returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


