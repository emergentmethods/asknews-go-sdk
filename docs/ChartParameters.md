# ChartParameters

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ChartType** | **string** | The type of chart to create | 
**Title** | Pointer to **NullableString** |  | [optional] 
**Series** | [**[]SeriesConfig**](SeriesConfig.md) | The series configurations for the chart | 

## Methods

### NewChartParameters

`func NewChartParameters(chartType string, series []SeriesConfig, ) *ChartParameters`

NewChartParameters instantiates a new ChartParameters object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChartParametersWithDefaults

`func NewChartParametersWithDefaults() *ChartParameters`

NewChartParametersWithDefaults instantiates a new ChartParameters object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChartType

`func (o *ChartParameters) GetChartType() string`

GetChartType returns the ChartType field if non-nil, zero value otherwise.

### GetChartTypeOk

`func (o *ChartParameters) GetChartTypeOk() (*string, bool)`

GetChartTypeOk returns a tuple with the ChartType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChartType

`func (o *ChartParameters) SetChartType(v string)`

SetChartType sets ChartType field to given value.


### GetTitle

`func (o *ChartParameters) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ChartParameters) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ChartParameters) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *ChartParameters) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *ChartParameters) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *ChartParameters) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetSeries

`func (o *ChartParameters) GetSeries() []SeriesConfig`

GetSeries returns the Series field if non-nil, zero value otherwise.

### GetSeriesOk

`func (o *ChartParameters) GetSeriesOk() (*[]SeriesConfig, bool)`

GetSeriesOk returns a tuple with the Series field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeries

`func (o *ChartParameters) SetSeries(v []SeriesConfig)`

SetSeries sets Series field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


