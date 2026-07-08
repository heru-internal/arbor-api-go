# GetGroupHeadsetExperience200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Mode** | **string** |  | 
**VisibleContents** | [**[]GetGroupHeadsetExperience200ResponseOneOfVisibleContentsInner**](GetGroupHeadsetExperience200ResponseOneOfVisibleContentsInner.md) |  | 
**Shortcuts** | **[]string** | Present when isMenuEnabled is true | 
**AdminPin** | Pointer to **NullableString** | Present when isMenuEnabled is true | [optional] 
**CategorizationTags** | **[]string** |  | 
**Background** | Pointer to [**NullableGetGroupHeadsetExperience200ResponseOneOfBackground**](GetGroupHeadsetExperience200ResponseOneOfBackground.md) |  | [optional] 
**ThemeId** | Pointer to **NullableString** | Present when isMenuEnabled is true | [optional] 
**Language** | Pointer to **NullableString** | Present when isMenuEnabled is true | [optional] 
**MenuTitle** | Pointer to **NullableString** |  | [optional] 
**MenuIconImageId** | Pointer to **NullableString** | Present when isMenuEnabled is true | [optional] 
**RemovePoweredByArborXrBranding** | **bool** | Present when isMenuEnabled is true | 
**SharedModeSettings** | [**GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings**](GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings.md) |  | 
**CreatedAt** | **Time** |  | 
**UpdatedAt** | **Time** |  | 
**KioskContent** | Pointer to [**NullableGetGroupHeadsetExperience200ResponseOneOf1KioskContent**](GetGroupHeadsetExperience200ResponseOneOf1KioskContent.md) |  | [optional] 
**IsMenuEnabled** | **bool** |  | 
**MetaHmsSettings** | [**ConfigureGroupDefaultHomeHeadsetExperienceRequestMetaHmsSettings**](ConfigureGroupDefaultHomeHeadsetExperienceRequestMetaHmsSettings.md) |  | 
**LauncherContent** | Pointer to [**NullableGetGroupHeadsetExperience200ResponseOneOf3LauncherContent**](GetGroupHeadsetExperience200ResponseOneOf3LauncherContent.md) |  | [optional] 
**ReturnToLauncherViaHomeButton** | **bool** |  | 

## Methods

### NewGetGroupHeadsetExperience200Response

`func NewGetGroupHeadsetExperience200Response(id string, mode string, visibleContents []GetGroupHeadsetExperience200ResponseOneOfVisibleContentsInner, shortcuts []string, categorizationTags []string, removePoweredByArborXrBranding bool, sharedModeSettings GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings, createdAt Time, updatedAt Time, isMenuEnabled bool, metaHmsSettings ConfigureGroupDefaultHomeHeadsetExperienceRequestMetaHmsSettings, returnToLauncherViaHomeButton bool, ) *GetGroupHeadsetExperience200Response`

NewGetGroupHeadsetExperience200Response instantiates a new GetGroupHeadsetExperience200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetGroupHeadsetExperience200ResponseWithDefaults

`func NewGetGroupHeadsetExperience200ResponseWithDefaults() *GetGroupHeadsetExperience200Response`

