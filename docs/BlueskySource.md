# BlueskySource

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Identifier** | **string** |  | 
**Params** | Pointer to [**NullableBlueskySourceParams**](BlueskySourceParams.md) |  | [optional] 

## Methods

### NewBlueskySource

`func NewBlueskySource(identifier string, ) *BlueskySource`

NewBlueskySource instantiates a new BlueskySource object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBlueskySourceWithDefaults

`func NewBlueskySourceWithDefaults() *BlueskySource`

NewBlueskySourceWithDefaults instantiates a new BlueskySource object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentifier

`func (o *BlueskySource) GetIdentifier() string`

GetIdentifier returns the Identifier field if non-nil, zero value otherwise.

### GetIdentifierOk

`func (o *BlueskySource) GetIdentifierOk() (*string, bool)`

GetIdentifierOk returns a tuple with the Identifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentifier

`func (o *BlueskySource) SetIdentifier(v string)`

SetIdentifier sets Identifier field to given value.


### GetParams

`func (o *BlueskySource) GetParams() BlueskySourceParams`

GetParams returns the Params field if non-nil, zero value otherwise.

### GetParamsOk

`func (o *BlueskySource) GetParamsOk() (*BlueskySourceParams, bool)`

GetParamsOk returns a tuple with the Params field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParams

`func (o *BlueskySource) SetParams(v BlueskySourceParams)`

SetParams sets Params field to given value.

### HasParams

`func (o *BlueskySource) HasParams() bool`

HasParams returns a boolean if a field has been set.

### SetParamsNil

`func (o *BlueskySource) SetParamsNil(b bool)`

 SetParamsNil sets the value for Params to be an explicit nil

### UnsetParams
`func (o *BlueskySource) UnsetParams()`

UnsetParams ensures that no value is present for Params, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


