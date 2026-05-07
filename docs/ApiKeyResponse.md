# ApiKeyResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Provider** | **string** |  | 
**KeyHint** | **string** |  | 

## Methods

### NewApiKeyResponse

`func NewApiKeyResponse(provider string, keyHint string, ) *ApiKeyResponse`

NewApiKeyResponse instantiates a new ApiKeyResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiKeyResponseWithDefaults

`func NewApiKeyResponseWithDefaults() *ApiKeyResponse`

NewApiKeyResponseWithDefaults instantiates a new ApiKeyResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProvider

`func (o *ApiKeyResponse) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *ApiKeyResponse) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *ApiKeyResponse) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetKeyHint

`func (o *ApiKeyResponse) GetKeyHint() string`

GetKeyHint returns the KeyHint field if non-nil, zero value otherwise.

### GetKeyHintOk

`func (o *ApiKeyResponse) GetKeyHintOk() (*string, bool)`

GetKeyHintOk returns a tuple with the KeyHint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyHint

`func (o *ApiKeyResponse) SetKeyHint(v string)`

SetKeyHint sets KeyHint field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


