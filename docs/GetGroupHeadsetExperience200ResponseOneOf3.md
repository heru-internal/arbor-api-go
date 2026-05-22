# GetGroupHeadsetExperience200ResponseOneOf3

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Mode** | **string** |  | 
**LauncherContent** | Pointer to [**NullableGetGroupHeadsetExperience200ResponseOneOf3LauncherContent**](GetGroupHeadsetExperience200ResponseOneOf3LauncherContent.md) |  | [optional] 
**VisibleContents** | [**[]GetGroupHeadsetExperience200ResponseOneOfVisibleContentsInner**](GetGroupHeadsetExperience200ResponseOneOfVisibleContentsInner.md) |  | 
**ReturnToLauncherViaHomeButton** | **bool** |  | 
**SharedModeSettings** | [**GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings**](GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings.md) |  | 
**CreatedAt** | **Time** |  | 
**UpdatedAt** | **Time** |  | 

## Methods

### NewGetGroupHeadsetExperience200ResponseOneOf3

`func NewGetGroupHeadsetExperience200ResponseOneOf3(id string, mode string, visibleContents []GetGroupHeadsetExperience200ResponseOneOfVisibleContentsInner, returnToLauncherViaHomeButton bool, sharedModeSettings GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings, createdAt Time, updatedAt Time, ) *GetGroupHeadsetExperience200ResponseOneOf3`

NewGetGroupHeadsetExperience200ResponseOneOf3 instantiates a new GetGroupHeadsetExperience200ResponseOneOf3 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetGroupHeadsetExperience200ResponseOneOf3WithDefaults

`func NewGetGroupHeadsetExperience200ResponseOneOf3WithDefaults() *GetGroupHeadsetExperience200ResponseOneOf3`

NewGetGroupHeadsetExperience200ResponseOneOf3WithDefaults instantiates a new GetGroupHeadsetExperience200ResponseOneOf3 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) SetId(v string)`

SetId sets Id field to given value.


### GetMode

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) SetMode(v string)`

SetMode sets Mode field to given value.


### GetLauncherContent

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) GetLauncherContent() GetGroupHeadsetExperience200ResponseOneOf3LauncherContent`

GetLauncherContent returns the LauncherContent field if non-nil, zero value otherwise.

### GetLauncherContentOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) GetLauncherContentOk() (*GetGroupHeadsetExperience200ResponseOneOf3LauncherContent, bool)`

GetLauncherContentOk returns a tuple with the LauncherContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLauncherContent

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) SetLauncherContent(v GetGroupHeadsetExperience200ResponseOneOf3LauncherContent)`

SetLauncherContent sets LauncherContent field to given value.

### HasLauncherContent

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) HasLauncherContent() bool`

HasLauncherContent returns a boolean if a field has been set.

### SetLauncherContentNil

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) SetLauncherContentNil(b bool)`

 SetLauncherContentNil sets the value for LauncherContent to be an explicit nil

### UnsetLauncherContent
`func (o *GetGroupHeadsetExperience200ResponseOneOf3) UnsetLauncherContent()`

UnsetLauncherContent ensures that no value is present for LauncherContent, not even an explicit nil
### GetVisibleContents

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) GetVisibleContents() []GetGroupHeadsetExperience200ResponseOneOfVisibleContentsInner`

GetVisibleContents returns the VisibleContents field if non-nil, zero value otherwise.

### GetVisibleContentsOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) GetVisibleContentsOk() (*[]GetGroupHeadsetExperience200ResponseOneOfVisibleContentsInner, bool)`

GetVisibleContentsOk returns a tuple with the VisibleContents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibleContents

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) SetVisibleContents(v []GetGroupHeadsetExperience200ResponseOneOfVisibleContentsInner)`

SetVisibleContents sets VisibleContents field to given value.


### GetReturnToLauncherViaHomeButton

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) GetReturnToLauncherViaHomeButton() bool`

GetReturnToLauncherViaHomeButton returns the ReturnToLauncherViaHomeButton field if non-nil, zero value otherwise.

### GetReturnToLauncherViaHomeButtonOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) GetReturnToLauncherViaHomeButtonOk() (*bool, bool)`

GetReturnToLauncherViaHomeButtonOk returns a tuple with the ReturnToLauncherViaHomeButton field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnToLauncherViaHomeButton

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) SetReturnToLauncherViaHomeButton(v bool)`

SetReturnToLauncherViaHomeButton sets ReturnToLauncherViaHomeButton field to given value.


### GetSharedModeSettings

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) GetSharedModeSettings() GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings`

GetSharedModeSettings returns the SharedModeSettings field if non-nil, zero value otherwise.

### GetSharedModeSettingsOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) GetSharedModeSettingsOk() (*GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings, bool)`

GetSharedModeSettingsOk returns a tuple with the SharedModeSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSharedModeSettings

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) SetSharedModeSettings(v GetGroupHeadsetExperience200ResponseOneOfSharedModeSettings)`

SetSharedModeSettings sets SharedModeSettings field to given value.


### GetCreatedAt

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) GetCreatedAt() Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) GetCreatedAtOk() (*Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) SetCreatedAt(v Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) GetUpdatedAt() Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) GetUpdatedAtOk() (*Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetGroupHeadsetExperience200ResponseOneOf3) SetUpdatedAt(v Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


