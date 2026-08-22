# DomainMetricsDayItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Day** | **string** |  | 
**Surfaces** | **int32** |  | 
**Citations** | **int32** |  | 
**FullText** | **int32** |  | 
**Grounded** | Pointer to **int32** |  | [optional] [default to 0]

## Methods

### NewDomainMetricsDayItem

`func NewDomainMetricsDayItem(day string, surfaces int32, citations int32, fullText int32, ) *DomainMetricsDayItem`

NewDomainMetricsDayItem instantiates a new DomainMetricsDayItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainMetricsDayItemWithDefaults

`func NewDomainMetricsDayItemWithDefaults() *DomainMetricsDayItem`

NewDomainMetricsDayItemWithDefaults instantiates a new DomainMetricsDayItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDay

`func (o *DomainMetricsDayItem) GetDay() string`

GetDay returns the Day field if non-nil, zero value otherwise.

### GetDayOk

`func (o *DomainMetricsDayItem) GetDayOk() (*string, bool)`

GetDayOk returns a tuple with the Day field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDay

`func (o *DomainMetricsDayItem) SetDay(v string)`

SetDay sets Day field to given value.


### GetSurfaces

`func (o *DomainMetricsDayItem) GetSurfaces() int32`

GetSurfaces returns the Surfaces field if non-nil, zero value otherwise.

### GetSurfacesOk

`func (o *DomainMetricsDayItem) GetSurfacesOk() (*int32, bool)`

GetSurfacesOk returns a tuple with the Surfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSurfaces

`func (o *DomainMetricsDayItem) SetSurfaces(v int32)`

SetSurfaces sets Surfaces field to given value.


### GetCitations

`func (o *DomainMetricsDayItem) GetCitations() int32`

GetCitations returns the Citations field if non-nil, zero value otherwise.

### GetCitationsOk

`func (o *DomainMetricsDayItem) GetCitationsOk() (*int32, bool)`

GetCitationsOk returns a tuple with the Citations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitations

`func (o *DomainMetricsDayItem) SetCitations(v int32)`

SetCitations sets Citations field to given value.


### GetFullText

`func (o *DomainMetricsDayItem) GetFullText() int32`

GetFullText returns the FullText field if non-nil, zero value otherwise.

### GetFullTextOk

`func (o *DomainMetricsDayItem) GetFullTextOk() (*int32, bool)`

GetFullTextOk returns a tuple with the FullText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFullText

`func (o *DomainMetricsDayItem) SetFullText(v int32)`

SetFullText sets FullText field to given value.


### GetGrounded

`func (o *DomainMetricsDayItem) GetGrounded() int32`

GetGrounded returns the Grounded field if non-nil, zero value otherwise.

### GetGroundedOk

`func (o *DomainMetricsDayItem) GetGroundedOk() (*int32, bool)`

GetGroundedOk returns a tuple with the Grounded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrounded

`func (o *DomainMetricsDayItem) SetGrounded(v int32)`

SetGrounded sets Grounded field to given value.

### HasGrounded

`func (o *DomainMetricsDayItem) HasGrounded() bool`

HasGrounded returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


