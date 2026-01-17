# Article

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ArticleUrl** | **string** |  | 
**ArticleId** | **string** |  | 
**Classification** | [**Classification**](Classification.md) |  | 
**Country** | **string** |  | 
**SourceId** | **string** |  | 
**PageRank** | **int32** |  | 
**DomainUrl** | **string** |  | 
**EngTitle** | **string** |  | 
**Entities** | [**Entities**](Entities.md) |  | 
**ImageUrl** | Pointer to **NullableString** |  | [optional] 
**Keywords** | **[]string** |  | 
**Language** | **string** |  | 
**PubDate** | **time.Time** |  | 
**Summary** | **string** |  | 
**KeyPoints** | Pointer to **[]string** |  | [optional] 
**Title** | **string** |  | 
**Sentiment** | **int32** |  | 
**CentroidDistance** | **float32** |  | 
**ClusterProbability** | **float32** |  | 
**MarkdownCitation** | Pointer to **string** |  | [optional] [default to ""]
**Provocative** | Pointer to **string** |  | [optional] [default to "unknown"]
**ReportingVoice** | Pointer to [**ReportingVoice1**](ReportingVoice1.md) |  | [optional] [default to Unknown]
**EntityRelationGraph** | Pointer to [**NullableAsknewsApiSchemaV1CommonGraphRelationships**](AsknewsApiSchemaV1CommonGraphRelationships.md) |  | [optional] 
**GeoCoordinates** | Pointer to [**map[string]GeoCoordinate**](GeoCoordinate.md) |  | [optional] 
**Continent** | Pointer to **NullableString** |  | [optional] 
**Assets** | Pointer to [**NullableAssets**](Assets.md) |  | [optional] 
**SocialEmbeds** | Pointer to **[]string** |  | [optional] 
**Bias** | Pointer to **NullableString** |  | [optional] 
**Authors** | Pointer to [**[]Author**](Author.md) |  | [optional] 
**FullText** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewArticle

`func NewArticle(articleUrl string, articleId string, classification Classification, country string, sourceId string, pageRank int32, domainUrl string, engTitle string, entities Entities, keywords []string, language string, pubDate time.Time, summary string, title string, sentiment int32, centroidDistance float32, clusterProbability float32, ) *Article`

NewArticle instantiates a new Article object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewArticleWithDefaults

`func NewArticleWithDefaults() *Article`

NewArticleWithDefaults instantiates a new Article object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArticleUrl

`func (o *Article) GetArticleUrl() string`

GetArticleUrl returns the ArticleUrl field if non-nil, zero value otherwise.

### GetArticleUrlOk

`func (o *Article) GetArticleUrlOk() (*string, bool)`

GetArticleUrlOk returns a tuple with the ArticleUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArticleUrl

`func (o *Article) SetArticleUrl(v string)`

SetArticleUrl sets ArticleUrl field to given value.


### GetArticleId

`func (o *Article) GetArticleId() string`

GetArticleId returns the ArticleId field if non-nil, zero value otherwise.

### GetArticleIdOk

`func (o *Article) GetArticleIdOk() (*string, bool)`

GetArticleIdOk returns a tuple with the ArticleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArticleId

`func (o *Article) SetArticleId(v string)`

SetArticleId sets ArticleId field to given value.


### GetClassification

`func (o *Article) GetClassification() Classification`

GetClassification returns the Classification field if non-nil, zero value otherwise.

### GetClassificationOk

`func (o *Article) GetClassificationOk() (*Classification, bool)`

GetClassificationOk returns a tuple with the Classification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClassification

`func (o *Article) SetClassification(v Classification)`

SetClassification sets Classification field to given value.


### GetCountry

`func (o *Article) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *Article) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *Article) SetCountry(v string)`

SetCountry sets Country field to given value.


### GetSourceId

`func (o *Article) GetSourceId() string`

GetSourceId returns the SourceId field if non-nil, zero value otherwise.

### GetSourceIdOk

`func (o *Article) GetSourceIdOk() (*string, bool)`

GetSourceIdOk returns a tuple with the SourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceId

`func (o *Article) SetSourceId(v string)`

SetSourceId sets SourceId field to given value.


### GetPageRank

`func (o *Article) GetPageRank() int32`

GetPageRank returns the PageRank field if non-nil, zero value otherwise.

### GetPageRankOk

`func (o *Article) GetPageRankOk() (*int32, bool)`

GetPageRankOk returns a tuple with the PageRank field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageRank

`func (o *Article) SetPageRank(v int32)`

SetPageRank sets PageRank field to given value.


### GetDomainUrl

`func (o *Article) GetDomainUrl() string`

