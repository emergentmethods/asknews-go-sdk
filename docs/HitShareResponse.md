# HitShareResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]HitShareItem**](HitShareItem.md) |  | 
**TotalShare** | **float32** |  | 

## Methods

### NewHitShareResponse

`func NewHitShareResponse(data []HitShareItem, totalShare float32, ) *HitShareResponse`

NewHitShareResponse instantiates a new HitShareResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHitShareResponseWithDefaults

`func NewHitShareResponseWithDefaults() *HitShareResponse`

NewHitShareResponseWithDefaults instantiates a new HitShareResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *HitShareResponse) GetData() []HitShareItem`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *HitShareResponse) GetDataOk() (*[]HitShareItem, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *HitShareResponse) SetData(v []HitShareItem)`

SetData sets Data field to given value.


### GetTotalShare

`func (o *HitShareResponse) GetTotalShare() float32`

GetTotalShare returns the TotalShare field if non-nil, zero value otherwise.

### GetTotalShareOk

`func (o *HitShareResponse) GetTotalShareOk() (*float32, bool)`

GetTotalShareOk returns a tuple with the TotalShare field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalShare

`func (o *HitShareResponse) SetTotalShare(v float32)`

SetTotalShare sets TotalShare field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


