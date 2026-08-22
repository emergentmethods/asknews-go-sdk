# DomainMetricsTimeWindowResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]DomainMetricsDayItem**](DomainMetricsDayItem.md) |  | 
**TotalSurfaces** | **int32** |  | 
**TotalCitations** | **int32** |  | 
**TotalFullText** | **int32** |  | 
**TotalGrounded** | Pointer to **int32** |  | [optional] [default to 0]

## Methods

### NewDomainMetricsTimeWindowResponse

`func NewDomainMetricsTimeWindowResponse(data []DomainMetricsDayItem, totalSurfaces int32, totalCitations int32, totalFullText int32, ) *DomainMetricsTimeWindowResponse`

NewDomainMetricsTimeWindowResponse instantiates a new DomainMetricsTimeWindowResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainMetricsTimeWindowResponseWithDefaults

`func NewDomainMetricsTimeWindowResponseWithDefaults() *DomainMetricsTimeWindowResponse`

NewDomainMetricsTimeWindowResponseWithDefaults instantiates a new DomainMetricsTimeWindowResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *DomainMetricsTimeWindowResponse) GetData() []DomainMetricsDayItem`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *DomainMetricsTimeWindowResponse) GetDataOk() (*[]DomainMetricsDayItem, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *DomainMetricsTimeWindowResponse) SetData(v []DomainMetricsDayItem)`

SetData sets Data field to given value.


### GetTotalSurfaces

`func (o *DomainMetricsTimeWindowResponse) GetTotalSurfaces() int32`

GetTotalSurfaces returns the TotalSurfaces field if non-nil, zero value otherwise.

### GetTotalSurfacesOk

`func (o *DomainMetricsTimeWindowResponse) GetTotalSurfacesOk() (*int32, bool)`

GetTotalSurfacesOk returns a tuple with the TotalSurfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalSurfaces

`func (o *DomainMetricsTimeWindowResponse) SetTotalSurfaces(v int32)`

SetTotalSurfaces sets TotalSurfaces field to given value.


### GetTotalCitations

`func (o *DomainMetricsTimeWindowResponse) GetTotalCitations() int32`

GetTotalCitations returns the TotalCitations field if non-nil, zero value otherwise.

### GetTotalCitationsOk

`func (o *DomainMetricsTimeWindowResponse) GetTotalCitationsOk() (*int32, bool)`

GetTotalCitationsOk returns a tuple with the TotalCitations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCitations

`func (o *DomainMetricsTimeWindowResponse) SetTotalCitations(v int32)`

SetTotalCitations sets TotalCitations field to given value.


### GetTotalFullText

`func (o *DomainMetricsTimeWindowResponse) GetTotalFullText() int32`

GetTotalFullText returns the TotalFullText field if non-nil, zero value otherwise.

### GetTotalFullTextOk

`func (o *DomainMetricsTimeWindowResponse) GetTotalFullTextOk() (*int32, bool)`

GetTotalFullTextOk returns a tuple with the TotalFullText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalFullText

`func (o *DomainMetricsTimeWindowResponse) SetTotalFullText(v int32)`

SetTotalFullText sets TotalFullText field to given value.


### GetTotalGrounded

`func (o *DomainMetricsTimeWindowResponse) GetTotalGrounded() int32`

GetTotalGrounded returns the TotalGrounded field if non-nil, zero value otherwise.

### GetTotalGroundedOk

`func (o *DomainMetricsTimeWindowResponse) GetTotalGroundedOk() (*int32, bool)`

GetTotalGroundedOk returns a tuple with the TotalGrounded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalGrounded

`func (o *DomainMetricsTimeWindowResponse) SetTotalGrounded(v int32)`

SetTotalGrounded sets TotalGrounded field to given value.

### HasTotalGrounded

`func (o *DomainMetricsTimeWindowResponse) HasTotalGrounded() bool`

HasTotalGrounded returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


