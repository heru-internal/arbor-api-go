# GetGroupHeadsetExperience200ResponseOneOf1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Mode** | **string** |  | 
**KioskContent** | Pointer to [**NullableGetGroupHeadsetExperience200ResponseOneOf1KioskContent**](GetGroupHeadsetExperience200ResponseOneOf1KioskContent.md) |  | [optional] 
**IsMenuEnabled** | **bool** |  | 
**Shortcuts** | Pointer to **[]string** | Present when isMenuEnabled is true | [optional] 
**AdminPin** | Pointer to **NullableString** | Present when isMenuEnabled is true | [optional] 
**Background** | Pointer to [**NullableGetGroupHeadsetExperience200ResponseOneOfBackground**](GetGroupHeadsetExperience200ResponseOneOfBackground.md) |  | [optional] 
**ThemeId** | Pointer to **NullableString** | Present when isMenuEnabled is true | [optional] 
**Language** | Pointer to **NullableString** | Present when isMenuEnabled is true | [optional] 
**MenuIconImageId** | Pointer to **NullableString** | Present when isMenuEnabled is true | [optional] 
**RemovePoweredByArborXrBranding** | Pointer to **bool** | Present when isMenuEnabled is true | [optional] 
**SharedModeSettings** | [**GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings**](GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings.md) |  | 
**CreatedAt** | **Time** |  | 
**UpdatedAt** | **Time** |  | 

## Methods

### NewGetGroupHeadsetExperience200ResponseOneOf1

`func NewGetGroupHeadsetExperience200ResponseOneOf1(id string, mode string, isMenuEnabled bool, sharedModeSettings GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings, createdAt Time, updatedAt Time, ) *GetGroupHeadsetExperience200ResponseOneOf1`

NewGetGroupHeadsetExperience200ResponseOneOf1 instantiates a new GetGroupHeadsetExperience200ResponseOneOf1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetGroupHeadsetExperience200ResponseOneOf1WithDefaults

`func NewGetGroupHeadsetExperience200ResponseOneOf1WithDefaults() *GetGroupHeadsetExperience200ResponseOneOf1`

NewGetGroupHeadsetExperience200ResponseOneOf1WithDefaults instantiates a new GetGroupHeadsetExperience200ResponseOneOf1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) SetId(v string)`

SetId sets Id field to given value.


### GetMode

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) SetMode(v string)`

SetMode sets Mode field to given value.


### GetKioskContent

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetKioskContent() GetGroupHeadsetExperience200ResponseOneOf1KioskContent`

GetKioskContent returns the KioskContent field if non-nil, zero value otherwise.

### GetKioskContentOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetKioskContentOk() (*GetGroupHeadsetExperience200ResponseOneOf1KioskContent, bool)`

GetKioskContentOk returns a tuple with the KioskContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKioskContent

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) SetKioskContent(v GetGroupHeadsetExperience200ResponseOneOf1KioskContent)`

SetKioskContent sets KioskContent field to given value.

### HasKioskContent

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) HasKioskContent() bool`

HasKioskContent returns a boolean if a field has been set.

### SetKioskContentNil

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) SetKioskContentNil(b bool)`

 SetKioskContentNil sets the value for KioskContent to be an explicit nil

### UnsetKioskContent
`func (o *GetGroupHeadsetExperience200ResponseOneOf1) UnsetKioskContent()`

UnsetKioskContent ensures that no value is present for KioskContent, not even an explicit nil
### GetIsMenuEnabled

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetIsMenuEnabled() bool`

GetIsMenuEnabled returns the IsMenuEnabled field if non-nil, zero value otherwise.

### GetIsMenuEnabledOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetIsMenuEnabledOk() (*bool, bool)`

GetIsMenuEnabledOk returns a tuple with the IsMenuEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsMenuEnabled

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) SetIsMenuEnabled(v bool)`

SetIsMenuEnabled sets IsMenuEnabled field to given value.


### GetShortcuts

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetShortcuts() []string`

GetShortcuts returns the Shortcuts field if non-nil, zero value otherwise.

### GetShortcutsOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetShortcutsOk() (*[]string, bool)`

GetShortcutsOk returns a tuple with the Shortcuts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortcuts

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) SetShortcuts(v []string)`

SetShortcuts sets Shortcuts field to given value.

### HasShortcuts

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) HasShortcuts() bool`

HasShortcuts returns a boolean if a field has been set.

### GetAdminPin

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetAdminPin() string`

GetAdminPin returns the AdminPin field if non-nil, zero value otherwise.

### GetAdminPinOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetAdminPinOk() (*string, bool)`

GetAdminPinOk returns a tuple with the AdminPin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminPin

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) SetAdminPin(v string)`

SetAdminPin sets AdminPin field to given value.

### HasAdminPin

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) HasAdminPin() bool`

HasAdminPin returns a boolean if a field has been set.

