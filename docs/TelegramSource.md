# TelegramSource

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** |  | 
**Params** | [**TelegramSourceParams**](TelegramSourceParams.md) |  | 

## Methods

### NewTelegramSource

`func NewTelegramSource(identifier string, params TelegramSourceParams, ) *TelegramSource`

NewTelegramSource instantiates a new TelegramSource object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTelegramSourceWithDefaults

`func NewTelegramSourceWithDefaults() *TelegramSource`

NewTelegramSourceWithDefaults instantiates a new TelegramSource object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *TelegramSource) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *TelegramSource) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *TelegramSource) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetParams

`func (o *TelegramSource) GetParams() TelegramSourceParams`

GetParams returns the Params field if non-nil, zero value otherwise.

### GetParamsOk

`func (o *TelegramSource) GetParamsOk() (*TelegramSourceParams, bool)`

GetParamsOk returns a tuple with the Params field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParams

`func (o *TelegramSource) SetParams(v TelegramSourceParams)`

SetParams sets Params field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


