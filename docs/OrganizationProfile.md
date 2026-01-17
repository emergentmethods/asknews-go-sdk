# OrganizationProfile

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IdentityType** | Pointer to **string** |  | [optional] [default to "organization"]
**Id** | **string** |  | 
**Subscription** | [**OrganizationProfileSubscription**](OrganizationProfileSubscription.md) |  | 

## Methods

### NewOrganizationProfile

`func NewOrganizationProfile(id string, subscription OrganizationProfileSubscription, ) *OrganizationProfile`

NewOrganizationProfile instantiates a new OrganizationProfile object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrganizationProfileWithDefaults

`func NewOrganizationProfileWithDefaults() *OrganizationProfile`

NewOrganizationProfileWithDefaults instantiates a new OrganizationProfile object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIdentityType

`func (o *OrganizationProfile) GetIdentityType() string`

GetIdentityType returns the IdentityType field if non-nil, zero value otherwise.

### GetIdentityTypeOk

`func (o *OrganizationProfile) GetIdentityTypeOk() (*string, bool)`

GetIdentityTypeOk returns a tuple with the IdentityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentityType

`func (o *OrganizationProfile) SetIdentityType(v string)`

SetIdentityType sets IdentityType field to given value.

### HasIdentityType

`func (o *OrganizationProfile) HasIdentityType() bool`

HasIdentityType returns a boolean if a field has been set.

### GetId

`func (o *OrganizationProfile) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *OrganizationProfile) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *OrganizationProfile) SetId(v string)`

SetId sets Id field to given value.


### GetSubscription

`func (o *OrganizationProfile) GetSubscription() OrganizationProfileSubscription`

GetSubscription returns the Subscription field if non-nil, zero value otherwise.

### GetSubscriptionOk

`func (o *OrganizationProfile) GetSubscriptionOk() (*OrganizationProfileSubscription, bool)`

GetSubscriptionOk returns a tuple with the Subscription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscription

`func (o *OrganizationProfile) SetSubscription(v OrganizationProfileSubscription)`

SetSubscription sets Subscription field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


