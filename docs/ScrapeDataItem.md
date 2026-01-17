# ScrapeDataItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Scrapes** | [**[]ScrapeItem**](ScrapeItem.md) |  | 
**Referrals** | [**[]ReferralItem**](ReferralItem.md) |  | 

## Methods

### NewScrapeDataItem

`func NewScrapeDataItem(scrapes []ScrapeItem, referrals []ReferralItem, ) *ScrapeDataItem`

NewScrapeDataItem instantiates a new ScrapeDataItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewScrapeDataItemWithDefaults

`func NewScrapeDataItemWithDefaults() *ScrapeDataItem`

NewScrapeDataItemWithDefaults instantiates a new ScrapeDataItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetScrapes

`func (o *ScrapeDataItem) GetScrapes() []ScrapeItem`

GetScrapes returns the Scrapes field if non-nil, zero value otherwise.

### GetScrapesOk

`func (o *ScrapeDataItem) GetScrapesOk() (*[]ScrapeItem, bool)`

GetScrapesOk returns a tuple with the Scrapes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScrapes

`func (o *ScrapeDataItem) SetScrapes(v []ScrapeItem)`

SetScrapes sets Scrapes field to given value.


### GetReferrals

`func (o *ScrapeDataItem) GetReferrals() []ReferralItem`

GetReferrals returns the Referrals field if non-nil, zero value otherwise.

### GetReferralsOk

`func (o *ScrapeDataItem) GetReferralsOk() (*[]ReferralItem, bool)`

GetReferralsOk returns a tuple with the Referrals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferrals

`func (o *ScrapeDataItem) SetReferrals(v []ReferralItem)`

SetReferrals sets Referrals field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


