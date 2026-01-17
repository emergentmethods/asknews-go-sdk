# StoryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** |  | 
**Categories** | **[]string** |  | 
**Countries** | **map[string]int32** |  | 
**CountriesPct** | **map[string]float32** |  | 
**CurrentUpdateUuid** | **string** |  | 
**RequestedUpdateUuid** | **string** |  | 
**GenerateImage** | **bool** |  | 
**Keywords** | **[]string** |  | 
**Languages** | **map[string]int32** |  | 
**LanguagesPct** | **map[string]float32** |  | 
**Locations** | **[]string** |  | 
**MetaType** | **string** |  | 
**NArticles** | **[]int32** |  | 
**NUpdates** | **int32** |  | 
**People** | **[]string** |  | 
**RedditSentiment** | [**[]ClusterProbabilitiesValue**](ClusterProbabilitiesValue.md) |  | 
**RedditSentimentTimestamps** | **[]int32** |  | 
**RollingSentiment** | **[]float32** |  | 
**Sentiment** | **[]int32** |  | 
**SentimentTimestamps** | **[]int32** |  | 
**Sources** | **map[string]int32** |  | 
**SourcesUrls** | **map[string]int32** |  | 
**Topic** | **string** |  | 
**Topics** | **[]string** |  | 
**Updates** | [**[]StoryUpdate**](StoryUpdate.md) |  | 
**UpdatedTs** | **int32** |  | 
**UpdateUuids** | **[]string** |  | 

## Methods

### NewStoryResponse

`func NewStoryResponse(uuid string, categories []string, countries map[string]int32, countriesPct map[string]float32, currentUpdateUuid string, requestedUpdateUuid string, generateImage bool, keywords []string, languages map[string]int32, languagesPct map[string]float32, locations []string, metaType string, nArticles []int32, nUpdates int32, people []string, redditSentiment []ClusterProbabilitiesValue, redditSentimentTimestamps []int32, rollingSentiment []float32, sentiment []int32, sentimentTimestamps []int32, sources map[string]int32, sourcesUrls map[string]int32, topic string, topics []string, updates []StoryUpdate, updatedTs int32, updateUuids []string, ) *StoryResponse`

NewStoryResponse instantiates a new StoryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoryResponseWithDefaults

`func NewStoryResponseWithDefaults() *StoryResponse`

NewStoryResponseWithDefaults instantiates a new StoryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *StoryResponse) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *StoryResponse) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *StoryResponse) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetCategories

`func (o *StoryResponse) GetCategories() []string`

GetCategories returns the Categories field if non-nil, zero value otherwise.

### GetCategoriesOk

`func (o *StoryResponse) GetCategoriesOk() (*[]string, bool)`

GetCategoriesOk returns a tuple with the Categories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategories

`func (o *StoryResponse) SetCategories(v []string)`

SetCategories sets Categories field to given value.


### GetCountries

`func (o *StoryResponse) GetCountries() map[string]int32`

GetCountries returns the Countries field if non-nil, zero value otherwise.

### GetCountriesOk

`func (o *StoryResponse) GetCountriesOk() (*map[string]int32, bool)`

GetCountriesOk returns a tuple with the Countries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountries

`func (o *StoryResponse) SetCountries(v map[string]int32)`

SetCountries sets Countries field to given value.


### GetCountriesPct

`func (o *StoryResponse) GetCountriesPct() map[string]float32`

GetCountriesPct returns the CountriesPct field if non-nil, zero value otherwise.

### GetCountriesPctOk

`func (o *StoryResponse) GetCountriesPctOk() (*map[string]float32, bool)`

GetCountriesPctOk returns a tuple with the CountriesPct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountriesPct

`func (o *StoryResponse) SetCountriesPct(v map[string]float32)`

SetCountriesPct sets CountriesPct field to given value.


### GetCurrentUpdateUuid

`func (o *StoryResponse) GetCurrentUpdateUuid() string`

GetCurrentUpdateUuid returns the CurrentUpdateUuid field if non-nil, zero value otherwise.

### GetCurrentUpdateUuidOk

`func (o *StoryResponse) GetCurrentUpdateUuidOk() (*string, bool)`

GetCurrentUpdateUuidOk returns a tuple with the CurrentUpdateUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentUpdateUuid

`func (o *StoryResponse) SetCurrentUpdateUuid(v string)`

SetCurrentUpdateUuid sets CurrentUpdateUuid field to given value.


### GetRequestedUpdateUuid

`func (o *StoryResponse) GetRequestedUpdateUuid() string`

GetRequestedUpdateUuid returns the RequestedUpdateUuid field if non-nil, zero value otherwise.

### GetRequestedUpdateUuidOk

`func (o *StoryResponse) GetRequestedUpdateUuidOk() (*string, bool)`

GetRequestedUpdateUuidOk returns a tuple with the RequestedUpdateUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedUpdateUuid

`func (o *StoryResponse) SetRequestedUpdateUuid(v string)`

