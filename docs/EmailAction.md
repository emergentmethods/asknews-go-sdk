# EmailAction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | Pointer to **string** |  | [optional] [default to "email"]
**Params** | [**EmailParams**](EmailParams.md) |  | 

## Methods

### NewEmailAction

`func NewEmailAction(params EmailParams, ) *EmailAction`

NewEmailAction instantiates a new EmailAction object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmailActionWithDefaults

`func NewEmailActionWithDefaults() *EmailAction`

NewEmailActionWithDefaults instantiates a new EmailAction object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *EmailAction) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *EmailAction) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *EmailAction) SetAction(v string)`

SetAction sets Action field to given value.

### HasAction

`func (o *EmailAction) HasAction() bool`

HasAction returns a boolean if a field has been set.

### GetParams

`func (o *EmailAction) GetParams() EmailParams`

GetParams returns the Params field if non-nil, zero value otherwise.

### GetParamsOk

`func (o *EmailAction) GetParamsOk() (*EmailParams, bool)`

GetParamsOk returns a tuple with the Params field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParams

`func (o *EmailAction) SetParams(v EmailParams)`

SetParams sets Params field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


