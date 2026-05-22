# ConfigureGroupArborXrKioskHeadsetExperienceRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**KioskContent** | [**ConfigureGroupArborXrKioskHeadsetExperienceRequestKioskContent**](ConfigureGroupArborXrKioskHeadsetExperienceRequestKioskContent.md) |  | 
**IsMenuEnabled** | **bool** | Whether to enable the menu in kiosk mode | 
**Language** | Pointer to **string** | Language for the headset experience (required when isMenuEnabled is true) | [optional] 
**MenuIconImageId** | Pointer to **string** | UUID of the image to use as menu icon (required when isMenuEnabled is true) | [optional] 
**RemovePoweredByArborXrBranding** | Pointer to **bool** | Whether to remove &#39;Powered by ArborXR&#39; branding (required when isMenuEnabled is true) | [optional] 
**Shortcuts** | Pointer to **[]string** | Array of shortcuts to enable (present when isMenuEnabled is true) | [optional] 
**AdminPin** | Pointer to **NullableString** | Numeric admin PIN (4-10 digits, present when isMenuEnabled is true) | [optional] 
**Background** | Pointer to [**ConfigureGroupArborXrKioskHeadsetExperienceRequestBackground**](ConfigureGroupArborXrKioskHeadsetExperienceRequestBackground.md) |  | [optional] 
**ThemeId** | Pointer to **string** | UUID of the theme to apply (required when isMenuEnabled is true) | [optional] 
**SharedModeSettings** | Pointer to [**ConfigureGroupArborXrKioskHeadsetExperienceRequestSharedModeSettings**](ConfigureGroupArborXrKioskHeadsetExperienceRequestSharedModeSettings.md) |  | [optional] 

## Methods

### NewConfigureGroupArborXrKioskHeadsetExperienceRequest

`func NewConfigureGroupArborXrKioskHeadsetExperienceRequest(kioskContent ConfigureGroupArborXrKioskHeadsetExperienceRequestKioskContent, isMenuEnabled bool, ) *ConfigureGroupArborXrKioskHeadsetExperienceRequest`

NewConfigureGroupArborXrKioskHeadsetExperienceRequest instantiates a new ConfigureGroupArborXrKioskHeadsetExperienceRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConfigureGroupArborXrKioskHeadsetExperienceRequestWithDefaults

`func NewConfigureGroupArborXrKioskHeadsetExperienceRequestWithDefaults() *ConfigureGroupArborXrKioskHeadsetExperienceRequest`

NewConfigureGroupArborXrKioskHeadsetExperienceRequestWithDefaults instantiates a new ConfigureGroupArborXrKioskHeadsetExperienceRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKioskContent

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) GetKioskContent() ConfigureGroupArborXrKioskHeadsetExperienceRequestKioskContent`

GetKioskContent returns the KioskContent field if non-nil, zero value otherwise.

### GetKioskContentOk

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) GetKioskContentOk() (*ConfigureGroupArborXrKioskHeadsetExperienceRequestKioskContent, bool)`

GetKioskContentOk returns a tuple with the KioskContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKioskContent

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) SetKioskContent(v ConfigureGroupArborXrKioskHeadsetExperienceRequestKioskContent)`

SetKioskContent sets KioskContent field to given value.


### GetIsMenuEnabled

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) GetIsMenuEnabled() bool`

GetIsMenuEnabled returns the IsMenuEnabled field if non-nil, zero value otherwise.

### GetIsMenuEnabledOk

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) GetIsMenuEnabledOk() (*bool, bool)`

GetIsMenuEnabledOk returns a tuple with the IsMenuEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsMenuEnabled

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) SetIsMenuEnabled(v bool)`

SetIsMenuEnabled sets IsMenuEnabled field to given value.


### GetLanguage

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetMenuIconImageId

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) GetMenuIconImageId() string`

GetMenuIconImageId returns the MenuIconImageId field if non-nil, zero value otherwise.

### GetMenuIconImageIdOk

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) GetMenuIconImageIdOk() (*string, bool)`

GetMenuIconImageIdOk returns a tuple with the MenuIconImageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMenuIconImageId

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) SetMenuIconImageId(v string)`

SetMenuIconImageId sets MenuIconImageId field to given value.

### HasMenuIconImageId

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) HasMenuIconImageId() bool`

