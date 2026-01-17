# UpdateAlertRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Query** | Pointer to **NullableString** |  | [optional] 
**Cron** | Pointer to **NullableString** |  | [optional] 
**Model** | Pointer to **NullableString** |  | [optional] 
**ShareLink** | Pointer to **NullableString** |  | [optional] 
**Sources** | Pointer to [**[]SourcesInner**](SourcesInner.md) |  | [optional] 
**Report** | Pointer to [**NullableReportRequest**](ReportRequest.md) |  | [optional] 
**Triggers** | Pointer to [**[]TriggersInner**](TriggersInner.md) |  | [optional] 
**AlwaysTrigger** | Pointer to **NullableBool** |  | [optional] 
**Repeat** | Pointer to **NullableBool** |  | [optional] 
**Active** | Pointer to **NullableBool** |  | [optional] 
**ExpiresAt** | Pointer to **NullableTime** |  | [optional] 
**Title** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewUpdateAlertRequest

`func NewUpdateAlertRequest() *UpdateAlertRequest`

NewUpdateAlertRequest instantiates a new UpdateAlertRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateAlertRequestWithDefaults

`func NewUpdateAlertRequestWithDefaults() *UpdateAlertRequest`

NewUpdateAlertRequestWithDefaults instantiates a new UpdateAlertRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuery

`func (o *UpdateAlertRequest) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *UpdateAlertRequest) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *UpdateAlertRequest) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *UpdateAlertRequest) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### SetQueryNil

`func (o *UpdateAlertRequest) SetQueryNil(b bool)`

 SetQueryNil sets the value for Query to be an explicit nil

### UnsetQuery
`func (o *UpdateAlertRequest) UnsetQuery()`

UnsetQuery ensures that no value is present for Query, not even an explicit nil
### GetCron

`func (o *UpdateAlertRequest) GetCron() string`

GetCron returns the Cron field if non-nil, zero value otherwise.

### GetCronOk

`func (o *UpdateAlertRequest) GetCronOk() (*string, bool)`

GetCronOk returns a tuple with the Cron field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCron

`func (o *UpdateAlertRequest) SetCron(v string)`

SetCron sets Cron field to given value.

### HasCron

`func (o *UpdateAlertRequest) HasCron() bool`

HasCron returns a boolean if a field has been set.

### SetCronNil

`func (o *UpdateAlertRequest) SetCronNil(b bool)`

 SetCronNil sets the value for Cron to be an explicit nil

### UnsetCron
`func (o *UpdateAlertRequest) UnsetCron()`

UnsetCron ensures that no value is present for Cron, not even an explicit nil
### GetModel

`func (o *UpdateAlertRequest) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *UpdateAlertRequest) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *UpdateAlertRequest) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *UpdateAlertRequest) HasModel() bool`

HasModel returns a boolean if a field has been set.

### SetModelNil

`func (o *UpdateAlertRequest) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *UpdateAlertRequest) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetShareLink

`func (o *UpdateAlertRequest) GetShareLink() string`

GetShareLink returns the ShareLink field if non-nil, zero value otherwise.

### GetShareLinkOk

`func (o *UpdateAlertRequest) GetShareLinkOk() (*string, bool)`

GetShareLinkOk returns a tuple with the ShareLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShareLink

`func (o *UpdateAlertRequest) SetShareLink(v string)`

SetShareLink sets ShareLink field to given value.

### HasShareLink

`func (o *UpdateAlertRequest) HasShareLink() bool`

HasShareLink returns a boolean if a field has been set.

### SetShareLinkNil

`func (o *UpdateAlertRequest) SetShareLinkNil(b bool)`

 SetShareLinkNil sets the value for ShareLink to be an explicit nil

### UnsetShareLink
`func (o *UpdateAlertRequest) UnsetShareLink()`

UnsetShareLink ensures that no value is present for ShareLink, not even an explicit nil
### GetSources

