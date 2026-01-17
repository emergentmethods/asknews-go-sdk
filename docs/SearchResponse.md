# SearchResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AsDicts** | Pointer to [**[]SearchResponseDictItem**](SearchResponseDictItem.md) |  | [optional] 
**AsString** | Pointer to **NullableString** |  | [optional] 
**Offset** | Pointer to [**NullableOffset3**](Offset3.md) |  | [optional] 

## Methods

### NewSearchResponse

`func NewSearchResponse() *SearchResponse`

NewSearchResponse instantiates a new SearchResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchResponseWithDefaults

`func NewSearchResponseWithDefaults() *SearchResponse`

NewSearchResponseWithDefaults instantiates a new SearchResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAsDicts

`func (o *SearchResponse) GetAsDicts() []SearchResponseDictItem`

GetAsDicts returns the AsDicts field if non-nil, zero value otherwise.

### GetAsDictsOk

`func (o *SearchResponse) GetAsDictsOk() (*[]SearchResponseDictItem, bool)`

GetAsDictsOk returns a tuple with the AsDicts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsDicts

`func (o *SearchResponse) SetAsDicts(v []SearchResponseDictItem)`

SetAsDicts sets AsDicts field to given value.

### HasAsDicts

`func (o *SearchResponse) HasAsDicts() bool`

HasAsDicts returns a boolean if a field has been set.

### SetAsDictsNil

`func (o *SearchResponse) SetAsDictsNil(b bool)`

 SetAsDictsNil sets the value for AsDicts to be an explicit nil

### UnsetAsDicts
`func (o *SearchResponse) UnsetAsDicts()`

UnsetAsDicts ensures that no value is present for AsDicts, not even an explicit nil
### GetAsString

`func (o *SearchResponse) GetAsString() string`

GetAsString returns the AsString field if non-nil, zero value otherwise.

### GetAsStringOk

`func (o *SearchResponse) GetAsStringOk() (*string, bool)`

GetAsStringOk returns a tuple with the AsString field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsString

`func (o *SearchResponse) SetAsString(v string)`

SetAsString sets AsString field to given value.

### HasAsString

`func (o *SearchResponse) HasAsString() bool`

HasAsString returns a boolean if a field has been set.

### SetAsStringNil

`func (o *SearchResponse) SetAsStringNil(b bool)`

 SetAsStringNil sets the value for AsString to be an explicit nil

### UnsetAsString
`func (o *SearchResponse) UnsetAsString()`

UnsetAsString ensures that no value is present for AsString, not even an explicit nil
### GetOffset

`func (o *SearchResponse) GetOffset() Offset3`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *SearchResponse) GetOffsetOk() (*Offset3, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *SearchResponse) SetOffset(v Offset3)`

SetOffset sets Offset field to given value.

### HasOffset

`func (o *SearchResponse) HasOffset() bool`

HasOffset returns a boolean if a field has been set.

### SetOffsetNil

`func (o *SearchResponse) SetOffsetNil(b bool)`

 SetOffsetNil sets the value for Offset to be an explicit nil

### UnsetOffset
`func (o *SearchResponse) UnsetOffset()`

UnsetOffset ensures that no value is present for Offset, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