GetDomainUrl returns the DomainUrl field if non-nil, zero value otherwise.

### GetDomainUrlOk

`func (o *Article) GetDomainUrlOk() (*string, bool)`

GetDomainUrlOk returns a tuple with the DomainUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainUrl

`func (o *Article) SetDomainUrl(v string)`

SetDomainUrl sets DomainUrl field to given value.


### GetEngTitle

`func (o *Article) GetEngTitle() string`

GetEngTitle returns the EngTitle field if non-nil, zero value otherwise.

### GetEngTitleOk

`func (o *Article) GetEngTitleOk() (*string, bool)`

GetEngTitleOk returns a tuple with the EngTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngTitle

`func (o *Article) SetEngTitle(v string)`

SetEngTitle sets EngTitle field to given value.


### GetEntities

`func (o *Article) GetEntities() Entities`

GetEntities returns the Entities field if non-nil, zero value otherwise.

### GetEntitiesOk

`func (o *Article) GetEntitiesOk() (*Entities, bool)`

GetEntitiesOk returns a tuple with the Entities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntities

`func (o *Article) SetEntities(v Entities)`

SetEntities sets Entities field to given value.


### GetImageUrl

`func (o *Article) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *Article) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *Article) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *Article) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### SetImageUrlNil

`func (o *Article) SetImageUrlNil(b bool)`

 SetImageUrlNil sets the value for ImageUrl to be an explicit nil

### UnsetImageUrl
`func (o *Article) UnsetImageUrl()`

UnsetImageUrl ensures that no value is present for ImageUrl, not even an explicit nil
### GetKeywords

`func (o *Article) GetKeywords() []string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *Article) GetKeywordsOk() (*[]string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *Article) SetKeywords(v []string)`

SetKeywords sets Keywords field to given value.


### GetLanguage

`func (o *Article) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *Article) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *Article) SetLanguage(v string)`

SetLanguage sets Language field to given value.


### GetPubDate

`func (o *Article) GetPubDate() time.Time`

GetPubDate returns the PubDate field if non-nil, zero value otherwise.

### GetPubDateOk

`func (o *Article) GetPubDateOk() (*time.Time, bool)`

GetPubDateOk returns a tuple with the PubDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPubDate

`func (o *Article) SetPubDate(v time.Time)`

SetPubDate sets PubDate field to given value.


### GetSummary

`func (o *Article) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *Article) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *Article) SetSummary(v string)`

SetSummary sets Summary field to given value.


### GetKeyPoints

`func (o *Article) GetKeyPoints() []string`

GetKeyPoints returns the KeyPoints field if non-nil, zero value otherwise.

### GetKeyPointsOk

`func (o *Article) GetKeyPointsOk() (*[]string, bool)`

GetKeyPointsOk returns a tuple with the KeyPoints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyPoints

`func (o *Article) SetKeyPoints(v []string)`

SetKeyPoints sets KeyPoints field to given value.

### HasKeyPoints

`func (o *Article) HasKeyPoints() bool`

HasKeyPoints returns a boolean if a field has been set.

### SetKeyPointsNil

`func (o *Article) SetKeyPointsNil(b bool)`

 SetKeyPointsNil sets the value for KeyPoints to be an explicit nil

### UnsetKeyPoints
`func (o *Article) UnsetKeyPoints()`

UnsetKeyPoints ensures that no value is present for KeyPoints, not even an explicit nil
### GetTitle

`func (o *Article) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Article) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Article) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetSentiment

`func (o *Article) GetSentiment() int32`

GetSentiment returns the Sentiment field if non-nil, zero value otherwise.

### GetSentimentOk

`func (o *Article) GetSentimentOk() (*int32, bool)`

GetSentimentOk returns a tuple with the Sentiment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentiment

`func (o *Article) SetSentiment(v int32)`

SetSentiment sets Sentiment field to given value.


### GetCentroidDistance

`func (o *Article) GetCentroidDistance() float32`

GetCentroidDistance returns the CentroidDistance field if non-nil, zero value otherwise.

### GetCentroidDistanceOk

`func (o *Article) GetCentroidDistanceOk() (*float32, bool)`

GetCentroidDistanceOk returns a tuple with the CentroidDistance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCentroidDistance

`func (o *Article) SetCentroidDistance(v float32)`

SetCentroidDistance sets CentroidDistance field to given value.


### GetClusterProbability

`func (o *Article) GetClusterProbability() float32`

GetClusterProbability returns the ClusterProbability field if non-nil, zero value otherwise.

### GetClusterProbabilityOk

`func (o *Article) GetClusterProbabilityOk() (*float32, bool)`

