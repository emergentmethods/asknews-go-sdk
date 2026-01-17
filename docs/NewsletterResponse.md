# NewsletterResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**CreatedAt** | Pointer to **NullableTime** |  | [optional] 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 
**UserId** | **string** |  | 
**AlertId** | Pointer to **NullableString** |  | [optional] 
**Name** | **string** |  | 
**Query** | **string** |  | 
**Cron** | **string** |  | 
**Model** | **NullableString** |  | 
**Subject** | **NullableString** |  | 
**Sender** | **string** |  | 
**LogoUrl** | **NullableString** |  | 
**ReplyTo** | **NullableString** |  | 
**AudienceId** | **NullableString** |  | 
**ResendApiKey** | **NullableString** |  | 
**Public** | Pointer to **bool** |  | [optional] [default to true]
**Active** | Pointer to **bool** |  | [optional] [default to true]
**ExpiresAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewNewsletterResponse

`func NewNewsletterResponse(id string, userId string, name string, query string, cron string, model NullableString, subject NullableString, sender string, logoUrl NullableString, replyTo NullableString, audienceId NullableString, resendApiKey NullableString, ) *NewsletterResponse`

NewNewsletterResponse instantiates a new NewsletterResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNewsletterResponseWithDefaults

`func NewNewsletterResponseWithDefaults() *NewsletterResponse`

NewNewsletterResponseWithDefaults instantiates a new NewsletterResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *NewsletterResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *NewsletterResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *NewsletterResponse) SetId(v string)`

SetId sets Id field to given value.


### GetCreatedAt

`func (o *NewsletterResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *NewsletterResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *NewsletterResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *NewsletterResponse) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *NewsletterResponse) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *NewsletterResponse) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetUpdatedAt

`func (o *NewsletterResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *NewsletterResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *NewsletterResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *NewsletterResponse) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *NewsletterResponse) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *NewsletterResponse) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetUserId

`func (o *NewsletterResponse) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *NewsletterResponse) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *NewsletterResponse) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetAlertId

`func (o *NewsletterResponse) GetAlertId() string`

GetAlertId returns the AlertId field if non-nil, zero value otherwise.

### GetAlertIdOk

`func (o *NewsletterResponse) GetAlertIdOk() (*string, bool)`

GetAlertIdOk returns a tuple with the AlertId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlertId

`func (o *NewsletterResponse) SetAlertId(v string)`

SetAlertId sets AlertId field to given value.

### HasAlertId

`func (o *NewsletterResponse) HasAlertId() bool`

HasAlertId returns a boolean if a field has been set.

### SetAlertIdNil

`func (o *NewsletterResponse) SetAlertIdNil(b bool)`

 SetAlertIdNil sets the value for AlertId to be an explicit nil

### UnsetAlertId
`func (o *NewsletterResponse) UnsetAlertId()`

UnsetAlertId ensures that no value is present for AlertId, not even an explicit nil
### GetName

`func (o *NewsletterResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *NewsletterResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *NewsletterResponse) SetName(v string)`

SetName sets Name field to given value.


### GetQuery

`func (o *NewsletterResponse) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *NewsletterResponse) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *NewsletterResponse) SetQuery(v string)`

SetQuery sets Query field to given value.


### GetCron

`func (o *NewsletterResponse) GetCron() string`

GetCron returns the Cron field if non-nil, zero value otherwise.

### GetCronOk

`func (o *NewsletterResponse) GetCronOk() (*string, bool)`

GetCronOk returns a tuple with the Cron field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCron

`func (o *NewsletterResponse) SetCron(v string)`

SetCron sets Cron field to given value.


### GetModel

`func (o *NewsletterResponse) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *NewsletterResponse) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *NewsletterResponse) SetModel(v string)`

SetModel sets Model field to given value.


### SetModelNil

