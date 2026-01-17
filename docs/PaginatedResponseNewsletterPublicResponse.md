# PaginatedResponseNewsletterPublicResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]NewsletterPublicResponse**](NewsletterPublicResponse.md) |  | 
**Count** | **int32** |  | 
**NextPage** | **NullableInt32** |  | 
**PreviousPage** | **NullableInt32** |  | 

## Methods

### NewPaginatedResponseNewsletterPublicResponse

`func NewPaginatedResponseNewsletterPublicResponse(items []NewsletterPublicResponse, count int32, nextPage NullableInt32, previousPage NullableInt32, ) *PaginatedResponseNewsletterPublicResponse`

NewPaginatedResponseNewsletterPublicResponse instantiates a new PaginatedResponseNewsletterPublicResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaginatedResponseNewsletterPublicResponseWithDefaults

`func NewPaginatedResponseNewsletterPublicResponseWithDefaults() *PaginatedResponseNewsletterPublicResponse`

NewPaginatedResponseNewsletterPublicResponseWithDefaults instantiates a new PaginatedResponseNewsletterPublicResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *PaginatedResponseNewsletterPublicResponse) GetItems() []NewsletterPublicResponse`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *PaginatedResponseNewsletterPublicResponse) GetItemsOk() (*[]NewsletterPublicResponse, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *PaginatedResponseNewsletterPublicResponse) SetItems(v []NewsletterPublicResponse)`

SetItems sets Items field to given value.


### GetCount

`func (o *PaginatedResponseNewsletterPublicResponse) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *PaginatedResponseNewsletterPublicResponse) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *PaginatedResponseNewsletterPublicResponse) SetCount(v int32)`

SetCount sets Count field to given value.


### GetNextPage

`func (o *PaginatedResponseNewsletterPublicResponse) GetNextPage() int32`

GetNextPage returns the NextPage field if non-nil, zero value otherwise.

### GetNextPageOk

`func (o *PaginatedResponseNewsletterPublicResponse) GetNextPageOk() (*int32, bool)`

GetNextPageOk returns a tuple with the NextPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPage

`func (o *PaginatedResponseNewsletterPublicResponse) SetNextPage(v int32)`

SetNextPage sets NextPage field to given value.


### SetNextPageNil

`func (o *PaginatedResponseNewsletterPublicResponse) SetNextPageNil(b bool)`

 SetNextPageNil sets the value for NextPage to be an explicit nil

### UnsetNextPage
`func (o *PaginatedResponseNewsletterPublicResponse) UnsetNextPage()`

UnsetNextPage ensures that no value is present for NextPage, not even an explicit nil
### GetPreviousPage

`func (o *PaginatedResponseNewsletterPublicResponse) GetPreviousPage() int32`

GetPreviousPage returns the PreviousPage field if non-nil, zero value otherwise.

### GetPreviousPageOk

`func (o *PaginatedResponseNewsletterPublicResponse) GetPreviousPageOk() (*int32, bool)`

GetPreviousPageOk returns a tuple with the PreviousPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviousPage

`func (o *PaginatedResponseNewsletterPublicResponse) SetPreviousPage(v int32)`

SetPreviousPage sets PreviousPage field to given value.


### SetPreviousPageNil

`func (o *PaginatedResponseNewsletterPublicResponse) SetPreviousPageNil(b bool)`

 SetPreviousPageNil sets the value for PreviousPage to be an explicit nil

### UnsetPreviousPage
`func (o *PaginatedResponseNewsletterPublicResponse) UnsetPreviousPage()`

UnsetPreviousPage ensures that no value is present for PreviousPage, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


