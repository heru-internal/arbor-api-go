# GetAppBundleFiles200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Name** | **string** |  | 
**Location** | **string** |  | 
**BundlePaths** | **[]string** |  | 
**SizeBytes** | **int32** |  | 
**Checksum** | [**CreateAppBundle201ResponseAppBuildChecksum**](CreateAppBundle201ResponseAppBuildChecksum.md) |  | 
**CreatedAt** | **Time** |  | 
**UpdatedAt** | **Time** |  | 

## Methods

### NewGetAppBundleFiles200ResponseDataInner

`func NewGetAppBundleFiles200ResponseDataInner(id string, name string, location string, bundlePaths []string, sizeBytes int32, checksum CreateAppBundle201ResponseAppBuildChecksum, createdAt Time, updatedAt Time, ) *GetAppBundleFiles200ResponseDataInner`

NewGetAppBundleFiles200ResponseDataInner instantiates a new GetAppBundleFiles200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetAppBundleFiles200ResponseDataInnerWithDefaults

`func NewGetAppBundleFiles200ResponseDataInnerWithDefaults() *GetAppBundleFiles200ResponseDataInner`

NewGetAppBundleFiles200ResponseDataInnerWithDefaults instantiates a new GetAppBundleFiles200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetAppBundleFiles200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetAppBundleFiles200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetAppBundleFiles200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *GetAppBundleFiles200ResponseDataInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GetAppBundleFiles200ResponseDataInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GetAppBundleFiles200ResponseDataInner) SetName(v string)`

SetName sets Name field to given value.


### GetLocation

`func (o *GetAppBundleFiles200ResponseDataInner) GetLocation() string`

GetLocation returns the Location field if non-nil, zero value otherwise.

### GetLocationOk

`func (o *GetAppBundleFiles200ResponseDataInner) GetLocationOk() (*string, bool)`

GetLocationOk returns a tuple with the Location field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocation

`func (o *GetAppBundleFiles200ResponseDataInner) SetLocation(v string)`

SetLocation sets Location field to given value.


### GetBundlePaths

`func (o *GetAppBundleFiles200ResponseDataInner) GetBundlePaths() []string`

GetBundlePaths returns the BundlePaths field if non-nil, zero value otherwise.

### GetBundlePathsOk

`func (o *GetAppBundleFiles200ResponseDataInner) GetBundlePathsOk() (*[]string, bool)`

GetBundlePathsOk returns a tuple with the BundlePaths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundlePaths

`func (o *GetAppBundleFiles200ResponseDataInner) SetBundlePaths(v []string)`

SetBundlePaths sets BundlePaths field to given value.


### GetSizeBytes

`func (o *GetAppBundleFiles200ResponseDataInner) GetSizeBytes() int32`

GetSizeBytes returns the SizeBytes field if non-nil, zero value otherwise.

### GetSizeBytesOk

`func (o *GetAppBundleFiles200ResponseDataInner) GetSizeBytesOk() (*int32, bool)`

GetSizeBytesOk returns a tuple with the SizeBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSizeBytes

`func (o *GetAppBundleFiles200ResponseDataInner) SetSizeBytes(v int32)`

SetSizeBytes sets SizeBytes field to given value.


### GetChecksum

`func (o *GetAppBundleFiles200ResponseDataInner) GetChecksum() CreateAppBundle201ResponseAppBuildChecksum`

GetChecksum returns the Checksum field if non-nil, zero value otherwise.

### GetChecksumOk

`func (o *GetAppBundleFiles200ResponseDataInner) GetChecksumOk() (*CreateAppBundle201ResponseAppBuildChecksum, bool)`

GetChecksumOk returns a tuple with the Checksum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecksum

`func (o *GetAppBundleFiles200ResponseDataInner) SetChecksum(v CreateAppBundle201ResponseAppBuildChecksum)`

SetChecksum sets Checksum field to given value.


### GetCreatedAt

`func (o *GetAppBundleFiles200ResponseDataInner) GetCreatedAt() Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetAppBundleFiles200ResponseDataInner) GetCreatedAtOk() (*Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetAppBundleFiles200ResponseDataInner) SetCreatedAt(v Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *GetAppBundleFiles200ResponseDataInner) GetUpdatedAt() Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetAppBundleFiles200ResponseDataInner) GetUpdatedAtOk() (*Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetAppBundleFiles200ResponseDataInner) SetUpdatedAt(v Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


