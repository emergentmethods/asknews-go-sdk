# FinanceResponseTimeSeriesData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Datetime** | **time.Time** |  | 
**Value** | [**Value**](Value.md) |  | 

## Methods

### NewFinanceResponseTimeSeriesData

`func NewFinanceResponseTimeSeriesData(datetime time.Time, value Value, ) *FinanceResponseTimeSeriesData`

NewFinanceResponseTimeSeriesData instantiates a new FinanceResponseTimeSeriesData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFinanceResponseTimeSeriesDataWithDefaults

`func NewFinanceResponseTimeSeriesDataWithDefaults() *FinanceResponseTimeSeriesData`

NewFinanceResponseTimeSeriesDataWithDefaults instantiates a new FinanceResponseTimeSeriesData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDatetime

`func (o *FinanceResponseTimeSeriesData) GetDatetime() time.Time`

GetDatetime returns the Datetime field if non-nil, zero value otherwise.

### GetDatetimeOk

`func (o *FinanceResponseTimeSeriesData) GetDatetimeOk() (*time.Time, bool)`

GetDatetimeOk returns a tuple with the Datetime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatetime

`func (o *FinanceResponseTimeSeriesData) SetDatetime(v time.Time)`

SetDatetime sets Datetime field to given value.


### GetValue

`func (o *FinanceResponseTimeSeriesData) GetValue() Value`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *FinanceResponseTimeSeriesData) GetValueOk() (*Value, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *FinanceResponseTimeSeriesData) SetValue(v Value)`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


