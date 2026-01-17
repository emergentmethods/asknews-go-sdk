# URLIndexingRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StartTime** | **time.Time** |  | 
**EndTime** | **time.Time** |  | 
**Urls** | [**[]ScrapedURLItem**](ScrapedURLItem.md) |  | 

## Methods

### NewURLIndexingRequest

`func NewURLIndexingRequest(startTime time.Time, endTime time.Time, urls []ScrapedURLItem, ) *URLIndexingRequest`

NewURLIndexingRequest instantiates a new URLIndexingRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewURLIndexingRequestWithDefaults

`func NewURLIndexingRequestWithDefaults() *URLIndexingRequest`

NewURLIndexingRequestWithDefaults instantiates a new URLIndexingRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStartTime

`func (o *URLIndexingRequest) GetStartTime() time.Time`

GetStartTime returns the StartTime field if non-nil, zero value otherwise.

### GetStartTimeOk

`func (o *URLIndexingRequest) GetStartTimeOk() (*time.Time, bool)`

GetStartTimeOk returns a tuple with the StartTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartTime

`func (o *URLIndexingRequest) SetStartTime(v time.Time)`

SetStartTime sets StartTime field to given value.


### GetEndTime

`func (o *URLIndexingRequest) GetEndTime() time.Time`

GetEndTime returns the EndTime field if non-nil, zero value otherwise.

### GetEndTimeOk

`func (o *URLIndexingRequest) GetEndTimeOk() (*time.Time, bool)`

GetEndTimeOk returns a tuple with the EndTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndTime

`func (o *URLIndexingRequest) SetEndTime(v time.Time)`

SetEndTime sets EndTime field to given value.


### GetUrls

`func (o *URLIndexingRequest) GetUrls() []ScrapedURLItem`

GetUrls returns the Urls field if non-nil, zero value otherwise.

### GetUrlsOk

`func (o *URLIndexingRequest) GetUrlsOk() (*[]ScrapedURLItem, bool)`

GetUrlsOk returns a tuple with the Urls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrls

`func (o *URLIndexingRequest) SetUrls(v []ScrapedURLItem)`

SetUrls sets Urls field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


