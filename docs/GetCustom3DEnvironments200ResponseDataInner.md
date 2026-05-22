# GetCustom3DEnvironments200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**ObjectName** | **string** | The filename of the 3D environment file (must be .glb format) | 
**SizeBytes** | Pointer to **NullableInt32** | The size of the 3D environment file in bytes | [optional] 
**Status** | **string** | The current status of the 3D environment | 
**DownloadUrl** | Pointer to **NullableString** | Download URL for the 3D environment (only present when status is available) | [optional] 
**CreatedAt** | **Time** |  | 
**UpdatedAt** | **Time** |  | 

## Methods

### NewGetCustom3DEnvironments200ResponseDataInner

`func NewGetCustom3DEnvironments200ResponseDataInner(id string, objectName string, status string, createdAt Time, updatedAt Time, ) *GetCustom3DEnvironments200ResponseDataInner`

NewGetCustom3DEnvironments200ResponseDataInner instantiates a new GetCustom3DEnvironments200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetCustom3DEnvironments200ResponseDataInnerWithDefaults

`func NewGetCustom3DEnvironments200ResponseDataInnerWithDefaults() *GetCustom3DEnvironments200ResponseDataInner`

NewGetCustom3DEnvironments200ResponseDataInnerWithDefaults instantiates a new GetCustom3DEnvironments200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetCustom3DEnvironments200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetCustom3DEnvironments200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetCustom3DEnvironments200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.


### GetObjectName

`func (o *GetCustom3DEnvironments200ResponseDataInner) GetObjectName() string`

GetObjectName returns the ObjectName field if non-nil, zero value otherwise.

### GetObjectNameOk

`func (o *GetCustom3DEnvironments200ResponseDataInner) GetObjectNameOk() (*string, bool)`

GetObjectNameOk returns a tuple with the ObjectName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjectName

`func (o *GetCustom3DEnvironments200ResponseDataInner) SetObjectName(v string)`

SetObjectName sets ObjectName field to given value.


### GetSizeBytes

`func (o *GetCustom3DEnvironments200ResponseDataInner) GetSizeBytes() int32`

GetSizeBytes returns the SizeBytes field if non-nil, zero value otherwise.

### GetSizeBytesOk

`func (o *GetCustom3DEnvironments200ResponseDataInner) GetSizeBytesOk() (*int32, bool)`

GetSizeBytesOk returns a tuple with the SizeBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSizeBytes

`func (o *GetCustom3DEnvironments200ResponseDataInner) SetSizeBytes(v int32)`

SetSizeBytes sets SizeBytes field to given value.

### HasSizeBytes

`func (o *GetCustom3DEnvironments200ResponseDataInner) HasSizeBytes() bool`

HasSizeBytes returns a boolean if a field has been set.

### SetSizeBytesNil

`func (o *GetCustom3DEnvironments200ResponseDataInner) SetSizeBytesNil(b bool)`

 SetSizeBytesNil sets the value for SizeBytes to be an explicit nil

### UnsetSizeBytes
`func (o *GetCustom3DEnvironments200ResponseDataInner) UnsetSizeBytes()`

UnsetSizeBytes ensures that no value is present for SizeBytes, not even an explicit nil
### GetStatus

`func (o *GetCustom3DEnvironments200ResponseDataInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GetCustom3DEnvironments200ResponseDataInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GetCustom3DEnvironments200ResponseDataInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetDownloadUrl

`func (o *GetCustom3DEnvironments200ResponseDataInner) GetDownloadUrl() string`

GetDownloadUrl returns the DownloadUrl field if non-nil, zero value otherwise.

### GetDownloadUrlOk

`func (o *GetCustom3DEnvironments200ResponseDataInner) GetDownloadUrlOk() (*string, bool)`

GetDownloadUrlOk returns a tuple with the DownloadUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownloadUrl

`func (o *GetCustom3DEnvironments200ResponseDataInner) SetDownloadUrl(v string)`

SetDownloadUrl sets DownloadUrl field to given value.

### HasDownloadUrl

`func (o *GetCustom3DEnvironments200ResponseDataInner) HasDownloadUrl() bool`

HasDownloadUrl returns a boolean if a field has been set.

### SetDownloadUrlNil

`func (o *GetCustom3DEnvironments200ResponseDataInner) SetDownloadUrlNil(b bool)`

 SetDownloadUrlNil sets the value for DownloadUrl to be an explicit nil

### UnsetDownloadUrl
`func (o *GetCustom3DEnvironments200ResponseDataInner) UnsetDownloadUrl()`

UnsetDownloadUrl ensures that no value is present for DownloadUrl, not even an explicit nil
### GetCreatedAt

`func (o *GetCustom3DEnvironments200ResponseDataInner) GetCreatedAt() Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetCustom3DEnvironments200ResponseDataInner) GetCreatedAtOk() (*Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetCustom3DEnvironments200ResponseDataInner) SetCreatedAt(v Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *GetCustom3DEnvironments200ResponseDataInner) GetUpdatedAt() Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetCustom3DEnvironments200ResponseDataInner) GetUpdatedAtOk() (*Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetCustom3DEnvironments200ResponseDataInner) SetUpdatedAt(v Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


