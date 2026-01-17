# StoryUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** |  | 
**ClusterArticles** | [**[]Article**](Article.md) |  | 
**PromptArticles** | [**[]Article**](Article.md) |  | 
**NArticles** | **int32** |  | 
**Entities** | [**Entities**](Entities.md) |  | 
**Headline** | **string** |  | 
**Story** | **string** |  | 
**StoryUpdateTs** | **int32** |  | 
**SourcesUrls** | **map[string]int32** |  | 
**LanguagesPct** | **map[string]float32** |  | 
**CountriesPct** | **map[string]float32** |  | 
**KeyTakeaways** | **[]string** |  | 
**Contradictions** | **[]string** |  | 
**Continent** | **string** |  | 
**People** | **[]string** |  | 
**Locations** | **[]string** |  | 
**NewInformation** | **string** |  | 
**ImageUrl** | **string** |  | 
**UrlSafeTitle** | **string** |  | 
**StoryUuid** | **string** |  | 
**Categories** | **[]string** |  | 
**ImagePrompt** | **string** |  | 
**RedditPerspective** | [**RedditPerspective**](RedditPerspective.md) |  | 
**RedditThreads** | [**[]RedditThread**](RedditThread.md) |  | 
**Languages** | **map[string]int32** |  | 
**Keywords** | **[]string** |  | 
**IntraClusterStatistics** | [**IntraClusterStatistics**](IntraClusterStatistics.md) |  | 
**SilhouetteScore** | **map[string]interface{}** |  | 
**ArticleIds** | **[]string** |  | 
**Countries** | **map[string]int32** |  | 
**MarkdownCitations** | **[]string** |  | 
**Confidence** | Pointer to **float32** |  | [optional] [default to 0.0]
**Provocative** | Pointer to **string** |  | [optional] [default to "unknown"]
**ReportingVoice** | Pointer to **string** |  | [optional] [default to "Reporting voice unknown."]
**Relationships** | [**AsknewsApiSchemaV1StoriesGraphRelationships**](AsknewsApiSchemaV1StoriesGraphRelationships.md) |  | 
**Mermaid** | **string** |  | 
**CcImageUrl** | **string** |  | 
**DisplayImageUrls** | [**[]StoryUpdateDisplayImageUrlsInner**](StoryUpdateDisplayImageUrlsInner.md) |  | 
**Alignment** | Pointer to **int32** |  | [optional] [default to 0]

## Methods

### NewStoryUpdate

`func NewStoryUpdate(uuid string, clusterArticles []Article, promptArticles []Article, nArticles int32, entities Entities, headline string, story string, storyUpdateTs int32, sourcesUrls map[string]int32, languagesPct map[string]float32, countriesPct map[string]float32, keyTakeaways []string, contradictions []string, continent string, people []string, locations []string, newInformation string, imageUrl string, urlSafeTitle string, storyUuid string, categories []string, imagePrompt string, redditPerspective RedditPerspective, redditThreads []RedditThread, languages map[string]int32, keywords []string, intraClusterStatistics IntraClusterStatistics, silhouetteScore map[string]interface{}, articleIds []string, countries map[string]int32, markdownCitations []string, relationships AsknewsApiSchemaV1StoriesGraphRelationships, mermaid string, ccImageUrl string, displayImageUrls []StoryUpdateDisplayImageUrlsInner, ) *StoryUpdate`

NewStoryUpdate instantiates a new StoryUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoryUpdateWithDefaults

`func NewStoryUpdateWithDefaults() *StoryUpdate`

NewStoryUpdateWithDefaults instantiates a new StoryUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *StoryUpdate) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *StoryUpdate) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *StoryUpdate) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetClusterArticles

`func (o *StoryUpdate) GetClusterArticles() []Article`

GetClusterArticles returns the ClusterArticles field if non-nil, zero value otherwise.

### GetClusterArticlesOk

`func (o *StoryUpdate) GetClusterArticlesOk() (*[]Article, bool)`

GetClusterArticlesOk returns a tuple with the ClusterArticles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterArticles

`func (o *StoryUpdate) SetClusterArticles(v []Article)`

SetClusterArticles sets ClusterArticles field to given value.


### GetPromptArticles

`func (o *StoryUpdate) GetPromptArticles() []Article`

GetPromptArticles returns the PromptArticles field if non-nil, zero value otherwise.

### GetPromptArticlesOk

`func (o *StoryUpdate) GetPromptArticlesOk() (*[]Article, bool)`

GetPromptArticlesOk returns a tuple with the PromptArticles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptArticles

