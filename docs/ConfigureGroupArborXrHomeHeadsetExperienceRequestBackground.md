# ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Type of background environment | 
**BannerImageId** | Pointer to **string** | UUID of banner image (required when &#x60;type&#x60; is &#x60;3d-model&#x60;) | [optional] 
**SkyboxImageId** | Pointer to **string** | UUID of skybox image (required when &#x60;type&#x60; is &#x60;3d-model&#x60;) | [optional] 
**ThreeSixtyImageId** | Pointer to **string** | UUID of 360-degree background image (required when &#x60;type&#x60; is &#x60;360-background&#x60;) | [optional] 
**Custom3DEnvironmentId** | Pointer to **string** | UUID of custom 3D environment (required when &#x60;type&#x60; is &#x60;custom-3d-environment&#x60;) | [optional] 

## Methods

### NewConfigureGroupArborXrHomeHeadsetExperienceRequestBackground

`func NewConfigureGroupArborXrHomeHeadsetExperienceRequestBackground(type_ string, ) *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground`

NewConfigureGroupArborXrHomeHeadsetExperienceRequestBackground instantiates a new ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConfigureGroupArborXrHomeHeadsetExperienceRequestBackgroundWithDefaults

`func NewConfigureGroupArborXrHomeHeadsetExperienceRequestBackgroundWithDefaults() *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground`

NewConfigureGroupArborXrHomeHeadsetExperienceRequestBackgroundWithDefaults instantiates a new ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground) SetType(v string)`

SetType sets Type field to given value.


### GetBannerImageId

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground) GetBannerImageId() string`

GetBannerImageId returns the BannerImageId field if non-nil, zero value otherwise.

### GetBannerImageIdOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground) GetBannerImageIdOk() (*string, bool)`

GetBannerImageIdOk returns a tuple with the BannerImageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBannerImageId

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground) SetBannerImageId(v string)`

SetBannerImageId sets BannerImageId field to given value.

### HasBannerImageId

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground) HasBannerImageId() bool`

HasBannerImageId returns a boolean if a field has been set.

### GetSkyboxImageId

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground) GetSkyboxImageId() string`

GetSkyboxImageId returns the SkyboxImageId field if non-nil, zero value otherwise.

### GetSkyboxImageIdOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground) GetSkyboxImageIdOk() (*string, bool)`

GetSkyboxImageIdOk returns a tuple with the SkyboxImageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkyboxImageId

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground) SetSkyboxImageId(v string)`

SetSkyboxImageId sets SkyboxImageId field to given value.

### HasSkyboxImageId

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground) HasSkyboxImageId() bool`

HasSkyboxImageId returns a boolean if a field has been set.

### GetThreeSixtyImageId

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground) GetThreeSixtyImageId() string`

GetThreeSixtyImageId returns the ThreeSixtyImageId field if non-nil, zero value otherwise.

### GetThreeSixtyImageIdOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground) GetThreeSixtyImageIdOk() (*string, bool)`

GetThreeSixtyImageIdOk returns a tuple with the ThreeSixtyImageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreeSixtyImageId

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground) SetThreeSixtyImageId(v string)`

SetThreeSixtyImageId sets ThreeSixtyImageId field to given value.

### HasThreeSixtyImageId

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground) HasThreeSixtyImageId() bool`

HasThreeSixtyImageId returns a boolean if a field has been set.

### GetCustom3DEnvironmentId

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground) GetCustom3DEnvironmentId() string`

GetCustom3DEnvironmentId returns the Custom3DEnvironmentId field if non-nil, zero value otherwise.

### GetCustom3DEnvironmentIdOk

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground) GetCustom3DEnvironmentIdOk() (*string, bool)`

GetCustom3DEnvironmentIdOk returns a tuple with the Custom3DEnvironmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustom3DEnvironmentId

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground) SetCustom3DEnvironmentId(v string)`

SetCustom3DEnvironmentId sets Custom3DEnvironmentId field to given value.

### HasCustom3DEnvironmentId

`func (o *ConfigureGroupArborXrHomeHeadsetExperienceRequestBackground) HasCustom3DEnvironmentId() bool`

HasCustom3DEnvironmentId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


