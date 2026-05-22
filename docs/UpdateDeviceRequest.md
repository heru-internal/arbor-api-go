# UpdateDeviceRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**GroupId** | Pointer to **NullableString** |  | [optional] 
**Tags** | Pointer to **[]string** |  | [optional] 

## Methods

### NewUpdateDeviceRequest

`func NewUpdateDeviceRequest() *UpdateDeviceRequest`

NewUpdateDeviceRequest instantiates a new UpdateDeviceRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateDeviceRequestWithDefaults

`func NewUpdateDeviceRequestWithDefaults() *UpdateDeviceRequest`

NewUpdateDeviceRequestWithDefaults instantiates a new UpdateDeviceRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateDeviceRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateDeviceRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateDeviceRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateDeviceRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetGroupId

`func (o *UpdateDeviceRequest) GetGroupId() string`

GetGroupId returns the GroupId field if non-nil, zero value otherwise.

### GetGroupIdOk

`func (o *UpdateDeviceRequest) GetGroupIdOk() (*string, bool)`

GetGroupIdOk returns a tuple with the GroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupId

`func (o *UpdateDeviceRequest) SetGroupId(v string)`

SetGroupId sets GroupId field to given value.

### HasGroupId

`func (o *UpdateDeviceRequest) HasGroupId() bool`

HasGroupId returns a boolean if a field has been set.

### SetGroupIdNil

`func (o *UpdateDeviceRequest) SetGroupIdNil(b bool)`

 SetGroupIdNil sets the value for GroupId to be an explicit nil

### UnsetGroupId
`func (o *UpdateDeviceRequest) UnsetGroupId()`

UnsetGroupId ensures that no value is present for GroupId, not even an explicit nil
### GetTags

`func (o *UpdateDeviceRequest) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *UpdateDeviceRequest) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *UpdateDeviceRequest) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *UpdateDeviceRequest) HasTags() bool`

HasTags returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


