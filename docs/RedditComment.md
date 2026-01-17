# RedditComment

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Author** | **string** |  | 
**Body** | **string** |  | 
**Date** | **time.Time** |  | 
**Upvotes** | **int32** |  | 

## Methods

### NewRedditComment

`func NewRedditComment(author string, body string, date time.Time, upvotes int32, ) *RedditComment`

NewRedditComment instantiates a new RedditComment object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRedditCommentWithDefaults

`func NewRedditCommentWithDefaults() *RedditComment`

NewRedditCommentWithDefaults instantiates a new RedditComment object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuthor

`func (o *RedditComment) GetAuthor() string`

GetAuthor returns the Author field if non-nil, zero value otherwise.

### GetAuthorOk

`func (o *RedditComment) GetAuthorOk() (*string, bool)`

GetAuthorOk returns a tuple with the Author field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthor

`func (o *RedditComment) SetAuthor(v string)`

SetAuthor sets Author field to given value.


### GetBody

`func (o *RedditComment) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *RedditComment) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *RedditComment) SetBody(v string)`

SetBody sets Body field to given value.


### GetDate

`func (o *RedditComment) GetDate() time.Time`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *RedditComment) GetDateOk() (*time.Time, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *RedditComment) SetDate(v time.Time)`

SetDate sets Date field to given value.


### GetUpvotes

`func (o *RedditComment) GetUpvotes() int32`

GetUpvotes returns the Upvotes field if non-nil, zero value otherwise.

### GetUpvotesOk

`func (o *RedditComment) GetUpvotesOk() (*int32, bool)`

GetUpvotesOk returns a tuple with the Upvotes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpvotes

`func (o *RedditComment) SetUpvotes(v int32)`

SetUpvotes sets Upvotes field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


