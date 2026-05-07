# MessageStartEvent1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "message_start"]
**Role** | Pointer to **string** |  | [optional] [default to "assistant"]

## Methods

### NewMessageStartEvent1

`func NewMessageStartEvent1() *MessageStartEvent1`

NewMessageStartEvent1 instantiates a new MessageStartEvent1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageStartEvent1WithDefaults

`func NewMessageStartEvent1WithDefaults() *MessageStartEvent1`

NewMessageStartEvent1WithDefaults instantiates a new MessageStartEvent1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *MessageStartEvent1) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *MessageStartEvent1) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *MessageStartEvent1) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *MessageStartEvent1) HasType() bool`

HasType returns a boolean if a field has been set.

### GetRole

`func (o *MessageStartEvent1) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *MessageStartEvent1) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *MessageStartEvent1) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *MessageStartEvent1) HasRole() bool`

HasRole returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


