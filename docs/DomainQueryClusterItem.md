# DomainQueryClusterItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ClusterLabel** | **string** |  | 
**ClusterDescription** | **string** |  | 
**ClusterClassification** | **string** |  | 
**CentroidCoords** | **[]interface{}** |  | 
**ClusterQueries** | [**[]DomainQueryItem**](DomainQueryItem.md) |  | 

## Methods

### NewDomainQueryClusterItem

`func NewDomainQueryClusterItem(clusterLabel string, clusterDescription string, clusterClassification string, centroidCoords []interface{}, clusterQueries []DomainQueryItem, ) *DomainQueryClusterItem`

NewDomainQueryClusterItem instantiates a new DomainQueryClusterItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainQueryClusterItemWithDefaults

`func NewDomainQueryClusterItemWithDefaults() *DomainQueryClusterItem`

NewDomainQueryClusterItemWithDefaults instantiates a new DomainQueryClusterItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetClusterLabel

`func (o *DomainQueryClusterItem) GetClusterLabel() string`

GetClusterLabel returns the ClusterLabel field if non-nil, zero value otherwise.

### GetClusterLabelOk

`func (o *DomainQueryClusterItem) GetClusterLabelOk() (*string, bool)`

GetClusterLabelOk returns a tuple with the ClusterLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterLabel

`func (o *DomainQueryClusterItem) SetClusterLabel(v string)`

SetClusterLabel sets ClusterLabel field to given value.


### GetClusterDescription

`func (o *DomainQueryClusterItem) GetClusterDescription() string`

GetClusterDescription returns the ClusterDescription field if non-nil, zero value otherwise.

### GetClusterDescriptionOk

`func (o *DomainQueryClusterItem) GetClusterDescriptionOk() (*string, bool)`

GetClusterDescriptionOk returns a tuple with the ClusterDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterDescription

`func (o *DomainQueryClusterItem) SetClusterDescription(v string)`

SetClusterDescription sets ClusterDescription field to given value.


### GetClusterClassification

`func (o *DomainQueryClusterItem) GetClusterClassification() string`

GetClusterClassification returns the ClusterClassification field if non-nil, zero value otherwise.

### GetClusterClassificationOk

`func (o *DomainQueryClusterItem) GetClusterClassificationOk() (*string, bool)`

GetClusterClassificationOk returns a tuple with the ClusterClassification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterClassification

`func (o *DomainQueryClusterItem) SetClusterClassification(v string)`

SetClusterClassification sets ClusterClassification field to given value.


### GetCentroidCoords

`func (o *DomainQueryClusterItem) GetCentroidCoords() []interface{}`

GetCentroidCoords returns the CentroidCoords field if non-nil, zero value otherwise.

### GetCentroidCoordsOk

`func (o *DomainQueryClusterItem) GetCentroidCoordsOk() (*[]interface{}, bool)`

GetCentroidCoordsOk returns a tuple with the CentroidCoords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCentroidCoords

`func (o *DomainQueryClusterItem) SetCentroidCoords(v []interface{})`

SetCentroidCoords sets CentroidCoords field to given value.


### GetClusterQueries

`func (o *DomainQueryClusterItem) GetClusterQueries() []DomainQueryItem`

GetClusterQueries returns the ClusterQueries field if non-nil, zero value otherwise.

### GetClusterQueriesOk

`func (o *DomainQueryClusterItem) GetClusterQueriesOk() (*[]DomainQueryItem, bool)`

GetClusterQueriesOk returns a tuple with the ClusterQueries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClusterQueries

`func (o *DomainQueryClusterItem) SetClusterQueries(v []DomainQueryItem)`

SetClusterQueries sets ClusterQueries field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