NewGetGroupHeadsetExperience200ResponseWithDefaults instantiates a new GetGroupHeadsetExperience200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetGroupHeadsetExperience200Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetGroupHeadsetExperience200Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetGroupHeadsetExperience200Response) SetId(v string)`

SetId sets Id field to given value.


### GetMode

`func (o *GetGroupHeadsetExperience200Response) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *GetGroupHeadsetExperience200Response) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *GetGroupHeadsetExperience200Response) SetMode(v string)`

SetMode sets Mode field to given value.


### GetVisibleContents

`func (o *GetGroupHeadsetExperience200Response) GetVisibleContents() []GetGroupHeadsetExperience200ResponseOneOfVisibleContentsInner`

GetVisibleContents returns the VisibleContents field if non-nil, zero value otherwise.

### GetVisibleContentsOk

`func (o *GetGroupHeadsetExperience200Response) GetVisibleContentsOk() (*[]GetGroupHeadsetExperience200ResponseOneOfVisibleContentsInner, bool)`

GetVisibleContentsOk returns a tuple with the VisibleContents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibleContents

`func (o *GetGroupHeadsetExperience200Response) SetVisibleContents(v []GetGroupHeadsetExperience200ResponseOneOfVisibleContentsInner)`

SetVisibleContents sets VisibleContents field to given value.


### GetShortcuts

`func (o *GetGroupHeadsetExperience200Response) GetShortcuts() []string`

GetShortcuts returns the Shortcuts field if non-nil, zero value otherwise.

### GetShortcutsOk

`func (o *GetGroupHeadsetExperience200Response) GetShortcutsOk() (*[]string, bool)`

GetShortcutsOk returns a tuple with the Shortcuts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortcuts

`func (o *GetGroupHeadsetExperience200Response) SetShortcuts(v []string)`

SetShortcuts sets Shortcuts field to given value.


### GetAdminPin

`func (o *GetGroupHeadsetExperience200Response) GetAdminPin() string`

GetAdminPin returns the AdminPin field if non-nil, zero value otherwise.

### GetAdminPinOk

`func (o *GetGroupHeadsetExperience200Response) GetAdminPinOk() (*string, bool)`

GetAdminPinOk returns a tuple with the AdminPin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminPin

`func (o *GetGroupHeadsetExperience200Response) SetAdminPin(v string)`

SetAdminPin sets AdminPin field to given value.

### HasAdminPin

`func (o *GetGroupHeadsetExperience200Response) HasAdminPin() bool`

HasAdminPin returns a boolean if a field has been set.

### SetAdminPinNil

`func (o *GetGroupHeadsetExperience200Response) SetAdminPinNil(b bool)`

 SetAdminPinNil sets the value for AdminPin to be an explicit nil

### UnsetAdminPin
`func (o *GetGroupHeadsetExperience200Response) UnsetAdminPin()`

UnsetAdminPin ensures that no value is present for AdminPin, not even an explicit nil
### GetCategorizationTags

`func (o *GetGroupHeadsetExperience200Response) GetCategorizationTags() []string`

GetCategorizationTags returns the CategorizationTags field if non-nil, zero value otherwise.

### GetCategorizationTagsOk

`func (o *GetGroupHeadsetExperience200Response) GetCategorizationTagsOk() (*[]string, bool)`

GetCategorizationTagsOk returns a tuple with the CategorizationTags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategorizationTags

`func (o *GetGroupHeadsetExperience200Response) SetCategorizationTags(v []string)`

SetCategorizationTags sets CategorizationTags field to given value.


### GetBackground

`func (o *GetGroupHeadsetExperience200Response) GetBackground() GetGroupHeadsetExperience200ResponseOneOfBackground`

GetBackground returns the Background field if non-nil, zero value otherwise.

### GetBackgroundOk

`func (o *GetGroupHeadsetExperience200Response) GetBackgroundOk() (*GetGroupHeadsetExperience200ResponseOneOfBackground, bool)`

GetBackgroundOk returns a tuple with the Background field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackground

`func (o *GetGroupHeadsetExperience200Response) SetBackground(v GetGroupHeadsetExperience200ResponseOneOfBackground)`

SetBackground sets Background field to given value.

### HasBackground

`func (o *GetGroupHeadsetExperience200Response) HasBackground() bool`

HasBackground returns a boolean if a field has been set.

### SetBackgroundNil

`func (o *GetGroupHeadsetExperience200Response) SetBackgroundNil(b bool)`

 SetBackgroundNil sets the value for Background to be an explicit nil

### UnsetBackground
`func (o *GetGroupHeadsetExperience200Response) UnsetBackground()`

UnsetBackground ensures that no value is present for Background, not even an explicit nil
### GetThemeId

`func (o *GetGroupHeadsetExperience200Response) GetThemeId() string`

GetThemeId returns the ThemeId field if non-nil, zero value otherwise.

### GetThemeIdOk

`func (o *GetGroupHeadsetExperience200Response) GetThemeIdOk() (*string, bool)`

GetThemeIdOk returns a tuple with the ThemeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThemeId

`func (o *GetGroupHeadsetExperience200Response) SetThemeId(v string)`

SetThemeId sets ThemeId field to given value.

### HasThemeId

`func (o *GetGroupHeadsetExperience200Response) HasThemeId() bool`

HasThemeId returns a boolean if a field has been set.

### SetThemeIdNil

`func (o *GetGroupHeadsetExperience200Response) SetThemeIdNil(b bool)`

 SetThemeIdNil sets the value for ThemeId to be an explicit nil

### UnsetThemeId
`func (o *GetGroupHeadsetExperience200Response) UnsetThemeId()`

UnsetThemeId ensures that no value is present for ThemeId, not even an explicit nil
### GetLanguage

`func (o *GetGroupHeadsetExperience200Response) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *GetGroupHeadsetExperience200Response) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *GetGroupHeadsetExperience200Response) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *GetGroupHeadsetExperience200Response) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### SetLanguageNil

`func (o *GetGroupHeadsetExperience200Response) SetLanguageNil(b bool)`

 SetLanguageNil sets the value for Language to be an explicit nil

### UnsetLanguage
`func (o *GetGroupHeadsetExperience200Response) UnsetLanguage()`