### SetAdminPinNil

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) SetAdminPinNil(b bool)`

 SetAdminPinNil sets the value for AdminPin to be an explicit nil

### UnsetAdminPin
`func (o *GetGroupHeadsetExperience200ResponseOneOf1) UnsetAdminPin()`

UnsetAdminPin ensures that no value is present for AdminPin, not even an explicit nil
### GetBackground

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetBackground() GetGroupHeadsetExperience200ResponseOneOfBackground`

GetBackground returns the Background field if non-nil, zero value otherwise.

### GetBackgroundOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetBackgroundOk() (*GetGroupHeadsetExperience200ResponseOneOfBackground, bool)`

GetBackgroundOk returns a tuple with the Background field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackground

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) SetBackground(v GetGroupHeadsetExperience200ResponseOneOfBackground)`

SetBackground sets Background field to given value.

### HasBackground

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) HasBackground() bool`

HasBackground returns a boolean if a field has been set.

### SetBackgroundNil

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) SetBackgroundNil(b bool)`

 SetBackgroundNil sets the value for Background to be an explicit nil

### UnsetBackground
`func (o *GetGroupHeadsetExperience200ResponseOneOf1) UnsetBackground()`

UnsetBackground ensures that no value is present for Background, not even an explicit nil
### GetThemeId

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetThemeId() string`

GetThemeId returns the ThemeId field if non-nil, zero value otherwise.

### GetThemeIdOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetThemeIdOk() (*string, bool)`

GetThemeIdOk returns a tuple with the ThemeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThemeId

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) SetThemeId(v string)`

SetThemeId sets ThemeId field to given value.

### HasThemeId

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) HasThemeId() bool`

HasThemeId returns a boolean if a field has been set.

### SetThemeIdNil

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) SetThemeIdNil(b bool)`

 SetThemeIdNil sets the value for ThemeId to be an explicit nil

### UnsetThemeId
`func (o *GetGroupHeadsetExperience200ResponseOneOf1) UnsetThemeId()`

UnsetThemeId ensures that no value is present for ThemeId, not even an explicit nil
### GetLanguage

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### SetLanguageNil

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) SetLanguageNil(b bool)`

 SetLanguageNil sets the value for Language to be an explicit nil

### UnsetLanguage
`func (o *GetGroupHeadsetExperience200ResponseOneOf1) UnsetLanguage()`

UnsetLanguage ensures that no value is present for Language, not even an explicit nil
### GetMenuIconImageId

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetMenuIconImageId() string`

GetMenuIconImageId returns the MenuIconImageId field if non-nil, zero value otherwise.

### GetMenuIconImageIdOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetMenuIconImageIdOk() (*string, bool)`

GetMenuIconImageIdOk returns a tuple with the MenuIconImageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMenuIconImageId

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) SetMenuIconImageId(v string)`

SetMenuIconImageId sets MenuIconImageId field to given value.

### HasMenuIconImageId

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) HasMenuIconImageId() bool`

HasMenuIconImageId returns a boolean if a field has been set.

### SetMenuIconImageIdNil

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) SetMenuIconImageIdNil(b bool)`

 SetMenuIconImageIdNil sets the value for MenuIconImageId to be an explicit nil

### UnsetMenuIconImageId
`func (o *GetGroupHeadsetExperience200ResponseOneOf1) UnsetMenuIconImageId()`

UnsetMenuIconImageId ensures that no value is present for MenuIconImageId, not even an explicit nil
### GetRemovePoweredByArborXrBranding

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetRemovePoweredByArborXrBranding() bool`

GetRemovePoweredByArborXrBranding returns the RemovePoweredByArborXrBranding field if non-nil, zero value otherwise.

### GetRemovePoweredByArborXrBrandingOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetRemovePoweredByArborXrBrandingOk() (*bool, bool)`

GetRemovePoweredByArborXrBrandingOk returns a tuple with the RemovePoweredByArborXrBranding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemovePoweredByArborXrBranding

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) SetRemovePoweredByArborXrBranding(v bool)`

SetRemovePoweredByArborXrBranding sets RemovePoweredByArborXrBranding field to given value.

### HasRemovePoweredByArborXrBranding

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) HasRemovePoweredByArborXrBranding() bool`

HasRemovePoweredByArborXrBranding returns a boolean if a field has been set.

### GetSharedModeSettings

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetSharedModeSettings() GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings`

GetSharedModeSettings returns the SharedModeSettings field if non-nil, zero value otherwise.

### GetSharedModeSettingsOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetSharedModeSettingsOk() (*GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings, bool)`

GetSharedModeSettingsOk returns a tuple with the SharedModeSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedModeSettings

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) SetSharedModeSettings(v GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings)`

SetSharedModeSettings sets SharedModeSettings field to given value.


### GetCreatedAt

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetCreatedAt() Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetCreatedAtOk() (*Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) SetCreatedAt(v Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetUpdatedAt() Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) GetUpdatedAtOk() (*Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetGroupHeadsetExperience200ResponseOneOf1) SetUpdatedAt(v Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


