# CirrusMetadata

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreateTimestamp** | **time.Time** |  | 
**WikibaseItem** | **string** |  | 
**Version** | **int32** |  | 
**PopularityScore** | **float32** |  | 
**TextBytes** | **int32** |  | 

## Methods

### NewCirrusMetadata

`func NewCirrusMetadata(createTimestamp time.Time, wikibaseItem string, version int32, popularityScore float32, textBytes int32, ) *CirrusMetadata`

NewCirrusMetadata instantiates a new CirrusMetadata object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCirrusMetadataWithDefaults

`func NewCirrusMetadataWithDefaults() *CirrusMetadata`

NewCirrusMetadataWithDefaults instantiates a new CirrusMetadata object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreateTimestamp

`func (o *CirrusMetadata) GetCreateTimestamp() time.Time`

GetCreateTimestamp returns the CreateTimestamp field if non-nil, zero value otherwise.

### GetCreateTimestampOk

`func (o *CirrusMetadata) GetCreateTimestampOk() (*time.Time, bool)`

GetCreateTimestampOk returns a tuple with the CreateTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreateTimestamp

`func (o *CirrusMetadata) SetCreateTimestamp(v time.Time)`

SetCreateTimestamp sets CreateTimestamp field to given value.


### GetWikibaseItem

`func (o *CirrusMetadata) GetWikibaseItem() string`

GetWikibaseItem returns the WikibaseItem field if non-nil, zero value otherwise.

### GetWikibaseItemOk

`func (o *CirrusMetadata) GetWikibaseItemOk() (*string, bool)`

GetWikibaseItemOk returns a tuple with the WikibaseItem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWikibaseItem

`func (o *CirrusMetadata) SetWikibaseItem(v string)`

SetWikibaseItem sets WikibaseItem field to given value.


### GetVersion

`func (o *CirrusMetadata) GetVersion() int32`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *CirrusMetadata) GetVersionOk() (*int32, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *CirrusMetadata) SetVersion(v int32)`

SetVersion sets Version field to given value.


### GetPopularityScore

`func (o *CirrusMetadata) GetPopularityScore() float32`

GetPopularityScore returns the PopularityScore field if non-nil, zero value otherwise.

### GetPopularityScoreOk

`func (o *CirrusMetadata) GetPopularityScoreOk() (*float32, bool)`

GetPopularityScoreOk returns a tuple with the PopularityScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPopularityScore

`func (o *CirrusMetadata) SetPopularityScore(v float32)`

SetPopularityScore sets PopularityScore field to given value.


### GetTextBytes

`func (o *CirrusMetadata) GetTextBytes() int32`

GetTextBytes returns the TextBytes field if non-nil, zero value otherwise.

### GetTextBytesOk

`func (o *CirrusMetadata) GetTextBytesOk() (*int32, bool)`

GetTextBytesOk returns a tuple with the TextBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTextBytes

`func (o *CirrusMetadata) SetTextBytes(v int32)`

SetTextBytes sets TextBytes field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


