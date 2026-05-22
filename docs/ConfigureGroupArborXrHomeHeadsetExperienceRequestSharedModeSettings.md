# ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EnableOfflineMode** | **bool** | Whether to enable offline mode | 
**RequireManagedMetaLogin** | **bool** | Whether to require managed Meta login | 
**RequiredPasswordComplexity** | Pointer to **NullableString** | Required password complexity level. Use this instead of requireSessionPasscode. | [optional] 
**RequireSessionPasscode** | Pointer to **bool** | Deprecated. Use requiredPasswordComplexity instead. true maps to LOW, false maps to NONE. | [optional] 
**SessionTimeout** | Pointer to **string** | Deprecated. Session timeout in minutes. | [optional] 
**EnableControllerFree** | **bool** | Whether to enable controller-free mode | 
**WakeControllers** | Pointer to **bool** | Whether to wake controllers (required when &#x60;enableControllerFree&#x60; is &#x60;false&#x60;) | [optional] 
**AdjustDeviceFit** | **bool** | Whether to adjust device fit | 
**DefaultToStationaryBoundary** | **bool** | Whether to default to stationary boundary | 

## Methods

### NewConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings

`func NewConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings(enableOfflineMode bool, requireManagedMetaLogin bool, enableControllerFree bool, adjustDeviceFit bool, defaultToStationaryBoundary bool, ) *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings`

NewConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings instantiates a new ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettingsWithDefaults

`func NewConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettingsWithDefaults() *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings`

NewConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettingsWithDefaults instantiates a new ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnableOfflineMode

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) GetEnableOfflineMode() bool`

GetEnableOfflineMode returns the EnableOfflineMode field if non-nil, zero value otherwise.

### GetEnableOfflineModeOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) GetEnableOfflineModeOk() (*bool, bool)`

GetEnableOfflineModeOk returns a tuple with the EnableOfflineMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableOfflineMode

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) SetEnableOfflineMode(v bool)`

SetEnableOfflineMode sets EnableOfflineMode field to given value.


### GetRequireManagedMetaLogin

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) GetRequireManagedMetaLogin() bool`

GetRequireManagedMetaLogin returns the RequireManagedMetaLogin field if non-nil, zero value otherwise.

### GetRequireManagedMetaLoginOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) GetRequireManagedMetaLoginOk() (*bool, bool)`

GetRequireManagedMetaLoginOk returns a tuple with the RequireManagedMetaLogin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequireManagedMetaLogin

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) SetRequireManagedMetaLogin(v bool)`

SetRequireManagedMetaLogin sets RequireManagedMetaLogin field to given value.


### GetRequiredPasswordComplexity

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) GetRequiredPasswordComplexity() string`

GetRequiredPasswordComplexity returns the RequiredPasswordComplexity field if non-nil, zero value otherwise.

### GetRequiredPasswordComplexityOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) GetRequiredPasswordComplexityOk() (*string, bool)`

GetRequiredPasswordComplexityOk returns a tuple with the RequiredPasswordComplexity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequiredPasswordComplexity

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) SetRequiredPasswordComplexity(v string)`

SetRequiredPasswordComplexity sets RequiredPasswordComplexity field to given value.

### HasRequiredPasswordComplexity

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) HasRequiredPasswordComplexity() bool`

HasRequiredPasswordComplexity returns a boolean if a field has been set.

### SetRequiredPasswordComplexityNil

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) SetRequiredPasswordComplexityNil(b bool)`

 SetRequiredPasswordComplexityNil sets the value for RequiredPasswordComplexity to be an explicit nil

### UnsetRequiredPasswordComplexity
`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) UnsetRequiredPasswordComplexity()`

UnsetRequiredPasswordComplexity ensures that no value is present for RequiredPasswordComplexity, not even an explicit nil
### GetRequireSessionPasscode

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) GetRequireSessionPasscode() bool`

GetRequireSessionPasscode returns the RequireSessionPasscode field if non-nil, zero value otherwise.

### GetRequireSessionPasscodeOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) GetRequireSessionPasscodeOk() (*bool, bool)`

GetRequireSessionPasscodeOk returns a tuple with the RequireSessionPasscode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequireSessionPasscode

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) SetRequireSessionPasscode(v bool)`

SetRequireSessionPasscode sets RequireSessionPasscode field to given value.

### HasRequireSessionPasscode

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) HasRequireSessionPasscode() bool`

HasRequireSessionPasscode returns a boolean if a field has been set.

### GetSessionTimeout

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) GetSessionTimeout() string`

GetSessionTimeout returns the SessionTimeout field if non-nil, zero value otherwise.

### GetSessionTimeoutOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) GetSessionTimeoutOk() (*string, bool)`

GetSessionTimeoutOk returns a tuple with the SessionTimeout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSessionTimeout

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) SetSessionTimeout(v string)`

SetSessionTimeout sets SessionTimeout field to given value.

### HasSessionTimeout

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) HasSessionTimeout() bool`

HasSessionTimeout returns a boolean if a field has been set.

### GetEnableControllerFree

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) GetEnableControllerFree() bool`

GetEnableControllerFree returns the EnableControllerFree field if non-nil, zero value otherwise.

### GetEnableControllerFreeOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) GetEnableControllerFreeOk() (*bool, bool)`

GetEnableControllerFreeOk returns a tuple with the EnableControllerFree field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnableControllerFree

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) SetEnableControllerFree(v bool)`

SetEnableControllerFree sets EnableControllerFree field to given value.


### GetWakeControllers

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) GetWakeControllers() bool`

GetWakeControllers returns the WakeControllers field if non-nil, zero value otherwise.

### GetWakeControllersOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) GetWakeControllersOk() (*bool, bool)`

GetWakeControllersOk returns a tuple with the WakeControllers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWakeControllers

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) SetWakeControllers(v bool)`

SetWakeControllers sets WakeControllers field to given value.

### HasWakeControllers

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) HasWakeControllers() bool`

HasWakeControllers returns a boolean if a field has been set.

### GetAdjustDeviceFit

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) GetAdjustDeviceFit() bool`

GetAdjustDeviceFit returns the AdjustDeviceFit field if non-nil, zero value otherwise.

### GetAdjustDeviceFitOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) GetAdjustDeviceFitOk() (*bool, bool)`

GetAdjustDeviceFitOk returns a tuple with the AdjustDeviceFit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdjustDeviceFit

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) SetAdjustDeviceFit(v bool)`

SetAdjustDeviceFit sets AdjustDeviceFit field to given value.


### GetDefaultToStationaryBoundary

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) GetDefaultToStationaryBoundary() bool`

GetDefaultToStationaryBoundary returns the DefaultToStationaryBoundary field if non-nil, zero value otherwise.

### GetDefaultToStationaryBoundaryOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) GetDefaultToStationaryBoundaryOk() (*bool, bool)`

GetDefaultToStationaryBoundaryOk returns a tuple with the DefaultToStationaryBoundary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultToStationaryBoundary

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings) SetDefaultToStationaryBoundary(v bool)`

SetDefaultToStationaryBoundary sets DefaultToStationaryBoundary field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


