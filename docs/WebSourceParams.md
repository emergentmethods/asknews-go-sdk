# WebSourceParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Queries** | **[]string** | The queries to use for the web search. This is a list of strings. | 
**Domains** | Pointer to **[]string** |  | [optional] 
**Strict** | Pointer to **bool** | If true, the web search will only return results that have a known publication date and are within the lookback period. | [optional] [default to true]
**Lookback** | Pointer to **int32** | The number of hours back to accept for the web search. If not provided, no lookback will be applied. | [optional] [default to 24]

## Methods

### NewWebSourceParams

`func NewWebSourceParams(queries []string, ) *WebSourceParams`

NewWebSourceParams instantiates a new WebSourceParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebSourceParamsWithDefaults

`func NewWebSourceParamsWithDefaults() *WebSourceParams`

NewWebSourceParamsWithDefaults instantiates a new WebSourceParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQueries

`func (o *WebSourceParams) GetQueries() []string`

GetQueries returns the Queries field if non-nil, zero value otherwise.

### GetQueriesOk

`func (o *WebSourceParams) GetQueriesOk() (*[]string, bool)`

GetQueriesOk returns a tuple with the Queries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueries

`func (o *WebSourceParams) SetQueries(v []string)`

SetQueries sets Queries field to given value.


### GetDomains

`func (o *WebSourceParams) GetDomains() []string`

GetDomains returns the Domains field if non-nil, zero value otherwise.

### GetDomainsOk

`func (o *WebSourceParams) GetDomainsOk() (*[]string, bool)`

GetDomainsOk returns a tuple with the Domains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomains

`func (o *WebSourceParams) SetDomains(v []string)`

SetDomains sets Domains field to given value.

### HasDomains

`func (o *WebSourceParams) HasDomains() bool`

HasDomains returns a boolean if a field has been set.

### SetDomainsNil

`func (o *WebSourceParams) SetDomainsNil(b bool)`

 SetDomainsNil sets the value for Domains to be an explicit nil

### UnsetDomains
`func (o *WebSourceParams) UnsetDomains()`

UnsetDomains ensures that no value is present for Domains, not even an explicit nil
### GetStrict

`func (o *WebSourceParams) GetStrict() bool`

GetStrict returns the Strict field if non-nil, zero value otherwise.

### GetStrictOk

`func (o *WebSourceParams) GetStrictOk() (*bool, bool)`

GetStrictOk returns a tuple with the Strict field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStrict

`func (o *WebSourceParams) SetStrict(v bool)`

SetStrict sets Strict field to given value.

### HasStrict

`func (o *WebSourceParams) HasStrict() bool`

HasStrict returns a boolean if a field has been set.

### GetLookback

`func (o *WebSourceParams) GetLookback() int32`

GetLookback returns the Lookback field if non-nil, zero value otherwise.

### GetLookbackOk

`func (o *WebSourceParams) GetLookbackOk() (*int32, bool)`

GetLookbackOk returns a tuple with the Lookback field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLookback

`func (o *WebSourceParams) SetLookback(v int32)`

SetLookback sets Lookback field to given value.

### HasLookback

`func (o *WebSourceParams) HasLookback() bool`

HasLookback returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


