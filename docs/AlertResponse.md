# AlertResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**CreatedAt** | Pointer to **NullableTime** |  | [optional] 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 
**ExpiresAt** | Pointer to **NullableTime** |  | [optional] 
**UserId** | **string** |  | 
**Query** | Pointer to **NullableString** |  | [optional] 
**Cron** | **string** |  | 
**Model** | **NullableString** |  | 
**ShareLink** | Pointer to **NullableString** |  | [optional] 
**Sources** | **[]map[string]interface{}** |  | 
**Report** | Pointer to **map[string]interface{}** |  | [optional] 
**Triggers** | **[]map[string]interface{}** |  | 
**AlwaysTrigger** | Pointer to **bool** |  | [optional] [default to false]
**Repeat** | Pointer to **bool** |  | [optional] [default to true]
**Active** | Pointer to **bool** |  | [optional] [default to true]

## Methods

### NewAlertResponse

`func NewAlertResponse(id string, userId string, cron string, model NullableString, sources []*map[string]interface{}, triggers []*map[string]interface{}, ) *AlertResponse`

NewAlertResponse instantiates a new AlertResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlertResponseWithDefaults

`func NewAlertResponseWithDefaults() *AlertResponse`

NewAlertResponseWithDefaults instantiates a new AlertResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AlertResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AlertResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AlertResponse) SetId(v string)`

SetId sets Id field to given value.


### GetCreatedAt

`func (o *AlertResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AlertResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AlertResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *AlertResponse) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *AlertResponse) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *AlertResponse) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetUpdatedAt

`func (o *AlertResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *AlertResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *AlertResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *AlertResponse) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *AlertResponse) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *AlertResponse) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetExpiresAt

`func (o *AlertResponse) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *AlertResponse) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *AlertResponse) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *AlertResponse) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *AlertResponse) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *AlertResponse) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetUserId

`func (o *AlertResponse) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *AlertResponse) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *AlertResponse) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetQuery

`func (o *AlertResponse) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *AlertResponse) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *AlertResponse) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *AlertResponse) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### SetQueryNil

`func (o *AlertResponse) SetQueryNil(b bool)`

 SetQueryNil sets the value for Query to be an explicit nil

### UnsetQuery
`func (o *AlertResponse) UnsetQuery()`

UnsetQuery ensures that no value is present for Query, not even an explicit nil
### GetCron

`func (o *AlertResponse) GetCron() string`

GetCron returns the Cron field if non-nil, zero value otherwise.

### GetCronOk

`func (o *AlertResponse) GetCronOk() (*string, bool)`

GetCronOk returns a tuple with the Cron field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCron

`func (o *AlertResponse) SetCron(v string)`

SetCron sets Cron field to given value.


### GetModel

`func (o *AlertResponse) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *AlertResponse) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *AlertResponse) SetModel(v string)`

SetModel sets Model field to given value.


### SetModelNil

`func (o *AlertResponse) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *AlertResponse) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetShareLink

`func (o *AlertResponse) GetShareLink() string`

GetShareLink returns the ShareLink field if non-nil, zero value otherwise.

### GetShareLinkOk

`func (o *AlertResponse) GetShareLinkOk() (*string, bool)`

GetShareLinkOk returns a tuple with the ShareLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShareLink

`func (o *AlertResponse) SetShareLink(v string)`

SetShareLink sets ShareLink field to given value.

### HasShareLink

`func (o *AlertResponse) HasShareLink() bool`

HasShareLink returns a boolean if a field has been set.

### SetShareLinkNil

`func (o *AlertResponse) SetShareLinkNil(b bool)`

 SetShareLinkNil sets the value for ShareLink to be an explicit nil

### UnsetShareLink
`func (o *AlertResponse) UnsetShareLink()`

UnsetShareLink ensures that no value is present for ShareLink, not even an explicit nil
### GetSources

`func (o *AlertResponse) GetSources() []*map[string]interface{}`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *AlertResponse) GetSourcesOk() (*[]*map[string]interface{}, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *AlertResponse) SetSources(v []*map[string]interface{})`

SetSources sets Sources field to given value.


### GetReport

`func (o *AlertResponse) GetReport() map[string]interface{}`

GetReport returns the Report field if non-nil, zero value otherwise.

### GetReportOk

`func (o *AlertResponse) GetReportOk() (*map[string]interface{}, bool)`

GetReportOk returns a tuple with the Report field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReport

`func (o *AlertResponse) SetReport(v map[string]interface{})`

SetReport sets Report field to given value.

### HasReport

`func (o *AlertResponse) HasReport() bool`

HasReport returns a boolean if a field has been set.

### SetReportNil

`func (o *AlertResponse) SetReportNil(b bool)`

 SetReportNil sets the value for Report to be an explicit nil

### UnsetReport
`func (o *AlertResponse) UnsetReport()`

UnsetReport ensures that no value is present for Report, not even an explicit nil
### GetTriggers

`func (o *AlertResponse) GetTriggers() []*map[string]interface{}`

GetTriggers returns the Triggers field if non-nil, zero value otherwise.

### GetTriggersOk

`func (o *AlertResponse) GetTriggersOk() (*[]*map[string]interface{}, bool)`

GetTriggersOk returns a tuple with the Triggers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggers

`func (o *AlertResponse) SetTriggers(v []*map[string]interface{})`

SetTriggers sets Triggers field to given value.


### GetAlwaysTrigger

`func (o *AlertResponse) GetAlwaysTrigger() bool`

GetAlwaysTrigger returns the AlwaysTrigger field if non-nil, zero value otherwise.

### GetAlwaysTriggerOk

`func (o *AlertResponse) GetAlwaysTriggerOk() (*bool, bool)`

GetAlwaysTriggerOk returns a tuple with the AlwaysTrigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlwaysTrigger

`func (o *AlertResponse) SetAlwaysTrigger(v bool)`

SetAlwaysTrigger sets AlwaysTrigger field to given value.

### HasAlwaysTrigger

`func (o *AlertResponse) HasAlwaysTrigger() bool`

HasAlwaysTrigger returns a boolean if a field has been set.

### GetRepeat

`func (o *AlertResponse) GetRepeat() bool`

GetRepeat returns the Repeat field if non-nil, zero value otherwise.

### GetRepeatOk

`func (o *AlertResponse) GetRepeatOk() (*bool, bool)`

GetRepeatOk returns a tuple with the Repeat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepeat

`func (o *AlertResponse) SetRepeat(v bool)`

SetRepeat sets Repeat field to given value.

### HasRepeat

`func (o *AlertResponse) HasRepeat() bool`

HasRepeat returns a boolean if a field has been set.

### GetActive

`func (o *AlertResponse) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *AlertResponse) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *AlertResponse) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *AlertResponse) HasActive() bool`

HasActive returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


