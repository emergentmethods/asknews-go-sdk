# AlertLog

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**CreatedAt** | **time.Time** |  | 
**AlertId** | **string** |  | 
**UserId** | **string** |  | 
**Alert** | **bool** |  | 
**Reasoning** | **string** |  | 
**Report** | Pointer to **NullableString** |  | [optional] 
**ReportUrl** | Pointer to **NullableString** |  | [optional] 
**ArticleIds** | **[]string** |  | 
**Webhook** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewAlertLog

`func NewAlertLog(id string, createdAt time.Time, alertId string, userId string, alert bool, reasoning string, articleIds []string, ) *AlertLog`

NewAlertLog instantiates a new AlertLog object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAlertLogWithDefaults

`func NewAlertLogWithDefaults() *AlertLog`

NewAlertLogWithDefaults instantiates a new AlertLog object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AlertLog) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AlertLog) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AlertLog) SetId(v string)`

SetId sets Id field to given value.


### GetCreatedAt

`func (o *AlertLog) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AlertLog) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AlertLog) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetAlertId

`func (o *AlertLog) GetAlertId() string`

GetAlertId returns the AlertId field if non-nil, zero value otherwise.

### GetAlertIdOk

`func (o *AlertLog) GetAlertIdOk() (*string, bool)`

GetAlertIdOk returns a tuple with the AlertId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlertId

`func (o *AlertLog) SetAlertId(v string)`

SetAlertId sets AlertId field to given value.


### GetUserId

`func (o *AlertLog) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *AlertLog) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *AlertLog) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetAlert

`func (o *AlertLog) GetAlert() bool`

GetAlert returns the Alert field if non-nil, zero value otherwise.

### GetAlertOk

`func (o *AlertLog) GetAlertOk() (*bool, bool)`

GetAlertOk returns a tuple with the Alert field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlert

`func (o *AlertLog) SetAlert(v bool)`

SetAlert sets Alert field to given value.


### GetReasoning

`func (o *AlertLog) GetReasoning() string`

GetReasoning returns the Reasoning field if non-nil, zero value otherwise.

### GetReasoningOk

`func (o *AlertLog) GetReasoningOk() (*string, bool)`

GetReasoningOk returns a tuple with the Reasoning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasoning

`func (o *AlertLog) SetReasoning(v string)`

SetReasoning sets Reasoning field to given value.


### GetReport

`func (o *AlertLog) GetReport() string`

GetReport returns the Report field if non-nil, zero value otherwise.

### GetReportOk

`func (o *AlertLog) GetReportOk() (*string, bool)`

GetReportOk returns a tuple with the Report field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReport

`func (o *AlertLog) SetReport(v string)`

SetReport sets Report field to given value.

### HasReport

`func (o *AlertLog) HasReport() bool`

HasReport returns a boolean if a field has been set.

### SetReportNil

`func (o *AlertLog) SetReportNil(b bool)`

 SetReportNil sets the value for Report to be an explicit nil

### UnsetReport
`func (o *AlertLog) UnsetReport()`

UnsetReport ensures that no value is present for Report, not even an explicit nil
### GetReportUrl

`func (o *AlertLog) GetReportUrl() string`

GetReportUrl returns the ReportUrl field if non-nil, zero value otherwise.

### GetReportUrlOk

`func (o *AlertLog) GetReportUrlOk() (*string, bool)`

GetReportUrlOk returns a tuple with the ReportUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportUrl

`func (o *AlertLog) SetReportUrl(v string)`

SetReportUrl sets ReportUrl field to given value.

### HasReportUrl

`func (o *AlertLog) HasReportUrl() bool`

HasReportUrl returns a boolean if a field has been set.

### SetReportUrlNil

`func (o *AlertLog) SetReportUrlNil(b bool)`

 SetReportUrlNil sets the value for ReportUrl to be an explicit nil

### UnsetReportUrl
`func (o *AlertLog) UnsetReportUrl()`

UnsetReportUrl ensures that no value is present for ReportUrl, not even an explicit nil
### GetArticleIds

`func (o *AlertLog) GetArticleIds() []string`

GetArticleIds returns the ArticleIds field if non-nil, zero value otherwise.

### GetArticleIdsOk

`func (o *AlertLog) GetArticleIdsOk() (*[]string, bool)`

GetArticleIdsOk returns a tuple with the ArticleIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArticleIds

`func (o *AlertLog) SetArticleIds(v []string)`

SetArticleIds sets ArticleIds field to given value.


### GetWebhook

`func (o *AlertLog) GetWebhook() map[string]interface{}`

GetWebhook returns the Webhook field if non-nil, zero value otherwise.

### GetWebhookOk

`func (o *AlertLog) GetWebhookOk() (*map[string]interface{}, bool)`

GetWebhookOk returns a tuple with the Webhook field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhook

`func (o *AlertLog) SetWebhook(v map[string]interface{})`

SetWebhook sets Webhook field to given value.

### HasWebhook

`func (o *AlertLog) HasWebhook() bool`

HasWebhook returns a boolean if a field has been set.

### SetWebhookNil

`func (o *AlertLog) SetWebhookNil(b bool)`

 SetWebhookNil sets the value for Webhook to be an explicit nil

### UnsetWebhook
`func (o *AlertLog) UnsetWebhook()`

UnsetWebhook ensures that no value is present for Webhook, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


