# WebSearchResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Title** | **string** |  | 
**Url** | **string** |  | 
**Source** | **string** |  | 
**Published** | **string** |  | 
**KeyPoints** | **[]string** |  | 
**RawText** | Pointer to **string** |  | [optional] [default to ""]
**AsStringKey** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewWebSearchResult

`func NewWebSearchResult(title string, url string, source string, published string, keyPoints []string, ) *WebSearchResult`

NewWebSearchResult instantiates a new WebSearchResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebSearchResultWithDefaults

`func NewWebSearchResultWithDefaults() *WebSearchResult`

NewWebSearchResultWithDefaults instantiates a new WebSearchResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitle

`func (o *WebSearchResult) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *WebSearchResult) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *WebSearchResult) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetUrl

`func (o *WebSearchResult) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *WebSearchResult) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *WebSearchResult) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetSource

`func (o *WebSearchResult) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *WebSearchResult) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *WebSearchResult) SetSource(v string)`

SetSource sets Source field to given value.


### GetPublished

`func (o *WebSearchResult) GetPublished() string`

GetPublished returns the Published field if non-nil, zero value otherwise.

### GetPublishedOk

`func (o *WebSearchResult) GetPublishedOk() (*string, bool)`

GetPublishedOk returns a tuple with the Published field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublished

`func (o *WebSearchResult) SetPublished(v string)`

SetPublished sets Published field to given value.


### GetKeyPoints

`func (o *WebSearchResult) GetKeyPoints() []string`

GetKeyPoints returns the KeyPoints field if non-nil, zero value otherwise.

### GetKeyPointsOk

`func (o *WebSearchResult) GetKeyPointsOk() (*[]string, bool)`

GetKeyPointsOk returns a tuple with the KeyPoints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyPoints

`func (o *WebSearchResult) SetKeyPoints(v []string)`

SetKeyPoints sets KeyPoints field to given value.


### GetRawText

`func (o *WebSearchResult) GetRawText() string`

GetRawText returns the RawText field if non-nil, zero value otherwise.

### GetRawTextOk

`func (o *WebSearchResult) GetRawTextOk() (*string, bool)`

GetRawTextOk returns a tuple with the RawText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawText

`func (o *WebSearchResult) SetRawText(v string)`

SetRawText sets RawText field to given value.

### HasRawText

`func (o *WebSearchResult) HasRawText() bool`

HasRawText returns a boolean if a field has been set.

### GetAsStringKey

`func (o *WebSearchResult) GetAsStringKey() string`

GetAsStringKey returns the AsStringKey field if non-nil, zero value otherwise.

### GetAsStringKeyOk

`func (o *WebSearchResult) GetAsStringKeyOk() (*string, bool)`

GetAsStringKeyOk returns a tuple with the AsStringKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsStringKey

`func (o *WebSearchResult) SetAsStringKey(v string)`

SetAsStringKey sets AsStringKey field to given value.

### HasAsStringKey

`func (o *WebSearchResult) HasAsStringKey() bool`

HasAsStringKey returns a boolean if a field has been set.

### SetAsStringKeyNil

`func (o *WebSearchResult) SetAsStringKeyNil(b bool)`

 SetAsStringKeyNil sets the value for AsStringKey to be an explicit nil

### UnsetAsStringKey
`func (o *WebSearchResult) UnsetAsStringKey()`

UnsetAsStringKey ensures that no value is present for AsStringKey, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