GetClusterProbabilityOk returns a tuple with the ClusterProbability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterProbability

`func (o *Article) SetClusterProbability(v float32)`

SetClusterProbability sets ClusterProbability field to given value.


### GetMarkdownCitation

`func (o *Article) GetMarkdownCitation() string`

GetMarkdownCitation returns the MarkdownCitation field if non-nil, zero value otherwise.

### GetMarkdownCitationOk

`func (o *Article) GetMarkdownCitationOk() (*string, bool)`

GetMarkdownCitationOk returns a tuple with the MarkdownCitation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarkdownCitation

`func (o *Article) SetMarkdownCitation(v string)`

SetMarkdownCitation sets MarkdownCitation field to given value.

### HasMarkdownCitation

`func (o *Article) HasMarkdownCitation() bool`

HasMarkdownCitation returns a boolean if a field has been set.

### GetProvocative

`func (o *Article) GetProvocative() string`

GetProvocative returns the Provocative field if non-nil, zero value otherwise.

### GetProvocativeOk

`func (o *Article) GetProvocativeOk() (*string, bool)`

GetProvocativeOk returns a tuple with the Provocative field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvocative

`func (o *Article) SetProvocative(v string)`

SetProvocative sets Provocative field to given value.

### HasProvocative

`func (o *Article) HasProvocative() bool`

HasProvocative returns a boolean if a field has been set.

### GetReportingVoice

`func (o *Article) GetReportingVoice() ReportingVoice1`

GetReportingVoice returns the ReportingVoice field if non-nil, zero value otherwise.

### GetReportingVoiceOk

`func (o *Article) GetReportingVoiceOk() (*ReportingVoice1, bool)`

GetReportingVoiceOk returns a tuple with the ReportingVoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportingVoice

`func (o *Article) SetReportingVoice(v ReportingVoice1)`

SetReportingVoice sets ReportingVoice field to given value.

### HasReportingVoice

`func (o *Article) HasReportingVoice() bool`

HasReportingVoice returns a boolean if a field has been set.

### GetEntityRelationGraph

`func (o *Article) GetEntityRelationGraph() AsknewsApiSchemaV1CommonGraphRelationships`

GetEntityRelationGraph returns the EntityRelationGraph field if non-nil, zero value otherwise.

### GetEntityRelationGraphOk

`func (o *Article) GetEntityRelationGraphOk() (*AsknewsApiSchemaV1CommonGraphRelationships, bool)`

GetEntityRelationGraphOk returns a tuple with the EntityRelationGraph field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityRelationGraph

`func (o *Article) SetEntityRelationGraph(v AsknewsApiSchemaV1CommonGraphRelationships)`

SetEntityRelationGraph sets EntityRelationGraph field to given value.

### HasEntityRelationGraph

`func (o *Article) HasEntityRelationGraph() bool`

HasEntityRelationGraph returns a boolean if a field has been set.

### SetEntityRelationGraphNil

`func (o *Article) SetEntityRelationGraphNil(b bool)`

 SetEntityRelationGraphNil sets the value for EntityRelationGraph to be an explicit nil

### UnsetEntityRelationGraph
`func (o *Article) UnsetEntityRelationGraph()`

UnsetEntityRelationGraph ensures that no value is present for EntityRelationGraph, not even an explicit nil
### GetGeoCoordinates

`func (o *Article) GetGeoCoordinates() map[string]GeoCoordinate`

GetGeoCoordinates returns the GeoCoordinates field if non-nil, zero value otherwise.

### GetGeoCoordinatesOk

`func (o *Article) GetGeoCoordinatesOk() (*map[string]GeoCoordinate, bool)`

GetGeoCoordinatesOk returns a tuple with the GeoCoordinates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeoCoordinates

`func (o *Article) SetGeoCoordinates(v map[string]GeoCoordinate)`

SetGeoCoordinates sets GeoCoordinates field to given value.

### HasGeoCoordinates

`func (o *Article) HasGeoCoordinates() bool`

HasGeoCoordinates returns a boolean if a field has been set.

### SetGeoCoordinatesNil

`func (o *Article) SetGeoCoordinatesNil(b bool)`

 SetGeoCoordinatesNil sets the value for GeoCoordinates to be an explicit nil

### UnsetGeoCoordinates
`func (o *Article) UnsetGeoCoordinates()`

UnsetGeoCoordinates ensures that no value is present for GeoCoordinates, not even an explicit nil
### GetContinent

`func (o *Article) GetContinent() string`

GetContinent returns the Continent field if non-nil, zero value otherwise.

### GetContinentOk

`func (o *Article) GetContinentOk() (*string, bool)`

GetContinentOk returns a tuple with the Continent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContinent

