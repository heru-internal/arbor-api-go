# GetImages200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**IsSystemOwned** | **bool** | Whether this image is owned by the system (true) or by the organization (false) | 
**ObjectName** | Pointer to **NullableString** | A randomized filename used to prevent filename collisions on devices | [optional] 
**OriginalFileName** | Pointer to **NullableString** | The original filename when uploaded | [optional] 
**MimeType** | Pointer to **NullableString** | The MIME type of the image | [optional] 
**SizeBytes** | Pointer to **NullableInt32** | The size of the image in bytes | [optional] 
**Type** | **string** | The type/category of the image | 
**Status** | **string** | The current status of the image | 
**DownloadUrl** | Pointer to **NullableString** | Download URL for the image (only present when status is available) | [optional] 
**CreatedAt** | **Time** |  | 
**UpdatedAt** | **Time** |  | 

## Methods

### NewGetImages200ResponseDataInner

`func NewGetImages200ResponseDataInner(id string, isSystemOwned bool, type_ string, status string, createdAt Time, updatedAt Time, ) *GetImages200ResponseDataInner`

NewGetImages200ResponseDataInner instantiates a new GetImages200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetImages200ResponseDataInnerWithDefaults

`func NewGetImages200ResponseDataInnerWithDefaults() *GetImages200ResponseDataInner`

NewGetImages200ResponseDataInnerWithDefaults instantiates a new GetImages200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetImages200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetImages200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetImages200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.


### GetIsSystemOwned

`func (o *GetImages200ResponseDataInner) GetIsSystemOwned() bool`

GetIsSystemOwned returns the IsSystemOwned field if non-nil, zero value otherwise.

### GetIsSystemOwnedOk

`func (o *GetImages200ResponseDataInner) GetIsSystemOwnedOk() (*bool, bool)`

GetIsSystemOwnedOk returns a tuple with the IsSystemOwned field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSystemOwned

`func (o *GetImages200ResponseDataInner) SetIsSystemOwned(v bool)`

SetIsSystemOwned sets IsSystemOwned field to given value.


### GetObjectName

`func (o *GetImages200ResponseDataInner) GetObjectName() string`

GetObjectName returns the ObjectName field if non-nil, zero value otherwise.

### GetObjectNameOk

`func (o *GetImages200ResponseDataInner) GetObjectNameOk() (*string, bool)`

GetObjectNameOk returns a tuple with the ObjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjectName

`func (o *GetImages200ResponseDataInner) SetObjectName(v string)`

SetObjectName sets ObjectName field to given value.

### HasObjectName

`func (o *GetImages200ResponseDataInner) HasObjectName() bool`

HasObjectName returns a boolean if a field has been set.

### SetObjectNameNil

`func (o *GetImages200ResponseDataInner) SetObjectNameNil(b bool)`

 SetObjectNameNil sets the value for ObjectName to be an explicit nil

### UnsetObjectName
`func (o *GetImages200ResponseDataInner) UnsetObjectName()`

UnsetObjectName ensures that no value is present for ObjectName, not even an explicit nil
### GetOriginalFileName

`func (o *GetImages200ResponseDataInner) GetOriginalFileName() string`

GetOriginalFileName returns the OriginalFileName field if non-nil, zero value otherwise.

### GetOriginalFileNameOk

`func (o *GetImages200ResponseDataInner) GetOriginalFileNameOk() (*string, bool)`

GetOriginalFileNameOk returns a tuple with the OriginalFileName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalFileName

`func (o *GetImages200ResponseDataInner) SetOriginalFileName(v string)`

SetOriginalFileName sets OriginalFileName field to given value.

### HasOriginalFileName

`func (o *GetImages200ResponseDataInner) HasOriginalFileName() bool`

HasOriginalFileName returns a boolean if a field has been set.

### SetOriginalFileNameNil

`func (o *GetImages200ResponseDataInner) SetOriginalFileNameNil(b bool)`

 SetOriginalFileNameNil sets the value for OriginalFileName to be an explicit nil

### UnsetOriginalFileName
`func (o *GetImages200ResponseDataInner) UnsetOriginalFileName()`

