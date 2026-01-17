# WikiResponseDictItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Content** | **string** |  | 
**Title** | **string** |  | 
**Url** | **string** |  | 
**Categories** | **[]string** |  | 
**Timestamp** | **time.Time** |  | 
**CirrusMetadata** | Pointer to [**NullableCirrusMetadata**](CirrusMetadata.md) |  | [optional] 
**PointId** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewWikiResponseDictItem

`func NewWikiResponseDictItem(content string, title string, url string, categories []string, timestamp time.Time, ) *WikiResponseDictItem`

NewWikiResponseDictItem instantiates a new WikiResponseDictItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWikiResponseDictItemWithDefaults

`func NewWikiResponseDictItemWithDefaults() *WikiResponseDictItem`

NewWikiResponseDictItemWithDefaults instantiates a new WikiResponseDictItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContent

`func (o *WikiResponseDictItem) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *WikiResponseDictItem) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *WikiResponseDictItem) SetContent(v string)`

SetContent sets Content field to given value.


### GetTitle

`func (o *WikiResponseDictItem) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *WikiResponseDictItem) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *WikiResponseDictItem) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetUrl

`func (o *WikiResponseDictItem) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *WikiResponseDictItem) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *WikiResponseDictItem) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetCategories

`func (o *WikiResponseDictItem) GetCategories() []string`

GetCategories returns the Categories field if non-nil, zero value otherwise.

### GetCategoriesOk

`func (o *WikiResponseDictItem) GetCategoriesOk() (*[]string, bool)`

GetCategoriesOk returns a tuple with the Categories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategories

`func (o *WikiResponseDictItem) SetCategories(v []string)`

SetCategories sets Categories field to given value.


### GetTimestamp

`func (o *WikiResponseDictItem) GetTimestamp() time.Time`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *WikiResponseDictItem) GetTimestampOk() (*time.Time, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *WikiResponseDictItem) SetTimestamp(v time.Time)`

SetTimestamp sets Timestamp field to given value.


### GetCirrusMetadata

`func (o *WikiResponseDictItem) GetCirrusMetadata() CirrusMetadata`

GetCirrusMetadata returns the CirrusMetadata field if non-nil, zero value otherwise.

### GetCirrusMetadataOk

`func (o *WikiResponseDictItem) GetCirrusMetadataOk() (*CirrusMetadata, bool)`

GetCirrusMetadataOk returns a tuple with the CirrusMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCirrusMetadata

`func (o *WikiResponseDictItem) SetCirrusMetadata(v CirrusMetadata)`

SetCirrusMetadata sets CirrusMetadata field to given value.

### HasCirrusMetadata

`func (o *WikiResponseDictItem) HasCirrusMetadata() bool`

HasCirrusMetadata returns a boolean if a field has been set.

### SetCirrusMetadataNil

`func (o *WikiResponseDictItem) SetCirrusMetadataNil(b bool)`

 SetCirrusMetadataNil sets the value for CirrusMetadata to be an explicit nil

### UnsetCirrusMetadata
`func (o *WikiResponseDictItem) UnsetCirrusMetadata()`

UnsetCirrusMetadata ensures that no value is present for CirrusMetadata, not even an explicit nil
### GetPointId

`func (o *WikiResponseDictItem) GetPointId() string`

GetPointId returns the PointId field if non-nil, zero value otherwise.

### GetPointIdOk

`func (o *WikiResponseDictItem) GetPointIdOk() (*string, bool)`

GetPointIdOk returns a tuple with the PointId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPointId

`func (o *WikiResponseDictItem) SetPointId(v string)`

SetPointId sets PointId field to given value.

### HasPointId

`func (o *WikiResponseDictItem) HasPointId() bool`

HasPointId returns a boolean if a field has been set.

### SetPointIdNil

`func (o *WikiResponseDictItem) SetPointIdNil(b bool)`

 SetPointIdNil sets the value for PointId to be an explicit nil

### UnsetPointId
`func (o *WikiResponseDictItem) UnsetPointId()`

UnsetPointId ensures that no value is present for PointId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


