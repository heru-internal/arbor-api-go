# GetAppSessions200ResponseDataInnerDevice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The unique identifier of the device. | [optional] 
**Name** | Pointer to **string** | The name of the device. | [optional] 
**Serial** | Pointer to **string** | The serial number of the device. | [optional] 
**Group** | Pointer to [**NullableGetAppSessions200ResponseDataInnerDeviceGroup**](GetAppSessions200ResponseDataInnerDeviceGroup.md) |  | [optional] 

## Methods

### NewGetAppSessions200ResponseDataInnerDevice

`func NewGetAppSessions200ResponseDataInnerDevice() *GetAppSessions200ResponseDataInnerDevice`

NewGetAppSessions200ResponseDataInnerDevice instantiates a new GetAppSessions200ResponseDataInnerDevice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetAppSessions200ResponseDataInnerDeviceWithDefaults

`func NewGetAppSessions200ResponseDataInnerDeviceWithDefaults() *GetAppSessions200ResponseDataInnerDevice`

NewGetAppSessions200ResponseDataInnerDeviceWithDefaults instantiates a new GetAppSessions200ResponseDataInnerDevice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetAppSessions200ResponseDataInnerDevice) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetAppSessions200ResponseDataInnerDevice) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetAppSessions200ResponseDataInnerDevice) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *GetAppSessions200ResponseDataInnerDevice) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *GetAppSessions200ResponseDataInnerDevice) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GetAppSessions200ResponseDataInnerDevice) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GetAppSessions200ResponseDataInnerDevice) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *GetAppSessions200ResponseDataInnerDevice) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSerial

`func (o *GetAppSessions200ResponseDataInnerDevice) GetSerial() string`

GetSerial returns the Serial field if non-nil, zero value otherwise.

### GetSerialOk

`func (o *GetAppSessions200ResponseDataInnerDevice) GetSerialOk() (*string, bool)`

GetSerialOk returns a tuple with the Serial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerial

`func (o *GetAppSessions200ResponseDataInnerDevice) SetSerial(v string)`

SetSerial sets Serial field to given value.

### HasSerial

`func (o *GetAppSessions200ResponseDataInnerDevice) HasSerial() bool`

HasSerial returns a boolean if a field has been set.

### GetGroup

`func (o *GetAppSessions200ResponseDataInnerDevice) GetGroup() GetAppSessions200ResponseDataInnerDeviceGroup`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *GetAppSessions200ResponseDataInnerDevice) GetGroupOk() (*GetAppSessions200ResponseDataInnerDeviceGroup, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *GetAppSessions200ResponseDataInnerDevice) SetGroup(v GetAppSessions200ResponseDataInnerDeviceGroup)`

SetGroup sets Group field to given value.

### HasGroup

`func (o *GetAppSessions200ResponseDataInnerDevice) HasGroup() bool`

HasGroup returns a boolean if a field has been set.

### SetGroupNil

`func (o *GetAppSessions200ResponseDataInnerDevice) SetGroupNil(b bool)`

 SetGroupNil sets the value for Group to be an explicit nil

### UnsetGroup
`func (o *GetAppSessions200ResponseDataInnerDevice) UnsetGroup()`

UnsetGroup ensures that no value is present for Group, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