SetRequestedUpdateUuid sets RequestedUpdateUuid field to given value.


### GetGenerateImage

`func (o *StoryResponse) GetGenerateImage() bool`

GetGenerateImage returns the GenerateImage field if non-nil, zero value otherwise.

### GetGenerateImageOk

`func (o *StoryResponse) GetGenerateImageOk() (*bool, bool)`

GetGenerateImageOk returns a tuple with the GenerateImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenerateImage

`func (o *StoryResponse) SetGenerateImage(v bool)`

SetGenerateImage sets GenerateImage field to given value.


### GetKeywords

`func (o *StoryResponse) GetKeywords() []string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *StoryResponse) GetKeywordsOk() (*[]string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *StoryResponse) SetKeywords(v []string)`

SetKeywords sets Keywords field to given value.


### GetLanguages

`func (o *StoryResponse) GetLanguages() map[string]int32`

GetLanguages returns the Languages field if non-nil, zero value otherwise.

### GetLanguagesOk

`func (o *StoryResponse) GetLanguagesOk() (*map[string]int32, bool)`

GetLanguagesOk returns a tuple with the Languages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguages

`func (o *StoryResponse) SetLanguages(v map[string]int32)`

SetLanguages sets Languages field to given value.


### GetLanguagesPct

`func (o *StoryResponse) GetLanguagesPct() map[string]float32`

GetLanguagesPct returns the LanguagesPct field if non-nil, zero value otherwise.

### GetLanguagesPctOk

`func (o *StoryResponse) GetLanguagesPctOk() (*map[string]float32, bool)`

GetLanguagesPctOk returns a tuple with the LanguagesPct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguagesPct

`func (o *StoryResponse) SetLanguagesPct(v map[string]float32)`

SetLanguagesPct sets LanguagesPct field to given value.


### GetLocations

`func (o *StoryResponse) GetLocations() []string`

GetLocations returns the Locations field if non-nil, zero value otherwise.

### GetLocationsOk

`func (o *StoryResponse) GetLocationsOk() (*[]string, bool)`

GetLocationsOk returns a tuple with the Locations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocations

`func (o *StoryResponse) SetLocations(v []string)`

SetLocations sets Locations field to given value.


### GetMetaType

`func (o *StoryResponse) GetMetaType() string`

GetMetaType returns the MetaType field if non-nil, zero value otherwise.

### GetMetaTypeOk

`func (o *StoryResponse) GetMetaTypeOk() (*string, bool)`

GetMetaTypeOk returns a tuple with the MetaType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetaType

`func (o *StoryResponse) SetMetaType(v string)`

SetMetaType sets MetaType field to given value.


### GetNArticles

`func (o *StoryResponse) GetNArticles() []int32`

GetNArticles returns the NArticles field if non-nil, zero value otherwise.

### GetNArticlesOk

`func (o *StoryResponse) GetNArticlesOk() (*[]int32, bool)`

GetNArticlesOk returns a tuple with the NArticles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNArticles

`func (o *StoryResponse) SetNArticles(v []int32)`

SetNArticles sets NArticles field to given value.


### GetNUpdates

`func (o *StoryResponse) GetNUpdates() int32`

GetNUpdates returns the NUpdates field if non-nil, zero value otherwise.

### GetNUpdatesOk

`func (o *StoryResponse) GetNUpdatesOk() (*int32, bool)`

GetNUpdatesOk returns a tuple with the NUpdates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNUpdates

`func (o *StoryResponse) SetNUpdates(v int32)`

SetNUpdates sets NUpdates field to given value.


### GetPeople

`func (o *StoryResponse) GetPeople() []string`

GetPeople returns the People field if non-nil, zero value otherwise.

### GetPeopleOk

`func (o *StoryResponse) GetPeopleOk() (*[]string, bool)`

GetPeopleOk returns a tuple with the People field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeople

`func (o *StoryResponse) SetPeople(v []string)`

SetPeople sets People field to given value.


### GetRedditSentiment

`func (o *StoryResponse) GetRedditSentiment() []ClusterProbabilitiesValue`

GetRedditSentiment returns the RedditSentiment field if non-nil, zero value otherwise.

### GetRedditSentimentOk

`func (o *StoryResponse) GetRedditSentimentOk() (*[]ClusterProbabilitiesValue, bool)`

GetRedditSentimentOk returns a tuple with the RedditSentiment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedditSentiment

`func (o *StoryResponse) SetRedditSentiment(v []ClusterProbabilitiesValue)`

SetRedditSentiment sets RedditSentiment field to given value.


### GetRedditSentimentTimestamps

`func (o *StoryResponse) GetRedditSentimentTimestamps() []int32`

GetRedditSentimentTimestamps returns the RedditSentimentTimestamps field if non-nil, zero value otherwise.

### GetRedditSentimentTimestampsOk

`func (o *StoryResponse) GetRedditSentimentTimestampsOk() (*[]int32, bool)`

