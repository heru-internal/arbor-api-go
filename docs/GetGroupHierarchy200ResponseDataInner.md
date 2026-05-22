# GetGroupHierarchy200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Name** | **string** |  | 
**IsConfigured** | **bool** |  | 
**DeviceCount** | Pointer to **int32** | Only present for configured groups | [optional] 
**Children** | Pointer to [**[]Object**](Object.md) | Only present for unconfigured groups | [optional] 
**CreatedAt** | **Time** |  | 
**UpdatedAt** | **Time** |  | 

## Methods

### NewGetGroupHierarchy200ResponseDataInner

`func NewGetGroupHierarchy200ResponseDataInner(id string, name string, isConfigured bool, createdAt Time, updatedAt Time, ) *GetGroupHierarchy200ResponseDataInner`

NewGetGroupHierarchy200ResponseDataInner instantiates a new GetGroupHierarchy200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetGroupHierarchy200ResponseDataInnerWithDefaults

`func NewGetGroupHierarchy200ResponseDataInnerWithDefaults() *GetGroupHierarchy200ResponseDataInner`

NewGetGroupHierarchy200ResponseDataInnerWithDefaults instantiates a new GetGroupHierarchy200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetGroupHierarchy200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetGroupHierarchy200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetGroupHierarchy200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *GetGroupHierarchy200ResponseDataInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GetGroupHierarchy200ResponseDataInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GetGroupHierarchy200ResponseDataInner) SetName(v string)`

SetName sets Name field to given value.


### GetIsConfigured

`func (o *GetGroupHierarchy200ResponseDataInner) GetIsConfigured() bool`

GetIsConfigured returns the IsConfigured field if non-nil, zero value otherwise.

### GetIsConfiguredOk

`func (o *GetGroupHierarchy200ResponseDataInner) GetIsConfiguredOk() (*bool, bool)`

GetIsConfiguredOk returns a tuple with the IsConfigured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsConfigured

`func (o *GetGroupHierarchy200ResponseDataInner) SetIsConfigured(v bool)`

SetIsConfigured sets IsConfigured field to given value.


### GetDeviceCount

`func (o *GetGroupHierarchy200ResponseDataInner) GetDeviceCount() int32`

GetDeviceCount returns the DeviceCount field if non-nil, zero value otherwise.

### GetDeviceCountOk

`func (o *GetGroupHierarchy200ResponseDataInner) GetDeviceCountOk() (*int32, bool)`

GetDeviceCountOk returns a tuple with the DeviceCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceCount

`func (o *GetGroupHierarchy200ResponseDataInner) SetDeviceCount(v int32)`

SetDeviceCount sets DeviceCount field to given value.

### HasDeviceCount

`func (o *GetGroupHierarchy200ResponseDataInner) HasDeviceCount() bool`

HasDeviceCount returns a boolean if a field has been set.

### GetChildren

`func (o *GetGroupHierarchy200ResponseDataInner) GetChildren() []Object`

GetChildren returns the Children field if non-nil, zero value otherwise.

### GetChildrenOk

`func (o *GetGroupHierarchy200ResponseDataInner) GetChildrenOk() (*[]Object, bool)`

GetChildrenOk returns a tuple with the Children field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChildren

`func (o *GetGroupHierarchy200ResponseDataInner) SetChildren(v []Object)`

SetChildren sets Children field to given value.

### HasChildren

`func (o *GetGroupHierarchy200ResponseDataInner) HasChildren() bool`

HasChildren returns a boolean if a field has been set.

### GetCreatedAt

`func (o *GetGroupHierarchy200ResponseDataInner) GetCreatedAt() Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetGroupHierarchy200ResponseDataInner) GetCreatedAtOk() (*Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetGroupHierarchy200ResponseDataInner) SetCreatedAt(v Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *GetGroupHierarchy200ResponseDataInner) GetUpdatedAt() Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetGroupHierarchy200ResponseDataInner) GetUpdatedAtOk() (*Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetGroupHierarchy200ResponseDataInner) SetUpdatedAt(v Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