`func (o *UpdateAlertRequest) GetSources() []SourcesInner`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *UpdateAlertRequest) GetSourcesOk() (*[]SourcesInner, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *UpdateAlertRequest) SetSources(v []SourcesInner)`

SetSources sets Sources field to given value.

### HasSources

`func (o *UpdateAlertRequest) HasSources() bool`

HasSources returns a boolean if a field has been set.

### GetReport

`func (o *UpdateAlertRequest) GetReport() ReportRequest`

GetReport returns the Report field if non-nil, zero value otherwise.

### GetReportOk

`func (o *UpdateAlertRequest) GetReportOk() (*ReportRequest, bool)`

GetReportOk returns a tuple with the Report field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReport

`func (o *UpdateAlertRequest) SetReport(v ReportRequest)`

SetReport sets Report field to given value.

### HasReport

`func (o *UpdateAlertRequest) HasReport() bool`

HasReport returns a boolean if a field has been set.

### SetReportNil

`func (o *UpdateAlertRequest) SetReportNil(b bool)`

 SetReportNil sets the value for Report to be an explicit nil

### UnsetReport
`func (o *UpdateAlertRequest) UnsetReport()`

UnsetReport ensures that no value is present for Report, not even an explicit nil
### GetTriggers

`func (o *UpdateAlertRequest) GetTriggers() []TriggersInner`

GetTriggers returns the Triggers field if non-nil, zero value otherwise.

### GetTriggersOk

`func (o *UpdateAlertRequest) GetTriggersOk() (*[]TriggersInner, bool)`

GetTriggersOk returns a tuple with the Triggers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggers

`func (o *UpdateAlertRequest) SetTriggers(v []TriggersInner)`

SetTriggers sets Triggers field to given value.

### HasTriggers

`func (o *UpdateAlertRequest) HasTriggers() bool`

HasTriggers returns a boolean if a field has been set.

### GetAlwaysTrigger

`func (o *UpdateAlertRequest) GetAlwaysTrigger() bool`

GetAlwaysTrigger returns the AlwaysTrigger field if non-nil, zero value otherwise.

### GetAlwaysTriggerOk

`func (o *UpdateAlertRequest) GetAlwaysTriggerOk() (*bool, bool)`

GetAlwaysTriggerOk returns a tuple with the AlwaysTrigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlwaysTrigger

`func (o *UpdateAlertRequest) SetAlwaysTrigger(v bool)`

SetAlwaysTrigger sets AlwaysTrigger field to given value.

### HasAlwaysTrigger

`func (o *UpdateAlertRequest) HasAlwaysTrigger() bool`

HasAlwaysTrigger returns a boolean if a field has been set.

### SetAlwaysTriggerNil

`func (o *UpdateAlertRequest) SetAlwaysTriggerNil(b bool)`

 SetAlwaysTriggerNil sets the value for AlwaysTrigger to be an explicit nil

### UnsetAlwaysTrigger
`func (o *UpdateAlertRequest) UnsetAlwaysTrigger()`

UnsetAlwaysTrigger ensures that no value is present for AlwaysTrigger, not even an explicit nil
### GetRepeat

`func (o *UpdateAlertRequest) GetRepeat() bool`

GetRepeat returns the Repeat field if non-nil, zero value otherwise.

### GetRepeatOk

`func (o *UpdateAlertRequest) GetRepeatOk() (*bool, bool)`

GetRepeatOk returns a tuple with the Repeat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepeat

`func (o *UpdateAlertRequest) SetRepeat(v bool)`

SetRepeat sets Repeat field to given value.

### HasRepeat

`func (o *UpdateAlertRequest) HasRepeat() bool`

HasRepeat returns a boolean if a field has been set.

### SetRepeatNil

`func (o *UpdateAlertRequest) SetRepeatNil(b bool)`

 SetRepeatNil sets the value for Repeat to be an explicit nil

### UnsetRepeat
`func (o *UpdateAlertRequest) UnsetRepeat()`

UnsetRepeat ensures that no value is present for Repeat, not even an explicit nil
### GetActive

`func (o *UpdateAlertRequest) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *UpdateAlertRequest) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *UpdateAlertRequest) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *UpdateAlertRequest) HasActive() bool`

HasActive returns a boolean if a field has been set.

### SetActiveNil

`func (o *UpdateAlertRequest) SetActiveNil(b bool)`

 SetActiveNil sets the value for Active to be an explicit nil

### UnsetActive
`func (o *UpdateAlertRequest) UnsetActive()`

UnsetActive ensures that no value is present for Active, not even an explicit nil
### GetExpiresAt

`func (o *UpdateAlertRequest) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *UpdateAlertRequest) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *UpdateAlertRequest) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *UpdateAlertRequest) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *UpdateAlertRequest) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *UpdateAlertRequest) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetTitle

`func (o *UpdateAlertRequest) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *UpdateAlertRequest) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *UpdateAlertRequest) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *UpdateAlertRequest) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### SetTitleNil

`func (o *UpdateAlertRequest) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *UpdateAlertRequest) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


