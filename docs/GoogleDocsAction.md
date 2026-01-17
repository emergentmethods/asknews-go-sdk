# GoogleDocsAction

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | Pointer to **string** |  | [optional] [default to "google_docs"]
**Params** | [**GoogleDocsParams**](GoogleDocsParams.md) |  | 

## Methods

### NewGoogleDocsAction

`func NewGoogleDocsAction(params GoogleDocsParams, ) *GoogleDocsAction`

NewGoogleDocsAction instantiates a new GoogleDocsAction object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGoogleDocsActionWithDefaults

`func NewGoogleDocsActionWithDefaults() *GoogleDocsAction`

NewGoogleDocsActionWithDefaults instantiates a new GoogleDocsAction object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *GoogleDocsAction) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *GoogleDocsAction) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *GoogleDocsAction) SetAction(v string)`

SetAction sets Action field to given value.

### HasAction

`func (o *GoogleDocsAction) HasAction() bool`

HasAction returns a boolean if a field has been set.

### GetParams

`func (o *GoogleDocsAction) GetParams() GoogleDocsParams`

GetParams returns the Params field if non-nil, zero value otherwise.

### GetParamsOk

`func (o *GoogleDocsAction) GetParamsOk() (*GoogleDocsParams, bool)`

GetParamsOk returns a tuple with the Params field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParams

`func (o *GoogleDocsAction) SetParams(v GoogleDocsParams)`

SetParams sets Params field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


