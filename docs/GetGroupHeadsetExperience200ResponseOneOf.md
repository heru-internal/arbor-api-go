# GetGroupHeadsetExperience200ResponseOneOf

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Mode** | **string** |  | 
**VisibleContents** | [**[]GetGroupHeadsetExperience200ResponseOneOfVisibleContentsInner**](GetGroupHeadsetExperience200ResponseOneOfVisibleContentsInner.md) |  | 
**Shortcuts** | **[]string** |  | 
**AdminPin** | Pointer to **NullableString** |  | [optional] 
**CategorizationTags** | **[]string** |  | 
**Background** | Pointer to [**NullableGetGroupHeadsetExperience200ResponseOneOfBackground**](GetGroupHeadsetExperience200ResponseOneOfBackground.md) |  | [optional] 
**ThemeId** | Pointer to **NullableString** |  | [optional] 
**Language** | Pointer to **NullableString** |  | [optional] 
**MenuTitle** | Pointer to **NullableString** |  | [optional] 
**MenuIconImageId** | Pointer to **NullableString** |  | [optional] 
**RemovePoweredByArborXrBranding** | **bool** |  | 
**SharedModeSettings** | [**GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings**](GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings.md) |  | 
**CreatedAt** | **Time** |  | 
**UpdatedAt** | **Time** |  | 

## Methods

### NewGetGroupHeadsetExperience200ResponseOneOf

`func NewGetGroupHeadsetExperience200ResponseOneOf(id string, mode string, visibleContents []GetGroupHeadsetExperience200ResponseOneOfVisibleContentsInner, shortcuts []string, categorizationTags []string, removePoweredByArborXrBranding bool, sharedModeSettings GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings, createdAt Time, updatedAt Time, ) *GetGroupHeadsetExperience200ResponseOneOf`

NewGetGroupHeadsetExperience200ResponseOneOf instantiates a new GetGroupHeadsetExperience200ResponseOneOf object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetGroupHeadsetExperience200ResponseOneOfWithDefaults

`func NewGetGroupHeadsetExperience200ResponseOneOfWithDefaults() *GetGroupHeadsetExperience200ResponseOneOf`

NewGetGroupHeadsetExperience200ResponseOneOfWithDefaults instantiates a new GetGroupHeadsetExperience200ResponseOneOf object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetId(v string)`

SetId sets Id field to given value.


### GetMode

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetMode(v string)`

SetMode sets Mode field to given value.


### GetVisibleContents

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetVisibleContents() []GetGroupHeadsetExperience200ResponseOneOfVisibleContentsInner`

GetVisibleContents returns the VisibleContents field if non-nil, zero value otherwise.

### GetVisibleContentsOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetVisibleContentsOk() (*[]GetGroupHeadsetExperience200ResponseOneOfVisibleContentsInner, bool)`

GetVisibleContentsOk returns a tuple with the VisibleContents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibleContents

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetVisibleContents(v []GetGroupHeadsetExperience200ResponseOneOfVisibleContentsInner)`

SetVisibleContents sets VisibleContents field to given value.


### GetShortcuts

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetShortcuts() []string`

GetShortcuts returns the Shortcuts field if non-nil, zero value otherwise.

### GetShortcutsOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetShortcutsOk() (*[]string, bool)`

GetShortcutsOk returns a tuple with the Shortcuts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortcuts

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetShortcuts(v []string)`

SetShortcuts sets Shortcuts field to given value.


### GetAdminPin

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetAdminPin() string`

GetAdminPin returns the AdminPin field if non-nil, zero value otherwise.

### GetAdminPinOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetAdminPinOk() (*string, bool)`

GetAdminPinOk returns a tuple with the AdminPin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdminPin

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetAdminPin(v string)`

SetAdminPin sets AdminPin field to given value.

### HasAdminPin

`func (o *GetGroupHeadsetExperience200ResponseOneOf) HasAdminPin() bool`

HasAdminPin returns a boolean if a field has been set.

### SetAdminPinNil

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetAdminPinNil(b bool)`

 SetAdminPinNil sets the value for AdminPin to be an explicit nil

### UnsetAdminPin
`func (o *GetGroupHeadsetExperience200ResponseOneOf) UnsetAdminPin()`

UnsetAdminPin ensures that no value is present for AdminPin, not even an explicit nil
### GetCategorizationTags

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetCategorizationTags() []string`

GetCategorizationTags returns the CategorizationTags field if non-nil, zero value otherwise.

### GetCategorizationTagsOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetCategorizationTagsOk() (*[]string, bool)`

GetCategorizationTagsOk returns a tuple with the CategorizationTags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategorizationTags

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetCategorizationTags(v []string)`

SetCategorizationTags sets CategorizationTags field to given value.


### GetBackground

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetBackground() GetGroupHeadsetExperience200ResponseOneOfBackground`

GetBackground returns the Background field if non-nil, zero value otherwise.

### GetBackgroundOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetBackgroundOk() (*GetGroupHeadsetExperience200ResponseOneOfBackground, bool)`

