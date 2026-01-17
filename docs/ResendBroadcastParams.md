# ResendBroadcastParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Sender** | **string** | The sender email address, use the format: Your Name &lt;sender@domain.com&gt; | 
**ReplyTo** | Pointer to [**NullableReplyTo**](ReplyTo.md) |  | [optional] 
**Subject** | Pointer to **NullableString** |  | [optional] 
**AudienceId** | **string** | The audience id that the broadcast will be sent to | 
**ResendApiKey** | **string** | Resend API key to use | 

## Methods

### NewResendBroadcastParams

`func NewResendBroadcastParams(sender string, audienceId string, resendApiKey string, ) *ResendBroadcastParams`

NewResendBroadcastParams instantiates a new ResendBroadcastParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResendBroadcastParamsWithDefaults

`func NewResendBroadcastParamsWithDefaults() *ResendBroadcastParams`

NewResendBroadcastParamsWithDefaults instantiates a new ResendBroadcastParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSender

`func (o *ResendBroadcastParams) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *ResendBroadcastParams) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *ResendBroadcastParams) SetSender(v string)`

SetSender sets Sender field to given value.


### GetReplyTo

`func (o *ResendBroadcastParams) GetReplyTo() ReplyTo`

GetReplyTo returns the ReplyTo field if non-nil, zero value otherwise.

### GetReplyToOk

`func (o *ResendBroadcastParams) GetReplyToOk() (*ReplyTo, bool)`

GetReplyToOk returns a tuple with the ReplyTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplyTo

`func (o *ResendBroadcastParams) SetReplyTo(v ReplyTo)`

SetReplyTo sets ReplyTo field to given value.

### HasReplyTo

`func (o *ResendBroadcastParams) HasReplyTo() bool`

HasReplyTo returns a boolean if a field has been set.

### SetReplyToNil

`func (o *ResendBroadcastParams) SetReplyToNil(b bool)`

 SetReplyToNil sets the value for ReplyTo to be an explicit nil

### UnsetReplyTo
`func (o *ResendBroadcastParams) UnsetReplyTo()`

UnsetReplyTo ensures that no value is present for ReplyTo, not even an explicit nil
### GetSubject

`func (o *ResendBroadcastParams) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *ResendBroadcastParams) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *ResendBroadcastParams) SetSubject(v string)`

SetSubject sets Subject field to given value.

### HasSubject

`func (o *ResendBroadcastParams) HasSubject() bool`

HasSubject returns a boolean if a field has been set.

### SetSubjectNil

`func (o *ResendBroadcastParams) SetSubjectNil(b bool)`

 SetSubjectNil sets the value for Subject to be an explicit nil

### UnsetSubject
`func (o *ResendBroadcastParams) UnsetSubject()`

UnsetSubject ensures that no value is present for Subject, not even an explicit nil
### GetAudienceId

`func (o *ResendBroadcastParams) GetAudienceId() string`

GetAudienceId returns the AudienceId field if non-nil, zero value otherwise.

### GetAudienceIdOk

`func (o *ResendBroadcastParams) GetAudienceIdOk() (*string, bool)`

GetAudienceIdOk returns a tuple with the AudienceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAudienceId

`func (o *ResendBroadcastParams) SetAudienceId(v string)`

SetAudienceId sets AudienceId field to given value.


### GetResendApiKey

`func (o *ResendBroadcastParams) GetResendApiKey() string`

GetResendApiKey returns the ResendApiKey field if non-nil, zero value otherwise.

### GetResendApiKeyOk

`func (o *ResendBroadcastParams) GetResendApiKeyOk() (*string, bool)`

GetResendApiKeyOk returns a tuple with the ResendApiKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResendApiKey

`func (o *ResendBroadcastParams) SetResendApiKey(v string)`

SetResendApiKey sets ResendApiKey field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


