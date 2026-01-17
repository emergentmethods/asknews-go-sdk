# UpdateDomainRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Owner** | Pointer to **NullableString** |  | [optional] 
**IsTollbit** | Pointer to **NullableBool** |  | [optional] 
**Publisher** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewUpdateDomainRequest

`func NewUpdateDomainRequest() *UpdateDomainRequest`

NewUpdateDomainRequest instantiates a new UpdateDomainRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateDomainRequestWithDefaults

`func NewUpdateDomainRequestWithDefaults() *UpdateDomainRequest`

NewUpdateDomainRequestWithDefaults instantiates a new UpdateDomainRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOwner

`func (o *UpdateDomainRequest) GetOwner() string`

GetOwner returns the Owner field if non-nil, zero value otherwise.

### GetOwnerOk

`func (o *UpdateDomainRequest) GetOwnerOk() (*string, bool)`

GetOwnerOk returns a tuple with the Owner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwner

`func (o *UpdateDomainRequest) SetOwner(v string)`

SetOwner sets Owner field to given value.

### HasOwner

`func (o *UpdateDomainRequest) HasOwner() bool`

HasOwner returns a boolean if a field has been set.

### SetOwnerNil

`func (o *UpdateDomainRequest) SetOwnerNil(b bool)`

 SetOwnerNil sets the value for Owner to be an explicit nil

### UnsetOwner
`func (o *UpdateDomainRequest) UnsetOwner()`

UnsetOwner ensures that no value is present for Owner, not even an explicit nil
### GetIsTollbit

`func (o *UpdateDomainRequest) GetIsTollbit() bool`

GetIsTollbit returns the IsTollbit field if non-nil, zero value otherwise.

### GetIsTollbitOk

`func (o *UpdateDomainRequest) GetIsTollbitOk() (*bool, bool)`

GetIsTollbitOk returns a tuple with the IsTollbit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTollbit

`func (o *UpdateDomainRequest) SetIsTollbit(v bool)`

SetIsTollbit sets IsTollbit field to given value.

### HasIsTollbit

`func (o *UpdateDomainRequest) HasIsTollbit() bool`

HasIsTollbit returns a boolean if a field has been set.

### SetIsTollbitNil

`func (o *UpdateDomainRequest) SetIsTollbitNil(b bool)`

 SetIsTollbitNil sets the value for IsTollbit to be an explicit nil

### UnsetIsTollbit
`func (o *UpdateDomainRequest) UnsetIsTollbit()`

UnsetIsTollbit ensures that no value is present for IsTollbit, not even an explicit nil
### GetPublisher

`func (o *UpdateDomainRequest) GetPublisher() string`

GetPublisher returns the Publisher field if non-nil, zero value otherwise.

### GetPublisherOk

`func (o *UpdateDomainRequest) GetPublisherOk() (*string, bool)`

GetPublisherOk returns a tuple with the Publisher field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublisher

`func (o *UpdateDomainRequest) SetPublisher(v string)`

SetPublisher sets Publisher field to given value.

### HasPublisher

`func (o *UpdateDomainRequest) HasPublisher() bool`

HasPublisher returns a boolean if a field has been set.

### SetPublisherNil

`func (o *UpdateDomainRequest) SetPublisherNil(b bool)`

 SetPublisherNil sets the value for Publisher to be an explicit nil

### UnsetPublisher
`func (o *UpdateDomainRequest) UnsetPublisher()`

UnsetPublisher ensures that no value is present for Publisher, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


