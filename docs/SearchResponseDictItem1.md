# SearchResponseDictItem1

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
**Entities** | [**Entities1**](Entities1.md) |  | 
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
**EntityRelationGraph** | Pointer to [**NullableGraphRelationships**](GraphRelationships.md) |  | [optional] 
**GeoCoordinates** | Pointer to [**map[string]GeoCoordinate1**](GeoCoordinate1.md) |  | [optional] 
**Continent** | Pointer to **NullableString** |  | [optional] 
**Assets** | Pointer to [**NullableAssets1**](Assets1.md) |  | [optional] 
**SocialEmbeds** | Pointer to **[]string** |  | [optional] 
**Bias** | Pointer to **NullableString** |  | [optional] 
**Authors** | Pointer to [**[]Author1**](Author1.md) |  | [optional] 
**FullText** | Pointer to **NullableString** |  | [optional] 
**AsStringKey** | **string** |  | 

## Methods

### NewSearchResponseDictItem1

`func NewSearchResponseDictItem1(articleUrl string, articleId string, classification Classification, country string, sourceId string, pageRank int32, domainUrl string, engTitle string, entities Entities1, keywords []string, language string, pubDate time.Time, summary string, title string, sentiment int32, centroidDistance float32, clusterProbability float32, asStringKey string, ) *SearchResponseDictItem1`

NewSearchResponseDictItem1 instantiates a new SearchResponseDictItem1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSearchResponseDictItem1WithDefaults

`func NewSearchResponseDictItem1WithDefaults() *SearchResponseDictItem1`

NewSearchResponseDictItem1WithDefaults instantiates a new SearchResponseDictItem1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetArticleUrl

`func (o *SearchResponseDictItem1) GetArticleUrl() string`

GetArticleUrl returns the ArticleUrl field if non-nil, zero value otherwise.

### GetArticleUrlOk

`func (o *SearchResponseDictItem1) GetArticleUrlOk() (*string, bool)`

GetArticleUrlOk returns a tuple with the ArticleUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArticleUrl

`func (o *SearchResponseDictItem1) SetArticleUrl(v string)`

SetArticleUrl sets ArticleUrl field to given value.


### GetArticleId

`func (o *SearchResponseDictItem1) GetArticleId() string`

GetArticleId returns the ArticleId field if non-nil, zero value otherwise.

### GetArticleIdOk

`func (o *SearchResponseDictItem1) GetArticleIdOk() (*string, bool)`

GetArticleIdOk returns a tuple with the ArticleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArticleId

`func (o *SearchResponseDictItem1) SetArticleId(v string)`

SetArticleId sets ArticleId field to given value.


### GetClassification

`func (o *SearchResponseDictItem1) GetClassification() Classification`

GetClassification returns the Classification field if non-nil, zero value otherwise.

### GetClassificationOk

`func (o *SearchResponseDictItem1) GetClassificationOk() (*Classification, bool)`

GetClassificationOk returns a tuple with the Classification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClassification

`func (o *SearchResponseDictItem1) SetClassification(v Classification)`

SetClassification sets Classification field to given value.


### GetCountry

`func (o *SearchResponseDictItem1) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *SearchResponseDictItem1) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *SearchResponseDictItem1) SetCountry(v string)`

SetCountry sets Country field to given value.


### GetSourceId

`func (o *SearchResponseDictItem1) GetSourceId() string`

GetSourceId returns the SourceId field if non-nil, zero value otherwise.

### GetSourceIdOk

`func (o *SearchResponseDictItem1) GetSourceIdOk() (*string, bool)`

GetSourceIdOk returns a tuple with the SourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceId

`func (o *SearchResponseDictItem1) SetSourceId(v string)`

SetSourceId sets SourceId field to given value.


### GetPageRank

`func (o *SearchResponseDictItem1) GetPageRank() int32`

GetPageRank returns the PageRank field if non-nil, zero value otherwise.

### GetPageRankOk

`func (o *SearchResponseDictItem1) GetPageRankOk() (*int32, bool)`

GetPageRankOk returns a tuple with the PageRank field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageRank

`func (o *SearchResponseDictItem1) SetPageRank(v int32)`

SetPageRank sets PageRank field to given value.


