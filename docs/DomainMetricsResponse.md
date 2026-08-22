# DomainMetricsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Surfaces** | **int32** |  | 
**Citations** | **int32** |  | 
**FullText** | **int32** |  | 
**Grounded** | Pointer to **int32** |  | [optional] [default to 0]

## Methods

### NewDomainMetricsResponse

`func NewDomainMetricsResponse(surfaces int32, citations int32, fullText int32, ) *DomainMetricsResponse`

NewDomainMetricsResponse instantiates a new DomainMetricsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainMetricsResponseWithDefaults

`func NewDomainMetricsResponseWithDefaults() *DomainMetricsResponse`

NewDomainMetricsResponseWithDefaults instantiates a new DomainMetricsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSurfaces

`func (o *DomainMetricsResponse) GetSurfaces() int32`

GetSurfaces returns the Surfaces field if non-nil, zero value otherwise.

### GetSurfacesOk

`func (o *DomainMetricsResponse) GetSurfacesOk() (*int32, bool)`

GetSurfacesOk returns a tuple with the Surfaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSurfaces

`func (o *DomainMetricsResponse) SetSurfaces(v int32)`

SetSurfaces sets Surfaces field to given value.


### GetCitations

`func (o *DomainMetricsResponse) GetCitations() int32`

GetCitations returns the Citations field if non-nil, zero value otherwise.

### GetCitationsOk

`func (o *DomainMetricsResponse) GetCitationsOk() (*int32, bool)`

GetCitationsOk returns a tuple with the Citations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitations

`func (o *DomainMetricsResponse) SetCitations(v int32)`

SetCitations sets Citations field to given value.


### GetFullText

`func (o *DomainMetricsResponse) GetFullText() int32`

GetFullText returns the FullText field if non-nil, zero value otherwise.

### GetFullTextOk

`func (o *DomainMetricsResponse) GetFullTextOk() (*int32, bool)`

GetFullTextOk returns a tuple with the FullText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFullText

`func (o *DomainMetricsResponse) SetFullText(v int32)`

SetFullText sets FullText field to given value.


### GetGrounded

`func (o *DomainMetricsResponse) GetGrounded() int32`

GetGrounded returns the Grounded field if non-nil, zero value otherwise.

### GetGroundedOk

`func (o *DomainMetricsResponse) GetGroundedOk() (*int32, bool)`

GetGroundedOk returns a tuple with the Grounded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGrounded

`func (o *DomainMetricsResponse) SetGrounded(v int32)`

SetGrounded sets Grounded field to given value.

### HasGrounded

`func (o *DomainMetricsResponse) HasGrounded() bool`

HasGrounded returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


