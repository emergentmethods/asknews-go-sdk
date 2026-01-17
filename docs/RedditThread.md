# RedditThread

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Author** | **string** |  | 
**AuthorCommentKarma** | **int32** |  | 
**AuthorLinkKarma** | **int32** |  | 
**Body** | **string** |  | 
**Classification** | [**Classification**](Classification.md) |  | 
**Comments** | [**[]RedditComment**](RedditComment.md) |  | 
**CommentsCount** | **int32** |  | 
**Date** | **time.Time** |  | 
**Entities** | [**RedditEntities**](RedditEntities.md) |  | 
**Id** | **string** |  | 
**KeyTakeaways** | Pointer to **[]string** |  | [optional] [default to []]
**Keywords** | **[]string** |  | 
**Sentiment** | [**Sentiment**](Sentiment.md) |  | 
**SubredditName** | **string** |  | 
**SubredditUrl** | **string** |  | 
**Summary** | **string** |  | 
**Title** | **string** |  | 
**Topic** | **string** |  | 
**Upvotes** | **int32** |  | 
**Url** | **string** |  | 
**MainSpeculation** | Pointer to **string** |  | [optional] [default to ""]

## Methods

### NewRedditThread

`func NewRedditThread(author string, authorCommentKarma int32, authorLinkKarma int32, body string, classification Classification, comments []RedditComment, commentsCount int32, date time.Time, entities RedditEntities, id string, keywords []string, sentiment Sentiment, subredditName string, subredditUrl string, summary string, title string, topic string, upvotes int32, url string, ) *RedditThread`

NewRedditThread instantiates a new RedditThread object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRedditThreadWithDefaults

`func NewRedditThreadWithDefaults() *RedditThread`

NewRedditThreadWithDefaults instantiates a new RedditThread object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuthor

`func (o *RedditThread) GetAuthor() string`

GetAuthor returns the Author field if non-nil, zero value otherwise.

### GetAuthorOk

`func (o *RedditThread) GetAuthorOk() (*string, bool)`

GetAuthorOk returns a tuple with the Author field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthor

`func (o *RedditThread) SetAuthor(v string)`

SetAuthor sets Author field to given value.


### GetAuthorCommentKarma

`func (o *RedditThread) GetAuthorCommentKarma() int32`

GetAuthorCommentKarma returns the AuthorCommentKarma field if non-nil, zero value otherwise.

### GetAuthorCommentKarmaOk

`func (o *RedditThread) GetAuthorCommentKarmaOk() (*int32, bool)`

GetAuthorCommentKarmaOk returns a tuple with the AuthorCommentKarma field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorCommentKarma

`func (o *RedditThread) SetAuthorCommentKarma(v int32)`

SetAuthorCommentKarma sets AuthorCommentKarma field to given value.


### GetAuthorLinkKarma

`func (o *RedditThread) GetAuthorLinkKarma() int32`

GetAuthorLinkKarma returns the AuthorLinkKarma field if non-nil, zero value otherwise.

### GetAuthorLinkKarmaOk

`func (o *RedditThread) GetAuthorLinkKarmaOk() (*int32, bool)`

GetAuthorLinkKarmaOk returns a tuple with the AuthorLinkKarma field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorLinkKarma

`func (o *RedditThread) SetAuthorLinkKarma(v int32)`

SetAuthorLinkKarma sets AuthorLinkKarma field to given value.


### GetBody

`func (o *RedditThread) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *RedditThread) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *RedditThread) SetBody(v string)`

SetBody sets Body field to given value.


### GetClassification

`func (o *RedditThread) GetClassification() Classification`

GetClassification returns the Classification field if non-nil, zero value otherwise.

### GetClassificationOk

`func (o *RedditThread) GetClassificationOk() (*Classification, bool)`

GetClassificationOk returns a tuple with the Classification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClassification

`func (o *RedditThread) SetClassification(v Classification)`

SetClassification sets Classification field to given value.


### GetComments

`func (o *RedditThread) GetComments() []RedditComment`

GetComments returns the Comments field if non-nil, zero value otherwise.

### GetCommentsOk

`func (o *RedditThread) GetCommentsOk() (*[]RedditComment, bool)`

GetCommentsOk returns a tuple with the Comments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComments

`func (o *RedditThread) SetComments(v []RedditComment)`

SetComments sets Comments field to given value.


### GetCommentsCount

`func (o *RedditThread) GetCommentsCount() int32`

GetCommentsCount returns the CommentsCount field if non-nil, zero value otherwise.

### GetCommentsCountOk

`func (o *RedditThread) GetCommentsCountOk() (*int32, bool)`

GetCommentsCountOk returns a tuple with the CommentsCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommentsCount

`func (o *RedditThread) SetCommentsCount(v int32)`

SetCommentsCount sets CommentsCount field to given value.


### GetDate

