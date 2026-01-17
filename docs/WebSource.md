# WebSource

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** |  | 
**Params** | [**WebSourceParams**](WebSourceParams.md) |  | 

## Methods

### NewWebSource

`func NewWebSource(identifier string, params WebSourceParams, ) *WebSource`

NewWebSource instantiates a new WebSource object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebSourceWithDefaults

`func NewWebSourceWithDefaults() *WebSource`

NewWebSourceWithDefaults instantiates a new WebSource object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *WebSource) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *WebSource) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *WebSource) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetParams

`func (o *WebSource) GetParams() WebSourceParams`

GetParams returns the Params field if non-nil, zero value otherwise.

### GetParamsOk

`func (o *WebSource) GetParamsOk() (*WebSourceParams, bool)`

GetParamsOk returns a tuple with the Params field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParams

`func (o *WebSource) SetParams(v WebSourceParams)`

SetParams sets Params field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


