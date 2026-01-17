# WebSearchResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AsString** | **string** |  | 
**AsDicts** | [**[]WebSearchResult**](WebSearchResult.md) |  | 
**Offset** | Pointer to [**NullableOffset3**](Offset3.md) |  | [optional] 

## Methods

### NewWebSearchResponse

`func NewWebSearchResponse(asString string, asDicts []WebSearchResult, ) *WebSearchResponse`

NewWebSearchResponse instantiates a new WebSearchResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebSearchResponseWithDefaults

`func NewWebSearchResponseWithDefaults() *WebSearchResponse`

NewWebSearchResponseWithDefaults instantiates a new WebSearchResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAsString

`func (o *WebSearchResponse) GetAsString() string`

GetAsString returns the AsString field if non-nil, zero value otherwise.

### GetAsStringOk

`func (o *WebSearchResponse) GetAsStringOk() (*string, bool)`

GetAsStringOk returns a tuple with the AsString field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsString

`func (o *WebSearchResponse) SetAsString(v string)`

SetAsString sets AsString field to given value.


### GetAsDicts

`func (o *WebSearchResponse) GetAsDicts() []WebSearchResult`

GetAsDicts returns the AsDicts field if non-nil, zero value otherwise.

### GetAsDictsOk

`func (o *WebSearchResponse) GetAsDictsOk() (*[]WebSearchResult, bool)`

GetAsDictsOk returns a tuple with the AsDicts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsDicts

`func (o *WebSearchResponse) SetAsDicts(v []WebSearchResult)`

SetAsDicts sets AsDicts field to given value.


### GetOffset

`func (o *WebSearchResponse) GetOffset() Offset3`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *WebSearchResponse) GetOffsetOk() (*Offset3, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *WebSearchResponse) SetOffset(v Offset3)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *WebSearchResponse) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### SetOffsetNil

`func (o *WebSearchResponse) SetOffsetNil(b bool)`

 SetOffsetNil sets the value for Offset to be an explicit nil

### UnsetOffset
`func (o *WebSearchResponse) UnsetOffset()`

UnsetOffset ensures that no value is present for Offset, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


