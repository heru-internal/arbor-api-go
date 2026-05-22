# MigrateDeviceToOrganizationRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**GroupId** | Pointer to **NullableString** | ID of the configured group in the target organization to assign the device to | [optional] 

## Methods

### NewMigrateDeviceToOrganizationRequest

`func NewMigrateDeviceToOrganizationRequest() *MigrateDeviceToOrganizationRequest`

NewMigrateDeviceToOrganizationRequest instantiates a new MigrateDeviceToOrganizationRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMigrateDeviceToOrganizationRequestWithDefaults

`func NewMigrateDeviceToOrganizationRequestWithDefaults() *MigrateDeviceToOrganizationRequest`

NewMigrateDeviceToOrganizationRequestWithDefaults instantiates a new MigrateDeviceToOrganizationRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGroupId

`func (o *MigrateDeviceToOrganizationRequest) GetGroupId() string`

GetGroupId returns the GroupId field if non-nil, zero value otherwise.

### GetGroupIdOk

`func (o *MigrateDeviceToOrganizationRequest) GetGroupIdOk() (*string, bool)`

GetGroupIdOk returns a tuple with the GroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupId

`func (o *MigrateDeviceToOrganizationRequest) SetGroupId(v string)`

SetGroupId sets GroupId field to given value.

### HasGroupId

`func (o *MigrateDeviceToOrganizationRequest) HasGroupId() bool`

HasGroupId returns a boolean if a field has been set.

### SetGroupIdNil

`func (o *MigrateDeviceToOrganizationRequest) SetGroupIdNil(b bool)`

 SetGroupIdNil sets the value for GroupId to be an explicit nil

### UnsetGroupId
`func (o *MigrateDeviceToOrganizationRequest) UnsetGroupId()`

UnsetGroupId ensures that no value is present for GroupId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


