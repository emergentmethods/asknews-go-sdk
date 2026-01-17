# IndexUrlsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | **string** |  | 
**JobId** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewIndexUrlsResponse

`func NewIndexUrlsResponse(status string, ) *IndexUrlsResponse`

NewIndexUrlsResponse instantiates a new IndexUrlsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIndexUrlsResponseWithDefaults

`func NewIndexUrlsResponseWithDefaults() *IndexUrlsResponse`

NewIndexUrlsResponseWithDefaults instantiates a new IndexUrlsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *IndexUrlsResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *IndexUrlsResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *IndexUrlsResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetJobId

`func (o *IndexUrlsResponse) GetJobId() string`

GetJobId returns the JobId field if non-nil, zero value otherwise.

### GetJobIdOk

`func (o *IndexUrlsResponse) GetJobIdOk() (*string, bool)`

GetJobIdOk returns a tuple with the JobId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobId

`func (o *IndexUrlsResponse) SetJobId(v string)`

SetJobId sets JobId field to given value.

### HasJobId

`func (o *IndexUrlsResponse) HasJobId() bool`

HasJobId returns a boolean if a field has been set.

### SetJobIdNil

`func (o *IndexUrlsResponse) SetJobIdNil(b bool)`

 SetJobIdNil sets the value for JobId to be an explicit nil

### UnsetJobId
`func (o *IndexUrlsResponse) UnsetJobId()`

UnsetJobId ensures that no value is present for JobId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


