# StoriesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Stories** | [**[]StoryResponse**](StoryResponse.md) |  | 
**Offset** | [**Offset4**](Offset4.md) |  | 

## Methods

### NewStoriesResponse

`func NewStoriesResponse(stories []StoryResponse, offset Offset4, ) *StoriesResponse`

NewStoriesResponse instantiates a new StoriesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoriesResponseWithDefaults

`func NewStoriesResponseWithDefaults() *StoriesResponse`

NewStoriesResponseWithDefaults instantiates a new StoriesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStories

`func (o *StoriesResponse) GetStories() []StoryResponse`

GetStories returns the Stories field if non-nil, zero value otherwise.

### GetStoriesOk

`func (o *StoriesResponse) GetStoriesOk() (*[]StoryResponse, bool)`

GetStoriesOk returns a tuple with the Stories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStories

`func (o *StoriesResponse) SetStories(v []StoryResponse)`

SetStories sets Stories field to given value.


### GetOffset

`func (o *StoriesResponse) GetOffset() Offset4`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *StoriesResponse) GetOffsetOk() (*Offset4, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *StoriesResponse) SetOffset(v Offset4)`

SetOffset sets Offset field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


