# TopNArticlesTimeseriesDayItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Day** | **string** |  | 
**Articles** | [**[]TopNArticlesTimeseriesItem**](TopNArticlesTimeseriesItem.md) |  | 
**TotalCount** | **int32** |  | 

## Methods

### NewTopNArticlesTimeseriesDayItem

`func NewTopNArticlesTimeseriesDayItem(day string, articles []TopNArticlesTimeseriesItem, totalCount int32, ) *TopNArticlesTimeseriesDayItem`

NewTopNArticlesTimeseriesDayItem instantiates a new TopNArticlesTimeseriesDayItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTopNArticlesTimeseriesDayItemWithDefaults

`func NewTopNArticlesTimeseriesDayItemWithDefaults() *TopNArticlesTimeseriesDayItem`

NewTopNArticlesTimeseriesDayItemWithDefaults instantiates a new TopNArticlesTimeseriesDayItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDay

`func (o *TopNArticlesTimeseriesDayItem) GetDay() string`

GetDay returns the Day field if non-nil, zero value otherwise.

### GetDayOk

`func (o *TopNArticlesTimeseriesDayItem) GetDayOk() (*string, bool)`

GetDayOk returns a tuple with the Day field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDay

`func (o *TopNArticlesTimeseriesDayItem) SetDay(v string)`

SetDay sets Day field to given value.


### GetArticles

`func (o *TopNArticlesTimeseriesDayItem) GetArticles() []TopNArticlesTimeseriesItem`

GetArticles returns the Articles field if non-nil, zero value otherwise.

### GetArticlesOk

`func (o *TopNArticlesTimeseriesDayItem) GetArticlesOk() (*[]TopNArticlesTimeseriesItem, bool)`

GetArticlesOk returns a tuple with the Articles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArticles

`func (o *TopNArticlesTimeseriesDayItem) SetArticles(v []TopNArticlesTimeseriesItem)`

SetArticles sets Articles field to given value.


### GetTotalCount

`func (o *TopNArticlesTimeseriesDayItem) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *TopNArticlesTimeseriesDayItem) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *TopNArticlesTimeseriesDayItem) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


