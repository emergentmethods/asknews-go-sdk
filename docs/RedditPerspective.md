# RedditPerspective

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Sentiment** | [**Sentiment**](Sentiment.md) |  | 
**Relevant** | **bool** |  | 
**Summary** | **string** |  | 

## Methods

### NewRedditPerspective

`func NewRedditPerspective(sentiment Sentiment, relevant bool, summary string, ) *RedditPerspective`

NewRedditPerspective instantiates a new RedditPerspective object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRedditPerspectiveWithDefaults

`func NewRedditPerspectiveWithDefaults() *RedditPerspective`

NewRedditPerspectiveWithDefaults instantiates a new RedditPerspective object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSentiment

`func (o *RedditPerspective) GetSentiment() Sentiment`

GetSentiment returns the Sentiment field if non-nil, zero value otherwise.

### GetSentimentOk

`func (o *RedditPerspective) GetSentimentOk() (*Sentiment, bool)`

GetSentimentOk returns a tuple with the Sentiment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentiment

`func (o *RedditPerspective) SetSentiment(v Sentiment)`

SetSentiment sets Sentiment field to given value.


### GetRelevant

`func (o *RedditPerspective) GetRelevant() bool`

GetRelevant returns the Relevant field if non-nil, zero value otherwise.

### GetRelevantOk

`func (o *RedditPerspective) GetRelevantOk() (*bool, bool)`

GetRelevantOk returns a tuple with the Relevant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelevant

`func (o *RedditPerspective) SetRelevant(v bool)`

SetRelevant sets Relevant field to given value.


### GetSummary

`func (o *RedditPerspective) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *RedditPerspective) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *RedditPerspective) SetSummary(v string)`

SetSummary sets Summary field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


