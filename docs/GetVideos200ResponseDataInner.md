# GetVideos200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Filename** | Pointer to **string** |  | [optional] 
**Location** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **NullableString** |  | [optional] 
**SizeBytes** | Pointer to **int32** |  | [optional] 
**Checksum** | Pointer to [**CreateAppBundle201ResponseAppBuildChecksum**](CreateAppBundle201ResponseAppBuildChecksum.md) |  | [optional] 
**Details** | Pointer to [**GetVideos200ResponseDataInnerDetails**](GetVideos200ResponseDataInnerDetails.md) |  | [optional] 
**Tags** | Pointer to **[]string** |  | [optional] 
**DeviceStatuses** | Pointer to [**[]GetAppFiles200ResponseDataInnerDeviceStatusesInner**](GetAppFiles200ResponseDataInnerDeviceStatusesInner.md) | Deprecated. Use the GET /videos/{videoId}/device-statuses endpoint instead. | [optional] 
**CreatedAt** | Pointer to **Time** |  | [optional] 
**UpdatedAt** | Pointer to **Time** |  | [optional] 

## Methods

### NewGetVideos200ResponseDataInner

`func NewGetVideos200ResponseDataInner() *GetVideos200ResponseDataInner`

NewGetVideos200ResponseDataInner instantiates a new GetVideos200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetVideos200ResponseDataInnerWithDefaults

`func NewGetVideos200ResponseDataInnerWithDefaults() *GetVideos200ResponseDataInner`

NewGetVideos200ResponseDataInnerWithDefaults instantiates a new GetVideos200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetVideos200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetVideos200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetVideos200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *GetVideos200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *GetVideos200ResponseDataInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GetVideos200ResponseDataInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GetVideos200ResponseDataInner) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *GetVideos200ResponseDataInner) HasName() bool`

HasName returns a boolean if a field has been set.

### GetFilename

`func (o *GetVideos200ResponseDataInner) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *GetVideos200ResponseDataInner) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *GetVideos200ResponseDataInner) SetFilename(v string)`

SetFilename sets Filename field to given value.

### HasFilename

`func (o *GetVideos200ResponseDataInner) HasFilename() bool`

HasFilename returns a boolean if a field has been set.

### GetLocation

`func (o *GetVideos200ResponseDataInner) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *GetVideos200ResponseDataInner) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *GetVideos200ResponseDataInner) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *GetVideos200ResponseDataInner) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetDescription

`func (o *GetVideos200ResponseDataInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *GetVideos200ResponseDataInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *GetVideos200ResponseDataInner) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *GetVideos200ResponseDataInner) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *GetVideos200ResponseDataInner) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *GetVideos200ResponseDataInner) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetSizeBytes

`func (o *GetVideos200ResponseDataInner) GetSizeBytes() int32`

GetSizeBytes returns the SizeBytes field if non-nil, zero value otherwise.

### GetSizeBytesOk

`func (o *GetVideos200ResponseDataInner) GetSizeBytesOk() (*int32, bool)`

GetSizeBytesOk returns a tuple with the SizeBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSizeBytes

`func (o *GetVideos200ResponseDataInner) SetSizeBytes(v int32)`

SetSizeBytes sets SizeBytes field to given value.

### HasSizeBytes

`func (o *GetVideos200ResponseDataInner) HasSizeBytes() bool`

HasSizeBytes returns a boolean if a field has been set.

### GetChecksum

`func (o *GetVideos200ResponseDataInner) GetChecksum() CreateAppBundle201ResponseAppBuildChecksum`

GetChecksum returns the Checksum field if non-nil, zero value otherwise.

### GetChecksumOk

`func (o *GetVideos200ResponseDataInner) GetChecksumOk() (*CreateAppBundle201ResponseAppBuildChecksum, bool)`

GetChecksumOk returns a tuple with the Checksum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecksum

`func (o *GetVideos200ResponseDataInner) SetChecksum(v CreateAppBundle201ResponseAppBuildChecksum)`

SetChecksum sets Checksum field to given value.

### HasChecksum

`func (o *GetVideos200ResponseDataInner) HasChecksum() bool`

HasChecksum returns a boolean if a field has been set.

### GetDetails

`func (o *GetVideos200ResponseDataInner) GetDetails() GetVideos200ResponseDataInnerDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *GetVideos200ResponseDataInner) GetDetailsOk() (*GetVideos200ResponseDataInnerDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *GetVideos200ResponseDataInner) SetDetails(v GetVideos200ResponseDataInnerDetails)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *GetVideos200ResponseDataInner) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### GetTags

`func (o *GetVideos200ResponseDataInner) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *GetVideos200ResponseDataInner) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *GetVideos200ResponseDataInner) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *GetVideos200ResponseDataInner) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetDeviceStatuses

`func (o *GetVideos200ResponseDataInner) GetDeviceStatuses() []GetAppFiles200ResponseDataInnerDeviceStatusesInner`

GetDeviceStatuses returns the DeviceStatuses field if non-nil, zero value otherwise.

### GetDeviceStatusesOk

`func (o *GetVideos200ResponseDataInner) GetDeviceStatusesOk() (*[]GetAppFiles200ResponseDataInnerDeviceStatusesInner, bool)`

GetDeviceStatusesOk returns a tuple with the DeviceStatuses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceStatuses

`func (o *GetVideos200ResponseDataInner) SetDeviceStatuses(v []GetAppFiles200ResponseDataInnerDeviceStatusesInner)`

SetDeviceStatuses sets DeviceStatuses field to given value.

### HasDeviceStatuses

`func (o *GetVideos200ResponseDataInner) HasDeviceStatuses() bool`

HasDeviceStatuses returns a boolean if a field has been set.

### GetCreatedAt

`func (o *GetVideos200ResponseDataInner) GetCreatedAt() Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetVideos200ResponseDataInner) GetCreatedAtOk() (*Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetVideos200ResponseDataInner) SetCreatedAt(v Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *GetVideos200ResponseDataInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *GetVideos200ResponseDataInner) GetUpdatedAt() Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetVideos200ResponseDataInner) GetUpdatedAtOk() (*Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetVideos200ResponseDataInner) SetUpdatedAt(v Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *GetVideos200ResponseDataInner) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


