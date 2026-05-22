# UpdateVideoRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Description** | **NullableString** |  | 
**VideoType** | **string** |  | 
**VideoMapping** | Pointer to **NullableString** | Required for ThreeSixty and OneEighty video types. Prohibited for TwoDimensional. | [optional] 
**VideoDisplay** | Pointer to **NullableString** | Required for ThreeSixty and OneEighty video types. Prohibited for TwoDimensional. | [optional] 
**VideoPacking** | Pointer to **NullableString** | Required when videoDisplay is Stereoscopic. Prohibited when videoDisplay is Monoscopic. | [optional] 
**AudioEncoding** | **string** |  | 
**Tags** | **[]string** |  | 

## Methods

### NewUpdateVideoRequest

`func NewUpdateVideoRequest(name string, description NullableString, videoType string, audioEncoding string, tags []string, ) *UpdateVideoRequest`

NewUpdateVideoRequest instantiates a new UpdateVideoRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateVideoRequestWithDefaults

`func NewUpdateVideoRequestWithDefaults() *UpdateVideoRequest`

NewUpdateVideoRequestWithDefaults instantiates a new UpdateVideoRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateVideoRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateVideoRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateVideoRequest) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *UpdateVideoRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdateVideoRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdateVideoRequest) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *UpdateVideoRequest) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *UpdateVideoRequest) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetVideoType

`func (o *UpdateVideoRequest) GetVideoType() string`

GetVideoType returns the VideoType field if non-nil, zero value otherwise.

### GetVideoTypeOk

`func (o *UpdateVideoRequest) GetVideoTypeOk() (*string, bool)`

GetVideoTypeOk returns a tuple with the VideoType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideoType

`func (o *UpdateVideoRequest) SetVideoType(v string)`

SetVideoType sets VideoType field to given value.


### GetVideoMapping

`func (o *UpdateVideoRequest) GetVideoMapping() string`

GetVideoMapping returns the VideoMapping field if non-nil, zero value otherwise.

### GetVideoMappingOk

`func (o *UpdateVideoRequest) GetVideoMappingOk() (*string, bool)`

GetVideoMappingOk returns a tuple with the VideoMapping field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideoMapping

`func (o *UpdateVideoRequest) SetVideoMapping(v string)`

SetVideoMapping sets VideoMapping field to given value.

### HasVideoMapping

`func (o *UpdateVideoRequest) HasVideoMapping() bool`

HasVideoMapping returns a boolean if a field has been set.

### SetVideoMappingNil

`func (o *UpdateVideoRequest) SetVideoMappingNil(b bool)`

 SetVideoMappingNil sets the value for VideoMapping to be an explicit nil

### UnsetVideoMapping
`func (o *UpdateVideoRequest) UnsetVideoMapping()`

UnsetVideoMapping ensures that no value is present for VideoMapping, not even an explicit nil
### GetVideoDisplay

`func (o *UpdateVideoRequest) GetVideoDisplay() string`

GetVideoDisplay returns the VideoDisplay field if non-nil, zero value otherwise.

### GetVideoDisplayOk

`func (o *UpdateVideoRequest) GetVideoDisplayOk() (*string, bool)`

GetVideoDisplayOk returns a tuple with the VideoDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideoDisplay

`func (o *UpdateVideoRequest) SetVideoDisplay(v string)`

SetVideoDisplay sets VideoDisplay field to given value.

### HasVideoDisplay

`func (o *UpdateVideoRequest) HasVideoDisplay() bool`

HasVideoDisplay returns a boolean if a field has been set.

### SetVideoDisplayNil

`func (o *UpdateVideoRequest) SetVideoDisplayNil(b bool)`

 SetVideoDisplayNil sets the value for VideoDisplay to be an explicit nil

### UnsetVideoDisplay
`func (o *UpdateVideoRequest) UnsetVideoDisplay()`

UnsetVideoDisplay ensures that no value is present for VideoDisplay, not even an explicit nil
### GetVideoPacking

`func (o *UpdateVideoRequest) GetVideoPacking() string`

GetVideoPacking returns the VideoPacking field if non-nil, zero value otherwise.

### GetVideoPackingOk

`func (o *UpdateVideoRequest) GetVideoPackingOk() (*string, bool)`

GetVideoPackingOk returns a tuple with the VideoPacking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideoPacking

`func (o *UpdateVideoRequest) SetVideoPacking(v string)`

SetVideoPacking sets VideoPacking field to given value.

### HasVideoPacking

`func (o *UpdateVideoRequest) HasVideoPacking() bool`

HasVideoPacking returns a boolean if a field has been set.

### SetVideoPackingNil

`func (o *UpdateVideoRequest) SetVideoPackingNil(b bool)`

 SetVideoPackingNil sets the value for VideoPacking to be an explicit nil

### UnsetVideoPacking
`func (o *UpdateVideoRequest) UnsetVideoPacking()`

UnsetVideoPacking ensures that no value is present for VideoPacking, not even an explicit nil
### GetAudioEncoding

`func (o *UpdateVideoRequest) GetAudioEncoding() string`

GetAudioEncoding returns the AudioEncoding field if non-nil, zero value otherwise.

### GetAudioEncodingOk

`func (o *UpdateVideoRequest) GetAudioEncodingOk() (*string, bool)`

GetAudioEncodingOk returns a tuple with the AudioEncoding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAudioEncoding

`func (o *UpdateVideoRequest) SetAudioEncoding(v string)`

SetAudioEncoding sets AudioEncoding field to given value.


### GetTags

`func (o *UpdateVideoRequest) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *UpdateVideoRequest) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *UpdateVideoRequest) SetTags(v []string)`

SetTags sets Tags field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


