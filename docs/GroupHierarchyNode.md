# GroupHierarchyNode

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Name** | **string** |  | 
**IsConfigured** | **bool** |  | 
**DeviceCount** | Pointer to **int32** | Only present for configured groups | [optional] 
**Children** | Pointer to [**[]GroupHierarchyNode**](GroupHierarchyNode.md) | Only present for unconfigured groups | [optional] 
**CreatedAt** | **Time** |  | 
**UpdatedAt** | **Time** |  | 

## Methods

### NewGroupHierarchyNode

`func NewGroupHierarchyNode(id string, name string, isConfigured bool, createdAt Time, updatedAt Time, ) *GroupHierarchyNode`

NewGroupHierarchyNode instantiates a new GroupHierarchyNode object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupHierarchyNodeWithDefaults

`func NewGroupHierarchyNodeWithDefaults() *GroupHierarchyNode`

NewGroupHierarchyNodeWithDefaults instantiates a new GroupHierarchyNode object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GroupHierarchyNode) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GroupHierarchyNode) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GroupHierarchyNode) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *GroupHierarchyNode) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GroupHierarchyNode) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GroupHierarchyNode) SetName(v string)`

SetName sets Name field to given value.


### GetIsConfigured

`func (o *GroupHierarchyNode) GetIsConfigured() bool`

GetIsConfigured returns the IsConfigured field if non-nil, zero value otherwise.

### GetIsConfiguredOk

`func (o *GroupHierarchyNode) GetIsConfiguredOk() (*bool, bool)`

GetIsConfiguredOk returns a tuple with the IsConfigured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsConfigured

`func (o *GroupHierarchyNode) SetIsConfigured(v bool)`

SetIsConfigured sets IsConfigured field to given value.


### GetDeviceCount

`func (o *GroupHierarchyNode) GetDeviceCount() int32`

GetDeviceCount returns the DeviceCount field if non-nil, zero value otherwise.

### GetDeviceCountOk

`func (o *GroupHierarchyNode) GetDeviceCountOk() (*int32, bool)`

GetDeviceCountOk returns a tuple with the DeviceCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceCount

`func (o *GroupHierarchyNode) SetDeviceCount(v int32)`

SetDeviceCount sets DeviceCount field to given value.

### HasDeviceCount

`func (o *GroupHierarchyNode) HasDeviceCount() bool`

HasDeviceCount returns a boolean if a field has been set.

### GetChildren

`func (o *GroupHierarchyNode) GetChildren() []GroupHierarchyNode`

GetChildren returns the Children field if non-nil, zero value otherwise.

### GetChildrenOk

`func (o *GroupHierarchyNode) GetChildrenOk() (*[]GroupHierarchyNode, bool)`

GetChildrenOk returns a tuple with the Children field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildren

`func (o *GroupHierarchyNode) SetChildren(v []GroupHierarchyNode)`

SetChildren sets Children field to given value.

### HasChildren

`func (o *GroupHierarchyNode) HasChildren() bool`

HasChildren returns a boolean if a field has been set.

### GetCreatedAt

`func (o *GroupHierarchyNode) GetCreatedAt() Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GroupHierarchyNode) GetCreatedAtOk() (*Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GroupHierarchyNode) SetCreatedAt(v Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *GroupHierarchyNode) GetUpdatedAt() Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GroupHierarchyNode) GetUpdatedAtOk() (*Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GroupHierarchyNode) SetUpdatedAt(v Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


