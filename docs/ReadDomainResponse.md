# ReadDomainResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Name** | **string** |  | 
**Owner** | Pointer to **NullableString** |  | [optional] 
**IsTollbit** | Pointer to **bool** |  | [optional] [default to false]
**Publisher** | Pointer to **bool** |  | [optional] [default to false]
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewReadDomainResponse

`func NewReadDomainResponse(id string, name string, createdAt time.Time, ) *ReadDomainResponse`

NewReadDomainResponse instantiates a new ReadDomainResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReadDomainResponseWithDefaults

`func NewReadDomainResponseWithDefaults() *ReadDomainResponse`

NewReadDomainResponseWithDefaults instantiates a new ReadDomainResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ReadDomainResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ReadDomainResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ReadDomainResponse) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *ReadDomainResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ReadDomainResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ReadDomainResponse) SetName(v string)`

SetName sets Name field to given value.


### GetOwner

`func (o *ReadDomainResponse) GetOwner() string`

GetOwner returns the Owner field if non-nil, zero value otherwise.

### GetOwnerOk

`func (o *ReadDomainResponse) GetOwnerOk() (*string, bool)`

GetOwnerOk returns a tuple with the Owner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwner

`func (o *ReadDomainResponse) SetOwner(v string)`

SetOwner sets Owner field to given value.

### HasOwner

`func (o *ReadDomainResponse) HasOwner() bool`

HasOwner returns a boolean if a field has been set.

### SetOwnerNil

`func (o *ReadDomainResponse) SetOwnerNil(b bool)`

 SetOwnerNil sets the value for Owner to be an explicit nil

### UnsetOwner
`func (o *ReadDomainResponse) UnsetOwner()`

UnsetOwner ensures that no value is present for Owner, not even an explicit nil
### GetIsTollbit

`func (o *ReadDomainResponse) GetIsTollbit() bool`

GetIsTollbit returns the IsTollbit field if non-nil, zero value otherwise.

### GetIsTollbitOk

`func (o *ReadDomainResponse) GetIsTollbitOk() (*bool, bool)`

GetIsTollbitOk returns a tuple with the IsTollbit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTollbit

`func (o *ReadDomainResponse) SetIsTollbit(v bool)`

SetIsTollbit sets IsTollbit field to given value.

### HasIsTollbit

`func (o *ReadDomainResponse) HasIsTollbit() bool`

HasIsTollbit returns a boolean if a field has been set.

### GetPublisher

`func (o *ReadDomainResponse) GetPublisher() bool`

GetPublisher returns the Publisher field if non-nil, zero value otherwise.

### GetPublisherOk

`func (o *ReadDomainResponse) GetPublisherOk() (*bool, bool)`

GetPublisherOk returns a tuple with the Publisher field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublisher

`func (o *ReadDomainResponse) SetPublisher(v bool)`

SetPublisher sets Publisher field to given value.

### HasPublisher

`func (o *ReadDomainResponse) HasPublisher() bool`

HasPublisher returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ReadDomainResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ReadDomainResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ReadDomainResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ReadDomainResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ReadDomainResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ReadDomainResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ReadDomainResponse) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *ReadDomainResponse) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *ReadDomainResponse) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


