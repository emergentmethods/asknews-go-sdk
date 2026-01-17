# SourceReportItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BsonDate** | **time.Time** |  | 
**NBucket** | **int32** |  | 
**NSelected** | **int32** |  | 
**BucketCounts** | **map[string]int32** |  | 
**SelectedCounts** | **map[string]int32** |  | 
**BucketPct** | **map[string]float32** |  | 
**SelectedPct** | **map[string]float32** |  | 

## Methods

### NewSourceReportItem

`func NewSourceReportItem(bsonDate time.Time, nBucket int32, nSelected int32, bucketCounts map[string]int32, selectedCounts map[string]int32, bucketPct map[string]float32, selectedPct map[string]float32, ) *SourceReportItem`

NewSourceReportItem instantiates a new SourceReportItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSourceReportItemWithDefaults

`func NewSourceReportItemWithDefaults() *SourceReportItem`

NewSourceReportItemWithDefaults instantiates a new SourceReportItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBsonDate

`func (o *SourceReportItem) GetBsonDate() time.Time`

GetBsonDate returns the BsonDate field if non-nil, zero value otherwise.

### GetBsonDateOk

`func (o *SourceReportItem) GetBsonDateOk() (*time.Time, bool)`

GetBsonDateOk returns a tuple with the BsonDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBsonDate

`func (o *SourceReportItem) SetBsonDate(v time.Time)`

SetBsonDate sets BsonDate field to given value.


### GetNBucket

`func (o *SourceReportItem) GetNBucket() int32`

GetNBucket returns the NBucket field if non-nil, zero value otherwise.

### GetNBucketOk

`func (o *SourceReportItem) GetNBucketOk() (*int32, bool)`

GetNBucketOk returns a tuple with the NBucket field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNBucket

`func (o *SourceReportItem) SetNBucket(v int32)`

SetNBucket sets NBucket field to given value.


### GetNSelected

`func (o *SourceReportItem) GetNSelected() int32`

GetNSelected returns the NSelected field if non-nil, zero value otherwise.

### GetNSelectedOk

`func (o *SourceReportItem) GetNSelectedOk() (*int32, bool)`

GetNSelectedOk returns a tuple with the NSelected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNSelected

`func (o *SourceReportItem) SetNSelected(v int32)`

SetNSelected sets NSelected field to given value.


### GetBucketCounts

`func (o *SourceReportItem) GetBucketCounts() map[string]int32`

GetBucketCounts returns the BucketCounts field if non-nil, zero value otherwise.

### GetBucketCountsOk

`func (o *SourceReportItem) GetBucketCountsOk() (*map[string]int32, bool)`

GetBucketCountsOk returns a tuple with the BucketCounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBucketCounts

`func (o *SourceReportItem) SetBucketCounts(v map[string]int32)`

SetBucketCounts sets BucketCounts field to given value.


### GetSelectedCounts

`func (o *SourceReportItem) GetSelectedCounts() map[string]int32`

GetSelectedCounts returns the SelectedCounts field if non-nil, zero value otherwise.

### GetSelectedCountsOk

`func (o *SourceReportItem) GetSelectedCountsOk() (*map[string]int32, bool)`

GetSelectedCountsOk returns a tuple with the SelectedCounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelectedCounts

`func (o *SourceReportItem) SetSelectedCounts(v map[string]int32)`

SetSelectedCounts sets SelectedCounts field to given value.


### GetBucketPct

`func (o *SourceReportItem) GetBucketPct() map[string]float32`

GetBucketPct returns the BucketPct field if non-nil, zero value otherwise.

### GetBucketPctOk

`func (o *SourceReportItem) GetBucketPctOk() (*map[string]float32, bool)`

GetBucketPctOk returns a tuple with the BucketPct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBucketPct

`func (o *SourceReportItem) SetBucketPct(v map[string]float32)`

SetBucketPct sets BucketPct field to given value.


### GetSelectedPct

`func (o *SourceReportItem) GetSelectedPct() map[string]float32`

GetSelectedPct returns the SelectedPct field if non-nil, zero value otherwise.

### GetSelectedPctOk

`func (o *SourceReportItem) GetSelectedPctOk() (*map[string]float32, bool)`

GetSelectedPctOk returns a tuple with the SelectedPct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSelectedPct

`func (o *SourceReportItem) SetSelectedPct(v map[string]float32)`

SetSelectedPct sets SelectedPct field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


