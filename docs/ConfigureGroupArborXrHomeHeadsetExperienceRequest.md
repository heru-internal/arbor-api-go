# ConfigureGroupArborXrHomeHeadsetExperienceRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**VisibleContents** | [**[]ConfigureGroupArborXrHomeHeadsetExperienceRequestVisibleContentsInner**](ConfigureGroupArborXrHomeHeadsetExperienceRequestVisibleContentsInner.md) | Array of content items visible in the ArborXR Home experience | 
**Language** | **string** | Language for the headset experience | 
**MenuTitle** | **string** | Title displayed in the menu | 
**MenuIconImageId** | **string** | UUID of the image to use as menu icon | 
**RemovePoweredByArborXrBranding** | **bool** | Whether to remove &#39;Powered by ArborXR&#39; branding | 
**Shortcuts** | **[]string** | Array of shortcuts to enable | 
**AdminPin** | **NullableString** | Numeric admin PIN (4-10 digits) | 
**CategorizationTags** | **[]string** | Array of tags for categorization | 
**Background** | [**ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground**](ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground.md) |  | 
**ThemeId** | **string** | UUID of the theme to apply | 
**SharedModeSettings** | Pointer to [**ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings**](ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings.md) |  | [optional] 

## Methods

### NewConfigureGroupArborXrHomeHeadsetExperienceRequest

`func NewConfigureGroupArborXrHomeHeadsetExperienceRequest(visibleContents []ConfigureGroupArborXrHomeHeadsetExperienceRequestVisibleContentsInner, language string, menuTitle string, menuIconImageId string, removePoweredByArborXrBranding bool, shortcuts []string, adminPin NullableString, categorizationTags []string, background ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground, themeId string, ) *ConfigureGroupArborXrHomeHeadsetExperienceRequest`

NewConfigureGroupArborXrHomeHeadsetExperienceRequest instantiates a new ConfigureGroupArborXrHomeHeadsetExperienceRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConfigureGroupArborXrHomeHeadsetExperienceRequestWithDefaults

`func NewConfigureGroupArborXrHomeHeadsetExperienceRequestWithDefaults() *ConfigureGroupArborXrHomeHeadsetExperienceRequest`

NewConfigureGroupArborXrHomeHeadsetExperienceRequestWithDefaults instantiates a new ConfigureGroupArborXrHomeHeadsetExperienceRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVisibleContents

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetVisibleContents() []ConfigureGroupArborXrHomeHeadsetExperienceRequestVisibleContentsInner`

GetVisibleContents returns the VisibleContents field if non-nil, zero value otherwise.

### GetVisibleContentsOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetVisibleContentsOk() (*[]ConfigureGroupArborXrHomeHeadsetExperienceRequestVisibleContentsInner, bool)`

GetVisibleContentsOk returns a tuple with the VisibleContents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibleContents

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) SetVisibleContents(v []ConfigureGroupArborXrHomeHeadsetExperienceRequestVisibleContentsInner)`

SetVisibleContents sets VisibleContents field to given value.


### GetLanguage

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) SetLanguage(v string)`

SetLanguage sets Language field to given value.


### GetMenuTitle

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetMenuTitle() string`

GetMenuTitle returns the MenuTitle field if non-nil, zero value otherwise.

### GetMenuTitleOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetMenuTitleOk() (*string, bool)`

GetMenuTitleOk returns a tuple with the MenuTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMenuTitle

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) SetMenuTitle(v string)`

SetMenuTitle sets MenuTitle field to given value.


### GetMenuIconImageId

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetMenuIconImageId() string`

GetMenuIconImageId returns the MenuIconImageId field if non-nil, zero value otherwise.

### GetMenuIconImageIdOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetMenuIconImageIdOk() (*string, bool)`

GetMenuIconImageIdOk returns a tuple with the MenuIconImageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMenuIconImageId

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) SetMenuIconImageId(v string)`

SetMenuIconImageId sets MenuIconImageId field to given value.


### GetRemovePoweredByArborXrBranding

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetRemovePoweredByArborXrBranding() bool`

GetRemovePoweredByArborXrBranding returns the RemovePoweredByArborXrBranding field if non-nil, zero value otherwise.

### GetRemovePoweredByArborXrBrandingOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetRemovePoweredByArborXrBrandingOk() (*bool, bool)`

GetRemovePoweredByArborXrBrandingOk returns a tuple with the RemovePoweredByArborXrBranding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemovePoweredByArborXrBranding

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) SetRemovePoweredByArborXrBranding(v bool)`

SetRemovePoweredByArborXrBranding sets RemovePoweredByArborXrBranding field to given value.


### GetShortcuts

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetShortcuts() []string`

GetShortcuts returns the Shortcuts field if non-nil, zero value otherwise.

### GetShortcutsOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetShortcutsOk() (*[]string, bool)`

GetShortcutsOk returns a tuple with the Shortcuts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortcuts

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) SetShortcuts(v []string)`

SetShortcuts sets Shortcuts field to given value.


### GetAdminPin

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetAdminPin() string`

GetAdminPin returns the AdminPin field if non-nil, zero value otherwise.

### GetAdminPinOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetAdminPinOk() (*string, bool)`

GetAdminPinOk returns a tuple with the AdminPin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminPin

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) SetAdminPin(v string)`

SetAdminPin sets AdminPin field to given value.


### SetAdminPinNil

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) SetAdminPinNil(b bool)`

 SetAdminPinNil sets the value for AdminPin to be an explicit nil

### UnsetAdminPin
`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) UnsetAdminPin()`

UnsetAdminPin ensures that no value is present for AdminPin, not even an explicit nil
### GetCategorizationTags

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetCategorizationTags() []string`

GetCategorizationTags returns the CategorizationTags field if non-nil, zero value otherwise.

### GetCategorizationTagsOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetCategorizationTagsOk() (*[]string, bool)`

GetCategorizationTagsOk returns a tuple with the CategorizationTags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategorizationTags

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) SetCategorizationTags(v []string)`

SetCategorizationTags sets CategorizationTags field to given value.


### GetBackground

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetBackground() ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground`

GetBackground returns the Background field if non-nil, zero value otherwise.

### GetBackgroundOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetBackgroundOk() (*ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground, bool)`

GetBackgroundOk returns a tuple with the Background field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackground

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) SetBackground(v ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground)`

SetBackground sets Background field to given value.


### GetThemeId

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetThemeId() string`

GetThemeId returns the ThemeId field if non-nil, zero value otherwise.

### GetThemeIdOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetThemeIdOk() (*string, bool)`

GetThemeIdOk returns a tuple with the ThemeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThemeId

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) SetThemeId(v string)`

SetThemeId sets ThemeId field to given value.


### GetSharedModeSettings

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetSharedModeSettings() ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings`

GetSharedModeSettings returns the SharedModeSettings field if non-nil, zero value otherwise.

### GetSharedModeSettingsOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) GetSharedModeSettingsOk() (*ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings, bool)`

GetSharedModeSettingsOk returns a tuple with the SharedModeSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedModeSettings

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) SetSharedModeSettings(v ConfigureGroupArborXrHomeHeadsetExperienceRequestSharedModeSettings)`

SetSharedModeSettings sets SharedModeSettings field to given value.

### HasSharedModeSettings

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequest) HasSharedModeSettings() bool`

HasSharedModeSettings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