UnsetLanguage ensures that no value is present for Language, not even an explicit nil
### GetMenuTitle

`func (o *GetGroupHeadsetExperience200Response) GetMenuTitle() string`

GetMenuTitle returns the MenuTitle field if non-nil, zero value otherwise.

### GetMenuTitleOk

`func (o *GetGroupHeadsetExperience200Response) GetMenuTitleOk() (*string, bool)`

GetMenuTitleOk returns a tuple with the MenuTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMenuTitle

`func (o *GetGroupHeadsetExperience200Response) SetMenuTitle(v string)`

SetMenuTitle sets MenuTitle field to given value.

### HasMenuTitle

`func (o *GetGroupHeadsetExperience200Response) HasMenuTitle() bool`

HasMenuTitle returns a boolean if a field has been set.

### SetMenuTitleNil

`func (o *GetGroupHeadsetExperience200Response) SetMenuTitleNil(b bool)`

 SetMenuTitleNil sets the value for MenuTitle to be an explicit nil

### UnsetMenuTitle
`func (o *GetGroupHeadsetExperience200Response) UnsetMenuTitle()`

UnsetMenuTitle ensures that no value is present for MenuTitle, not even an explicit nil
### GetMenuIconImageId

`func (o *GetGroupHeadsetExperience200Response) GetMenuIconImageId() string`

GetMenuIconImageId returns the MenuIconImageId field if non-nil, zero value otherwise.

### GetMenuIconImageIdOk

`func (o *GetGroupHeadsetExperience200Response) GetMenuIconImageIdOk() (*string, bool)`

GetMenuIconImageIdOk returns a tuple with the MenuIconImageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMenuIconImageId

`func (o *GetGroupHeadsetExperience200Response) SetMenuIconImageId(v string)`

SetMenuIconImageId sets MenuIconImageId field to given value.

### HasMenuIconImageId

`func (o *GetGroupHeadsetExperience200Response) HasMenuIconImageId() bool`

HasMenuIconImageId returns a boolean if a field has been set.

### SetMenuIconImageIdNil

`func (o *GetGroupHeadsetExperience200Response) SetMenuIconImageIdNil(b bool)`

 SetMenuIconImageIdNil sets the value for MenuIconImageId to be an explicit nil

### UnsetMenuIconImageId
`func (o *GetGroupHeadsetExperience200Response) UnsetMenuIconImageId()`

UnsetMenuIconImageId ensures that no value is present for MenuIconImageId, not even an explicit nil
### GetRemovePoweredByArborXrBranding

`func (o *GetGroupHeadsetExperience200Response) GetRemovePoweredByArborXrBranding() bool`

GetRemovePoweredByArborXrBranding returns the RemovePoweredByArborXrBranding field if non-nil, zero value otherwise.

### GetRemovePoweredByArborXrBrandingOk

`func (o *GetGroupHeadsetExperience200Response) GetRemovePoweredByArborXrBrandingOk() (*bool, bool)`

GetRemovePoweredByArborXrBrandingOk returns a tuple with the RemovePoweredByArborXrBranding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemovePoweredByArborXrBranding

`func (o *GetGroupHeadsetExperience200Response) SetRemovePoweredByArborXrBranding(v bool)`

SetRemovePoweredByArborXrBranding sets RemovePoweredByArborXrBranding field to given value.


### GetSharedModeSettings

`func (o *GetGroupHeadsetExperience200Response) GetSharedModeSettings() GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings`

GetSharedModeSettings returns the SharedModeSettings field if non-nil, zero value otherwise.

### GetSharedModeSettingsOk

`func (o *GetGroupHeadsetExperience200Response) GetSharedModeSettingsOk() (*GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings, bool)`

GetSharedModeSettingsOk returns a tuple with the SharedModeSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedModeSettings

`func (o *GetGroupHeadsetExperience200Response) SetSharedModeSettings(v GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings)`

SetSharedModeSettings sets SharedModeSettings field to given value.


### GetCreatedAt

