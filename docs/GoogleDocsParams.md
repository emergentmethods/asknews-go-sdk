# GoogleDocsParams

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClientJson** | **map[string]interface{}** | The google service account json. This should be a dict. You can get this from the google cloud console. The document will be created in the service account&#39;s google drive and shared with the user. | 
**Emails** | Pointer to **[]string** |  | [optional] 

## Methods

### NewGoogleDocsParams

`func NewGoogleDocsParams(clientJson map[string]interface{}, ) *GoogleDocsParams`

NewGoogleDocsParams instantiates a new GoogleDocsParams object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGoogleDocsParamsWithDefaults

`func NewGoogleDocsParamsWithDefaults() *GoogleDocsParams`

NewGoogleDocsParamsWithDefaults instantiates a new GoogleDocsParams object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClientJson

`func (o *GoogleDocsParams) GetClientJson() map[string]interface{}`

GetClientJson returns the ClientJson field if non-nil, zero value otherwise.

### GetClientJsonOk

`func (o *GoogleDocsParams) GetClientJsonOk() (*map[string]interface{}, bool)`

GetClientJsonOk returns a tuple with the ClientJson field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientJson

`func (o *GoogleDocsParams) SetClientJson(v map[string]interface{})`

SetClientJson sets ClientJson field to given value.


### GetEmails

`func (o *GoogleDocsParams) GetEmails() []string`

GetEmails returns the Emails field if non-nil, zero value otherwise.

### GetEmailsOk

`func (o *GoogleDocsParams) GetEmailsOk() (*[]string, bool)`

GetEmailsOk returns a tuple with the Emails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmails

`func (o *GoogleDocsParams) SetEmails(v []string)`

SetEmails sets Emails field to given value.

### HasEmails

`func (o *GoogleDocsParams) HasEmails() bool`

HasEmails returns a boolean if a field has been set.

### SetEmailsNil

`func (o *GoogleDocsParams) SetEmailsNil(b bool)`

 SetEmailsNil sets the value for Emails to be an explicit nil

### UnsetEmails
`func (o *GoogleDocsParams) UnsetEmails()`

UnsetEmails ensures that no value is present for Emails, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


