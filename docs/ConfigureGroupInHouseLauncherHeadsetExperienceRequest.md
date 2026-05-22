# ConfigureGroupInHouseLauncherHeadsetExperienceRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LauncherContent** | [**ConfigureGroupInHouseLauncherHeadsetExperienceRequestLauncherContent**](ConfigureGroupInHouseLauncherHeadsetExperienceRequestLauncherContent.md) |  | 
**VisibleContents** | [**[]ConfigureGroupInHouseLauncherHeadsetExperienceRequestVisibleContentsInner**](ConfigureGroupInHouseLauncherHeadsetExperienceRequestVisibleContentsInner.md) | Array of apps visible in the custom launcher | 
**ReturnToLauncherViaHomeButton** | **bool** | Whether pressing the home button returns to the custom launcher | 
**SharedModeSettings** | Pointer to [**ConfigureGroupArborXrKioskHeadsetExperienceRequestSharedModeSettings**](ConfigureGroupArborXrKioskHeadsetExperienceRequestSharedModeSettings.md) |  | [optional] 

## Methods

### NewConfigureGroupInHouseLauncherHeadsetExperienceRequest

`func NewConfigureGroupInHouseLauncherHeadsetExperienceRequest(launcherContent ConfigureGroupInHouseLauncherHeadsetExperienceRequestLauncherContent, visibleContents []ConfigureGroupInHouseLauncherHeadsetExperienceRequestVisibleContentsInner, returnToLauncherViaHomeButton bool, ) *ConfigureGroupInHouseLauncherHeadsetExperienceRequest`

NewConfigureGroupInHouseLauncherHeadsetExperienceRequest instantiates a new ConfigureGroupInHouseLauncherHeadsetExperienceRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConfigureGroupInHouseLauncherHeadsetExperienceRequestWithDefaults

`func NewConfigureGroupInHouseLauncherHeadsetExperienceRequestWithDefaults() *ConfigureGroupInHouseLauncherHeadsetExperienceRequest`

NewConfigureGroupInHouseLauncherHeadsetExperienceRequestWithDefaults instantiates a new ConfigureGroupInHouseLauncherHeadsetExperienceRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLauncherContent

`func (o *ConfigureGroupInHouseLauncherHeadsetExperienceRequest) GetLauncherContent() ConfigureGroupInHouseLauncherHeadsetExperienceRequestLauncherContent`

GetLauncherContent returns the LauncherContent field if non-nil, zero value otherwise.

### GetLauncherContentOk

`func (o *ConfigureGroupInHouseLauncherHeadsetExperienceRequest) GetLauncherContentOk() (*ConfigureGroupInHouseLauncherHeadsetExperienceRequestLauncherContent, bool)`

GetLauncherContentOk returns a tuple with the LauncherContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLauncherContent

`func (o *ConfigureGroupInHouseLauncherHeadsetExperienceRequest) SetLauncherContent(v ConfigureGroupInHouseLauncherHeadsetExperienceRequestLauncherContent)`

SetLauncherContent sets LauncherContent field to given value.


### GetVisibleContents

`func (o *ConfigureGroupInHouseLauncherHeadsetExperienceRequest) GetVisibleContents() []ConfigureGroupInHouseLauncherHeadsetExperienceRequestVisibleContentsInner`

GetVisibleContents returns the VisibleContents field if non-nil, zero value otherwise.

### GetVisibleContentsOk

`func (o *ConfigureGroupInHouseLauncherHeadsetExperienceRequest) GetVisibleContentsOk() (*[]ConfigureGroupInHouseLauncherHeadsetExperienceRequestVisibleContentsInner, bool)`

GetVisibleContentsOk returns a tuple with the VisibleContents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibleContents

`func (o *ConfigureGroupInHouseLauncherHeadsetExperienceRequest) SetVisibleContents(v []ConfigureGroupInHouseLauncherHeadsetExperienceRequestVisibleContentsInner)`

SetVisibleContents sets VisibleContents field to given value.


### GetReturnToLauncherViaHomeButton

`func (o *ConfigureGroupInHouseLauncherHeadsetExperienceRequest) GetReturnToLauncherViaHomeButton() bool`

GetReturnToLauncherViaHomeButton returns the ReturnToLauncherViaHomeButton field if non-nil, zero value otherwise.

### GetReturnToLauncherViaHomeButtonOk

`func (o *ConfigureGroupInHouseLauncherHeadsetExperienceRequest) GetReturnToLauncherViaHomeButtonOk() (*bool, bool)`

GetReturnToLauncherViaHomeButtonOk returns a tuple with the ReturnToLauncherViaHomeButton field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnToLauncherViaHomeButton

`func (o *ConfigureGroupInHouseLauncherHeadsetExperienceRequest) SetReturnToLauncherViaHomeButton(v bool)`

SetReturnToLauncherViaHomeButton sets ReturnToLauncherViaHomeButton field to given value.


### GetSharedModeSettings

`func (o *ConfigureGroupInHouseLauncherHeadsetExperienceRequest) GetSharedModeSettings() ConfigureGroupArborXrKioskHeadsetExperienceRequestSharedModeSettings`

GetSharedModeSettings returns the SharedModeSettings field if non-nil, zero value otherwise.

### GetSharedModeSettingsOk

`func (o *ConfigureGroupInHouseLauncherHeadsetExperienceRequest) GetSharedModeSettingsOk() (*ConfigureGroupArborXrKioskHeadsetExperienceRequestSharedModeSettings, bool)`

GetSharedModeSettingsOk returns a tuple with the SharedModeSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedModeSettings

`func (o *ConfigureGroupInHouseLauncherHeadsetExperienceRequest) SetSharedModeSettings(v ConfigureGroupArborXrKioskHeadsetExperienceRequestSharedModeSettings)`

SetSharedModeSettings sets SharedModeSettings field to given value.

### HasSharedModeSettings

`func (o *ConfigureGroupInHouseLauncherHeadsetExperienceRequest) HasSharedModeSettings() bool`

HasSharedModeSettings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