### GetDomainUrl

`func (o *SearchResponseDictItem1) GetDomainUrl() string`

GetDomainUrl returns the DomainUrl field if non-nil, zero value otherwise.

### GetDomainUrlOk

`func (o *SearchResponseDictItem1) GetDomainUrlOk() (*string, bool)`

GetDomainUrlOk returns a tuple with the DomainUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainUrl

`func (o *SearchResponseDictItem1) SetDomainUrl(v string)`

SetDomainUrl sets DomainUrl field to given value.


### GetEngTitle

`func (o *SearchResponseDictItem1) GetEngTitle() string`

GetEngTitle returns the EngTitle field if non-nil, zero value otherwise.

### GetEngTitleOk

`func (o *SearchResponseDictItem1) GetEngTitleOk() (*string, bool)`

GetEngTitleOk returns a tuple with the EngTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngTitle

`func (o *SearchResponseDictItem1) SetEngTitle(v string)`

SetEngTitle sets EngTitle field to given value.


### GetEntities

`func (o *SearchResponseDictItem1) GetEntities() Entities1`

GetEntities returns the Entities field if non-nil, zero value otherwise.

### GetEntitiesOk

`func (o *SearchResponseDictItem1) GetEntitiesOk() (*Entities1, bool)`

GetEntitiesOk returns a tuple with the Entities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntities

`func (o *SearchResponseDictItem1) SetEntities(v Entities1)`

SetEntities sets Entities field to given value.


### GetImageUrl

`func (o *SearchResponseDictItem1) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *SearchResponseDictItem1) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *SearchResponseDictItem1) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *SearchResponseDictItem1) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### SetImageUrlNil

`func (o *SearchResponseDictItem1) SetImageUrlNil(b bool)`

 SetImageUrlNil sets the value for ImageUrl to be an explicit nil

### UnsetImageUrl
`func (o *SearchResponseDictItem1) UnsetImageUrl()`

UnsetImageUrl ensures that no value is present for ImageUrl, not even an explicit nil
### GetKeywords

`func (o *SearchResponseDictItem1) GetKeywords() []string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *SearchResponseDictItem1) GetKeywordsOk() (*[]string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *SearchResponseDictItem1) SetKeywords(v []string)`

SetKeywords sets Keywords field to given value.


### GetLanguage

`func (o *SearchResponseDictItem1) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *SearchResponseDictItem1) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *SearchResponseDictItem1) SetLanguage(v string)`

SetLanguage sets Language field to given value.


### GetPubDate

`func (o *SearchResponseDictItem1) GetPubDate() time.Time`

GetPubDate returns the PubDate field if non-nil, zero value otherwise.

### GetPubDateOk

`func (o *SearchResponseDictItem1) GetPubDateOk() (*time.Time, bool)`

GetPubDateOk returns a tuple with the PubDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPubDate

`func (o *SearchResponseDictItem1) SetPubDate(v time.Time)`

SetPubDate sets PubDate field to given value.


### GetSummary

`func (o *SearchResponseDictItem1) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *SearchResponseDictItem1) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *SearchResponseDictItem1) SetSummary(v string)`

SetSummary sets Summary field to given value.


### GetKeyPoints

`func (o *SearchResponseDictItem1) GetKeyPoints() []string`

GetKeyPoints returns the KeyPoints field if non-nil, zero value otherwise.

### GetKeyPointsOk

`func (o *SearchResponseDictItem1) GetKeyPointsOk() (*[]string, bool)`

GetKeyPointsOk returns a tuple with the KeyPoints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyPoints

`func (o *SearchResponseDictItem1) SetKeyPoints(v []string)`

SetKeyPoints sets KeyPoints field to given value.

### HasKeyPoints

`func (o *SearchResponseDictItem1) HasKeyPoints() bool`

HasKeyPoints returns a boolean if a field has been set.

### SetKeyPointsNil

`func (o *SearchResponseDictItem1) SetKeyPointsNil(b bool)`

 SetKeyPointsNil sets the value for KeyPoints to be an explicit nil

### UnsetKeyPoints
`func (o *SearchResponseDictItem1) UnsetKeyPoints()`

UnsetKeyPoints ensures that no value is present for KeyPoints, not even an explicit nil
### GetTitle

`func (o *SearchResponseDictItem1) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *SearchResponseDictItem1) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *SearchResponseDictItem1) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetSentiment

