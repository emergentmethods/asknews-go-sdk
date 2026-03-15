# DeepNewsSource

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** |  | 
**Params** | Pointer to [**DeepNewsSourceParams**](DeepNewsSourceParams.md) |  | [optional] 

## Methods

### NewDeepNewsSource

`func NewDeepNewsSource(identifier string, ) *DeepNewsSource`

NewDeepNewsSource instantiates a new DeepNewsSource object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeepNewsSourceWithDefaults

`func NewDeepNewsSourceWithDefaults() *DeepNewsSource`

NewDeepNewsSourceWithDefaults instantiates a new DeepNewsSource object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *DeepNewsSource) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *DeepNewsSource) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *DeepNewsSource) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetParams

`func (o *DeepNewsSource) GetParams() DeepNewsSourceParams`

GetParams returns the Params field if non-nil, zero value otherwise.

### GetParamsOk

`func (o *DeepNewsSource) GetParamsOk() (*DeepNewsSourceParams, bool)`

GetParamsOk returns a tuple with the Params field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParams

`func (o *DeepNewsSource) SetParams(v DeepNewsSourceParams)`

SetParams sets Params field to given value.

### HasParams

`func (o *DeepNewsSource) HasParams() bool`

HasParams returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


