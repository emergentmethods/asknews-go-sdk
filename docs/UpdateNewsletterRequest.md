# UpdateNewsletterRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **NullableString** |  | [optional] 
**Query** | Pointer to **NullableString** |  | [optional] 
**Cron** | Pointer to **NullableString** |  | [optional] 
**Model** | Pointer to **NullableString** |  | [optional] 
**Subject** | Pointer to **NullableString** |  | [optional] 
**Sender** | Pointer to **NullableString** |  | [optional] 
**LogoUrl** | Pointer to **NullableString** |  | [optional] 
**ReplyTo** | Pointer to **NullableString** |  | [optional] 
**AudienceId** | Pointer to **NullableString** |  | [optional] 
**ResendApiKey** | Pointer to **NullableString** |  | [optional] 
**Public** | Pointer to **NullableBool** |  | [optional] 
**Active** | Pointer to **NullableBool** |  | [optional] 
**ExpiresAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewUpdateNewsletterRequest

`func NewUpdateNewsletterRequest() *UpdateNewsletterRequest`

NewUpdateNewsletterRequest instantiates a new UpdateNewsletterRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateNewsletterRequestWithDefaults

`func NewUpdateNewsletterRequestWithDefaults() *UpdateNewsletterRequest`

NewUpdateNewsletterRequestWithDefaults instantiates a new UpdateNewsletterRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateNewsletterRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateNewsletterRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateNewsletterRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateNewsletterRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *UpdateNewsletterRequest) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *UpdateNewsletterRequest) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetQuery

`func (o *UpdateNewsletterRequest) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *UpdateNewsletterRequest) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *UpdateNewsletterRequest) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *UpdateNewsletterRequest) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### SetQueryNil

`func (o *UpdateNewsletterRequest) SetQueryNil(b bool)`

 SetQueryNil sets the value for Query to be an explicit nil

### UnsetQuery
`func (o *UpdateNewsletterRequest) UnsetQuery()`

UnsetQuery ensures that no value is present for Query, not even an explicit nil
### GetCron

`func (o *UpdateNewsletterRequest) GetCron() string`

GetCron returns the Cron field if non-nil, zero value otherwise.

### GetCronOk

`func (o *UpdateNewsletterRequest) GetCronOk() (*string, bool)`

GetCronOk returns a tuple with the Cron field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCron

`func (o *UpdateNewsletterRequest) SetCron(v string)`

SetCron sets Cron field to given value.

### HasCron

`func (o *UpdateNewsletterRequest) HasCron() bool`

HasCron returns a boolean if a field has been set.

### SetCronNil

`func (o *UpdateNewsletterRequest) SetCronNil(b bool)`

 SetCronNil sets the value for Cron to be an explicit nil

### UnsetCron
`func (o *UpdateNewsletterRequest) UnsetCron()`

UnsetCron ensures that no value is present for Cron, not even an explicit nil
### GetModel

`func (o *UpdateNewsletterRequest) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *UpdateNewsletterRequest) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *UpdateNewsletterRequest) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *UpdateNewsletterRequest) HasModel() bool`

HasModel returns a boolean if a field has been set.

### SetModelNil

`func (o *UpdateNewsletterRequest) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *UpdateNewsletterRequest) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetSubject

