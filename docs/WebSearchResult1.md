# WebSearchResult1

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

### NewWebSearchResult1

`func NewWebSearchResult1(title string, url string, source string, published string, keyPoints []*string, ) *WebSearchResult1`

NewWebSearchResult1 instantiates a new WebSearchResult1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebSearchResult1WithDefaults

`func NewWebSearchResult1WithDefaults() *WebSearchResult1`

NewWebSearchResult1WithDefaults instantiates a new WebSearchResult1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitle

`func (o *WebSearchResult1) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *WebSearchResult1) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *WebSearchResult1) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetUrl

`func (o *WebSearchResult1) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *WebSearchResult1) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *WebSearchResult1) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetSource

`func (o *WebSearchResult1) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *WebSearchResult1) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *WebSearchResult1) SetSource(v string)`

SetSource sets Source field to given value.


### GetPublished

`func (o *WebSearchResult1) GetPublished() string`

GetPublished returns the Published field if non-nil, zero value otherwise.

### GetPublishedOk

`func (o *WebSearchResult1) GetPublishedOk() (*string, bool)`

GetPublishedOk returns a tuple with the Published field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublished

`func (o *WebSearchResult1) SetPublished(v string)`

SetPublished sets Published field to given value.


### GetKeyPoints

`func (o *WebSearchResult1) GetKeyPoints() []*string`

GetKeyPoints returns the KeyPoints field if non-nil, zero value otherwise.

### GetKeyPointsOk

`func (o *WebSearchResult1) GetKeyPointsOk() (*[]*string, bool)`

GetKeyPointsOk returns a tuple with the KeyPoints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyPoints

`func (o *WebSearchResult1) SetKeyPoints(v []*string)`

SetKeyPoints sets KeyPoints field to given value.


### GetRawText

`func (o *WebSearchResult1) GetRawText() string`

GetRawText returns the RawText field if non-nil, zero value otherwise.

### GetRawTextOk

`func (o *WebSearchResult1) GetRawTextOk() (*string, bool)`

GetRawTextOk returns a tuple with the RawText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawText

`func (o *WebSearchResult1) SetRawText(v string)`

SetRawText sets RawText field to given value.

### HasRawText

`func (o *WebSearchResult1) HasRawText() bool`

HasRawText returns a boolean if a field has been set.

### GetAsStringKey

`func (o *WebSearchResult1) GetAsStringKey() string`

GetAsStringKey returns the AsStringKey field if non-nil, zero value otherwise.

### GetAsStringKeyOk

`func (o *WebSearchResult1) GetAsStringKeyOk() (*string, bool)`

GetAsStringKeyOk returns a tuple with the AsStringKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsStringKey

`func (o *WebSearchResult1) SetAsStringKey(v string)`

SetAsStringKey sets AsStringKey field to given value.

### HasAsStringKey

`func (o *WebSearchResult1) HasAsStringKey() bool`

HasAsStringKey returns a boolean if a field has been set.

### SetAsStringKeyNil

`func (o *WebSearchResult1) SetAsStringKeyNil(b bool)`

 SetAsStringKeyNil sets the value for AsStringKey to be an explicit nil

### UnsetAsStringKey
`func (o *WebSearchResult1) UnsetAsStringKey()`

UnsetAsStringKey ensures that no value is present for AsStringKey, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