`func (o *SearchResponseDictItem1) GetSentiment() int32`

GetSentiment returns the Sentiment field if non-nil, zero value otherwise.

### GetSentimentOk

`func (o *SearchResponseDictItem1) GetSentimentOk() (*int32, bool)`

GetSentimentOk returns a tuple with the Sentiment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentiment

`func (o *SearchResponseDictItem1) SetSentiment(v int32)`

SetSentiment sets Sentiment field to given value.


### GetCentroidDistance

`func (o *SearchResponseDictItem1) GetCentroidDistance() float32`

GetCentroidDistance returns the CentroidDistance field if non-nil, zero value otherwise.

### GetCentroidDistanceOk

`func (o *SearchResponseDictItem1) GetCentroidDistanceOk() (*float32, bool)`

GetCentroidDistanceOk returns a tuple with the CentroidDistance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCentroidDistance

`func (o *SearchResponseDictItem1) SetCentroidDistance(v float32)`

SetCentroidDistance sets CentroidDistance field to given value.


### GetClusterProbability

`func (o *SearchResponseDictItem1) GetClusterProbability() float32`

GetClusterProbability returns the ClusterProbability field if non-nil, zero value otherwise.

### GetClusterProbabilityOk

`func (o *SearchResponseDictItem1) GetClusterProbabilityOk() (*float32, bool)`

GetClusterProbabilityOk returns a tuple with the ClusterProbability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterProbability

`func (o *SearchResponseDictItem1) SetClusterProbability(v float32)`

SetClusterProbability sets ClusterProbability field to given value.


### GetMarkdownCitation

`func (o *SearchResponseDictItem1) GetMarkdownCitation() string`

GetMarkdownCitation returns the MarkdownCitation field if non-nil, zero value otherwise.

### GetMarkdownCitationOk

`func (o *SearchResponseDictItem1) GetMarkdownCitationOk() (*string, bool)`

GetMarkdownCitationOk returns a tuple with the MarkdownCitation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarkdownCitation

`func (o *SearchResponseDictItem1) SetMarkdownCitation(v string)`

SetMarkdownCitation sets MarkdownCitation field to given value.

### HasMarkdownCitation

`func (o *SearchResponseDictItem1) HasMarkdownCitation() bool`

HasMarkdownCitation returns a boolean if a field has been set.

### GetProvocative

`func (o *SearchResponseDictItem1) GetProvocative() string`

GetProvocative returns the Provocative field if non-nil, zero value otherwise.

### GetProvocativeOk

`func (o *SearchResponseDictItem1) GetProvocativeOk() (*string, bool)`

GetProvocativeOk returns a tuple with the Provocative field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvocative

`func (o *SearchResponseDictItem1) SetProvocative(v string)`

SetProvocative sets Provocative field to given value.

### HasProvocative

`func (o *SearchResponseDictItem1) HasProvocative() bool`

HasProvocative returns a boolean if a field has been set.

### GetReportingVoice

`func (o *SearchResponseDictItem1) GetReportingVoice() ReportingVoice1`

GetReportingVoice returns the ReportingVoice field if non-nil, zero value otherwise.

### GetReportingVoiceOk

`func (o *SearchResponseDictItem1) GetReportingVoiceOk() (*ReportingVoice1, bool)`

GetReportingVoiceOk returns a tuple with the ReportingVoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportingVoice

`func (o *SearchResponseDictItem1) SetReportingVoice(v ReportingVoice1)`

SetReportingVoice sets ReportingVoice field to given value.

### HasReportingVoice

`func (o *SearchResponseDictItem1) HasReportingVoice() bool`

HasReportingVoice returns a boolean if a field has been set.

### GetEntityRelationGraph

`func (o *SearchResponseDictItem1) GetEntityRelationGraph() GraphRelationships`

GetEntityRelationGraph returns the EntityRelationGraph field if non-nil, zero value otherwise.

### GetEntityRelationGraphOk

`func (o *SearchResponseDictItem1) GetEntityRelationGraphOk() (*GraphRelationships, bool)`

