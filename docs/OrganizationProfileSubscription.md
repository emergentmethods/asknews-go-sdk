# OrganizationProfileSubscription

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | **string** |  | 
**Plan** | **string** |  | 
**PeriodStart** | Pointer to **NullableTime** |  | [optional] 
**PeriodEnd** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewOrganizationProfileSubscription

`func NewOrganizationProfileSubscription(status string, plan string, ) *OrganizationProfileSubscription`

NewOrganizationProfileSubscription instantiates a new OrganizationProfileSubscription object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganizationProfileSubscriptionWithDefaults

`func NewOrganizationProfileSubscriptionWithDefaults() *OrganizationProfileSubscription`

NewOrganizationProfileSubscriptionWithDefaults instantiates a new OrganizationProfileSubscription object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *OrganizationProfileSubscription) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *OrganizationProfileSubscription) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *OrganizationProfileSubscription) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetPlan

`func (o *OrganizationProfileSubscription) GetPlan() string`

GetPlan returns the Plan field if non-nil, zero value otherwise.

### GetPlanOk

`func (o *OrganizationProfileSubscription) GetPlanOk() (*string, bool)`

GetPlanOk returns a tuple with the Plan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlan

`func (o *OrganizationProfileSubscription) SetPlan(v string)`

SetPlan sets Plan field to given value.


### GetPeriodStart

`func (o *OrganizationProfileSubscription) GetPeriodStart() time.Time`

GetPeriodStart returns the PeriodStart field if non-nil, zero value otherwise.

### GetPeriodStartOk

`func (o *OrganizationProfileSubscription) GetPeriodStartOk() (*time.Time, bool)`

GetPeriodStartOk returns a tuple with the PeriodStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodStart

`func (o *OrganizationProfileSubscription) SetPeriodStart(v time.Time)`

SetPeriodStart sets PeriodStart field to given value.

### HasPeriodStart

`func (o *OrganizationProfileSubscription) HasPeriodStart() bool`

HasPeriodStart returns a boolean if a field has been set.

### SetPeriodStartNil

`func (o *OrganizationProfileSubscription) SetPeriodStartNil(b bool)`

 SetPeriodStartNil sets the value for PeriodStart to be an explicit nil

### UnsetPeriodStart
`func (o *OrganizationProfileSubscription) UnsetPeriodStart()`

UnsetPeriodStart ensures that no value is present for PeriodStart, not even an explicit nil
### GetPeriodEnd

`func (o *OrganizationProfileSubscription) GetPeriodEnd() time.Time`

GetPeriodEnd returns the PeriodEnd field if non-nil, zero value otherwise.

### GetPeriodEndOk

`func (o *OrganizationProfileSubscription) GetPeriodEndOk() (*time.Time, bool)`

GetPeriodEndOk returns a tuple with the PeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodEnd

`func (o *OrganizationProfileSubscription) SetPeriodEnd(v time.Time)`

SetPeriodEnd sets PeriodEnd field to given value.

### HasPeriodEnd

`func (o *OrganizationProfileSubscription) HasPeriodEnd() bool`

HasPeriodEnd returns a boolean if a field has been set.

### SetPeriodEndNil

`func (o *OrganizationProfileSubscription) SetPeriodEndNil(b bool)`

 SetPeriodEndNil sets the value for PeriodEnd to be an explicit nil

### UnsetPeriodEnd
`func (o *OrganizationProfileSubscription) UnsetPeriodEnd()`

UnsetPeriodEnd ensures that no value is present for PeriodEnd, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


