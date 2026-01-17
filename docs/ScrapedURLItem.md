# ScrapedURLItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** |  | 
**Data** | Pointer to [**NullableScrapeDataItem**](ScrapeDataItem.md) |  | [optional] 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 
**Enrichments** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewScrapedURLItem

`func NewScrapedURLItem(url string, ) *ScrapedURLItem`

NewScrapedURLItem instantiates a new ScrapedURLItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewScrapedURLItemWithDefaults

`func NewScrapedURLItemWithDefaults() *ScrapedURLItem`

NewScrapedURLItemWithDefaults instantiates a new ScrapedURLItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *ScrapedURLItem) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ScrapedURLItem) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ScrapedURLItem) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetData

`func (o *ScrapedURLItem) GetData() ScrapeDataItem`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ScrapedURLItem) GetDataOk() (*ScrapeDataItem, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ScrapedURLItem) SetData(v ScrapeDataItem)`

SetData sets Data field to given value.

### HasData

`func (o *ScrapedURLItem) HasData() bool`

HasData returns a boolean if a field has been set.

### SetDataNil

`func (o *ScrapedURLItem) SetDataNil(b bool)`

 SetDataNil sets the value for Data to be an explicit nil

### UnsetData
`func (o *ScrapedURLItem) UnsetData()`

UnsetData ensures that no value is present for Data, not even an explicit nil
### GetMetadata

`func (o *ScrapedURLItem) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ScrapedURLItem) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ScrapedURLItem) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *ScrapedURLItem) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *ScrapedURLItem) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *ScrapedURLItem) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetEnrichments

`func (o *ScrapedURLItem) GetEnrichments() map[string]interface{}`

GetEnrichments returns the Enrichments field if non-nil, zero value otherwise.

### GetEnrichmentsOk

`func (o *ScrapedURLItem) GetEnrichmentsOk() (*map[string]interface{}, bool)`

GetEnrichmentsOk returns a tuple with the Enrichments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnrichments

`func (o *ScrapedURLItem) SetEnrichments(v map[string]interface{})`

SetEnrichments sets Enrichments field to given value.

### HasEnrichments

`func (o *ScrapedURLItem) HasEnrichments() bool`

HasEnrichments returns a boolean if a field has been set.

### SetEnrichmentsNil

`func (o *ScrapedURLItem) SetEnrichmentsNil(b bool)`

 SetEnrichmentsNil sets the value for Enrichments to be an explicit nil

### UnsetEnrichments
`func (o *ScrapedURLItem) UnsetEnrichments()`

UnsetEnrichments ensures that no value is present for Enrichments, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