`func (o *GetGroupHeadsetExperience200Response) GetCreatedAt() Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetGroupHeadsetExperience200Response) GetCreatedAtOk() (*Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetGroupHeadsetExperience200Response) SetCreatedAt(v Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *GetGroupHeadsetExperience200Response) GetUpdatedAt() Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetGroupHeadsetExperience200Response) GetUpdatedAtOk() (*Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetGroupHeadsetExperience200Response) SetUpdatedAt(v Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetKioskContent

`func (o *GetGroupHeadsetExperience200Response) GetKioskContent() GetGroupHeadsetExperience200ResponseOneOf1KioskContent`

GetKioskContent returns the KioskContent field if non-nil, zero value otherwise.

### GetKioskContentOk

`func (o *GetGroupHeadsetExperience200Response) GetKioskContentOk() (*GetGroupHeadsetExperience200ResponseOneOf1KioskContent, bool)`

GetKioskContentOk returns a tuple with the KioskContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKioskContent

`func (o *GetGroupHeadsetExperience200Response) SetKioskContent(v GetGroupHeadsetExperience200ResponseOneOf1KioskContent)`

SetKioskContent sets KioskContent field to given value.

### HasKioskContent

`func (o *GetGroupHeadsetExperience200Response) HasKioskContent() bool`

HasKioskContent returns a boolean if a field has been set.

### SetKioskContentNil

`func (o *GetGroupHeadsetExperience200Response) SetKioskContentNil(b bool)`

 SetKioskContentNil sets the value for KioskContent to be an explicit nil

### UnsetKioskContent
`func (o *GetGroupHeadsetExperience200Response) UnsetKioskContent()`

UnsetKioskContent ensures that no value is present for KioskContent, not even an explicit nil
### GetIsMenuEnabled

`func (o *GetGroupHeadsetExperience200Response) GetIsMenuEnabled() bool`

GetIsMenuEnabled returns the IsMenuEnabled field if non-nil, zero value otherwise.

### GetIsMenuEnabledOk

`func (o *GetGroupHeadsetExperience200Response) GetIsMenuEnabledOk() (*bool, bool)`

GetIsMenuEnabledOk returns a tuple with the IsMenuEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsMenuEnabled

`func (o *GetGroupHeadsetExperience200Response) SetIsMenuEnabled(v bool)`

SetIsMenuEnabled sets IsMenuEnabled field to given value.


### GetMetaHmsSettings

`func (o *GetGroupHeadsetExperience200Response) GetMetaHmsSettings() ConfigureGroupDefaultHomeHeadsetExperienceRequestMetaHmsSettings`

GetMetaHmsSettings returns the MetaHmsSettings field if non-nil, zero value otherwise.

### GetMetaHmsSettingsOk

`func (o *GetGroupHeadsetExperience200Response) GetMetaHmsSettingsOk() (*ConfigureGroupDefaultHomeHeadsetExperienceRequestMetaHmsSettings, bool)`

GetMetaHmsSettingsOk returns a tuple with the MetaHmsSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetaHmsSettings

`func (o *GetGroupHeadsetExperience200Response) SetMetaHmsSettings(v ConfigureGroupDefaultHomeHeadsetExperienceRequestMetaHmsSettings)`

SetMetaHmsSettings sets MetaHmsSettings field to given value.


### GetLauncherContent

`func (o *GetGroupHeadsetExperience200Response) GetLauncherContent() GetGroupHeadsetExperience200ResponseOneOf3LauncherContent`

GetLauncherContent returns the LauncherContent field if non-nil, zero value otherwise.

### GetLauncherContentOk

`func (o *GetGroupHeadsetExperience200Response) GetLauncherContentOk() (*GetGroupHeadsetExperience200ResponseOneOf3LauncherContent, bool)`

GetLauncherContentOk returns a tuple with the LauncherContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLauncherContent

`func (o *GetGroupHeadsetExperience200Response) SetLauncherContent(v GetGroupHeadsetExperience200ResponseOneOf3LauncherContent)`

SetLauncherContent sets LauncherContent field to given value.

### HasLauncherContent

`func (o *GetGroupHeadsetExperience200Response) HasLauncherContent() bool`

HasLauncherContent returns a boolean if a field has been set.

### SetLauncherContentNil

`func (o *GetGroupHeadsetExperience200Response) SetLauncherContentNil(b bool)`

 SetLauncherContentNil sets the value for LauncherContent to be an explicit nil

### UnsetLauncherContent
`func (o *GetGroupHeadsetExperience200Response) UnsetLauncherContent()`

UnsetLauncherContent ensures that no value is present for LauncherContent, not even an explicit nil
### GetReturnToLauncherViaHomeButton

`func (o *GetGroupHeadsetExperience200Response) GetReturnToLauncherViaHomeButton() bool`

GetReturnToLauncherViaHomeButton returns the ReturnToLauncherViaHomeButton field if non-nil, zero value otherwise.

### GetReturnToLauncherViaHomeButtonOk

`func (o *GetGroupHeadsetExperience200Response) GetReturnToLauncherViaHomeButtonOk() (*bool, bool)`

GetReturnToLauncherViaHomeButtonOk returns a tuple with the ReturnToLauncherViaHomeButton field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnToLauncherViaHomeButton

`func (o *GetGroupHeadsetExperience200Response) SetReturnToLauncherViaHomeButton(v bool)`

SetReturnToLauncherViaHomeButton sets ReturnToLauncherViaHomeButton field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


