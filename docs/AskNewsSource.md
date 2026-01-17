# AskNewsSource

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** |  | 
**Params** | Pointer to [**NullableFilterParams**](FilterParams.md) |  | [optional] 

## Methods

### NewAskNewsSource

`func NewAskNewsSource(identifier string, ) *AskNewsSource`

NewAskNewsSource instantiates a new AskNewsSource object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAskNewsSourceWithDefaults

`func NewAskNewsSourceWithDefaults() *AskNewsSource`

NewAskNewsSourceWithDefaults instantiates a new AskNewsSource object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *AskNewsSource) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *AskNewsSource) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *AskNewsSource) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetParams

`func (o *AskNewsSource) GetParams() FilterParams`

GetParams returns the Params field if non-nil, zero value otherwise.

### GetParamsOk

`func (o *AskNewsSource) GetParamsOk() (*FilterParams, bool)`

GetParamsOk returns a tuple with the Params field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParams

`func (o *AskNewsSource) SetParams(v FilterParams)`

SetParams sets Params field to given value.

### HasParams

`func (o *AskNewsSource) HasParams() bool`

HasParams returns a boolean if a field has been set.

### SetParamsNil

`func (o *AskNewsSource) SetParamsNil(b bool)`

 SetParamsNil sets the value for Params to be an explicit nil

### UnsetParams
`func (o *AskNewsSource) UnsetParams()`

UnsetParams ensures that no value is present for Params, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


