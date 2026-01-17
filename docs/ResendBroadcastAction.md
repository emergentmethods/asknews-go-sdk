# ResendBroadcastAction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | Pointer to **string** |  | [optional] [default to "resend_broadcast"]
**Params** | [**ResendBroadcastParams**](ResendBroadcastParams.md) |  | 

## Methods

### NewResendBroadcastAction

`func NewResendBroadcastAction(params ResendBroadcastParams, ) *ResendBroadcastAction`

NewResendBroadcastAction instantiates a new ResendBroadcastAction object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResendBroadcastActionWithDefaults

`func NewResendBroadcastActionWithDefaults() *ResendBroadcastAction`

NewResendBroadcastActionWithDefaults instantiates a new ResendBroadcastAction object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *ResendBroadcastAction) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *ResendBroadcastAction) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *ResendBroadcastAction) SetAction(v string)`

SetAction sets Action field to given value.

### HasAction

`func (o *ResendBroadcastAction) HasAction() bool`

HasAction returns a boolean if a field has been set.

### GetParams

`func (o *ResendBroadcastAction) GetParams() ResendBroadcastParams`

GetParams returns the Params field if non-nil, zero value otherwise.

### GetParamsOk

`func (o *ResendBroadcastAction) GetParamsOk() (*ResendBroadcastParams, bool)`

GetParamsOk returns a tuple with the Params field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParams

`func (o *ResendBroadcastAction) SetParams(v ResendBroadcastParams)`

SetParams sets Params field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