`func (o *StoryUpdate) SetPromptArticles(v []Article)`

SetPromptArticles sets PromptArticles field to given value.


### GetNArticles

`func (o *StoryUpdate) GetNArticles() int32`

GetNArticles returns the NArticles field if non-nil, zero value otherwise.

### GetNArticlesOk

`func (o *StoryUpdate) GetNArticlesOk() (*int32, bool)`

GetNArticlesOk returns a tuple with the NArticles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNArticles

`func (o *StoryUpdate) SetNArticles(v int32)`

SetNArticles sets NArticles field to given value.


### GetEntities

`func (o *StoryUpdate) GetEntities() Entities`

GetEntities returns the Entities field if non-nil, zero value otherwise.

### GetEntitiesOk

`func (o *StoryUpdate) GetEntitiesOk() (*Entities, bool)`

GetEntitiesOk returns a tuple with the Entities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntities

`func (o *StoryUpdate) SetEntities(v Entities)`

SetEntities sets Entities field to given value.


### GetHeadline

`func (o *StoryUpdate) GetHeadline() string`

GetHeadline returns the Headline field if non-nil, zero value otherwise.

### GetHeadlineOk

`func (o *StoryUpdate) GetHeadlineOk() (*string, bool)`

GetHeadlineOk returns a tuple with the Headline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeadline

`func (o *StoryUpdate) SetHeadline(v string)`

SetHeadline sets Headline field to given value.


### GetStory

`func (o *StoryUpdate) GetStory() string`

GetStory returns the Story field if non-nil, zero value otherwise.

### GetStoryOk

`func (o *StoryUpdate) GetStoryOk() (*string, bool)`

GetStoryOk returns a tuple with the Story field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStory

`func (o *StoryUpdate) SetStory(v string)`

SetStory sets Story field to given value.


### GetStoryUpdateTs

`func (o *StoryUpdate) GetStoryUpdateTs() int32`

GetStoryUpdateTs returns the StoryUpdateTs field if non-nil, zero value otherwise.

### GetStoryUpdateTsOk

`func (o *StoryUpdate) GetStoryUpdateTsOk() (*int32, bool)`

GetStoryUpdateTsOk returns a tuple with the StoryUpdateTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoryUpdateTs

`func (o *StoryUpdate) SetStoryUpdateTs(v int32)`

SetStoryUpdateTs sets StoryUpdateTs field to given value.


### GetSourcesUrls

`func (o *StoryUpdate) GetSourcesUrls() map[string]int32`

GetSourcesUrls returns the SourcesUrls field if non-nil, zero value otherwise.

### GetSourcesUrlsOk

`func (o *StoryUpdate) GetSourcesUrlsOk() (*map[string]int32, bool)`

GetSourcesUrlsOk returns a tuple with the SourcesUrls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcesUrls

`func (o *StoryUpdate) SetSourcesUrls(v map[string]int32)`

SetSourcesUrls sets SourcesUrls field to given value.


### GetLanguagesPct

`func (o *StoryUpdate) GetLanguagesPct() map[string]float32`

GetLanguagesPct returns the LanguagesPct field if non-nil, zero value otherwise.

### GetLanguagesPctOk

`func (o *StoryUpdate) GetLanguagesPctOk() (*map[string]float32, bool)`

GetLanguagesPctOk returns a tuple with the LanguagesPct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguagesPct

`func (o *StoryUpdate) SetLanguagesPct(v map[string]float32)`

SetLanguagesPct sets LanguagesPct field to given value.


### GetCountriesPct

`func (o *StoryUpdate) GetCountriesPct() map[string]float32`

GetCountriesPct returns the CountriesPct field if non-nil, zero value otherwise.

### GetCountriesPctOk

`func (o *StoryUpdate) GetCountriesPctOk() (*map[string]float32, bool)`

GetCountriesPctOk returns a tuple with the CountriesPct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountriesPct

`func (o *StoryUpdate) SetCountriesPct(v map[string]float32)`

SetCountriesPct sets CountriesPct field to given value.


### GetKeyTakeaways

`func (o *StoryUpdate) GetKeyTakeaways() []string`

GetKeyTakeaways returns the KeyTakeaways field if non-nil, zero value otherwise.

### GetKeyTakeawaysOk

`func (o *StoryUpdate) GetKeyTakeawaysOk() (*[]string, bool)`

GetKeyTakeawaysOk returns a tuple with the KeyTakeaways field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeyTakeaways

