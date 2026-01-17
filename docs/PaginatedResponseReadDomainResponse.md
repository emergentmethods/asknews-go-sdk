# PaginatedResponseReadDomainResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]ReadDomainResponse**](ReadDomainResponse.md) |  | 
**Count** | **int32** |  | 
**NextPage** | **NullableInt32** |  | 
**PreviousPage** | **NullableInt32** |  | 

## Methods

### NewPaginatedResponseReadDomainResponse

`func NewPaginatedResponseReadDomainResponse(items []ReadDomainResponse, count int32, nextPage NullableInt32, previousPage NullableInt32, ) *PaginatedResponseReadDomainResponse`

NewPaginatedResponseReadDomainResponse instantiates a new PaginatedResponseReadDomainResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaginatedResponseReadDomainResponseWithDefaults

`func NewPaginatedResponseReadDomainResponseWithDefaults() *PaginatedResponseReadDomainResponse`

NewPaginatedResponseReadDomainResponseWithDefaults instantiates a new PaginatedResponseReadDomainResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *PaginatedResponseReadDomainResponse) GetItems() []ReadDomainResponse`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *PaginatedResponseReadDomainResponse) GetItemsOk() (*[]ReadDomainResponse, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *PaginatedResponseReadDomainResponse) SetItems(v []ReadDomainResponse)`

SetItems sets Items field to given value.


### GetCount

`func (o *PaginatedResponseReadDomainResponse) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *PaginatedResponseReadDomainResponse) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *PaginatedResponseReadDomainResponse) SetCount(v int32)`

SetCount sets Count field to given value.


### GetNextPage

`func (o *PaginatedResponseReadDomainResponse) GetNextPage() int32`

GetNextPage returns the NextPage field if non-nil, zero value otherwise.

### GetNextPageOk

`func (o *PaginatedResponseReadDomainResponse) GetNextPageOk() (*int32, bool)`

GetNextPageOk returns a tuple with the NextPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPage

`func (o *PaginatedResponseReadDomainResponse) SetNextPage(v int32)`

SetNextPage sets NextPage field to given value.


### SetNextPageNil

`func (o *PaginatedResponseReadDomainResponse) SetNextPageNil(b bool)`

 SetNextPageNil sets the value for NextPage to be an explicit nil

### UnsetNextPage
`func (o *PaginatedResponseReadDomainResponse) UnsetNextPage()`

UnsetNextPage ensures that no value is present for NextPage, not even an explicit nil
### GetPreviousPage

`func (o *PaginatedResponseReadDomainResponse) GetPreviousPage() int32`

GetPreviousPage returns the PreviousPage field if non-nil, zero value otherwise.

### GetPreviousPageOk

`func (o *PaginatedResponseReadDomainResponse) GetPreviousPageOk() (*int32, bool)`

GetPreviousPageOk returns a tuple with the PreviousPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviousPage

`func (o *PaginatedResponseReadDomainResponse) SetPreviousPage(v int32)`

SetPreviousPage sets PreviousPage field to given value.


### SetPreviousPageNil

`func (o *PaginatedResponseReadDomainResponse) SetPreviousPageNil(b bool)`

 SetPreviousPageNil sets the value for PreviousPage to be an explicit nil

### UnsetPreviousPage
`func (o *PaginatedResponseReadDomainResponse) UnsetPreviousPage()`

UnsetPreviousPage ensures that no value is present for PreviousPage, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


