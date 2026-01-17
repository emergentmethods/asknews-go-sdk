# TopNDomainsByHitsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]TopNDomainsByHitsItem**](TopNDomainsByHitsItem.md) |  | 
**TotalCount** | **int32** |  | 

## Methods

### NewTopNDomainsByHitsResponse

`func NewTopNDomainsByHitsResponse(data []TopNDomainsByHitsItem, totalCount int32, ) *TopNDomainsByHitsResponse`

NewTopNDomainsByHitsResponse instantiates a new TopNDomainsByHitsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTopNDomainsByHitsResponseWithDefaults

`func NewTopNDomainsByHitsResponseWithDefaults() *TopNDomainsByHitsResponse`

NewTopNDomainsByHitsResponseWithDefaults instantiates a new TopNDomainsByHitsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *TopNDomainsByHitsResponse) GetData() []TopNDomainsByHitsItem`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *TopNDomainsByHitsResponse) GetDataOk() (*[]TopNDomainsByHitsItem, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *TopNDomainsByHitsResponse) SetData(v []TopNDomainsByHitsItem)`

SetData sets Data field to given value.


### GetTotalCount

`func (o *TopNDomainsByHitsResponse) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *TopNDomainsByHitsResponse) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *TopNDomainsByHitsResponse) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


