# DomainQueryItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Query** | **string** |  | 
**Coords** | **[]interface{}** |  | 
**NHits** | **int32** |  | 
**Articles** | [**[]DomainQueryArticleItem**](DomainQueryArticleItem.md) |  | 

## Methods

### NewDomainQueryItem

`func NewDomainQueryItem(query string, coords []interface{}, nHits int32, articles []DomainQueryArticleItem, ) *DomainQueryItem`

NewDomainQueryItem instantiates a new DomainQueryItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainQueryItemWithDefaults

`func NewDomainQueryItemWithDefaults() *DomainQueryItem`

NewDomainQueryItemWithDefaults instantiates a new DomainQueryItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuery

`func (o *DomainQueryItem) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *DomainQueryItem) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *DomainQueryItem) SetQuery(v string)`

SetQuery sets Query field to given value.


### GetCoords

`func (o *DomainQueryItem) GetCoords() []interface{}`

GetCoords returns the Coords field if non-nil, zero value otherwise.

### GetCoordsOk

`func (o *DomainQueryItem) GetCoordsOk() (*[]interface{}, bool)`

GetCoordsOk returns a tuple with the Coords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoords

`func (o *DomainQueryItem) SetCoords(v []interface{})`

SetCoords sets Coords field to given value.


### GetNHits

`func (o *DomainQueryItem) GetNHits() int32`

GetNHits returns the NHits field if non-nil, zero value otherwise.

### GetNHitsOk

`func (o *DomainQueryItem) GetNHitsOk() (*int32, bool)`

GetNHitsOk returns a tuple with the NHits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNHits

`func (o *DomainQueryItem) SetNHits(v int32)`

SetNHits sets NHits field to given value.


### GetArticles

`func (o *DomainQueryItem) GetArticles() []DomainQueryArticleItem`

GetArticles returns the Articles field if non-nil, zero value otherwise.

### GetArticlesOk

`func (o *DomainQueryItem) GetArticlesOk() (*[]DomainQueryArticleItem, bool)`

GetArticlesOk returns a tuple with the Articles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArticles

`func (o *DomainQueryItem) SetArticles(v []DomainQueryArticleItem)`

SetArticles sets Articles field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


