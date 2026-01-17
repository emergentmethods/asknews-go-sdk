# CreateNewsletterRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | The name of the newsletter. | 
**Query** | **string** | The natural language query to run for the newsletter. | 
**Cron** | **string** | The cron schedule for the newsletter. For example daily at 00:00 UTC is &#39;0 0 * * *&#39;. See https://crontab.run/ for more examples | 
**Model** | **string** | The model to use for the newsletter. | 
**Subject** | Pointer to **NullableString** |  | [optional] 
**Sender** | **string** | The sender of the newsletter. | 
**LogoUrl** | Pointer to **NullableString** |  | [optional] 
**ReplyTo** | Pointer to **NullableString** |  | [optional] 
**AudienceId** | Pointer to **NullableString** |  | [optional] 
**ResendApiKey** | Pointer to **NullableString** |  | [optional] 
**Public** | Pointer to **bool** | Whether the newsletter is public or not. If not provided, the newsletter will be public. If you make the newsletter public only title and query will be shown. | [optional] [default to true]
**Active** | Pointer to **bool** | Whether the newsletter is active or not. If not provided, the newsletter will be active. If you make the newsletter inactive, it will not be sent. | [optional] [default to true]
**ExpiresAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewCreateNewsletterRequest

`func NewCreateNewsletterRequest(name string, query string, cron string, model string, sender string, ) *CreateNewsletterRequest`

NewCreateNewsletterRequest instantiates a new CreateNewsletterRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateNewsletterRequestWithDefaults

`func NewCreateNewsletterRequestWithDefaults() *CreateNewsletterRequest`

NewCreateNewsletterRequestWithDefaults instantiates a new CreateNewsletterRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateNewsletterRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateNewsletterRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateNewsletterRequest) SetName(v string)`

SetName sets Name field to given value.


### GetQuery

`func (o *CreateNewsletterRequest) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *CreateNewsletterRequest) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *CreateNewsletterRequest) SetQuery(v string)`

SetQuery sets Query field to given value.


### GetCron

`func (o *CreateNewsletterRequest) GetCron() string`

GetCron returns the Cron field if non-nil, zero value otherwise.

### GetCronOk

`func (o *CreateNewsletterRequest) GetCronOk() (*string, bool)`

GetCronOk returns a tuple with the Cron field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCron

`func (o *CreateNewsletterRequest) SetCron(v string)`

SetCron sets Cron field to given value.


### GetModel

`func (o *CreateNewsletterRequest) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *CreateNewsletterRequest) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *CreateNewsletterRequest) SetModel(v string)`

SetModel sets Model field to given value.


### GetSubject

`func (o *CreateNewsletterRequest) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *CreateNewsletterRequest) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *CreateNewsletterRequest) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *CreateNewsletterRequest) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### SetSubjectNil

`func (o *CreateNewsletterRequest) SetSubjectNil(b bool)`

 SetSubjectNil sets the value for Subject to be an explicit nil

### UnsetSubject
`func (o *CreateNewsletterRequest) UnsetSubject()`

UnsetSubject ensures that no value is present for Subject, not even an explicit nil
### GetSender

`func (o *CreateNewsletterRequest) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *CreateNewsletterRequest) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *CreateNewsletterRequest) SetSender(v string)`

SetSender sets Sender field to given value.


### GetLogoUrl

`func (o *CreateNewsletterRequest) GetLogoUrl() string`

GetLogoUrl returns the LogoUrl field if non-nil, zero value otherwise.

### GetLogoUrlOk

`func (o *CreateNewsletterRequest) GetLogoUrlOk() (*string, bool)`

GetLogoUrlOk returns a tuple with the LogoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogoUrl

`func (o *CreateNewsletterRequest) SetLogoUrl(v string)`

SetLogoUrl sets LogoUrl field to given value.

### HasLogoUrl

`func (o *CreateNewsletterRequest) HasLogoUrl() bool`

HasLogoUrl returns a boolean if a field has been set.

### SetLogoUrlNil

`func (o *CreateNewsletterRequest) SetLogoUrlNil(b bool)`

 SetLogoUrlNil sets the value for LogoUrl to be an explicit nil

### UnsetLogoUrl
`func (o *CreateNewsletterRequest) UnsetLogoUrl()`

