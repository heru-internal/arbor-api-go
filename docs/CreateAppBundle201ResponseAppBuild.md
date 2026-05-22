# CreateAppBundle201ResponseAppBuild

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**Version** | Pointer to **NullableString** |  | [optional] 
**Code** | Pointer to **NullableInt32** |  | [optional] 
**SizeBytes** | Pointer to **NullableInt32** |  | [optional] 
**Checksum** | Pointer to [**CreateAppBundle201ResponseAppBuildChecksum**](CreateAppBundle201ResponseAppBuildChecksum.md) |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**DownloadUrl** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | Pointer to **Time** |  | [optional] 
**UpdatedAt** | Pointer to **Time** |  | [optional] 

## Methods

### NewCreateAppBundle201ResponseAppBuild

`func NewCreateAppBundle201ResponseAppBuild() *CreateAppBundle201ResponseAppBuild`

NewCreateAppBundle201ResponseAppBuild instantiates a new CreateAppBundle201ResponseAppBuild object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAppBundle201ResponseAppBuildWithDefaults

`func NewCreateAppBundle201ResponseAppBuildWithDefaults() *CreateAppBundle201ResponseAppBuild`

NewCreateAppBundle201ResponseAppBuildWithDefaults instantiates a new CreateAppBundle201ResponseAppBuild object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateAppBundle201ResponseAppBuild) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateAppBundle201ResponseAppBuild) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateAppBundle201ResponseAppBuild) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CreateAppBundle201ResponseAppBuild) HasId() bool`

HasId returns a boolean if a field has been set.

### GetVersion

`func (o *CreateAppBundle201ResponseAppBuild) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *CreateAppBundle201ResponseAppBuild) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *CreateAppBundle201ResponseAppBuild) SetVersion(v string)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *CreateAppBundle201ResponseAppBuild) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### SetVersionNil

`func (o *CreateAppBundle201ResponseAppBuild) SetVersionNil(b bool)`

 SetVersionNil sets the value for Version to be an explicit nil

### UnsetVersion
`func (o *CreateAppBundle201ResponseAppBuild) UnsetVersion()`

UnsetVersion ensures that no value is present for Version, not even an explicit nil
### GetCode

`func (o *CreateAppBundle201ResponseAppBuild) GetCode() int32`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *CreateAppBundle201ResponseAppBuild) GetCodeOk() (*int32, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *CreateAppBundle201ResponseAppBuild) SetCode(v int32)`

SetCode sets Code field to given value.

### HasCode

`func (o *CreateAppBundle201ResponseAppBuild) HasCode() bool`

HasCode returns a boolean if a field has been set.

### SetCodeNil

`func (o *CreateAppBundle201ResponseAppBuild) SetCodeNil(b bool)`

 SetCodeNil sets the value for Code to be an explicit nil

### UnsetCode
`func (o *CreateAppBundle201ResponseAppBuild) UnsetCode()`

UnsetCode ensures that no value is present for Code, not even an explicit nil
### GetSizeBytes

`func (o *CreateAppBundle201ResponseAppBuild) GetSizeBytes() int32`

GetSizeBytes returns the SizeBytes field if non-nil, zero value otherwise.

### GetSizeBytesOk

`func (o *CreateAppBundle201ResponseAppBuild) GetSizeBytesOk() (*int32, bool)`

GetSizeBytesOk returns a tuple with the SizeBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSizeBytes

`func (o *CreateAppBundle201ResponseAppBuild) SetSizeBytes(v int32)`

SetSizeBytes sets SizeBytes field to given value.

### HasSizeBytes

`func (o *CreateAppBundle201ResponseAppBuild) HasSizeBytes() bool`

HasSizeBytes returns a boolean if a field has been set.

### SetSizeBytesNil

`func (o *CreateAppBundle201ResponseAppBuild) SetSizeBytesNil(b bool)`

 SetSizeBytesNil sets the value for SizeBytes to be an explicit nil

### UnsetSizeBytes
`func (o *CreateAppBundle201ResponseAppBuild) UnsetSizeBytes()`

UnsetSizeBytes ensures that no value is present for SizeBytes, not even an explicit nil
### GetChecksum

`func (o *CreateAppBundle201ResponseAppBuild) GetChecksum() CreateAppBundle201ResponseAppBuildChecksum`

GetChecksum returns the Checksum field if non-nil, zero value otherwise.

### GetChecksumOk

`func (o *CreateAppBundle201ResponseAppBuild) GetChecksumOk() (*CreateAppBundle201ResponseAppBuildChecksum, bool)`

GetChecksumOk returns a tuple with the Checksum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecksum

`func (o *CreateAppBundle201ResponseAppBuild) SetChecksum(v CreateAppBundle201ResponseAppBuildChecksum)`

SetChecksum sets Checksum field to given value.

### HasChecksum

`func (o *CreateAppBundle201ResponseAppBuild) HasChecksum() bool`

HasChecksum returns a boolean if a field has been set.

### GetStatus

`func (o *CreateAppBundle201ResponseAppBuild) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CreateAppBundle201ResponseAppBuild) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CreateAppBundle201ResponseAppBuild) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CreateAppBundle201ResponseAppBuild) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetDownloadUrl

`func (o *CreateAppBundle201ResponseAppBuild) GetDownloadUrl() string`

GetDownloadUrl returns the DownloadUrl field if non-nil, zero value otherwise.

### GetDownloadUrlOk

`func (o *CreateAppBundle201ResponseAppBuild) GetDownloadUrlOk() (*string, bool)`

GetDownloadUrlOk returns a tuple with the DownloadUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownloadUrl

`func (o *CreateAppBundle201ResponseAppBuild) SetDownloadUrl(v string)`

SetDownloadUrl sets DownloadUrl field to given value.

### HasDownloadUrl

`func (o *CreateAppBundle201ResponseAppBuild) HasDownloadUrl() bool`

HasDownloadUrl returns a boolean if a field has been set.

### SetDownloadUrlNil

`func (o *CreateAppBundle201ResponseAppBuild) SetDownloadUrlNil(b bool)`

 SetDownloadUrlNil sets the value for DownloadUrl to be an explicit nil

### UnsetDownloadUrl
`func (o *CreateAppBundle201ResponseAppBuild) UnsetDownloadUrl()`

UnsetDownloadUrl ensures that no value is present for DownloadUrl, not even an explicit nil
### GetCreatedAt

`func (o *CreateAppBundle201ResponseAppBuild) GetCreatedAt() Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateAppBundle201ResponseAppBuild) GetCreatedAtOk() (*Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateAppBundle201ResponseAppBuild) SetCreatedAt(v Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *CreateAppBundle201ResponseAppBuild) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *CreateAppBundle201ResponseAppBuild) GetUpdatedAt() Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CreateAppBundle201ResponseAppBuild) GetUpdatedAtOk() (*Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CreateAppBundle201ResponseAppBuild) SetUpdatedAt(v Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *CreateAppBundle201ResponseAppBuild) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


