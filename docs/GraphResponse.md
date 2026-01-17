# GraphResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FullGraph** | **map[string]interface{}** |  | 
**Disambiguations** | **[]map[string]interface{}** |  | 
**Articles** | Pointer to [**[]SearchResponseDictItem**](SearchResponseDictItem.md) |  | [optional] 
**Query** | Pointer to **NullableString** |  | [optional] 
**DocsEnhanced** | Pointer to **[]map[string]interface{}** |  | [optional] 
**TriplesUrl** | Pointer to **NullableString** |  | [optional] 
**VisualizeUrl** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewGraphResponse

`func NewGraphResponse(fullGraph map[string]interface{}, disambiguations []*map[string]interface{}, ) *GraphResponse`

NewGraphResponse instantiates a new GraphResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGraphResponseWithDefaults

`func NewGraphResponseWithDefaults() *GraphResponse`

NewGraphResponseWithDefaults instantiates a new GraphResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFullGraph

`func (o *GraphResponse) GetFullGraph() map[string]interface{}`

GetFullGraph returns the FullGraph field if non-nil, zero value otherwise.

### GetFullGraphOk

`func (o *GraphResponse) GetFullGraphOk() (*map[string]interface{}, bool)`

GetFullGraphOk returns a tuple with the FullGraph field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFullGraph

`func (o *GraphResponse) SetFullGraph(v map[string]interface{})`

SetFullGraph sets FullGraph field to given value.


### GetDisambiguations

`func (o *GraphResponse) GetDisambiguations() []*map[string]interface{}`

GetDisambiguations returns the Disambiguations field if non-nil, zero value otherwise.

### GetDisambiguationsOk

`func (o *GraphResponse) GetDisambiguationsOk() (*[]*map[string]interface{}, bool)`

GetDisambiguationsOk returns a tuple with the Disambiguations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisambiguations

`func (o *GraphResponse) SetDisambiguations(v []*map[string]interface{})`

SetDisambiguations sets Disambiguations field to given value.


### GetArticles

`func (o *GraphResponse) GetArticles() []SearchResponseDictItem`

GetArticles returns the Articles field if non-nil, zero value otherwise.

### GetArticlesOk

`func (o *GraphResponse) GetArticlesOk() (*[]SearchResponseDictItem, bool)`

GetArticlesOk returns a tuple with the Articles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArticles

`func (o *GraphResponse) SetArticles(v []SearchResponseDictItem)`

SetArticles sets Articles field to given value.

### HasArticles

`func (o *GraphResponse) HasArticles() bool`

HasArticles returns a boolean if a field has been set.

### SetArticlesNil

`func (o *GraphResponse) SetArticlesNil(b bool)`

 SetArticlesNil sets the value for Articles to be an explicit nil

### UnsetArticles
`func (o *GraphResponse) UnsetArticles()`

UnsetArticles ensures that no value is present for Articles, not even an explicit nil
### GetQuery

`func (o *GraphResponse) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *GraphResponse) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *GraphResponse) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *GraphResponse) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### SetQueryNil

`func (o *GraphResponse) SetQueryNil(b bool)`

 SetQueryNil sets the value for Query to be an explicit nil

### UnsetQuery
`func (o *GraphResponse) UnsetQuery()`

UnsetQuery ensures that no value is present for Query, not even an explicit nil
### GetDocsEnhanced

`func (o *GraphResponse) GetDocsEnhanced() []map[string]interface{}`

GetDocsEnhanced returns the DocsEnhanced field if non-nil, zero value otherwise.

### GetDocsEnhancedOk

`func (o *GraphResponse) GetDocsEnhancedOk() (*[]map[string]interface{}, bool)`

GetDocsEnhancedOk returns a tuple with the DocsEnhanced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocsEnhanced

`func (o *GraphResponse) SetDocsEnhanced(v []map[string]interface{})`

SetDocsEnhanced sets DocsEnhanced field to given value.

### HasDocsEnhanced

`func (o *GraphResponse) HasDocsEnhanced() bool`

HasDocsEnhanced returns a boolean if a field has been set.

### SetDocsEnhancedNil

`func (o *GraphResponse) SetDocsEnhancedNil(b bool)`

 SetDocsEnhancedNil sets the value for DocsEnhanced to be an explicit nil

### UnsetDocsEnhanced
`func (o *GraphResponse) UnsetDocsEnhanced()`

UnsetDocsEnhanced ensures that no value is present for DocsEnhanced, not even an explicit nil
### GetTriplesUrl

`func (o *GraphResponse) GetTriplesUrl() string`

GetTriplesUrl returns the TriplesUrl field if non-nil, zero value otherwise.

### GetTriplesUrlOk

`func (o *GraphResponse) GetTriplesUrlOk() (*string, bool)`

GetTriplesUrlOk returns a tuple with the TriplesUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriplesUrl

`func (o *GraphResponse) SetTriplesUrl(v string)`

SetTriplesUrl sets TriplesUrl field to given value.

### HasTriplesUrl

`func (o *GraphResponse) HasTriplesUrl() bool`

HasTriplesUrl returns a boolean if a field has been set.

### SetTriplesUrlNil

`func (o *GraphResponse) SetTriplesUrlNil(b bool)`

 SetTriplesUrlNil sets the value for TriplesUrl to be an explicit nil

### UnsetTriplesUrl
`func (o *GraphResponse) UnsetTriplesUrl()`

UnsetTriplesUrl ensures that no value is present for TriplesUrl, not even an explicit nil
### GetVisualizeUrl

`func (o *GraphResponse) GetVisualizeUrl() string`

GetVisualizeUrl returns the VisualizeUrl field if non-nil, zero value otherwise.

### GetVisualizeUrlOk

`func (o *GraphResponse) GetVisualizeUrlOk() (*string, bool)`

GetVisualizeUrlOk returns a tuple with the VisualizeUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisualizeUrl

`func (o *GraphResponse) SetVisualizeUrl(v string)`

SetVisualizeUrl sets VisualizeUrl field to given value.

### HasVisualizeUrl

`func (o *GraphResponse) HasVisualizeUrl() bool`

HasVisualizeUrl returns a boolean if a field has been set.

### SetVisualizeUrlNil

`func (o *GraphResponse) SetVisualizeUrlNil(b bool)`

 SetVisualizeUrlNil sets the value for VisualizeUrl to be an explicit nil

### UnsetVisualizeUrl
`func (o *GraphResponse) UnsetVisualizeUrl()`

UnsetVisualizeUrl ensures that no value is present for VisualizeUrl, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


