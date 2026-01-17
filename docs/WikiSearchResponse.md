# WikiSearchResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Documents** | [**[]WikiResponseDictItem**](WikiResponseDictItem.md) |  | 

## Methods

### NewWikiSearchResponse

`func NewWikiSearchResponse(documents []WikiResponseDictItem, ) *WikiSearchResponse`

NewWikiSearchResponse instantiates a new WikiSearchResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWikiSearchResponseWithDefaults

`func NewWikiSearchResponseWithDefaults() *WikiSearchResponse`

NewWikiSearchResponseWithDefaults instantiates a new WikiSearchResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDocuments

`func (o *WikiSearchResponse) GetDocuments() []WikiResponseDictItem`

GetDocuments returns the Documents field if non-nil, zero value otherwise.

### GetDocumentsOk

`func (o *WikiSearchResponse) GetDocumentsOk() (*[]WikiResponseDictItem, bool)`

GetDocumentsOk returns a tuple with the Documents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocuments

`func (o *WikiSearchResponse) SetDocuments(v []WikiResponseDictItem)`

SetDocuments sets Documents field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