`func (o *RedditThread) GetDate() time.Time`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *RedditThread) GetDateOk() (*time.Time, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *RedditThread) SetDate(v time.Time)`

SetDate sets Date field to given value.


### GetEntities

`func (o *RedditThread) GetEntities() RedditEntities`

GetEntities returns the Entities field if non-nil, zero value otherwise.

### GetEntitiesOk

`func (o *RedditThread) GetEntitiesOk() (*RedditEntities, bool)`

GetEntitiesOk returns a tuple with the Entities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntities

`func (o *RedditThread) SetEntities(v RedditEntities)`

SetEntities sets Entities field to given value.


### GetId

`func (o *RedditThread) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RedditThread) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RedditThread) SetId(v string)`

SetId sets Id field to given value.


### GetKeyTakeaways

`func (o *RedditThread) GetKeyTakeaways() []string`

GetKeyTakeaways returns the KeyTakeaways field if non-nil, zero value otherwise.

### GetKeyTakeawaysOk

`func (o *RedditThread) GetKeyTakeawaysOk() (*[]string, bool)`

GetKeyTakeawaysOk returns a tuple with the KeyTakeaways field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyTakeaways

`func (o *RedditThread) SetKeyTakeaways(v []string)`

SetKeyTakeaways sets KeyTakeaways field to given value.

### HasKeyTakeaways

`func (o *RedditThread) HasKeyTakeaways() bool`

HasKeyTakeaways returns a boolean if a field has been set.

### GetKeywords

`func (o *RedditThread) GetKeywords() []string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *RedditThread) GetKeywordsOk() (*[]string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *RedditThread) SetKeywords(v []string)`

SetKeywords sets Keywords field to given value.


### GetSentiment

`func (o *RedditThread) GetSentiment() Sentiment`

GetSentiment returns the Sentiment field if non-nil, zero value otherwise.

### GetSentimentOk

`func (o *RedditThread) GetSentimentOk() (*Sentiment, bool)`

GetSentimentOk returns a tuple with the Sentiment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentiment

`func (o *RedditThread) SetSentiment(v Sentiment)`

SetSentiment sets Sentiment field to given value.


### GetSubredditName

`func (o *RedditThread) GetSubredditName() string`

GetSubredditName returns the SubredditName field if non-nil, zero value otherwise.

### GetSubredditNameOk

`func (o *RedditThread) GetSubredditNameOk() (*string, bool)`

GetSubredditNameOk returns a tuple with the SubredditName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubredditName

`func (o *RedditThread) SetSubredditName(v string)`

SetSubredditName sets SubredditName field to given value.


### GetSubredditUrl

`func (o *RedditThread) GetSubredditUrl() string`

GetSubredditUrl returns the SubredditUrl field if non-nil, zero value otherwise.

### GetSubredditUrlOk

`func (o *RedditThread) GetSubredditUrlOk() (*string, bool)`

GetSubredditUrlOk returns a tuple with the SubredditUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubredditUrl

`func (o *RedditThread) SetSubredditUrl(v string)`

SetSubredditUrl sets SubredditUrl field to given value.


### GetSummary

`func (o *RedditThread) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *RedditThread) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *RedditThread) SetSummary(v string)`

SetSummary sets Summary field to given value.


### GetTitle

`func (o *RedditThread) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *RedditThread) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *RedditThread) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetTopic

`func (o *RedditThread) GetTopic() string`

GetTopic returns the Topic field if non-nil, zero value otherwise.

### GetTopicOk

`func (o *RedditThread) GetTopicOk() (*string, bool)`

GetTopicOk returns a tuple with the Topic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopic

`func (o *RedditThread) SetTopic(v string)`

SetTopic sets Topic field to given value.


### GetUpvotes

`func (o *RedditThread) GetUpvotes() int32`

GetUpvotes returns the Upvotes field if non-nil, zero value otherwise.

### GetUpvotesOk

`func (o *RedditThread) GetUpvotesOk() (*int32, bool)`

GetUpvotesOk returns a tuple with the Upvotes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpvotes

`func (o *RedditThread) SetUpvotes(v int32)`

SetUpvotes sets Upvotes field to given value.


### GetUrl

`func (o *RedditThread) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *RedditThread) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *RedditThread) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetMainSpeculation

`func (o *RedditThread) GetMainSpeculation() string`

GetMainSpeculation returns the MainSpeculation field if non-nil, zero value otherwise.

### GetMainSpeculationOk

`func (o *RedditThread) GetMainSpeculationOk() (*string, bool)`

GetMainSpeculationOk returns a tuple with the MainSpeculation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMainSpeculation

`func (o *RedditThread) SetMainSpeculation(v string)`

SetMainSpeculation sets MainSpeculation field to given value.

### HasMainSpeculation

`func (o *RedditThread) HasMainSpeculation() bool`

HasMainSpeculation returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


