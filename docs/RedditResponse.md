# RedditResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AsDicts** | Pointer to [**[]RedditThread**](RedditThread.md) |  | [optional] 
**AsString** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewRedditResponse

`func NewRedditResponse() *RedditResponse`

NewRedditResponse instantiates a new RedditResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRedditResponseWithDefaults

`func NewRedditResponseWithDefaults() *RedditResponse`

NewRedditResponseWithDefaults instantiates a new RedditResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAsDicts

`func (o *RedditResponse) GetAsDicts() []RedditThread`

GetAsDicts returns the AsDicts field if non-nil, zero value otherwise.

### GetAsDictsOk

`func (o *RedditResponse) GetAsDictsOk() (*[]RedditThread, bool)`

GetAsDictsOk returns a tuple with the AsDicts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsDicts

`func (o *RedditResponse) SetAsDicts(v []RedditThread)`

SetAsDicts sets AsDicts field to given value.

### HasAsDicts

`func (o *RedditResponse) HasAsDicts() bool`

HasAsDicts returns a boolean if a field has been set.

### SetAsDictsNil

`func (o *RedditResponse) SetAsDictsNil(b bool)`

 SetAsDictsNil sets the value for AsDicts to be an explicit nil

### UnsetAsDicts
`func (o *RedditResponse) UnsetAsDicts()`

UnsetAsDicts ensures that no value is present for AsDicts, not even an explicit nil
### GetAsString

`func (o *RedditResponse) GetAsString() string`

GetAsString returns the AsString field if non-nil, zero value otherwise.

### GetAsStringOk

`func (o *RedditResponse) GetAsStringOk() (*string, bool)`

GetAsStringOk returns a tuple with the AsString field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsString

`func (o *RedditResponse) SetAsString(v string)`

SetAsString sets AsString field to given value.

### HasAsString

`func (o *RedditResponse) HasAsString() bool`

HasAsString returns a boolean if a field has been set.

### SetAsStringNil

`func (o *RedditResponse) SetAsStringNil(b bool)`

 SetAsStringNil sets the value for AsString to be an explicit nil

### UnsetAsString
`func (o *RedditResponse) UnsetAsString()`

UnsetAsString ensures that no value is present for AsString, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