`func (o *Article) SetContinent(v string)`

SetContinent sets Continent field to given value.

### HasContinent

`func (o *Article) HasContinent() bool`

HasContinent returns a boolean if a field has been set.

### SetContinentNil

`func (o *Article) SetContinentNil(b bool)`

 SetContinentNil sets the value for Continent to be an explicit nil

### UnsetContinent
`func (o *Article) UnsetContinent()`

UnsetContinent ensures that no value is present for Continent, not even an explicit nil
### GetAssets

`func (o *Article) GetAssets() Assets`

GetAssets returns the Assets field if non-nil, zero value otherwise.

### GetAssetsOk

`func (o *Article) GetAssetsOk() (*Assets, bool)`

GetAssetsOk returns a tuple with the Assets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssets

`func (o *Article) SetAssets(v Assets)`

SetAssets sets Assets field to given value.

### HasAssets

`func (o *Article) HasAssets() bool`

HasAssets returns a boolean if a field has been set.

### SetAssetsNil

`func (o *Article) SetAssetsNil(b bool)`

 SetAssetsNil sets the value for Assets to be an explicit nil

### UnsetAssets
`func (o *Article) UnsetAssets()`

UnsetAssets ensures that no value is present for Assets, not even an explicit nil
### GetSocialEmbeds

`func (o *Article) GetSocialEmbeds() []string`

GetSocialEmbeds returns the SocialEmbeds field if non-nil, zero value otherwise.

### GetSocialEmbedsOk

`func (o *Article) GetSocialEmbedsOk() (*[]string, bool)`

GetSocialEmbedsOk returns a tuple with the SocialEmbeds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSocialEmbeds

`func (o *Article) SetSocialEmbeds(v []string)`

SetSocialEmbeds sets SocialEmbeds field to given value.

### HasSocialEmbeds

`func (o *Article) HasSocialEmbeds() bool`

HasSocialEmbeds returns a boolean if a field has been set.

### SetSocialEmbedsNil

`func (o *Article) SetSocialEmbedsNil(b bool)`

 SetSocialEmbedsNil sets the value for SocialEmbeds to be an explicit nil

### UnsetSocialEmbeds
`func (o *Article) UnsetSocialEmbeds()`

UnsetSocialEmbeds ensures that no value is present for SocialEmbeds, not even an explicit nil
### GetBias

`func (o *Article) GetBias() string`

GetBias returns the Bias field if non-nil, zero value otherwise.

### GetBiasOk

`func (o *Article) GetBiasOk() (*string, bool)`

GetBiasOk returns a tuple with the Bias field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBias

`func (o *Article) SetBias(v string)`

SetBias sets Bias field to given value.

### HasBias

`func (o *Article) HasBias() bool`

HasBias returns a boolean if a field has been set.

### SetBiasNil

`func (o *Article) SetBiasNil(b bool)`

 SetBiasNil sets the value for Bias to be an explicit nil

### UnsetBias
`func (o *Article) UnsetBias()`

UnsetBias ensures that no value is present for Bias, not even an explicit nil
### GetAuthors

`func (o *Article) GetAuthors() []Author`

GetAuthors returns the Authors field if non-nil, zero value otherwise.

### GetAuthorsOk

`func (o *Article) GetAuthorsOk() (*[]Author, bool)`

GetAuthorsOk returns a tuple with the Authors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthors

`func (o *Article) SetAuthors(v []Author)`

SetAuthors sets Authors field to given value.

### HasAuthors

`func (o *Article) HasAuthors() bool`

HasAuthors returns a boolean if a field has been set.

### SetAuthorsNil

`func (o *Article) SetAuthorsNil(b bool)`

 SetAuthorsNil sets the value for Authors to be an explicit nil

### UnsetAuthors
`func (o *Article) UnsetAuthors()`

UnsetAuthors ensures that no value is present for Authors, not even an explicit nil
### GetFullText

`func (o *Article) GetFullText() string`

GetFullText returns the FullText field if non-nil, zero value otherwise.

### GetFullTextOk

`func (o *Article) GetFullTextOk() (*string, bool)`

GetFullTextOk returns a tuple with the FullText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFullText

`func (o *Article) SetFullText(v string)`

SetFullText sets FullText field to given value.

### HasFullText

`func (o *Article) HasFullText() bool`

HasFullText returns a boolean if a field has been set.

### SetFullTextNil

`func (o *Article) SetFullTextNil(b bool)`

 SetFullTextNil sets the value for FullText to be an explicit nil

### UnsetFullText
`func (o *Article) UnsetFullText()`

UnsetFullText ensures that no value is present for FullText, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