GetRedditSentimentTimestampsOk returns a tuple with the RedditSentimentTimestamps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedditSentimentTimestamps

`func (o *StoryResponse) SetRedditSentimentTimestamps(v []int32)`

SetRedditSentimentTimestamps sets RedditSentimentTimestamps field to given value.


### GetRollingSentiment

`func (o *StoryResponse) GetRollingSentiment() []float32`

GetRollingSentiment returns the RollingSentiment field if non-nil, zero value otherwise.

### GetRollingSentimentOk

`func (o *StoryResponse) GetRollingSentimentOk() (*[]float32, bool)`

GetRollingSentimentOk returns a tuple with the RollingSentiment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRollingSentiment

`func (o *StoryResponse) SetRollingSentiment(v []float32)`

SetRollingSentiment sets RollingSentiment field to given value.


### GetSentiment

`func (o *StoryResponse) GetSentiment() []int32`

GetSentiment returns the Sentiment field if non-nil, zero value otherwise.

### GetSentimentOk

`func (o *StoryResponse) GetSentimentOk() (*[]int32, bool)`

GetSentimentOk returns a tuple with the Sentiment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentiment

`func (o *StoryResponse) SetSentiment(v []int32)`

SetSentiment sets Sentiment field to given value.


### GetSentimentTimestamps

`func (o *StoryResponse) GetSentimentTimestamps() []int32`

GetSentimentTimestamps returns the SentimentTimestamps field if non-nil, zero value otherwise.

### GetSentimentTimestampsOk

`func (o *StoryResponse) GetSentimentTimestampsOk() (*[]int32, bool)`

GetSentimentTimestampsOk returns a tuple with the SentimentTimestamps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentimentTimestamps

`func (o *StoryResponse) SetSentimentTimestamps(v []int32)`

SetSentimentTimestamps sets SentimentTimestamps field to given value.


### GetSources

`func (o *StoryResponse) GetSources() map[string]int32`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *StoryResponse) GetSourcesOk() (*map[string]int32, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *StoryResponse) SetSources(v map[string]int32)`

SetSources sets Sources field to given value.


### GetSourcesUrls

`func (o *StoryResponse) GetSourcesUrls() map[string]int32`

GetSourcesUrls returns the SourcesUrls field if non-nil, zero value otherwise.

### GetSourcesUrlsOk

`func (o *StoryResponse) GetSourcesUrlsOk() (*map[string]int32, bool)`

GetSourcesUrlsOk returns a tuple with the SourcesUrls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcesUrls

`func (o *StoryResponse) SetSourcesUrls(v map[string]int32)`

SetSourcesUrls sets SourcesUrls field to given value.


### GetTopic

`func (o *StoryResponse) GetTopic() string`

GetTopic returns the Topic field if non-nil, zero value otherwise.

### GetTopicOk

`func (o *StoryResponse) GetTopicOk() (*string, bool)`

GetTopicOk returns a tuple with the Topic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopic

`func (o *StoryResponse) SetTopic(v string)`

SetTopic sets Topic field to given value.


### GetTopics

`func (o *StoryResponse) GetTopics() []string`

GetTopics returns the Topics field if non-nil, zero value otherwise.

### GetTopicsOk

`func (o *StoryResponse) GetTopicsOk() (*[]string, bool)`

GetTopicsOk returns a tuple with the Topics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopics

`func (o *StoryResponse) SetTopics(v []string)`

SetTopics sets Topics field to given value.


### GetUpdates

`func (o *StoryResponse) GetUpdates() []StoryUpdate`

GetUpdates returns the Updates field if non-nil, zero value otherwise.

### GetUpdatesOk

`func (o *StoryResponse) GetUpdatesOk() (*[]StoryUpdate, bool)`

GetUpdatesOk returns a tuple with the Updates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdates

`func (o *StoryResponse) SetUpdates(v []StoryUpdate)`

SetUpdates sets Updates field to given value.


### GetUpdatedTs

`func (o *StoryResponse) GetUpdatedTs() int32`

GetUpdatedTs returns the UpdatedTs field if non-nil, zero value otherwise.

### GetUpdatedTsOk

`func (o *StoryResponse) GetUpdatedTsOk() (*int32, bool)`

GetUpdatedTsOk returns a tuple with the UpdatedTs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedTs

`func (o *StoryResponse) SetUpdatedTs(v int32)`

SetUpdatedTs sets UpdatedTs field to given value.


### GetUpdateUuids

`func (o *StoryResponse) GetUpdateUuids() []string`

GetUpdateUuids returns the UpdateUuids field if non-nil, zero value otherwise.

### GetUpdateUuidsOk

`func (o *StoryResponse) GetUpdateUuidsOk() (*[]string, bool)`

GetUpdateUuidsOk returns a tuple with the UpdateUuids field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdateUuids

`func (o *StoryResponse) SetUpdateUuids(v []string)`

SetUpdateUuids sets UpdateUuids field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


