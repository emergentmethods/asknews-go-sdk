# BodyBuildGraph

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Query** | Pointer to **string** | Query string that can be any phrase, keyword, question, or paragraph. If method&#x3D;&#39;nl&#39;, then this will be used as a natural language query. If method&#x3D;&#39;kw&#39;, then this will be used as a direct keyword query. | [optional] [default to ""]
**ReturnArticles** | Pointer to **bool** | Whether to return articles or not. | [optional] [default to false]
**MinClusterProbability** | Pointer to **float32** | Minimum cluster probability to use for disambiguation | [optional] [default to 0.9]
**GeoDisambiguation** | Pointer to **bool** | Whether to use geo disambiguation or not. | [optional] [default to false]
**FilterParams** | Pointer to **map[string]interface{}** |  | [optional] 
**ConstrainedDisambiguations** | Pointer to **[]map[string]interface{}** |  | [optional] 
**DocsUpload** | Pointer to **[]map[string]interface{}** |  | [optional] 
**VisualizeWith** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewBodyBuildGraph

`func NewBodyBuildGraph() *BodyBuildGraph`

NewBodyBuildGraph instantiates a new BodyBuildGraph object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBodyBuildGraphWithDefaults

`func NewBodyBuildGraphWithDefaults() *BodyBuildGraph`

NewBodyBuildGraphWithDefaults instantiates a new BodyBuildGraph object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuery

`func (o *BodyBuildGraph) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *BodyBuildGraph) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *BodyBuildGraph) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *BodyBuildGraph) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### GetReturnArticles

`func (o *BodyBuildGraph) GetReturnArticles() bool`

GetReturnArticles returns the ReturnArticles field if non-nil, zero value otherwise.

### GetReturnArticlesOk

`func (o *BodyBuildGraph) GetReturnArticlesOk() (*bool, bool)`

GetReturnArticlesOk returns a tuple with the ReturnArticles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnArticles

`func (o *BodyBuildGraph) SetReturnArticles(v bool)`

SetReturnArticles sets ReturnArticles field to given value.

### HasReturnArticles

`func (o *BodyBuildGraph) HasReturnArticles() bool`

HasReturnArticles returns a boolean if a field has been set.

### GetMinClusterProbability

`func (o *BodyBuildGraph) GetMinClusterProbability() float32`

GetMinClusterProbability returns the MinClusterProbability field if non-nil, zero value otherwise.

### GetMinClusterProbabilityOk

`func (o *BodyBuildGraph) GetMinClusterProbabilityOk() (*float32, bool)`

GetMinClusterProbabilityOk returns a tuple with the MinClusterProbability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinClusterProbability

`func (o *BodyBuildGraph) SetMinClusterProbability(v float32)`

SetMinClusterProbability sets MinClusterProbability field to given value.

### HasMinClusterProbability

`func (o *BodyBuildGraph) HasMinClusterProbability() bool`

HasMinClusterProbability returns a boolean if a field has been set.

### GetGeoDisambiguation

`func (o *BodyBuildGraph) GetGeoDisambiguation() bool`

GetGeoDisambiguation returns the GeoDisambiguation field if non-nil, zero value otherwise.

### GetGeoDisambiguationOk

`func (o *BodyBuildGraph) GetGeoDisambiguationOk() (*bool, bool)`

GetGeoDisambiguationOk returns a tuple with the GeoDisambiguation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeoDisambiguation

`func (o *BodyBuildGraph) SetGeoDisambiguation(v bool)`

SetGeoDisambiguation sets GeoDisambiguation field to given value.

### HasGeoDisambiguation

`func (o *BodyBuildGraph) HasGeoDisambiguation() bool`

HasGeoDisambiguation returns a boolean if a field has been set.

### GetFilterParams

`func (o *BodyBuildGraph) GetFilterParams() map[string]interface{}`

GetFilterParams returns the FilterParams field if non-nil, zero value otherwise.

### GetFilterParamsOk

`func (o *BodyBuildGraph) GetFilterParamsOk() (*map[string]interface{}, bool)`

GetFilterParamsOk returns a tuple with the FilterParams field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilterParams

`func (o *BodyBuildGraph) SetFilterParams(v map[string]interface{})`

SetFilterParams sets FilterParams field to given value.

### HasFilterParams

`func (o *BodyBuildGraph) HasFilterParams() bool`

HasFilterParams returns a boolean if a field has been set.

### SetFilterParamsNil

`func (o *BodyBuildGraph) SetFilterParamsNil(b bool)`

 SetFilterParamsNil sets the value for FilterParams to be an explicit nil

### UnsetFilterParams
`func (o *BodyBuildGraph) UnsetFilterParams()`

UnsetFilterParams ensures that no value is present for FilterParams, not even an explicit nil
### GetConstrainedDisambiguations

`func (o *BodyBuildGraph) GetConstrainedDisambiguations() []*map[string]interface{}`

GetConstrainedDisambiguations returns the ConstrainedDisambiguations field if non-nil, zero value otherwise.

### GetConstrainedDisambiguationsOk

`func (o *BodyBuildGraph) GetConstrainedDisambiguationsOk() (*[]*map[string]interface{}, bool)`

GetConstrainedDisambiguationsOk returns a tuple with the ConstrainedDisambiguations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConstrainedDisambiguations

`func (o *BodyBuildGraph) SetConstrainedDisambiguations(v []*map[string]interface{})`

SetConstrainedDisambiguations sets ConstrainedDisambiguations field to given value.

### HasConstrainedDisambiguations

`func (o *BodyBuildGraph) HasConstrainedDisambiguations() bool`

HasConstrainedDisambiguations returns a boolean if a field has been set.

### SetConstrainedDisambiguationsNil

`func (o *BodyBuildGraph) SetConstrainedDisambiguationsNil(b bool)`

 SetConstrainedDisambiguationsNil sets the value for ConstrainedDisambiguations to be an explicit nil

### UnsetConstrainedDisambiguations
`func (o *BodyBuildGraph) UnsetConstrainedDisambiguations()`

UnsetConstrainedDisambiguations ensures that no value is present for ConstrainedDisambiguations, not even an explicit nil
### GetDocsUpload

`func (o *BodyBuildGraph) GetDocsUpload() []map[string]interface{}`

GetDocsUpload returns the DocsUpload field if non-nil, zero value otherwise.

### GetDocsUploadOk

`func (o *BodyBuildGraph) GetDocsUploadOk() (*[]map[string]interface{}, bool)`

GetDocsUploadOk returns a tuple with the DocsUpload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocsUpload

`func (o *BodyBuildGraph) SetDocsUpload(v []map[string]interface{})`

SetDocsUpload sets DocsUpload field to given value.

### HasDocsUpload

`func (o *BodyBuildGraph) HasDocsUpload() bool`

HasDocsUpload returns a boolean if a field has been set.

### SetDocsUploadNil

`func (o *BodyBuildGraph) SetDocsUploadNil(b bool)`

 SetDocsUploadNil sets the value for DocsUpload to be an explicit nil

### UnsetDocsUpload
`func (o *BodyBuildGraph) UnsetDocsUpload()`

UnsetDocsUpload ensures that no value is present for DocsUpload, not even an explicit nil
### GetVisualizeWith

`func (o *BodyBuildGraph) GetVisualizeWith() string`

GetVisualizeWith returns the VisualizeWith field if non-nil, zero value otherwise.

### GetVisualizeWithOk

`func (o *BodyBuildGraph) GetVisualizeWithOk() (*string, bool)`

GetVisualizeWithOk returns a tuple with the VisualizeWith field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisualizeWith

`func (o *BodyBuildGraph) SetVisualizeWith(v string)`

SetVisualizeWith sets VisualizeWith field to given value.

### HasVisualizeWith

`func (o *BodyBuildGraph) HasVisualizeWith() bool`

HasVisualizeWith returns a boolean if a field has been set.

### SetVisualizeWithNil

`func (o *BodyBuildGraph) SetVisualizeWithNil(b bool)`

 SetVisualizeWithNil sets the value for VisualizeWith to be an explicit nil

### UnsetVisualizeWith
`func (o *BodyBuildGraph) UnsetVisualizeWith()`

UnsetVisualizeWith ensures that no value is present for VisualizeWith, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


