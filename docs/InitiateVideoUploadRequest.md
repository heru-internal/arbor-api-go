# InitiateVideoUploadRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Filename** | **string** | The original filename of the video. Must end with .mp4, .mkv, or .webm | 
**VideoType** | **string** | The dimensional type of the video | 
**VideoMapping** | Pointer to **NullableString** | How the 360°/180° video content is mapped. Required for ThreeSixty and OneEighty videos, prohibited for TwoDimensional | [optional] 
**VideoDisplay** | Pointer to **NullableString** | Whether the video is stereoscopic (3D) or monoscopic. Required for ThreeSixty and OneEighty videos, prohibited for TwoDimensional | [optional] 
**VideoPacking** | Pointer to **NullableString** | How stereoscopic video content is packed. Required if videoDisplay is Stereoscopic | [optional] 
**AudioEncoding** | **string** | The audio encoding format of the video | 

## Methods

### NewInitiateVideoUploadRequest

`func NewInitiateVideoUploadRequest(filename string, videoType string, audioEncoding string, ) *InitiateVideoUploadRequest`

NewInitiateVideoUploadRequest instantiates a new InitiateVideoUploadRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInitiateVideoUploadRequestWithDefaults

`func NewInitiateVideoUploadRequestWithDefaults() *InitiateVideoUploadRequest`

NewInitiateVideoUploadRequestWithDefaults instantiates a new InitiateVideoUploadRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFilename

`func (o *InitiateVideoUploadRequest) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *InitiateVideoUploadRequest) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *InitiateVideoUploadRequest) SetFilename(v string)`

SetFilename sets Filename field to given value.


### GetVideoType

`func (o *InitiateVideoUploadRequest) GetVideoType() string`

GetVideoType returns the VideoType field if non-nil, zero value otherwise.

### GetVideoTypeOk

`func (o *InitiateVideoUploadRequest) GetVideoTypeOk() (*string, bool)`

GetVideoTypeOk returns a tuple with the VideoType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideoType

`func (o *InitiateVideoUploadRequest) SetVideoType(v string)`

SetVideoType sets VideoType field to given value.


### GetVideoMapping

`func (o *InitiateVideoUploadRequest) GetVideoMapping() string`

GetVideoMapping returns the VideoMapping field if non-nil, zero value otherwise.

### GetVideoMappingOk

`func (o *InitiateVideoUploadRequest) GetVideoMappingOk() (*string, bool)`

GetVideoMappingOk returns a tuple with the VideoMapping field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideoMapping

`func (o *InitiateVideoUploadRequest) SetVideoMapping(v string)`

SetVideoMapping sets VideoMapping field to given value.

### HasVideoMapping

`func (o *InitiateVideoUploadRequest) HasVideoMapping() bool`

HasVideoMapping returns a boolean if a field has been set.

### SetVideoMappingNil

`func (o *InitiateVideoUploadRequest) SetVideoMappingNil(b bool)`

 SetVideoMappingNil sets the value for VideoMapping to be an explicit nil

### UnsetVideoMapping
`func (o *InitiateVideoUploadRequest) UnsetVideoMapping()`

UnsetVideoMapping ensures that no value is present for VideoMapping, not even an explicit nil
### GetVideoDisplay

`func (o *InitiateVideoUploadRequest) GetVideoDisplay() string`

GetVideoDisplay returns the VideoDisplay field if non-nil, zero value otherwise.

### GetVideoDisplayOk

`func (o *InitiateVideoUploadRequest) GetVideoDisplayOk() (*string, bool)`

GetVideoDisplayOk returns a tuple with the VideoDisplay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideoDisplay

`func (o *InitiateVideoUploadRequest) SetVideoDisplay(v string)`

SetVideoDisplay sets VideoDisplay field to given value.

### HasVideoDisplay

`func (o *InitiateVideoUploadRequest) HasVideoDisplay() bool`

HasVideoDisplay returns a boolean if a field has been set.

### SetVideoDisplayNil

`func (o *InitiateVideoUploadRequest) SetVideoDisplayNil(b bool)`

 SetVideoDisplayNil sets the value for VideoDisplay to be an explicit nil

### UnsetVideoDisplay
`func (o *InitiateVideoUploadRequest) UnsetVideoDisplay()`

UnsetVideoDisplay ensures that no value is present for VideoDisplay, not even an explicit nil
### GetVideoPacking

`func (o *InitiateVideoUploadRequest) GetVideoPacking() string`

GetVideoPacking returns the VideoPacking field if non-nil, zero value otherwise.

### GetVideoPackingOk

`func (o *InitiateVideoUploadRequest) GetVideoPackingOk() (*string, bool)`

GetVideoPackingOk returns a tuple with the VideoPacking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideoPacking

`func (o *InitiateVideoUploadRequest) SetVideoPacking(v string)`

SetVideoPacking sets VideoPacking field to given value.

### HasVideoPacking

`func (o *InitiateVideoUploadRequest) HasVideoPacking() bool`

HasVideoPacking returns a boolean if a field has been set.

### SetVideoPackingNil

`func (o *InitiateVideoUploadRequest) SetVideoPackingNil(b bool)`

 SetVideoPackingNil sets the value for VideoPacking to be an explicit nil

### UnsetVideoPacking
`func (o *InitiateVideoUploadRequest) UnsetVideoPacking()`

UnsetVideoPacking ensures that no value is present for VideoPacking, not even an explicit nil
### GetAudioEncoding

`func (o *InitiateVideoUploadRequest) GetAudioEncoding() string`

GetAudioEncoding returns the AudioEncoding field if non-nil, zero value otherwise.

### GetAudioEncodingOk

`func (o *InitiateVideoUploadRequest) GetAudioEncodingOk() (*string, bool)`

GetAudioEncodingOk returns a tuple with the AudioEncoding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAudioEncoding

`func (o *InitiateVideoUploadRequest) SetAudioEncoding(v string)`

SetAudioEncoding sets AudioEncoding field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