GetBackgroundOk returns a tuple with the Background field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackground

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetBackground(v GetGroupHeadsetExperience200ResponseOneOfBackground)`

SetBackground sets Background field to given value.

### HasBackground

`func (o *GetGroupHeadsetExperience200ResponseOneOf) HasBackground() bool`

HasBackground returns a boolean if a field has been set.

### SetBackgroundNil

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetBackgroundNil(b bool)`

 SetBackgroundNil sets the value for Background to be an explicit nil

### UnsetBackground
`func (o *GetGroupHeadsetExperience200ResponseOneOf) UnsetBackground()`

UnsetBackground ensures that no value is present for Background, not even an explicit nil
### GetThemeId

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetThemeId() string`

GetThemeId returns the ThemeId field if non-nil, zero value otherwise.

### GetThemeIdOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetThemeIdOk() (*string, bool)`

GetThemeIdOk returns a tuple with the ThemeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThemeId

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetThemeId(v string)`

SetThemeId sets ThemeId field to given value.

### HasThemeId

`func (o *GetGroupHeadsetExperience200ResponseOneOf) HasThemeId() bool`

HasThemeId returns a boolean if a field has been set.

### SetThemeIdNil

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetThemeIdNil(b bool)`

 SetThemeIdNil sets the value for ThemeId to be an explicit nil

### UnsetThemeId
`func (o *GetGroupHeadsetExperience200ResponseOneOf) UnsetThemeId()`

UnsetThemeId ensures that no value is present for ThemeId, not even an explicit nil
### GetLanguage

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *GetGroupHeadsetExperience200ResponseOneOf) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### SetLanguageNil

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetLanguageNil(b bool)`

 SetLanguageNil sets the value for Language to be an explicit nil

### UnsetLanguage
`func (o *GetGroupHeadsetExperience200ResponseOneOf) UnsetLanguage()`

UnsetLanguage ensures that no value is present for Language, not even an explicit nil
### GetMenuTitle

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetMenuTitle() string`

GetMenuTitle returns the MenuTitle field if non-nil, zero value otherwise.

### GetMenuTitleOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetMenuTitleOk() (*string, bool)`

GetMenuTitleOk returns a tuple with the MenuTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMenuTitle

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetMenuTitle(v string)`

SetMenuTitle sets MenuTitle field to given value.

### HasMenuTitle

`func (o *GetGroupHeadsetExperience200ResponseOneOf) HasMenuTitle() bool`

HasMenuTitle returns a boolean if a field has been set.

### SetMenuTitleNil

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetMenuTitleNil(b bool)`

 SetMenuTitleNil sets the value for MenuTitle to be an explicit nil

### UnsetMenuTitle
`func (o *GetGroupHeadsetExperience200ResponseOneOf) UnsetMenuTitle()`

UnsetMenuTitle ensures that no value is present for MenuTitle, not even an explicit nil
### GetMenuIconImageId

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetMenuIconImageId() string`

GetMenuIconImageId returns the MenuIconImageId field if non-nil, zero value otherwise.

### GetMenuIconImageIdOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetMenuIconImageIdOk() (*string, bool)`

GetMenuIconImageIdOk returns a tuple with the MenuIconImageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMenuIconImageId

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetMenuIconImageId(v string)`

SetMenuIconImageId sets MenuIconImageId field to given value.

### HasMenuIconImageId

`func (o *GetGroupHeadsetExperience200ResponseOneOf) HasMenuIconImageId() bool`

HasMenuIconImageId returns a boolean if a field has been set.

### SetMenuIconImageIdNil

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetMenuIconImageIdNil(b bool)`

 SetMenuIconImageIdNil sets the value for MenuIconImageId to be an explicit nil

### UnsetMenuIconImageId
`func (o *GetGroupHeadsetExperience200ResponseOneOf) UnsetMenuIconImageId()`

UnsetMenuIconImageId ensures that no value is present for MenuIconImageId, not even an explicit nil
### GetRemovePoweredByArborXrBranding

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetRemovePoweredByArborXrBranding() bool`

GetRemovePoweredByArborXrBranding returns the RemovePoweredByArborXrBranding field if non-nil, zero value otherwise.

### GetRemovePoweredByArborXrBrandingOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetRemovePoweredByArborXrBrandingOk() (*bool, bool)`

GetRemovePoweredByArborXrBrandingOk returns a tuple with the RemovePoweredByArborXrBranding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemovePoweredByArborXrBranding

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetRemovePoweredByArborXrBranding(v bool)`

SetRemovePoweredByArborXrBranding sets RemovePoweredByArborXrBranding field to given value.


### GetSharedModeSettings

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetSharedModeSettings() GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings`

GetSharedModeSettings returns the SharedModeSettings field if non-nil, zero value otherwise.

### GetSharedModeSettingsOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetSharedModeSettingsOk() (*GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings, bool)`

GetSharedModeSettingsOk returns a tuple with the SharedModeSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedModeSettings

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetSharedModeSettings(v GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings)`

SetSharedModeSettings sets SharedModeSettings field to given value.


### GetCreatedAt

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetCreatedAt() Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetCreatedAtOk() (*Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetCreatedAt(v Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetUpdatedAt() Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf) GetUpdatedAtOk() (*Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetGroupHeadsetExperience200ResponseOneOf) SetUpdatedAt(v Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


