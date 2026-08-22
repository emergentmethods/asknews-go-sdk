# TopNArticlesForDomainResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]TopNArticlesForDomainItem**](TopNArticlesForDomainItem.md) |  | 
**TotalCount** | **int32** |  | 
**Page** | Pointer to **int32** |  | [optional] [default to 1]
**NextPage** | Pointer to **NullableInt32** |  | [optional] 

## Methods

### NewTopNArticlesForDomainResponse

`func NewTopNArticlesForDomainResponse(data []TopNArticlesForDomainItem, totalCount int32, ) *TopNArticlesForDomainResponse`

NewTopNArticlesForDomainResponse instantiates a new TopNArticlesForDomainResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTopNArticlesForDomainResponseWithDefaults

`func NewTopNArticlesForDomainResponseWithDefaults() *TopNArticlesForDomainResponse`

NewTopNArticlesForDomainResponseWithDefaults instantiates a new TopNArticlesForDomainResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *TopNArticlesForDomainResponse) GetData() []TopNArticlesForDomainItem`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *TopNArticlesForDomainResponse) GetDataOk() (*[]TopNArticlesForDomainItem, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *TopNArticlesForDomainResponse) SetData(v []TopNArticlesForDomainItem)`

SetData sets Data field to given value.


### GetTotalCount

`func (o *TopNArticlesForDomainResponse) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *TopNArticlesForDomainResponse) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *TopNArticlesForDomainResponse) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.


### GetPage

`func (o *TopNArticlesForDomainResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *TopNArticlesForDomainResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *TopNArticlesForDomainResponse) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *TopNArticlesForDomainResponse) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetNextPage

`func (o *TopNArticlesForDomainResponse) GetNextPage() int32`

GetNextPage returns the NextPage field if non-nil, zero value otherwise.

### GetNextPageOk

`func (o *TopNArticlesForDomainResponse) GetNextPageOk() (*int32, bool)`

GetNextPageOk returns a tuple with the NextPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPage

`func (o *TopNArticlesForDomainResponse) SetNextPage(v int32)`

SetNextPage sets NextPage field to given value.

### HasNextPage

`func (o *TopNArticlesForDomainResponse) HasNextPage() bool`

HasNextPage returns a boolean if a field has been set.

### SetNextPageNil

`func (o *TopNArticlesForDomainResponse) SetNextPageNil(b bool)`

 SetNextPageNil sets the value for NextPage to be an explicit nil

### UnsetNextPage
`func (o *TopNArticlesForDomainResponse) UnsetNextPage()`

UnsetNextPage ensures that no value is present for NextPage, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


