# TopNArticlesForDomainResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]TopNArticlesForDomainItem**](TopNArticlesForDomainItem.md) |  | 
**TotalCount** | **int32** |  | 

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



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


