# WebhookAction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | Pointer to **string** |  | [optional] [default to "webhook"]
**Params** | [**WebhookParams**](WebhookParams.md) |  | 

## Methods

### NewWebhookAction

`func NewWebhookAction(params WebhookParams, ) *WebhookAction`

NewWebhookAction instantiates a new WebhookAction object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebhookActionWithDefaults

`func NewWebhookActionWithDefaults() *WebhookAction`

NewWebhookActionWithDefaults instantiates a new WebhookAction object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *WebhookAction) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *WebhookAction) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *WebhookAction) SetAction(v string)`

SetAction sets Action field to given value.

### HasAction

`func (o *WebhookAction) HasAction() bool`

HasAction returns a boolean if a field has been set.

### GetParams

`func (o *WebhookAction) GetParams() WebhookParams`

GetParams returns the Params field if non-nil, zero value otherwise.

### GetParamsOk

`func (o *WebhookAction) GetParamsOk() (*WebhookParams, bool)`

GetParamsOk returns a tuple with the Params field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParams

`func (o *WebhookAction) SetParams(v WebhookParams)`

SetParams sets Params field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


