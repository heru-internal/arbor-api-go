# ConfigureGroupInHouseLauncherDeviceExperienceRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LauncherContent** | [**ConfigureGroupInHouseLauncherHeadsetExperienceRequestVisibleContentsInner**](ConfigureGroupInHouseLauncherHeadsetExperienceRequestVisibleContentsInner.md) |  | 
**VisibleContents** | [**[]ConfigureGroupLockTaskDeviceExperienceRequestVisibleContentsInner**](ConfigureGroupLockTaskDeviceExperienceRequestVisibleContentsInner.md) | Array of apps visible within the in-house launcher | 

## Methods

### NewConfigureGroupInHouseLauncherDeviceExperienceRequest

`func NewConfigureGroupInHouseLauncherDeviceExperienceRequest(launcherContent ConfigureGroupInHouseLauncherHeadsetExperienceRequestVisibleContentsInner, visibleContents []ConfigureGroupLockTaskDeviceExperienceRequestVisibleContentsInner, ) *ConfigureGroupInHouseLauncherDeviceExperienceRequest`

NewConfigureGroupInHouseLauncherDeviceExperienceRequest instantiates a new ConfigureGroupInHouseLauncherDeviceExperienceRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConfigureGroupInHouseLauncherDeviceExperienceRequestWithDefaults

`func NewConfigureGroupInHouseLauncherDeviceExperienceRequestWithDefaults() *ConfigureGroupInHouseLauncherDeviceExperienceRequest`

NewConfigureGroupInHouseLauncherDeviceExperienceRequestWithDefaults instantiates a new ConfigureGroupInHouseLauncherDeviceExperienceRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLauncherContent

`func (o *ConfigureGroupInHouseLauncherDeviceExperienceRequest) GetLauncherContent() ConfigureGroupInHouseLauncherHeadsetExperienceRequestVisibleContentsInner`

GetLauncherContent returns the LauncherContent field if non-nil, zero value otherwise.

### GetLauncherContentOk

`func (o *ConfigureGroupInHouseLauncherDeviceExperienceRequest) GetLauncherContentOk() (*ConfigureGroupInHouseLauncherHeadsetExperienceRequestVisibleContentsInner, bool)`

GetLauncherContentOk returns a tuple with the LauncherContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLauncherContent

`func (o *ConfigureGroupInHouseLauncherDeviceExperienceRequest) SetLauncherContent(v ConfigureGroupInHouseLauncherHeadsetExperienceRequestVisibleContentsInner)`

SetLauncherContent sets LauncherContent field to given value.


### GetVisibleContents

`func (o *ConfigureGroupInHouseLauncherDeviceExperienceRequest) GetVisibleContents() []ConfigureGroupLockTaskDeviceExperienceRequestVisibleContentsInner`

GetVisibleContents returns the VisibleContents field if non-nil, zero value otherwise.

### GetVisibleContentsOk

`func (o *ConfigureGroupInHouseLauncherDeviceExperienceRequest) GetVisibleContentsOk() (*[]ConfigureGroupLockTaskDeviceExperienceRequestVisibleContentsInner, bool)`

GetVisibleContentsOk returns a tuple with the VisibleContents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibleContents

`func (o *ConfigureGroupInHouseLauncherDeviceExperienceRequest) SetVisibleContents(v []ConfigureGroupLockTaskDeviceExperienceRequestVisibleContentsInner)`

SetVisibleContents sets VisibleContents field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