UnsetLogoUrl ensures that no value is present for LogoUrl, not even an explicit nil
### GetReplyTo

`func (o *CreateNewsletterRequest) GetReplyTo() string`

GetReplyTo returns the ReplyTo field if non-nil, zero value otherwise.

### GetReplyToOk

`func (o *CreateNewsletterRequest) GetReplyToOk() (*string, bool)`

GetReplyToOk returns a tuple with the ReplyTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplyTo

`func (o *CreateNewsletterRequest) SetReplyTo(v string)`

SetReplyTo sets ReplyTo field to given value.

### HasReplyTo

`func (o *CreateNewsletterRequest) HasReplyTo() bool`

HasReplyTo returns a boolean if a field has been set.

### SetReplyToNil

`func (o *CreateNewsletterRequest) SetReplyToNil(b bool)`

 SetReplyToNil sets the value for ReplyTo to be an explicit nil

### UnsetReplyTo
`func (o *CreateNewsletterRequest) UnsetReplyTo()`

UnsetReplyTo ensures that no value is present for ReplyTo, not even an explicit nil
### GetAudienceId

`func (o *CreateNewsletterRequest) GetAudienceId() string`

GetAudienceId returns the AudienceId field if non-nil, zero value otherwise.

### GetAudienceIdOk

`func (o *CreateNewsletterRequest) GetAudienceIdOk() (*string, bool)`

GetAudienceIdOk returns a tuple with the AudienceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAudienceId

`func (o *CreateNewsletterRequest) SetAudienceId(v string)`

SetAudienceId sets AudienceId field to given value.

### HasAudienceId

`func (o *CreateNewsletterRequest) HasAudienceId() bool`

HasAudienceId returns a boolean if a field has been set.

### SetAudienceIdNil

`func (o *CreateNewsletterRequest) SetAudienceIdNil(b bool)`

 SetAudienceIdNil sets the value for AudienceId to be an explicit nil

### UnsetAudienceId
`func (o *CreateNewsletterRequest) UnsetAudienceId()`

UnsetAudienceId ensures that no value is present for AudienceId, not even an explicit nil
### GetResendApiKey

`func (o *CreateNewsletterRequest) GetResendApiKey() string`

GetResendApiKey returns the ResendApiKey field if non-nil, zero value otherwise.

### GetResendApiKeyOk

`func (o *CreateNewsletterRequest) GetResendApiKeyOk() (*string, bool)`

GetResendApiKeyOk returns a tuple with the ResendApiKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResendApiKey

`func (o *CreateNewsletterRequest) SetResendApiKey(v string)`

SetResendApiKey sets ResendApiKey field to given value.

### HasResendApiKey

`func (o *CreateNewsletterRequest) HasResendApiKey() bool`

HasResendApiKey returns a boolean if a field has been set.

### SetResendApiKeyNil

`func (o *CreateNewsletterRequest) SetResendApiKeyNil(b bool)`

 SetResendApiKeyNil sets the value for ResendApiKey to be an explicit nil

### UnsetResendApiKey
`func (o *CreateNewsletterRequest) UnsetResendApiKey()`

UnsetResendApiKey ensures that no value is present for ResendApiKey, not even an explicit nil
### GetPublic

`func (o *CreateNewsletterRequest) GetPublic() bool`

GetPublic returns the Public field if non-nil, zero value otherwise.

### GetPublicOk

`func (o *CreateNewsletterRequest) GetPublicOk() (*bool, bool)`

GetPublicOk returns a tuple with the Public field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublic

`func (o *CreateNewsletterRequest) SetPublic(v bool)`

SetPublic sets Public field to given value.

### HasPublic

`func (o *CreateNewsletterRequest) HasPublic() bool`

HasPublic returns a boolean if a field has been set.

### GetActive

`func (o *CreateNewsletterRequest) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *CreateNewsletterRequest) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *CreateNewsletterRequest) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *CreateNewsletterRequest) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetExpiresAt

`func (o *CreateNewsletterRequest) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *CreateNewsletterRequest) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *CreateNewsletterRequest) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *CreateNewsletterRequest) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *CreateNewsletterRequest) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *CreateNewsletterRequest) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


