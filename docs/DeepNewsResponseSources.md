# DeepNewsResponseSources

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**News** | Pointer to [**[]SearchResponseDictItem**](SearchResponseDictItem.md) |  | [optional] 
**Web** | Pointer to [**[]WebSearchResult**](WebSearchResult.md) |  | [optional] 

## Methods

### NewDeepNewsResponseSources

`func NewDeepNewsResponseSources() *DeepNewsResponseSources`

NewDeepNewsResponseSources instantiates a new DeepNewsResponseSources object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeepNewsResponseSourcesWithDefaults

`func NewDeepNewsResponseSourcesWithDefaults() *DeepNewsResponseSources`

NewDeepNewsResponseSourcesWithDefaults instantiates a new DeepNewsResponseSources object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNews

`func (o *DeepNewsResponseSources) GetNews() []SearchResponseDictItem`

GetNews returns the News field if non-nil, zero value otherwise.

### GetNewsOk

`func (o *DeepNewsResponseSources) GetNewsOk() (*[]SearchResponseDictItem, bool)`

GetNewsOk returns a tuple with the News field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNews

`func (o *DeepNewsResponseSources) SetNews(v []SearchResponseDictItem)`

SetNews sets News field to given value.

### HasNews

`func (o *DeepNewsResponseSources) HasNews() bool`

HasNews returns a boolean if a field has been set.

### SetNewsNil

`func (o *DeepNewsResponseSources) SetNewsNil(b bool)`

 SetNewsNil sets the value for News to be an explicit nil

### UnsetNews
`func (o *DeepNewsResponseSources) UnsetNews()`

UnsetNews ensures that no value is present for News, not even an explicit nil
### GetWeb

`func (o *DeepNewsResponseSources) GetWeb() []WebSearchResult`

GetWeb returns the Web field if non-nil, zero value otherwise.

### GetWebOk

`func (o *DeepNewsResponseSources) GetWebOk() (*[]WebSearchResult, bool)`

GetWebOk returns a tuple with the Web field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeb

`func (o *DeepNewsResponseSources) SetWeb(v []WebSearchResult)`

SetWeb sets Web field to given value.

### HasWeb

`func (o *DeepNewsResponseSources) HasWeb() bool`

HasWeb returns a boolean if a field has been set.

### SetWebNil

`func (o *DeepNewsResponseSources) SetWebNil(b bool)`

 SetWebNil sets the value for Web to be an explicit nil

### UnsetWeb
`func (o *DeepNewsResponseSources) UnsetWeb()`

UnsetWeb ensures that no value is present for Web, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


