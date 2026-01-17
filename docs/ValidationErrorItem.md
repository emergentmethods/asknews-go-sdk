# ValidationErrorItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Loc** | **[]string** |  | 
**Msg** | **string** |  | 
**Type** | **string** |  | 

## Methods

### NewValidationErrorItem

`func NewValidationErrorItem(loc []string, msg string, type_ string, ) *ValidationErrorItem`

NewValidationErrorItem instantiates a new ValidationErrorItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewValidationErrorItemWithDefaults

`func NewValidationErrorItemWithDefaults() *ValidationErrorItem`

NewValidationErrorItemWithDefaults instantiates a new ValidationErrorItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLoc

`func (o *ValidationErrorItem) GetLoc() []string`

GetLoc returns the Loc field if non-nil, zero value otherwise.

### GetLocOk

`func (o *ValidationErrorItem) GetLocOk() (*[]string, bool)`

GetLocOk returns a tuple with the Loc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoc

`func (o *ValidationErrorItem) SetLoc(v []string)`

SetLoc sets Loc field to given value.


### GetMsg

`func (o *ValidationErrorItem) GetMsg() string`

GetMsg returns the Msg field if non-nil, zero value otherwise.

### GetMsgOk

`func (o *ValidationErrorItem) GetMsgOk() (*string, bool)`

GetMsgOk returns a tuple with the Msg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsg

`func (o *ValidationErrorItem) SetMsg(v string)`

SetMsg sets Msg field to given value.


### GetType

`func (o *ValidationErrorItem) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ValidationErrorItem) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ValidationErrorItem) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


