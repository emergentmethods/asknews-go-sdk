# CreateAlertRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Query** | Pointer to **NullableString** |  | [optional] 
**Cron** | **string** | The cron schedule for the alert. For example hourly is &#39;0 * * * *&#39;. See https://crontab.run/ for more examples | 
**Model** | **NullableString** |  | 
**ShareLink** | Pointer to **NullableString** |  | [optional] 
**Sources** | [**[]SourcesInner**](SourcesInner.md) |  | 
**Report** | Pointer to [**NullableReportRequest**](ReportRequest.md) |  | [optional] 
**Triggers** | [**[]TriggersInner**](TriggersInner.md) |  | 
**AlwaysTrigger** | Pointer to **bool** | Whether to always trigger the alert. Default is False. This skips the alert check and run triggers immediately | [optional] [default to false]
**Repeat** | Pointer to **bool** | Whether to repeat the alert. Default is True. If False, the alert will be disabled after it triggers once | [optional] [default to true]
**Active** | Pointer to **bool** | Whether the alert is active or not. Default is True. | [optional] [default to true]
**ExpiresAt** | Pointer to **NullableTime** |  | [optional] 
**Title** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewCreateAlertRequest

`func NewCreateAlertRequest(cron string, model NullableString, sources []SourcesInner, triggers []TriggersInner, ) *CreateAlertRequest`

NewCreateAlertRequest instantiates a new CreateAlertRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAlertRequestWithDefaults

`func NewCreateAlertRequestWithDefaults() *CreateAlertRequest`

NewCreateAlertRequestWithDefaults instantiates a new CreateAlertRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuery

`func (o *CreateAlertRequest) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *CreateAlertRequest) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *CreateAlertRequest) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *CreateAlertRequest) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### SetQueryNil

`func (o *CreateAlertRequest) SetQueryNil(b bool)`

 SetQueryNil sets the value for Query to be an explicit nil

### UnsetQuery
`func (o *CreateAlertRequest) UnsetQuery()`

UnsetQuery ensures that no value is present for Query, not even an explicit nil
### GetCron

`func (o *CreateAlertRequest) GetCron() string`

GetCron returns the Cron field if non-nil, zero value otherwise.

### GetCronOk

`func (o *CreateAlertRequest) GetCronOk() (*string, bool)`

GetCronOk returns a tuple with the Cron field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCron

`func (o *CreateAlertRequest) SetCron(v string)`

SetCron sets Cron field to given value.


### GetModel

`func (o *CreateAlertRequest) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *CreateAlertRequest) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *CreateAlertRequest) SetModel(v string)`

SetModel sets Model field to given value.


### SetModelNil

`func (o *CreateAlertRequest) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *CreateAlertRequest) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetShareLink

`func (o *CreateAlertRequest) GetShareLink() string`

GetShareLink returns the ShareLink field if non-nil, zero value otherwise.

### GetShareLinkOk

`func (o *CreateAlertRequest) GetShareLinkOk() (*string, bool)`

GetShareLinkOk returns a tuple with the ShareLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShareLink

`func (o *CreateAlertRequest) SetShareLink(v string)`

SetShareLink sets ShareLink field to given value.

### HasShareLink

`func (o *CreateAlertRequest) HasShareLink() bool`

HasShareLink returns a boolean if a field has been set.

### SetShareLinkNil

`func (o *CreateAlertRequest) SetShareLinkNil(b bool)`

 SetShareLinkNil sets the value for ShareLink to be an explicit nil

### UnsetShareLink
`func (o *CreateAlertRequest) UnsetShareLink()`

UnsetShareLink ensures that no value is present for ShareLink, not even an explicit nil
### GetSources

`func (o *CreateAlertRequest) GetSources() []SourcesInner`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *CreateAlertRequest) GetSourcesOk() (*[]SourcesInner, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *CreateAlertRequest) SetSources(v []SourcesInner)`

SetSources sets Sources field to given value.


### GetReport

`func (o *CreateAlertRequest) GetReport() ReportRequest`

GetReport returns the Report field if non-nil, zero value otherwise.

### GetReportOk

`func (o *CreateAlertRequest) GetReportOk() (*ReportRequest, bool)`

GetReportOk returns a tuple with the Report field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReport

`func (o *CreateAlertRequest) SetReport(v ReportRequest)`

SetReport sets Report field to given value.

### HasReport

`func (o *CreateAlertRequest) HasReport() bool`

HasReport returns a boolean if a field has been set.

### SetReportNil

`func (o *CreateAlertRequest) SetReportNil(b bool)`

 SetReportNil sets the value for Report to be an explicit nil

### UnsetReport
`func (o *CreateAlertRequest) UnsetReport()`

UnsetReport ensures that no value is present for Report, not even an explicit nil
### GetTriggers

`func (o *CreateAlertRequest) GetTriggers() []TriggersInner`

GetTriggers returns the Triggers field if non-nil, zero value otherwise.

### GetTriggersOk

`func (o *CreateAlertRequest) GetTriggersOk() (*[]TriggersInner, bool)`

GetTriggersOk returns a tuple with the Triggers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggers

`func (o *CreateAlertRequest) SetTriggers(v []TriggersInner)`

SetTriggers sets Triggers field to given value.


### GetAlwaysTrigger

`func (o *CreateAlertRequest) GetAlwaysTrigger() bool`

GetAlwaysTrigger returns the AlwaysTrigger field if non-nil, zero value otherwise.

### GetAlwaysTriggerOk

`func (o *CreateAlertRequest) GetAlwaysTriggerOk() (*bool, bool)`

GetAlwaysTriggerOk returns a tuple with the AlwaysTrigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlwaysTrigger

`func (o *CreateAlertRequest) SetAlwaysTrigger(v bool)`

SetAlwaysTrigger sets AlwaysTrigger field to given value.

### HasAlwaysTrigger

`func (o *CreateAlertRequest) HasAlwaysTrigger() bool`

HasAlwaysTrigger returns a boolean if a field has been set.

### GetRepeat

`func (o *CreateAlertRequest) GetRepeat() bool`

GetRepeat returns the Repeat field if non-nil, zero value otherwise.

### GetRepeatOk

`func (o *CreateAlertRequest) GetRepeatOk() (*bool, bool)`

GetRepeatOk returns a tuple with the Repeat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepeat

`func (o *CreateAlertRequest) SetRepeat(v bool)`

SetRepeat sets Repeat field to given value.

### HasRepeat

`func (o *CreateAlertRequest) HasRepeat() bool`

HasRepeat returns a boolean if a field has been set.

### GetActive

`func (o *CreateAlertRequest) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *CreateAlertRequest) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *CreateAlertRequest) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *CreateAlertRequest) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetExpiresAt

`func (o *CreateAlertRequest) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *CreateAlertRequest) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *CreateAlertRequest) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *CreateAlertRequest) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *CreateAlertRequest) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *CreateAlertRequest) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetTitle

`func (o *CreateAlertRequest) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *CreateAlertRequest) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *CreateAlertRequest) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *CreateAlertRequest) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *CreateAlertRequest) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *CreateAlertRequest) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


