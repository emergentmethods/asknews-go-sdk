# ListModelResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Object** | Pointer to **string** |  | [optional] [default to "list"]
**Data** | [**[]ModelItem**](ModelItem.md) |  | 

## Methods

### NewListModelResponse

`func NewListModelResponse(data []ModelItem, ) *ListModelResponse`

NewListModelResponse instantiates a new ListModelResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListModelResponseWithDefaults

`func NewListModelResponseWithDefaults() *ListModelResponse`

NewListModelResponseWithDefaults instantiates a new ListModelResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetObject

`func (o *ListModelResponse) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *ListModelResponse) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *ListModelResponse) SetObject(v string)`

SetObject sets Object field to given value.

### HasObject

`func (o *ListModelResponse) HasObject() bool`

HasObject returns a boolean if a field has been set.

### GetData

`func (o *ListModelResponse) GetData() []ModelItem`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListModelResponse) GetDataOk() (*[]ModelItem, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListModelResponse) SetData(v []ModelItem)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