GetEntityRelationGraphOk returns a tuple with the EntityRelationGraph field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityRelationGraph

`func (o *SearchResponseDictItem1) SetEntityRelationGraph(v GraphRelationships)`

SetEntityRelationGraph sets EntityRelationGraph field to given value.

### HasEntityRelationGraph

`func (o *SearchResponseDictItem1) HasEntityRelationGraph() bool`

HasEntityRelationGraph returns a boolean if a field has been set.

### SetEntityRelationGraphNil

`func (o *SearchResponseDictItem1) SetEntityRelationGraphNil(b bool)`

 SetEntityRelationGraphNil sets the value for EntityRelationGraph to be an explicit nil

### UnsetEntityRelationGraph
`func (o *SearchResponseDictItem1) UnsetEntityRelationGraph()`

UnsetEntityRelationGraph ensures that no value is present for EntityRelationGraph, not even an explicit nil
### GetGeoCoordinates

`func (o *SearchResponseDictItem1) GetGeoCoordinates() map[string]GeoCoordinate1`

GetGeoCoordinates returns the GeoCoordinates field if non-nil, zero value otherwise.

### GetGeoCoordinatesOk

`func (o *SearchResponseDictItem1) GetGeoCoordinatesOk() (*map[string]GeoCoordinate1, bool)`

GetGeoCoordinatesOk returns a tuple with the GeoCoordinates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeoCoordinates

`func (o *SearchResponseDictItem1) SetGeoCoordinates(v map[string]GeoCoordinate1)`

SetGeoCoordinates sets GeoCoordinates field to given value.

### HasGeoCoordinates

`func (o *SearchResponseDictItem1) HasGeoCoordinates() bool`

HasGeoCoordinates returns a boolean if a field has been set.

### SetGeoCoordinatesNil

`func (o *SearchResponseDictItem1) SetGeoCoordinatesNil(b bool)`

 SetGeoCoordinatesNil sets the value for GeoCoordinates to be an explicit nil

### UnsetGeoCoordinates
`func (o *SearchResponseDictItem1) UnsetGeoCoordinates()`

UnsetGeoCoordinates ensures that no value is present for GeoCoordinates, not even an explicit nil
### GetContinent

`func (o *SearchResponseDictItem1) GetContinent() string`

GetContinent returns the Continent field if non-nil, zero value otherwise.

### GetContinentOk

`func (o *SearchResponseDictItem1) GetContinentOk() (*string, bool)`

GetContinentOk returns a tuple with the Continent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContinent

`func (o *SearchResponseDictItem1) SetContinent(v string)`

SetContinent sets Continent field to given value.

### HasContinent

`func (o *SearchResponseDictItem1) HasContinent() bool`

HasContinent returns a boolean if a field has been set.

### SetContinentNil

`func (o *SearchResponseDictItem1) SetContinentNil(b bool)`

 SetContinentNil sets the value for Continent to be an explicit nil

### UnsetContinent
`func (o *SearchResponseDictItem1) UnsetContinent()`

UnsetContinent ensures that no value is present for Continent, not even an explicit nil
### GetAssets

`func (o *SearchResponseDictItem1) GetAssets() Assets1`

GetAssets returns the Assets field if non-nil, zero value otherwise.

### GetAssetsOk

`func (o *SearchResponseDictItem1) GetAssetsOk() (*Assets1, bool)`

GetAssetsOk returns a tuple with the Assets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssets

`func (o *SearchResponseDictItem1) SetAssets(v Assets1)`

SetAssets sets Assets field to given value.

### HasAssets

`func (o *SearchResponseDictItem1) HasAssets() bool`

HasAssets returns a boolean if a field has been set.

### SetAssetsNil

`func (o *SearchResponseDictItem1) SetAssetsNil(b bool)`

 SetAssetsNil sets the value for Assets to be an explicit nil

### UnsetAssets
`func (o *SearchResponseDictItem1) UnsetAssets()`

UnsetAssets ensures that no value is present for Assets, not even an explicit nil
### GetSocialEmbeds

`func (o *SearchResponseDictItem1) GetSocialEmbeds() []string`

GetSocialEmbeds returns the SocialEmbeds field if non-nil, zero value otherwise.

### GetSocialEmbedsOk

