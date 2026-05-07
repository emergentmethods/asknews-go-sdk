# ChartParameters1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ChartType** | **string** | The type of chart to create | 
**Title** | Pointer to **NullableString** |  | [optional] 
**Series** | [**[]SeriesConfig1**](SeriesConfig1.md) | The series configurations for the chart | 

## Methods

### NewChartParameters1

`func NewChartParameters1(chartType string, series []SeriesConfig1, ) *ChartParameters1`

NewChartParameters1 instantiates a new ChartParameters1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChartParameters1WithDefaults

`func NewChartParameters1WithDefaults() *ChartParameters1`

NewChartParameters1WithDefaults instantiates a new ChartParameters1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChartType

`func (o *ChartParameters1) GetChartType() string`

GetChartType returns the ChartType field if non-nil, zero value otherwise.

### GetChartTypeOk

`func (o *ChartParameters1) GetChartTypeOk() (*string, bool)`

GetChartTypeOk returns a tuple with the ChartType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChartType

`func (o *ChartParameters1) SetChartType(v string)`

SetChartType sets ChartType field to given value.


### GetTitle

`func (o *ChartParameters1) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ChartParameters1) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ChartParameters1) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *ChartParameters1) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *ChartParameters1) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *ChartParameters1) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetSeries

`func (o *ChartParameters1) GetSeries() []SeriesConfig1`

GetSeries returns the Series field if non-nil, zero value otherwise.

### GetSeriesOk

`func (o *ChartParameters1) GetSeriesOk() (*[]SeriesConfig1, bool)`

GetSeriesOk returns a tuple with the Series field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeries

`func (o *ChartParameters1) SetSeries(v []SeriesConfig1)`

SetSeries sets Series field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


