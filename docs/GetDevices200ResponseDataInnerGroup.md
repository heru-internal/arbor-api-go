# GetDevices200ResponseDataInnerGroup

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Name** | **string** |  | 
**DeviceCount** | Pointer to **NullableInt32** | Number of devices in this group. Only present for configured groups. | [optional] 
**IsConfigured** | **bool** |  | 
**Parent** | Pointer to [**NullableGetDevices200ResponseDataInnerGroupParent**](GetDevices200ResponseDataInnerGroupParent.md) |  | [optional] 
**CreatedAt** | **Time** |  | 
**UpdatedAt** | **Time** |  | 

## Methods

### NewGetDevices200ResponseDataInnerGroup

`func NewGetDevices200ResponseDataInnerGroup(id string, name string, isConfigured bool, createdAt Time, updatedAt Time, ) *GetDevices200ResponseDataInnerGroup`

NewGetDevices200ResponseDataInnerGroup instantiates a new GetDevices200ResponseDataInnerGroup object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetDevices200ResponseDataInnerGroupWithDefaults

`func NewGetDevices200ResponseDataInnerGroupWithDefaults() *GetDevices200ResponseDataInnerGroup`

NewGetDevices200ResponseDataInnerGroupWithDefaults instantiates a new GetDevices200ResponseDataInnerGroup object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetDevices200ResponseDataInnerGroup) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetDevices200ResponseDataInnerGroup) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetDevices200ResponseDataInnerGroup) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *GetDevices200ResponseDataInnerGroup) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GetDevices200ResponseDataInnerGroup) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GetDevices200ResponseDataInnerGroup) SetName(v string)`

SetName sets Name field to given value.


### GetDeviceCount

`func (o *GetDevices200ResponseDataInnerGroup) GetDeviceCount() int32`

GetDeviceCount returns the DeviceCount field if non-nil, zero value otherwise.

### GetDeviceCountOk

`func (o *GetDevices200ResponseDataInnerGroup) GetDeviceCountOk() (*int32, bool)`

GetDeviceCountOk returns a tuple with the DeviceCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceCount

`func (o *GetDevices200ResponseDataInnerGroup) SetDeviceCount(v int32)`

SetDeviceCount sets DeviceCount field to given value.

### HasDeviceCount

`func (o *GetDevices200ResponseDataInnerGroup) HasDeviceCount() bool`

HasDeviceCount returns a boolean if a field has been set.

### SetDeviceCountNil

`func (o *GetDevices200ResponseDataInnerGroup) SetDeviceCountNil(b bool)`

 SetDeviceCountNil sets the value for DeviceCount to be an explicit nil

### UnsetDeviceCount
`func (o *GetDevices200ResponseDataInnerGroup) UnsetDeviceCount()`

UnsetDeviceCount ensures that no value is present for DeviceCount, not even an explicit nil
### GetIsConfigured

`func (o *GetDevices200ResponseDataInnerGroup) GetIsConfigured() bool`

GetIsConfigured returns the IsConfigured field if non-nil, zero value otherwise.

### GetIsConfiguredOk

`func (o *GetDevices200ResponseDataInnerGroup) GetIsConfiguredOk() (*bool, bool)`

GetIsConfiguredOk returns a tuple with the IsConfigured field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsConfigured

`func (o *GetDevices200ResponseDataInnerGroup) SetIsConfigured(v bool)`

SetIsConfigured sets IsConfigured field to given value.


### GetParent

`func (o *GetDevices200ResponseDataInnerGroup) GetParent() GetDevices200ResponseDataInnerGroupParent`

GetParent returns the Parent field if non-nil, zero value otherwise.

### GetParentOk

`func (o *GetDevices200ResponseDataInnerGroup) GetParentOk() (*GetDevices200ResponseDataInnerGroupParent, bool)`

GetParentOk returns a tuple with the Parent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParent

`func (o *GetDevices200ResponseDataInnerGroup) SetParent(v GetDevices200ResponseDataInnerGroupParent)`

SetParent sets Parent field to given value.

### HasParent

`func (o *GetDevices200ResponseDataInnerGroup) HasParent() bool`

HasParent returns a boolean if a field has been set.

### SetParentNil

`func (o *GetDevices200ResponseDataInnerGroup) SetParentNil(b bool)`

 SetParentNil sets the value for Parent to be an explicit nil

### UnsetParent
`func (o *GetDevices200ResponseDataInnerGroup) UnsetParent()`

UnsetParent ensures that no value is present for Parent, not even an explicit nil
### GetCreatedAt

`func (o *GetDevices200ResponseDataInnerGroup) GetCreatedAt() Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetDevices200ResponseDataInnerGroup) GetCreatedAtOk() (*Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetDevices200ResponseDataInnerGroup) SetCreatedAt(v Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *GetDevices200ResponseDataInnerGroup) GetUpdatedAt() Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetDevices200ResponseDataInnerGroup) GetUpdatedAtOk() (*Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetDevices200ResponseDataInnerGroup) SetUpdatedAt(v Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


