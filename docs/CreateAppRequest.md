# CreateAppRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | The name of the app. | 
**DeviceModelIds** | Pointer to **[]string** | Array of device model IDs that this app is compatible with. Use the GET /device-models?full&#x3D;true endpoint to get the list of available device model IDs. | [optional] 

## Methods

### NewCreateAppRequest

`func NewCreateAppRequest(name string, ) *CreateAppRequest`

NewCreateAppRequest instantiates a new CreateAppRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAppRequestWithDefaults

`func NewCreateAppRequestWithDefaults() *CreateAppRequest`

NewCreateAppRequestWithDefaults instantiates a new CreateAppRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateAppRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateAppRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateAppRequest) SetName(v string)`

SetName sets Name field to given value.


### GetDeviceModelIds

`func (o *CreateAppRequest) GetDeviceModelIds() []string`

GetDeviceModelIds returns the DeviceModelIds field if non-nil, zero value otherwise.

### GetDeviceModelIdsOk

`func (o *CreateAppRequest) GetDeviceModelIdsOk() (*[]string, bool)`

GetDeviceModelIdsOk returns a tuple with the DeviceModelIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceModelIds

`func (o *CreateAppRequest) SetDeviceModelIds(v []string)`

SetDeviceModelIds sets DeviceModelIds field to given value.

### HasDeviceModelIds

`func (o *CreateAppRequest) HasDeviceModelIds() bool`

HasDeviceModelIds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