`func (o *StoryUpdate) SetKeyTakeaways(v []string)`

SetKeyTakeaways sets KeyTakeaways field to given value.


### GetContradictions

`func (o *StoryUpdate) GetContradictions() []string`

GetContradictions returns the Contradictions field if non-nil, zero value otherwise.

### GetContradictionsOk

`func (o *StoryUpdate) GetContradictionsOk() (*[]string, bool)`

GetContradictionsOk returns a tuple with the Contradictions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContradictions

`func (o *StoryUpdate) SetContradictions(v []string)`

SetContradictions sets Contradictions field to given value.


### GetContinent

`func (o *StoryUpdate) GetContinent() string`

GetContinent returns the Continent field if non-nil, zero value otherwise.

### GetContinentOk

`func (o *StoryUpdate) GetContinentOk() (*string, bool)`

GetContinentOk returns a tuple with the Continent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContinent

`func (o *StoryUpdate) SetContinent(v string)`

SetContinent sets Continent field to given value.


### GetPeople

`func (o *StoryUpdate) GetPeople() []string`

GetPeople returns the People field if non-nil, zero value otherwise.

### GetPeopleOk

`func (o *StoryUpdate) GetPeopleOk() (*[]string, bool)`

GetPeopleOk returns a tuple with the People field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeople

`func (o *StoryUpdate) SetPeople(v []string)`

SetPeople sets People field to given value.


### GetLocations

`func (o *StoryUpdate) GetLocations() []string`

GetLocations returns the Locations field if non-nil, zero value otherwise.

### GetLocationsOk

`func (o *StoryUpdate) GetLocationsOk() (*[]string, bool)`

GetLocationsOk returns a tuple with the Locations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocations

`func (o *StoryUpdate) SetLocations(v []string)`

SetLocations sets Locations field to given value.


### GetNewInformation

`func (o *StoryUpdate) GetNewInformation() string`

GetNewInformation returns the NewInformation field if non-nil, zero value otherwise.

### GetNewInformationOk

`func (o *StoryUpdate) GetNewInformationOk() (*string, bool)`

GetNewInformationOk returns a tuple with the NewInformation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewInformation

`func (o *StoryUpdate) SetNewInformation(v string)`

SetNewInformation sets NewInformation field to given value.


### GetImageUrl