HasMenuIconImageId returns a boolean if a field has been set.

### GetRemovePoweredByArborXrBranding

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) GetRemovePoweredByArborXrBranding() bool`

GetRemovePoweredByArborXrBranding returns the RemovePoweredByArborXrBranding field if non-nil, zero value otherwise.

### GetRemovePoweredByArborXrBrandingOk

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) GetRemovePoweredByArborXrBrandingOk() (*bool, bool)`

GetRemovePoweredByArborXrBrandingOk returns a tuple with the RemovePoweredByArborXrBranding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemovePoweredByArborXrBranding

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) SetRemovePoweredByArborXrBranding(v bool)`

SetRemovePoweredByArborXrBranding sets RemovePoweredByArborXrBranding field to given value.

### HasRemovePoweredByArborXrBranding

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) HasRemovePoweredByArborXrBranding() bool`

HasRemovePoweredByArborXrBranding returns a boolean if a field has been set.

### GetShortcuts

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) GetShortcuts() []string`

GetShortcuts returns the Shortcuts field if non-nil, zero value otherwise.

### GetShortcutsOk

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) GetShortcutsOk() (*[]string, bool)`

GetShortcutsOk returns a tuple with the Shortcuts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortcuts

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) SetShortcuts(v []string)`

SetShortcuts sets Shortcuts field to given value.

### HasShortcuts

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) HasShortcuts() bool`

HasShortcuts returns a boolean if a field has been set.

### GetAdminPin

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) GetAdminPin() string`

GetAdminPin returns the AdminPin field if non-nil, zero value otherwise.

### GetAdminPinOk

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) GetAdminPinOk() (*string, bool)`

GetAdminPinOk returns a tuple with the AdminPin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminPin

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) SetAdminPin(v string)`

SetAdminPin sets AdminPin field to given value.

### HasAdminPin

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) HasAdminPin() bool`

HasAdminPin returns a boolean if a field has been set.

### SetAdminPinNil

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) SetAdminPinNil(b bool)`

 SetAdminPinNil sets the value for AdminPin to be an explicit nil

### UnsetAdminPin
`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) UnsetAdminPin()`

UnsetAdminPin ensures that no value is present for AdminPin, not even an explicit nil
### GetBackground

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) GetBackground() ConfigureGroupArborXrKioskHeadsetExperienceRequestBackground`

GetBackground returns the Background field if non-nil, zero value otherwise.

### GetBackgroundOk

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) GetBackgroundOk() (*ConfigureGroupArborXrKioskHeadsetExperienceRequestBackground, bool)`

GetBackgroundOk returns a tuple with the Background field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackground

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) SetBackground(v ConfigureGroupArborXrKioskHeadsetExperienceRequestBackground)`

SetBackground sets Background field to given value.

### HasBackground

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) HasBackground() bool`

HasBackground returns a boolean if a field has been set.

### GetThemeId

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) GetThemeId() string`

GetThemeId returns the ThemeId field if non-nil, zero value otherwise.

### GetThemeIdOk

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) GetThemeIdOk() (*string, bool)`

GetThemeIdOk returns a tuple with the ThemeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThemeId

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) SetThemeId(v string)`

SetThemeId sets ThemeId field to given value.

### HasThemeId

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) HasThemeId() bool`

HasThemeId returns a boolean if a field has been set.

### GetSharedModeSettings

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) GetSharedModeSettings() ConfigureGroupArborXrKioskHeadsetExperienceRequestSharedModeSettings`

GetSharedModeSettings returns the SharedModeSettings field if non-nil, zero value otherwise.

### GetSharedModeSettingsOk

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) GetSharedModeSettingsOk() (*ConfigureGroupArborXrKioskHeadsetExperienceRequestSharedModeSettings, bool)`

GetSharedModeSettingsOk returns a tuple with the SharedModeSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedModeSettings

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) SetSharedModeSettings(v ConfigureGroupArborXrKioskHeadsetExperienceRequestSharedModeSettings)`

SetSharedModeSettings sets SharedModeSettings field to given value.

### HasSharedModeSettings

`func (o *ConfigureGroupArborXrKioskHeadsetExperienceRequest) HasSharedModeSettings() bool`

HasSharedModeSettings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


