# DomainHitsSurfaceTimeWindowResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]DomainHitsSurfaceDayItem**](DomainHitsSurfaceDayItem.md) |  | 
**TotalHits** | **int32** |  | 
**TotalSurfaced** | **int32** |  | 

## Methods

### NewDomainHitsSurfaceTimeWindowResponse

`func NewDomainHitsSurfaceTimeWindowResponse(data []DomainHitsSurfaceDayItem, totalHits int32, totalSurfaced int32, ) *DomainHitsSurfaceTimeWindowResponse`

NewDomainHitsSurfaceTimeWindowResponse instantiates a new DomainHitsSurfaceTimeWindowResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainHitsSurfaceTimeWindowResponseWithDefaults

`func NewDomainHitsSurfaceTimeWindowResponseWithDefaults() *DomainHitsSurfaceTimeWindowResponse`

NewDomainHitsSurfaceTimeWindowResponseWithDefaults instantiates a new DomainHitsSurfaceTimeWindowResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *DomainHitsSurfaceTimeWindowResponse) GetData() []DomainHitsSurfaceDayItem`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *DomainHitsSurfaceTimeWindowResponse) GetDataOk() (*[]DomainHitsSurfaceDayItem, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *DomainHitsSurfaceTimeWindowResponse) SetData(v []DomainHitsSurfaceDayItem)`

SetData sets Data field to given value.


### GetTotalHits

`func (o *DomainHitsSurfaceTimeWindowResponse) GetTotalHits() int32`

GetTotalHits returns the TotalHits field if non-nil, zero value otherwise.

### GetTotalHitsOk

`func (o *DomainHitsSurfaceTimeWindowResponse) GetTotalHitsOk() (*int32, bool)`

GetTotalHitsOk returns a tuple with the TotalHits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalHits

`func (o *DomainHitsSurfaceTimeWindowResponse) SetTotalHits(v int32)`

SetTotalHits sets TotalHits field to given value.


### GetTotalSurfaced

`func (o *DomainHitsSurfaceTimeWindowResponse) GetTotalSurfaced() int32`

GetTotalSurfaced returns the TotalSurfaced field if non-nil, zero value otherwise.

### GetTotalSurfacedOk

`func (o *DomainHitsSurfaceTimeWindowResponse) GetTotalSurfacedOk() (*int32, bool)`

GetTotalSurfacedOk returns a tuple with the TotalSurfaced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalSurfaced

`func (o *DomainHitsSurfaceTimeWindowResponse) SetTotalSurfaced(v int32)`

SetTotalSurfaced sets TotalSurfaced field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


