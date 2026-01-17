# PaginatedResponseNewsletterResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]NewsletterResponse**](NewsletterResponse.md) |  | 
**Count** | **int32** |  | 
**NextPage** | **NullableInt32** |  | 
**PreviousPage** | **NullableInt32** |  | 

## Methods

### NewPaginatedResponseNewsletterResponse

`func NewPaginatedResponseNewsletterResponse(items []NewsletterResponse, count int32, nextPage NullableInt32, previousPage NullableInt32, ) *PaginatedResponseNewsletterResponse`

NewPaginatedResponseNewsletterResponse instantiates a new PaginatedResponseNewsletterResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaginatedResponseNewsletterResponseWithDefaults

`func NewPaginatedResponseNewsletterResponseWithDefaults() *PaginatedResponseNewsletterResponse`

NewPaginatedResponseNewsletterResponseWithDefaults instantiates a new PaginatedResponseNewsletterResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *PaginatedResponseNewsletterResponse) GetItems() []NewsletterResponse`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *PaginatedResponseNewsletterResponse) GetItemsOk() (*[]NewsletterResponse, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *PaginatedResponseNewsletterResponse) SetItems(v []NewsletterResponse)`

SetItems sets Items field to given value.


### GetCount

`func (o *PaginatedResponseNewsletterResponse) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *PaginatedResponseNewsletterResponse) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *PaginatedResponseNewsletterResponse) SetCount(v int32)`

SetCount sets Count field to given value.


### GetNextPage

`func (o *PaginatedResponseNewsletterResponse) GetNextPage() int32`

GetNextPage returns the NextPage field if non-nil, zero value otherwise.

### GetNextPageOk

`func (o *PaginatedResponseNewsletterResponse) GetNextPageOk() (*int32, bool)`

GetNextPageOk returns a tuple with the NextPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPage

`func (o *PaginatedResponseNewsletterResponse) SetNextPage(v int32)`

SetNextPage sets NextPage field to given value.


### SetNextPageNil

`func (o *PaginatedResponseNewsletterResponse) SetNextPageNil(b bool)`

 SetNextPageNil sets the value for NextPage to be an explicit nil

### UnsetNextPage
`func (o *PaginatedResponseNewsletterResponse) UnsetNextPage()`

UnsetNextPage ensures that no value is present for NextPage, not even an explicit nil
### GetPreviousPage

`func (o *PaginatedResponseNewsletterResponse) GetPreviousPage() int32`

GetPreviousPage returns the PreviousPage field if non-nil, zero value otherwise.

### GetPreviousPageOk

`func (o *PaginatedResponseNewsletterResponse) GetPreviousPageOk() (*int32, bool)`

GetPreviousPageOk returns a tuple with the PreviousPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviousPage

`func (o *PaginatedResponseNewsletterResponse) SetPreviousPage(v int32)`

SetPreviousPage sets PreviousPage field to given value.


### SetPreviousPageNil

`func (o *PaginatedResponseNewsletterResponse) SetPreviousPageNil(b bool)`

 SetPreviousPageNil sets the value for PreviousPage to be an explicit nil

### UnsetPreviousPage
`func (o *PaginatedResponseNewsletterResponse) UnsetPreviousPage()`

UnsetPreviousPage ensures that no value is present for PreviousPage, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


