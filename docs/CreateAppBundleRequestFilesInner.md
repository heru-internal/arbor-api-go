# CreateAppBundleRequestFilesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FileId** | **string** | UUID of the existing file | 
**Path** | Pointer to **string** | Optional custom device path for the file | [optional] 

## Methods

### NewCreateAppBundleRequestFilesInner

`func NewCreateAppBundleRequestFilesInner(fileId string, ) *CreateAppBundleRequestFilesInner`

NewCreateAppBundleRequestFilesInner instantiates a new CreateAppBundleRequestFilesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAppBundleRequestFilesInnerWithDefaults

`func NewCreateAppBundleRequestFilesInnerWithDefaults() *CreateAppBundleRequestFilesInner`

NewCreateAppBundleRequestFilesInnerWithDefaults instantiates a new CreateAppBundleRequestFilesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFileId

`func (o *CreateAppBundleRequestFilesInner) GetFileId() string`

GetFileId returns the FileId field if non-nil, zero value otherwise.

### GetFileIdOk

`func (o *CreateAppBundleRequestFilesInner) GetFileIdOk() (*string, bool)`

GetFileIdOk returns a tuple with the FileId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileId

`func (o *CreateAppBundleRequestFilesInner) SetFileId(v string)`

SetFileId sets FileId field to given value.


### GetPath

`func (o *CreateAppBundleRequestFilesInner) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *CreateAppBundleRequestFilesInner) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *CreateAppBundleRequestFilesInner) SetPath(v string)`

SetPath sets Path field to given value.

### HasPath

`func (o *CreateAppBundleRequestFilesInner) HasPath() bool`

HasPath returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


