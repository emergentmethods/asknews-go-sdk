# IndexCountItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Start** | **time.Time** |  | 
**End** | **time.Time** |  | 
**Count** | **int32** |  | 

## Methods

### NewIndexCountItem

`func NewIndexCountItem(start time.Time, end time.Time, count int32, ) *IndexCountItem`

NewIndexCountItem instantiates a new IndexCountItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIndexCountItemWithDefaults

`func NewIndexCountItemWithDefaults() *IndexCountItem`

NewIndexCountItemWithDefaults instantiates a new IndexCountItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStart

`func (o *IndexCountItem) GetStart() time.Time`

GetStart returns the Start field if non-nil, zero value otherwise.

### GetStartOk

`func (o *IndexCountItem) GetStartOk() (*time.Time, bool)`

GetStartOk returns a tuple with the Start field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStart

`func (o *IndexCountItem) SetStart(v time.Time)`

SetStart sets Start field to given value.


### GetEnd

`func (o *IndexCountItem) GetEnd() time.Time`

GetEnd returns the End field if non-nil, zero value otherwise.

### GetEndOk

`func (o *IndexCountItem) GetEndOk() (*time.Time, bool)`

GetEndOk returns a tuple with the End field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnd

`func (o *IndexCountItem) SetEnd(v time.Time)`

SetEnd sets End field to given value.


### GetCount

`func (o *IndexCountItem) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *IndexCountItem) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *IndexCountItem) SetCount(v int32)`

SetCount sets Count field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