`func (o *NewsletterResponse) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *NewsletterResponse) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetSubject

`func (o *NewsletterResponse) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *NewsletterResponse) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *NewsletterResponse) SetSubject(v string)`

SetSubject sets Subject field to given value.


### SetSubjectNil

`func (o *NewsletterResponse) SetSubjectNil(b bool)`

 SetSubjectNil sets the value for Subject to be an explicit nil

### UnsetSubject
`func (o *NewsletterResponse) UnsetSubject()`

UnsetSubject ensures that no value is present for Subject, not even an explicit nil
### GetSender

`func (o *NewsletterResponse) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *NewsletterResponse) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *NewsletterResponse) SetSender(v string)`

SetSender sets Sender field to given value.


### GetLogoUrl

`func (o *NewsletterResponse) GetLogoUrl() string`

GetLogoUrl returns the LogoUrl field if non-nil, zero value otherwise.

### GetLogoUrlOk

`func (o *NewsletterResponse) GetLogoUrlOk() (*string, bool)`

GetLogoUrlOk returns a tuple with the LogoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoUrl

`func (o *NewsletterResponse) SetLogoUrl(v string)`

SetLogoUrl sets LogoUrl field to given value.


### SetLogoUrlNil

`func (o *NewsletterResponse) SetLogoUrlNil(b bool)`

 SetLogoUrlNil sets the value for LogoUrl to be an explicit nil

### UnsetLogoUrl
`func (o *NewsletterResponse) UnsetLogoUrl()`

UnsetLogoUrl ensures that no value is present for LogoUrl, not even an explicit nil
### GetReplyTo

`func (o *NewsletterResponse) GetReplyTo() string`

GetReplyTo returns the ReplyTo field if non-nil, zero value otherwise.

### GetReplyToOk

`func (o *NewsletterResponse) GetReplyToOk() (*string, bool)`

GetReplyToOk returns a tuple with the ReplyTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplyTo

`func (o *NewsletterResponse) SetReplyTo(v string)`

SetReplyTo sets ReplyTo field to given value.


### SetReplyToNil

`func (o *NewsletterResponse) SetReplyToNil(b bool)`

 SetReplyToNil sets the value for ReplyTo to be an explicit nil

### UnsetReplyTo
`func (o *NewsletterResponse) UnsetReplyTo()`

UnsetReplyTo ensures that no value is present for ReplyTo, not even an explicit nil
### GetAudienceId

`func (o *NewsletterResponse) GetAudienceId() string`

GetAudienceId returns the AudienceId field if non-nil, zero value otherwise.

### GetAudienceIdOk

`func (o *NewsletterResponse) GetAudienceIdOk() (*string, bool)`

GetAudienceIdOk returns a tuple with the AudienceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAudienceId

`func (o *NewsletterResponse) SetAudienceId(v string)`

SetAudienceId sets AudienceId field to given value.


### SetAudienceIdNil

`func (o *NewsletterResponse) SetAudienceIdNil(b bool)`

 SetAudienceIdNil sets the value for AudienceId to be an explicit nil

### UnsetAudienceId
`func (o *NewsletterResponse) UnsetAudienceId()`

UnsetAudienceId ensures that no value is present for AudienceId, not even an explicit nil
### GetResendApiKey

`func (o *NewsletterResponse) GetResendApiKey() string`

GetResendApiKey returns the ResendApiKey field if non-nil, zero value otherwise.

### GetResendApiKeyOk

`func (o *NewsletterResponse) GetResendApiKeyOk() (*string, bool)`

GetResendApiKeyOk returns a tuple with the ResendApiKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResendApiKey

`func (o *NewsletterResponse) SetResendApiKey(v string)`

SetResendApiKey sets ResendApiKey field to given value.


### SetResendApiKeyNil

`func (o *NewsletterResponse) SetResendApiKeyNil(b bool)`

 SetResendApiKeyNil sets the value for ResendApiKey to be an explicit nil

### UnsetResendApiKey
`func (o *NewsletterResponse) UnsetResendApiKey()`

UnsetResendApiKey ensures that no value is present for ResendApiKey, not even an explicit nil
### GetPublic

`func (o *NewsletterResponse) GetPublic() bool`

GetPublic returns the Public field if non-nil, zero value otherwise.

### GetPublicOk

`func (o *NewsletterResponse) GetPublicOk() (*bool, bool)`

GetPublicOk returns a tuple with the Public field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublic

`func (o *NewsletterResponse) SetPublic(v bool)`

SetPublic sets Public field to given value.

### HasPublic

`func (o *NewsletterResponse) HasPublic() bool`

HasPublic returns a boolean if a field has been set.

### GetActive

`func (o *NewsletterResponse) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *NewsletterResponse) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *NewsletterResponse) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *NewsletterResponse) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetExpiresAt

`func (o *NewsletterResponse) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *NewsletterResponse) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *NewsletterResponse) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *NewsletterResponse) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *NewsletterResponse) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *NewsletterResponse) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


