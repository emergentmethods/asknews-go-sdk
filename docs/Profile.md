# Profile

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IdentityType** | Pointer to **string** |  | [optional] [default to "organization"]
**Id** | **string** |  | 
**Subscription** | [**OrganizationProfileSubscription**](OrganizationProfileSubscription.md) |  | 
**Organization** | Pointer to [**UserProfileOrganization**](UserProfileOrganization.md) |  | [optional] 
**Suspended** | Pointer to **bool** |  | [optional] [default to false]

## Methods

### NewProfile

`func NewProfile(id string, subscription OrganizationProfileSubscription, ) *Profile`

NewProfile instantiates a new Profile object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProfileWithDefaults

`func NewProfileWithDefaults() *Profile`

NewProfileWithDefaults instantiates a new Profile object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentityType

`func (o *Profile) GetIdentityType() string`

GetIdentityType returns the IdentityType field if non-nil, zero value otherwise.

### GetIdentityTypeOk

`func (o *Profile) GetIdentityTypeOk() (*string, bool)`

GetIdentityTypeOk returns a tuple with the IdentityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentityType

`func (o *Profile) SetIdentityType(v string)`

SetIdentityType sets IdentityType field to given value.

### HasIdentityType

`func (o *Profile) HasIdentityType() bool`

HasIdentityType returns a boolean if a field has been set.

### GetId

`func (o *Profile) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Profile) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Profile) SetId(v string)`

SetId sets Id field to given value.


### GetSubscription

`func (o *Profile) GetSubscription() OrganizationProfileSubscription`

GetSubscription returns the Subscription field if non-nil, zero value otherwise.

### GetSubscriptionOk

`func (o *Profile) GetSubscriptionOk() (*OrganizationProfileSubscription, bool)`

GetSubscriptionOk returns a tuple with the Subscription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscription

`func (o *Profile) SetSubscription(v OrganizationProfileSubscription)`

SetSubscription sets Subscription field to given value.


### GetOrganization

`func (o *Profile) GetOrganization() UserProfileOrganization`

GetOrganization returns the Organization field if non-nil, zero value otherwise.

### GetOrganizationOk

`func (o *Profile) GetOrganizationOk() (*UserProfileOrganization, bool)`

GetOrganizationOk returns a tuple with the Organization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganization

`func (o *Profile) SetOrganization(v UserProfileOrganization)`

SetOrganization sets Organization field to given value.

### HasOrganization

`func (o *Profile) HasOrganization() bool`

HasOrganization returns a boolean if a field has been set.

### GetSuspended

`func (o *Profile) GetSuspended() bool`

GetSuspended returns the Suspended field if non-nil, zero value otherwise.

### GetSuspendedOk

`func (o *Profile) GetSuspendedOk() (*bool, bool)`

GetSuspendedOk returns a tuple with the Suspended field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuspended

`func (o *Profile) SetSuspended(v bool)`

SetSuspended sets Suspended field to given value.

### HasSuspended

`func (o *Profile) HasSuspended() bool`

HasSuspended returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