UnsetOriginalFileName ensures that no value is present for OriginalFileName, not even an explicit nil
### GetMimeType

`func (o *GetImages200ResponseDataInner) GetMimeType() string`

GetMimeType returns the MimeType field if non-nil, zero value otherwise.

### GetMimeTypeOk

`func (o *GetImages200ResponseDataInner) GetMimeTypeOk() (*string, bool)`

GetMimeTypeOk returns a tuple with the MimeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMimeType

`func (o *GetImages200ResponseDataInner) SetMimeType(v string)`

SetMimeType sets MimeType field to given value.

### HasMimeType

`func (o *GetImages200ResponseDataInner) HasMimeType() bool`

HasMimeType returns a boolean if a field has been set.

### SetMimeTypeNil

`func (o *GetImages200ResponseDataInner) SetMimeTypeNil(b bool)`

 SetMimeTypeNil sets the value for MimeType to be an explicit nil

### UnsetMimeType
`func (o *GetImages200ResponseDataInner) UnsetMimeType()`

UnsetMimeType ensures that no value is present for MimeType, not even an explicit nil
### GetSizeBytes

`func (o *GetImages200ResponseDataInner) GetSizeBytes() int32`

GetSizeBytes returns the SizeBytes field if non-nil, zero value otherwise.

### GetSizeBytesOk

`func (o *GetImages200ResponseDataInner) GetSizeBytesOk() (*int32, bool)`

GetSizeBytesOk returns a tuple with the SizeBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSizeBytes

`func (o *GetImages200ResponseDataInner) SetSizeBytes(v int32)`

SetSizeBytes sets SizeBytes field to given value.

### HasSizeBytes

`func (o *GetImages200ResponseDataInner) HasSizeBytes() bool`

HasSizeBytes returns a boolean if a field has been set.

### SetSizeBytesNil

`func (o *GetImages200ResponseDataInner) SetSizeBytesNil(b bool)`

 SetSizeBytesNil sets the value for SizeBytes to be an explicit nil

### UnsetSizeBytes
`func (o *GetImages200ResponseDataInner) UnsetSizeBytes()`

UnsetSizeBytes ensures that no value is present for SizeBytes, not even an explicit nil
### GetType

`func (o *GetImages200ResponseDataInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *GetImages200ResponseDataInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *GetImages200ResponseDataInner) SetType(v string)`

SetType sets Type field to given value.


### GetStatus

`func (o *GetImages200ResponseDataInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GetImages200ResponseDataInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GetImages200ResponseDataInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetDownloadUrl

`func (o *GetImages200ResponseDataInner) GetDownloadUrl() string`

GetDownloadUrl returns the DownloadUrl field if non-nil, zero value otherwise.

### GetDownloadUrlOk

`func (o *GetImages200ResponseDataInner) GetDownloadUrlOk() (*string, bool)`

GetDownloadUrlOk returns a tuple with the DownloadUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownloadUrl

`func (o *GetImages200ResponseDataInner) SetDownloadUrl(v string)`

SetDownloadUrl sets DownloadUrl field to given value.

### HasDownloadUrl

`func (o *GetImages200ResponseDataInner) HasDownloadUrl() bool`

HasDownloadUrl returns a boolean if a field has been set.

### SetDownloadUrlNil

`func (o *GetImages200ResponseDataInner) SetDownloadUrlNil(b bool)`

 SetDownloadUrlNil sets the value for DownloadUrl to be an explicit nil

### UnsetDownloadUrl
`func (o *GetImages200ResponseDataInner) UnsetDownloadUrl()`

UnsetDownloadUrl ensures that no value is present for DownloadUrl, not even an explicit nil
### GetCreatedAt

`func (o *GetImages200ResponseDataInner) GetCreatedAt() Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetImages200ResponseDataInner) GetCreatedAtOk() (*Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetImages200ResponseDataInner) SetCreatedAt(v Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *GetImages200ResponseDataInner) GetUpdatedAt() Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetImages200ResponseDataInner) GetUpdatedAtOk() (*Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetImages200ResponseDataInner) SetUpdatedAt(v Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


