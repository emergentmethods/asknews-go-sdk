# GraphRelationships

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Nodes** | Pointer to **[]map[string]string** |  | [optional] [default to []]
**Edges** | Pointer to **[]map[string]string** |  | [optional] [default to []]

## Methods

### NewGraphRelationships

`func NewGraphRelationships() *GraphRelationships`

NewGraphRelationships instantiates a new GraphRelationships object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGraphRelationshipsWithDefaults

`func NewGraphRelationshipsWithDefaults() *GraphRelationships`

NewGraphRelationshipsWithDefaults instantiates a new GraphRelationships object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNodes

`func (o *GraphRelationships) GetNodes() []map[string]string`

GetNodes returns the Nodes field if non-nil, zero value otherwise.

### GetNodesOk

`func (o *GraphRelationships) GetNodesOk() (*[]map[string]string, bool)`

GetNodesOk returns a tuple with the Nodes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodes

`func (o *GraphRelationships) SetNodes(v []map[string]string)`

SetNodes sets Nodes field to given value.

### HasNodes

`func (o *GraphRelationships) HasNodes() bool`

HasNodes returns a boolean if a field has been set.

### GetEdges

`func (o *GraphRelationships) GetEdges() []map[string]string`

GetEdges returns the Edges field if non-nil, zero value otherwise.

### GetEdgesOk

`func (o *GraphRelationships) GetEdgesOk() (*[]map[string]string, bool)`

GetEdgesOk returns a tuple with the Edges field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdges

`func (o *GraphRelationships) SetEdges(v []map[string]string)`

SetEdges sets Edges field to given value.

### HasEdges

`func (o *GraphRelationships) HasEdges() bool`

HasEdges returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


