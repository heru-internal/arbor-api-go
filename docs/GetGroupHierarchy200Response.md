# GetGroupHierarchy200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]GroupHierarchyNode**](GroupHierarchyNode.md) |  | [optional] 

## Methods

### NewGetGroupHierarchy200Response

`func NewGetGroupHierarchy200Response() *GetGroupHierarchy200Response`

NewGetGroupHierarchy200Response instantiates a new GetGroupHierarchy200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetGroupHierarchy200ResponseWithDefaults

`func NewGetGroupHierarchy200ResponseWithDefaults() *GetGroupHierarchy200Response`

NewGetGroupHierarchy200ResponseWithDefaults instantiates a new GetGroupHierarchy200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetGroupHierarchy200Response) GetData() []GroupHierarchyNode`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetGroupHierarchy200Response) GetDataOk() (*[]GroupHierarchyNode, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetGroupHierarchy200Response) SetData(v []GroupHierarchyNode)`

SetData sets Data field to given value.

### HasData

`func (o *GetGroupHierarchy200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


