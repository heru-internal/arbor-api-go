# InitiateFileUploadRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Filename** | **string** | Name of the file to upload. Cannot end with .apk or .obb (except .obb files are allowed when appBundleId is provided). | 
**Path** | **string** |  | 
**AppBundleId** | Pointer to **string** | Optional UUID of an existing app bundle to associate this file with | [optional] 

## Methods

### NewInitiateFileUploadRequest

`func NewInitiateFileUploadRequest(filename string, path string, ) *InitiateFileUploadRequest`

NewInitiateFileUploadRequest instantiates a new InitiateFileUploadRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInitiateFileUploadRequestWithDefaults

`func NewInitiateFileUploadRequestWithDefaults() *InitiateFileUploadRequest`

NewInitiateFileUploadRequestWithDefaults instantiates a new InitiateFileUploadRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFilename

`func (o *InitiateFileUploadRequest) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *InitiateFileUploadRequest) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *InitiateFileUploadRequest) SetFilename(v string)`

SetFilename sets Filename field to given value.


### GetPath

`func (o *InitiateFileUploadRequest) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *InitiateFileUploadRequest) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *InitiateFileUploadRequest) SetPath(v string)`

SetPath sets Path field to given value.


### GetAppBundleId

`func (o *InitiateFileUploadRequest) GetAppBundleId() string`

GetAppBundleId returns the AppBundleId field if non-nil, zero value otherwise.

### GetAppBundleIdOk

`func (o *InitiateFileUploadRequest) GetAppBundleIdOk() (*string, bool)`

GetAppBundleIdOk returns a tuple with the AppBundleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppBundleId

`func (o *InitiateFileUploadRequest) SetAppBundleId(v string)`

SetAppBundleId sets AppBundleId field to given value.

### HasAppBundleId

`func (o *InitiateFileUploadRequest) HasAppBundleId() bool`

HasAppBundleId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