`func (o *UpdateNewsletterRequest) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *UpdateNewsletterRequest) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *UpdateNewsletterRequest) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *UpdateNewsletterRequest) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### SetSubjectNil

`func (o *UpdateNewsletterRequest) SetSubjectNil(b bool)`

 SetSubjectNil sets the value for Subject to be an explicit nil

### UnsetSubject
`func (o *UpdateNewsletterRequest) UnsetSubject()`

UnsetSubject ensures that no value is present for Subject, not even an explicit nil
### GetSender

`func (o *UpdateNewsletterRequest) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *UpdateNewsletterRequest) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *UpdateNewsletterRequest) SetSender(v string)`

SetSender sets Sender field to given value.

### HasSender

`func (o *UpdateNewsletterRequest) HasSender() bool`

HasSender returns a boolean if a field has been set.

### SetSenderNil

`func (o *UpdateNewsletterRequest) SetSenderNil(b bool)`

 SetSenderNil sets the value for Sender to be an explicit nil

### UnsetSender
`func (o *UpdateNewsletterRequest) UnsetSender()`

UnsetSender ensures that no value is present for Sender, not even an explicit nil
### GetLogoUrl

`func (o *UpdateNewsletterRequest) GetLogoUrl() string`

GetLogoUrl returns the LogoUrl field if non-nil, zero value otherwise.

### GetLogoUrlOk

`func (o *UpdateNewsletterRequest) GetLogoUrlOk() (*string, bool)`

GetLogoUrlOk returns a tuple with the LogoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoUrl

`func (o *UpdateNewsletterRequest) SetLogoUrl(v string)`

SetLogoUrl sets LogoUrl field to given value.

### HasLogoUrl

`func (o *UpdateNewsletterRequest) HasLogoUrl() bool`

HasLogoUrl returns a boolean if a field has been set.

### SetLogoUrlNil

`func (o *UpdateNewsletterRequest) SetLogoUrlNil(b bool)`

 SetLogoUrlNil sets the value for LogoUrl to be an explicit nil

### UnsetLogoUrl
`func (o *UpdateNewsletterRequest) UnsetLogoUrl()`

UnsetLogoUrl ensures that no value is present for LogoUrl, not even an explicit nil
### GetReplyTo

`func (o *UpdateNewsletterRequest) GetReplyTo() string`

GetReplyTo returns the ReplyTo field if non-nil, zero value otherwise.

### GetReplyToOk

`func (o *UpdateNewsletterRequest) GetReplyToOk() (*string, bool)`

GetReplyToOk returns a tuple with the ReplyTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplyTo

`func (o *UpdateNewsletterRequest) SetReplyTo(v string)`

SetReplyTo sets ReplyTo field to given value.

### HasReplyTo

`func (o *UpdateNewsletterRequest) HasReplyTo() bool`

HasReplyTo returns a boolean if a field has been set.

### SetReplyToNil

`func (o *UpdateNewsletterRequest) SetReplyToNil(b bool)`

 SetReplyToNil sets the value for ReplyTo to be an explicit nil

### UnsetReplyTo
`func (o *UpdateNewsletterRequest) UnsetReplyTo()`

UnsetReplyTo ensures that no value is present for ReplyTo, not even an explicit nil
### GetAudienceId

`func (o *UpdateNewsletterRequest) GetAudienceId() string`

GetAudienceId returns the AudienceId field if non-nil, zero value otherwise.

### GetAudienceIdOk

`func (o *UpdateNewsletterRequest) GetAudienceIdOk() (*string, bool)`

GetAudienceIdOk returns a tuple with the AudienceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAudienceId

`func (o *UpdateNewsletterRequest) SetAudienceId(v string)`

SetAudienceId sets AudienceId field to given value.

### HasAudienceId

`func (o *UpdateNewsletterRequest) HasAudienceId() bool`

HasAudienceId returns a boolean if a field has been set.

### SetAudienceIdNil

`func (o *UpdateNewsletterRequest) SetAudienceIdNil(b bool)`

 SetAudienceIdNil sets the value for AudienceId to be an explicit nil

### UnsetAudienceId
`func (o *UpdateNewsletterRequest) UnsetAudienceId()`

UnsetAudienceId ensures that no value is present for AudienceId, not even an explicit nil
### GetResendApiKey

`func (o *UpdateNewsletterRequest) GetResendApiKey() string`

GetResendApiKey returns the ResendApiKey field if non-nil, zero value otherwise.

### GetResendApiKeyOk

`func (o *UpdateNewsletterRequest) GetResendApiKeyOk() (*string, bool)`

GetResendApiKeyOk returns a tuple with the ResendApiKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResendApiKey

`func (o *UpdateNewsletterRequest) SetResendApiKey(v string)`

SetResendApiKey sets ResendApiKey field to given value.

### HasResendApiKey

`func (o *UpdateNewsletterRequest) HasResendApiKey() bool`

HasResendApiKey returns a boolean if a field has been set.

### SetResendApiKeyNil

`func (o *UpdateNewsletterRequest) SetResendApiKeyNil(b bool)`

 SetResendApiKeyNil sets the value for ResendApiKey to be an explicit nil

### UnsetResendApiKey
`func (o *UpdateNewsletterRequest) UnsetResendApiKey()`

UnsetResendApiKey ensures that no value is present for ResendApiKey, not even an explicit nil
### GetPublic

`func (o *UpdateNewsletterRequest) GetPublic() bool`

GetPublic returns the Public field if non-nil, zero value otherwise.

### GetPublicOk

`func (o *UpdateNewsletterRequest) GetPublicOk() (*bool, bool)`

GetPublicOk returns a tuple with the Public field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublic

`func (o *UpdateNewsletterRequest) SetPublic(v bool)`

SetPublic sets Public field to given value.

### HasPublic

`func (o *UpdateNewsletterRequest) HasPublic() bool`

HasPublic returns a boolean if a field has been set.

### SetPublicNil

`func (o *UpdateNewsletterRequest) SetPublicNil(b bool)`

 SetPublicNil sets the value for Public to be an explicit nil

### UnsetPublic
`func (o *UpdateNewsletterRequest) UnsetPublic()`

UnsetPublic ensures that no value is present for Public, not even an explicit nil
### GetActive

`func (o *UpdateNewsletterRequest) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *UpdateNewsletterRequest) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *UpdateNewsletterRequest) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *UpdateNewsletterRequest) HasActive() bool`

HasActive returns a boolean if a field has been set.

### SetActiveNil

`func (o *UpdateNewsletterRequest) SetActiveNil(b bool)`

 SetActiveNil sets the value for Active to be an explicit nil

### UnsetActive
`func (o *UpdateNewsletterRequest) UnsetActive()`

UnsetActive ensures that no value is present for Active, not even an explicit nil
### GetExpiresAt

`func (o *UpdateNewsletterRequest) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *UpdateNewsletterRequest) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *UpdateNewsletterRequest) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *UpdateNewsletterRequest) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *UpdateNewsletterRequest) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *UpdateNewsletterRequest) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


