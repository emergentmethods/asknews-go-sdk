# TopNArticlesTimeseriesItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ArticleUrl** | **string** |  | 
**ArticleId** | Pointer to **NullableString** |  | [optional] 
**HitCount** | **int32** |  | 

## Methods

### NewTopNArticlesTimeseriesItem

`func NewTopNArticlesTimeseriesItem(articleUrl string, hitCount int32, ) *TopNArticlesTimeseriesItem`

NewTopNArticlesTimeseriesItem instantiates a new TopNArticlesTimeseriesItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTopNArticlesTimeseriesItemWithDefaults

`func NewTopNArticlesTimeseriesItemWithDefaults() *TopNArticlesTimeseriesItem`

NewTopNArticlesTimeseriesItemWithDefaults instantiates a new TopNArticlesTimeseriesItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArticleUrl

`func (o *TopNArticlesTimeseriesItem) GetArticleUrl() string`

GetArticleUrl returns the ArticleUrl field if non-nil, zero value otherwise.

### GetArticleUrlOk

`func (o *TopNArticlesTimeseriesItem) GetArticleUrlOk() (*string, bool)`

GetArticleUrlOk returns a tuple with the ArticleUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArticleUrl

`func (o *TopNArticlesTimeseriesItem) SetArticleUrl(v string)`

SetArticleUrl sets ArticleUrl field to given value.


### GetArticleId

`func (o *TopNArticlesTimeseriesItem) GetArticleId() string`

GetArticleId returns the ArticleId field if non-nil, zero value otherwise.

### GetArticleIdOk

`func (o *TopNArticlesTimeseriesItem) GetArticleIdOk() (*string, bool)`

GetArticleIdOk returns a tuple with the ArticleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArticleId

`func (o *TopNArticlesTimeseriesItem) SetArticleId(v string)`

SetArticleId sets ArticleId field to given value.

### HasArticleId

`func (o *TopNArticlesTimeseriesItem) HasArticleId() bool`

HasArticleId returns a boolean if a field has been set.

### SetArticleIdNil

`func (o *TopNArticlesTimeseriesItem) SetArticleIdNil(b bool)`

 SetArticleIdNil sets the value for ArticleId to be an explicit nil

### UnsetArticleId
`func (o *TopNArticlesTimeseriesItem) UnsetArticleId()`

UnsetArticleId ensures that no value is present for ArticleId, not even an explicit nil
### GetHitCount

`func (o *TopNArticlesTimeseriesItem) GetHitCount() int32`

GetHitCount returns the HitCount field if non-nil, zero value otherwise.

### GetHitCountOk

`func (o *TopNArticlesTimeseriesItem) GetHitCountOk() (*int32, bool)`

GetHitCountOk returns a tuple with the HitCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHitCount

`func (o *TopNArticlesTimeseriesItem) SetHitCount(v int32)`

SetHitCount sets HitCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


