# CreateAppBundleRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AppBuildId** | **string** | UUID of the existing app build to associate with this bundle | 
**Files** | Pointer to [**[]CreateAppBundleRequestFilesInner**](CreateAppBundleRequestFilesInner.md) | Optional array of files to associate with the bundle | [optional] 
**ReleaseChannelId** | Pointer to **string** | UUID of an existing release channel to associate with this bundle. Cannot be specified together with newReleaseChannelTitle. | [optional] 
**NewReleaseChannelTitle** | Pointer to **string** | Title for a new release channel to create and associate with this bundle. Cannot be specified together with releaseChannelId. | [optional] 

## Methods

### NewCreateAppBundleRequest

`func NewCreateAppBundleRequest(appBuildId string, ) *CreateAppBundleRequest`

NewCreateAppBundleRequest instantiates a new CreateAppBundleRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAppBundleRequestWithDefaults

`func NewCreateAppBundleRequestWithDefaults() *CreateAppBundleRequest`

NewCreateAppBundleRequestWithDefaults instantiates a new CreateAppBundleRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAppBuildId

`func (o *CreateAppBundleRequest) GetAppBuildId() string`

GetAppBuildId returns the AppBuildId field if non-nil, zero value otherwise.

### GetAppBuildIdOk

`func (o *CreateAppBundleRequest) GetAppBuildIdOk() (*string, bool)`

GetAppBuildIdOk returns a tuple with the AppBuildId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppBuildId

`func (o *CreateAppBundleRequest) SetAppBuildId(v string)`

SetAppBuildId sets AppBuildId field to given value.


### GetFiles

`func (o *CreateAppBundleRequest) GetFiles() []CreateAppBundleRequestFilesInner`

GetFiles returns the Files field if non-nil, zero value otherwise.

### GetFilesOk

`func (o *CreateAppBundleRequest) GetFilesOk() (*[]CreateAppBundleRequestFilesInner, bool)`

GetFilesOk returns a tuple with the Files field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFiles

`func (o *CreateAppBundleRequest) SetFiles(v []CreateAppBundleRequestFilesInner)`

SetFiles sets Files field to given value.

### HasFiles

`func (o *CreateAppBundleRequest) HasFiles() bool`

HasFiles returns a boolean if a field has been set.

### GetReleaseChannelId

`func (o *CreateAppBundleRequest) GetReleaseChannelId() string`

GetReleaseChannelId returns the ReleaseChannelId field if non-nil, zero value otherwise.

### GetReleaseChannelIdOk

`func (o *CreateAppBundleRequest) GetReleaseChannelIdOk() (*string, bool)`

GetReleaseChannelIdOk returns a tuple with the ReleaseChannelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseChannelId

`func (o *CreateAppBundleRequest) SetReleaseChannelId(v string)`

SetReleaseChannelId sets ReleaseChannelId field to given value.

### HasReleaseChannelId

`func (o *CreateAppBundleRequest) HasReleaseChannelId() bool`

HasReleaseChannelId returns a boolean if a field has been set.

### GetNewReleaseChannelTitle

`func (o *CreateAppBundleRequest) GetNewReleaseChannelTitle() string`

GetNewReleaseChannelTitle returns the NewReleaseChannelTitle field if non-nil, zero value otherwise.

### GetNewReleaseChannelTitleOk

`func (o *CreateAppBundleRequest) GetNewReleaseChannelTitleOk() (*string, bool)`

GetNewReleaseChannelTitleOk returns a tuple with the NewReleaseChannelTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewReleaseChannelTitle

`func (o *CreateAppBundleRequest) SetNewReleaseChannelTitle(v string)`

SetNewReleaseChannelTitle sets NewReleaseChannelTitle field to given value.

### HasNewReleaseChannelTitle

`func (o *CreateAppBundleRequest) HasNewReleaseChannelTitle() bool`

HasNewReleaseChannelTitle returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


