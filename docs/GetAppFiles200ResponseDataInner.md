# GetAppFiles200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**Filename** | Pointer to **string** |  | [optional] 
**Location** | Pointer to **string** |  | [optional] 
**SizeBytes** | Pointer to **NullableInt32** |  | [optional] 
**Checksum** | Pointer to [**CreateAppBundle201ResponseAppBuildChecksum**](CreateAppBundle201ResponseAppBuildChecksum.md) |  | [optional] 
**Tags** | Pointer to **[]string** |  | [optional] 
**DeviceStatuses** | Pointer to [**[]GetAppFiles200ResponseDataInnerDeviceStatusesInner**](GetAppFiles200ResponseDataInnerDeviceStatusesInner.md) | Deprecated. Use the GET /files/{fileId}/device-statuses endpoint instead. | [optional] 
**CreatedAt** | Pointer to **Time** |  | [optional] 
**UpdatedAt** | Pointer to **Time** |  | [optional] 

## Methods

### NewGetAppFiles200ResponseDataInner

`func NewGetAppFiles200ResponseDataInner() *GetAppFiles200ResponseDataInner`

NewGetAppFiles200ResponseDataInner instantiates a new GetAppFiles200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetAppFiles200ResponseDataInnerWithDefaults

`func NewGetAppFiles200ResponseDataInnerWithDefaults() *GetAppFiles200ResponseDataInner`

NewGetAppFiles200ResponseDataInnerWithDefaults instantiates a new GetAppFiles200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetAppFiles200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetAppFiles200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetAppFiles200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *GetAppFiles200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetFilename

`func (o *GetAppFiles200ResponseDataInner) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *GetAppFiles200ResponseDataInner) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *GetAppFiles200ResponseDataInner) SetFilename(v string)`

SetFilename sets Filename field to given value.

### HasFilename

`func (o *GetAppFiles200ResponseDataInner) HasFilename() bool`

HasFilename returns a boolean if a field has been set.

### GetLocation

`func (o *GetAppFiles200ResponseDataInner) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *GetAppFiles200ResponseDataInner) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *GetAppFiles200ResponseDataInner) SetLocation(v string)`

SetLocation sets Location field to given value.

### HasLocation

`func (o *GetAppFiles200ResponseDataInner) HasLocation() bool`

HasLocation returns a boolean if a field has been set.

### GetSizeBytes

`func (o *GetAppFiles200ResponseDataInner) GetSizeBytes() int32`

GetSizeBytes returns the SizeBytes field if non-nil, zero value otherwise.

### GetSizeBytesOk

`func (o *GetAppFiles200ResponseDataInner) GetSizeBytesOk() (*int32, bool)`

GetSizeBytesOk returns a tuple with the SizeBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSizeBytes

`func (o *GetAppFiles200ResponseDataInner) SetSizeBytes(v int32)`

SetSizeBytes sets SizeBytes field to given value.

### HasSizeBytes

`func (o *GetAppFiles200ResponseDataInner) HasSizeBytes() bool`

HasSizeBytes returns a boolean if a field has been set.

### SetSizeBytesNil

`func (o *GetAppFiles200ResponseDataInner) SetSizeBytesNil(b bool)`

 SetSizeBytesNil sets the value for SizeBytes to be an explicit nil

### UnsetSizeBytes
`func (o *GetAppFiles200ResponseDataInner) UnsetSizeBytes()`

UnsetSizeBytes ensures that no value is present for SizeBytes, not even an explicit nil
### GetChecksum

`func (o *GetAppFiles200ResponseDataInner) GetChecksum() CreateAppBundle201ResponseAppBuildChecksum`

GetChecksum returns the Checksum field if non-nil, zero value otherwise.

### GetChecksumOk

`func (o *GetAppFiles200ResponseDataInner) GetChecksumOk() (*CreateAppBundle201ResponseAppBuildChecksum, bool)`

GetChecksumOk returns a tuple with the Checksum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecksum

`func (o *GetAppFiles200ResponseDataInner) SetChecksum(v CreateAppBundle201ResponseAppBuildChecksum)`

SetChecksum sets Checksum field to given value.

### HasChecksum

`func (o *GetAppFiles200ResponseDataInner) HasChecksum() bool`

HasChecksum returns a boolean if a field has been set.

### GetTags

`func (o *GetAppFiles200ResponseDataInner) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *GetAppFiles200ResponseDataInner) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *GetAppFiles200ResponseDataInner) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *GetAppFiles200ResponseDataInner) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetDeviceStatuses

`func (o *GetAppFiles200ResponseDataInner) GetDeviceStatuses() []GetAppFiles200ResponseDataInnerDeviceStatusesInner`

GetDeviceStatuses returns the DeviceStatuses field if non-nil, zero value otherwise.

### GetDeviceStatusesOk

`func (o *GetAppFiles200ResponseDataInner) GetDeviceStatusesOk() (*[]GetAppFiles200ResponseDataInnerDeviceStatusesInner, bool)`

GetDeviceStatusesOk returns a tuple with the DeviceStatuses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceStatuses

`func (o *GetAppFiles200ResponseDataInner) SetDeviceStatuses(v []GetAppFiles200ResponseDataInnerDeviceStatusesInner)`

SetDeviceStatuses sets DeviceStatuses field to given value.

### HasDeviceStatuses

`func (o *GetAppFiles200ResponseDataInner) HasDeviceStatuses() bool`

HasDeviceStatuses returns a boolean if a field has been set.

### GetCreatedAt

`func (o *GetAppFiles200ResponseDataInner) GetCreatedAt() Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetAppFiles200ResponseDataInner) GetCreatedAtOk() (*Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetAppFiles200ResponseDataInner) SetCreatedAt(v Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *GetAppFiles200ResponseDataInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *GetAppFiles200ResponseDataInner) GetUpdatedAt() Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetAppFiles200ResponseDataInner) GetUpdatedAtOk() (*Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetAppFiles200ResponseDataInner) SetUpdatedAt(v Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *GetAppFiles200ResponseDataInner) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