`func (o *StoryUpdate) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *StoryUpdate) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *StoryUpdate) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.


### GetUrlSafeTitle

`func (o *StoryUpdate) GetUrlSafeTitle() string`

GetUrlSafeTitle returns the UrlSafeTitle field if non-nil, zero value otherwise.

### GetUrlSafeTitleOk

`func (o *StoryUpdate) GetUrlSafeTitleOk() (*string, bool)`

GetUrlSafeTitleOk returns a tuple with the UrlSafeTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrlSafeTitle

`func (o *StoryUpdate) SetUrlSafeTitle(v string)`

SetUrlSafeTitle sets UrlSafeTitle field to given value.


### GetStoryUuid

`func (o *StoryUpdate) GetStoryUuid() string`

GetStoryUuid returns the StoryUuid field if non-nil, zero value otherwise.

### GetStoryUuidOk

`func (o *StoryUpdate) GetStoryUuidOk() (*string, bool)`

GetStoryUuidOk returns a tuple with the StoryUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoryUuid

`func (o *StoryUpdate) SetStoryUuid(v string)`

SetStoryUuid sets StoryUuid field to given value.


### GetCategories

`func (o *StoryUpdate) GetCategories() []string`

GetCategories returns the Categories field if non-nil, zero value otherwise.

### GetCategoriesOk

`func (o *StoryUpdate) GetCategoriesOk() (*[]string, bool)`

GetCategoriesOk returns a tuple with the Categories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategories

`func (o *StoryUpdate) SetCategories(v []string)`

SetCategories sets Categories field to given value.


### GetImagePrompt

`func (o *StoryUpdate) GetImagePrompt() string`

GetImagePrompt returns the ImagePrompt field if non-nil, zero value otherwise.

### GetImagePromptOk

`func (o *StoryUpdate) GetImagePromptOk() (*string, bool)`

GetImagePromptOk returns a tuple with the ImagePrompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImagePrompt

`func (o *StoryUpdate) SetImagePrompt(v string)`

SetImagePrompt sets ImagePrompt field to given value.


### GetRedditPerspective

`func (o *StoryUpdate) GetRedditPerspective() RedditPerspective`

GetRedditPerspective returns the RedditPerspective field if non-nil, zero value otherwise.

### GetRedditPerspectiveOk

`func (o *StoryUpdate) GetRedditPerspectiveOk() (*RedditPerspective, bool)`

GetRedditPerspectiveOk returns a tuple with the RedditPerspective field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedditPerspective

`func (o *StoryUpdate) SetRedditPerspective(v RedditPerspective)`

SetRedditPerspective sets RedditPerspective field to given value.


### GetRedditThreads

`func (o *StoryUpdate) GetRedditThreads() []RedditThread`

GetRedditThreads returns the RedditThreads field if non-nil, zero value otherwise.

### GetRedditThreadsOk

`func (o *StoryUpdate) GetRedditThreadsOk() (*[]RedditThread, bool)`

GetRedditThreadsOk returns a tuple with the RedditThreads field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedditThreads

`func (o *StoryUpdate) SetRedditThreads(v []RedditThread)`

SetRedditThreads sets RedditThreads field to given value.


### GetLanguages

`func (o *StoryUpdate) GetLanguages() map[string]int32`

GetLanguages returns the Languages field if non-nil, zero value otherwise.

### GetLanguagesOk

`func (o *StoryUpdate) GetLanguagesOk() (*map[string]int32, bool)`

GetLanguagesOk returns a tuple with the Languages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguages

`func (o *StoryUpdate) SetLanguages(v map[string]int32)`

SetLanguages sets Languages field to given value.


### GetKeywords

`func (o *StoryUpdate) GetKeywords() []string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *StoryUpdate) GetKeywordsOk() (*[]string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *StoryUpdate) SetKeywords(v []string)`

SetKeywords sets Keywords field to given value.


### GetIntraClusterStatistics

`func (o *StoryUpdate) GetIntraClusterStatistics() IntraClusterStatistics`

GetIntraClusterStatistics returns the IntraClusterStatistics field if non-nil, zero value otherwise.

### GetIntraClusterStatisticsOk

`func (o *StoryUpdate) GetIntraClusterStatisticsOk() (*IntraClusterStatistics, bool)`

GetIntraClusterStatisticsOk returns a tuple with the IntraClusterStatistics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntraClusterStatistics

`func (o *StoryUpdate) SetIntraClusterStatistics(v IntraClusterStatistics)`

SetIntraClusterStatistics sets IntraClusterStatistics field to given value.


### GetSilhouetteScore

`func (o *StoryUpdate) GetSilhouetteScore() map[string]interface{}`

GetSilhouetteScore returns the SilhouetteScore field if non-nil, zero value otherwise.

### GetSilhouetteScoreOk

`func (o *StoryUpdate) GetSilhouetteScoreOk() (*map[string]interface{}, bool)`

GetSilhouetteScoreOk returns a tuple with the SilhouetteScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSilhouetteScore

`func (o *StoryUpdate) SetSilhouetteScore(v map[string]interface{})`

SetSilhouetteScore sets SilhouetteScore field to given value.


### GetArticleIds

`func (o *StoryUpdate) GetArticleIds() []string`

GetArticleIds returns the ArticleIds field if non-nil, zero value otherwise.

### GetArticleIdsOk

`func (o *StoryUpdate) GetArticleIdsOk() (*[]string, bool)`

GetArticleIdsOk returns a tuple with the ArticleIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArticleIds

`func (o *StoryUpdate) SetArticleIds(v []string)`

SetArticleIds sets ArticleIds field to given value.


### GetCountries

`func (o *StoryUpdate) GetCountries() map[string]int32`

GetCountries returns the Countries field if non-nil, zero value otherwise.

### GetCountriesOk

`func (o *StoryUpdate) GetCountriesOk() (*map[string]int32, bool)`

GetCountriesOk returns a tuple with the Countries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountries

`func (o *StoryUpdate) SetCountries(v map[string]int32)`

SetCountries sets Countries field to given value.


### GetMarkdownCitations

`func (o *StoryUpdate) GetMarkdownCitations() []string`

GetMarkdownCitations returns the MarkdownCitations field if non-nil, zero value otherwise.

### GetMarkdownCitationsOk

`func (o *StoryUpdate) GetMarkdownCitationsOk() (*[]string, bool)`

GetMarkdownCitationsOk returns a tuple with the MarkdownCitations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarkdownCitations

`func (o *StoryUpdate) SetMarkdownCitations(v []string)`

SetMarkdownCitations sets MarkdownCitations field to given value.


### GetConfidence

`func (o *StoryUpdate) GetConfidence() float32`

GetConfidence returns the Confidence field if non-nil, zero value otherwise.

### GetConfidenceOk

`func (o *StoryUpdate) GetConfidenceOk() (*float32, bool)`

GetConfidenceOk returns a tuple with the Confidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfidence

`func (o *StoryUpdate) SetConfidence(v float32)`

SetConfidence sets Confidence field to given value.

### HasConfidence

`func (o *StoryUpdate) HasConfidence() bool`

HasConfidence returns a boolean if a field has been set.

### GetProvocative

`func (o *StoryUpdate) GetProvocative() string`

GetProvocative returns the Provocative field if non-nil, zero value otherwise.

### GetProvocativeOk

`func (o *StoryUpdate) GetProvocativeOk() (*string, bool)`

GetProvocativeOk returns a tuple with the Provocative field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvocative

`func (o *StoryUpdate) SetProvocative(v string)`

SetProvocative sets Provocative field to given value.

### HasProvocative

`func (o *StoryUpdate) HasProvocative() bool`

HasProvocative returns a boolean if a field has been set.

### GetReportingVoice

`func (o *StoryUpdate) GetReportingVoice() string`

GetReportingVoice returns the ReportingVoice field if non-nil, zero value otherwise.

### GetReportingVoiceOk

`func (o *StoryUpdate) GetReportingVoiceOk() (*string, bool)`

GetReportingVoiceOk returns a tuple with the ReportingVoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportingVoice

`func (o *StoryUpdate) SetReportingVoice(v string)`

SetReportingVoice sets ReportingVoice field to given value.

### HasReportingVoice

`func (o *StoryUpdate) HasReportingVoice() bool`

HasReportingVoice returns a boolean if a field has been set.

### GetRelationships

`func (o *StoryUpdate) GetRelationships() AsknewsApiSchemaV1StoriesGraphRelationships`

GetRelationships returns the Relationships field if non-nil, zero value otherwise.

### GetRelationshipsOk

`func (o *StoryUpdate) GetRelationshipsOk() (*AsknewsApiSchemaV1StoriesGraphRelationships, bool)`

GetRelationshipsOk returns a tuple with the Relationships field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelationships

`func (o *StoryUpdate) SetRelationships(v AsknewsApiSchemaV1StoriesGraphRelationships)`

SetRelationships sets Relationships field to given value.


### GetMermaid

`func (o *StoryUpdate) GetMermaid() string`

GetMermaid returns the Mermaid field if non-nil, zero value otherwise.

### GetMermaidOk

`func (o *StoryUpdate) GetMermaidOk() (*string, bool)`

GetMermaidOk returns a tuple with the Mermaid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMermaid

`func (o *StoryUpdate) SetMermaid(v string)`

SetMermaid sets Mermaid field to given value.


### GetCcImageUrl

`func (o *StoryUpdate) GetCcImageUrl() string`

GetCcImageUrl returns the CcImageUrl field if non-nil, zero value otherwise.

### GetCcImageUrlOk

`func (o *StoryUpdate) GetCcImageUrlOk() (*string, bool)`

GetCcImageUrlOk returns a tuple with the CcImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCcImageUrl

`func (o *StoryUpdate) SetCcImageUrl(v string)`

SetCcImageUrl sets CcImageUrl field to given value.


### GetDisplayImageUrls

`func (o *StoryUpdate) GetDisplayImageUrls() []StoryUpdateDisplayImageUrlsInner`

GetDisplayImageUrls returns the DisplayImageUrls field if non-nil, zero value otherwise.

### GetDisplayImageUrlsOk

`func (o *StoryUpdate) GetDisplayImageUrlsOk() (*[]StoryUpdateDisplayImageUrlsInner, bool)`

GetDisplayImageUrlsOk returns a tuple with the DisplayImageUrls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayImageUrls

`func (o *StoryUpdate) SetDisplayImageUrls(v []StoryUpdateDisplayImageUrlsInner)`

SetDisplayImageUrls sets DisplayImageUrls field to given value.


### GetAlignment

`func (o *StoryUpdate) GetAlignment() int32`

GetAlignment returns the Alignment field if non-nil, zero value otherwise.

### GetAlignmentOk

`func (o *StoryUpdate) GetAlignmentOk() (*int32, bool)`

GetAlignmentOk returns a tuple with the Alignment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlignment

`func (o *StoryUpdate) SetAlignment(v int32)`

SetAlignment sets Alignment field to given value.

### HasAlignment

`func (o *StoryUpdate) HasAlignment() bool`

HasAlignment returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