`func (o *SearchResponseDictItem1) GetSocialEmbedsOk() (*[]string, bool)`

GetSocialEmbedsOk returns a tuple with the SocialEmbeds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSocialEmbeds

`func (o *SearchResponseDictItem1) SetSocialEmbeds(v []string)`

SetSocialEmbeds sets SocialEmbeds field to given value.

### HasSocialEmbeds

`func (o *SearchResponseDictItem1) HasSocialEmbeds() bool`

HasSocialEmbeds returns a boolean if a field has been set.

### SetSocialEmbedsNil

`func (o *SearchResponseDictItem1) SetSocialEmbedsNil(b bool)`

 SetSocialEmbedsNil sets the value for SocialEmbeds to be an explicit nil

### UnsetSocialEmbeds
`func (o *SearchResponseDictItem1) UnsetSocialEmbeds()`

UnsetSocialEmbeds ensures that no value is present for SocialEmbeds, not even an explicit nil
### GetBias

`func (o *SearchResponseDictItem1) GetBias() string`

GetBias returns the Bias field if non-nil, zero value otherwise.

### GetBiasOk

`func (o *SearchResponseDictItem1) GetBiasOk() (*string, bool)`

GetBiasOk returns a tuple with the Bias field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBias

`func (o *SearchResponseDictItem1) SetBias(v string)`

SetBias sets Bias field to given value.

### HasBias

`func (o *SearchResponseDictItem1) HasBias() bool`

HasBias returns a boolean if a field has been set.

### SetBiasNil

`func (o *SearchResponseDictItem1) SetBiasNil(b bool)`

 SetBiasNil sets the value for Bias to be an explicit nil

### UnsetBias
`func (o *SearchResponseDictItem1) UnsetBias()`

UnsetBias ensures that no value is present for Bias, not even an explicit nil
### GetAuthors

`func (o *SearchResponseDictItem1) GetAuthors() []Author1`

GetAuthors returns the Authors field if non-nil, zero value otherwise.

### GetAuthorsOk

`func (o *SearchResponseDictItem1) GetAuthorsOk() (*[]Author1, bool)`

GetAuthorsOk returns a tuple with the Authors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthors

`func (o *SearchResponseDictItem1) SetAuthors(v []Author1)`

SetAuthors sets Authors field to given value.

### HasAuthors

`func (o *SearchResponseDictItem1) HasAuthors() bool`

HasAuthors returns a boolean if a field has been set.

### SetAuthorsNil

`func (o *SearchResponseDictItem1) SetAuthorsNil(b bool)`

 SetAuthorsNil sets the value for Authors to be an explicit nil

### UnsetAuthors
`func (o *SearchResponseDictItem1) UnsetAuthors()`

UnsetAuthors ensures that no value is present for Authors, not even an explicit nil
### GetFullText

`func (o *SearchResponseDictItem1) GetFullText() string`

GetFullText returns the FullText field if non-nil, zero value otherwise.

### GetFullTextOk

`func (o *SearchResponseDictItem1) GetFullTextOk() (*string, bool)`

GetFullTextOk returns a tuple with the FullText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFullText

`func (o *SearchResponseDictItem1) SetFullText(v string)`

SetFullText sets FullText field to given value.

### HasFullText

`func (o *SearchResponseDictItem1) HasFullText() bool`

HasFullText returns a boolean if a field has been set.

### SetFullTextNil

`func (o *SearchResponseDictItem1) SetFullTextNil(b bool)`

 SetFullTextNil sets the value for FullText to be an explicit nil

### UnsetFullText
`func (o *SearchResponseDictItem1) UnsetFullText()`

UnsetFullText ensures that no value is present for FullText, not even an explicit nil
### GetAsStringKey

`func (o *SearchResponseDictItem1) GetAsStringKey() string`

GetAsStringKey returns the AsStringKey field if non-nil, zero value otherwise.

### GetAsStringKeyOk

`func (o *SearchResponseDictItem1) GetAsStringKeyOk() (*string, bool)`

GetAsStringKeyOk returns a tuple with the AsStringKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAsStringKey

`func (o *SearchResponseDictItem1) SetAsStringKey(v string)`

SetAsStringKey sets AsStringKey field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


