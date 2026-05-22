# InitiateAppVersionUploadRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Filename** | **string** |  | 
**ReleaseChannelId** | Pointer to **string** | Mutually exclusive from newReleaseChannelTitle | [optional] 
**NewReleaseChannelTitle** | Pointer to **string** | Mutually exclusive from releaseChannelId | [optional] 
**AppBuildType** | Pointer to **string** | Type of app build. Use &#39;app-bundle&#39; to create an AppBundle with PENDING status. Defaults to &#39;standalone&#39;. | [optional] 

## Methods

### NewInitiateAppVersionUploadRequest

`func NewInitiateAppVersionUploadRequest(filename string, ) *InitiateAppVersionUploadRequest`

NewInitiateAppVersionUploadRequest instantiates a new InitiateAppVersionUploadRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInitiateAppVersionUploadRequestWithDefaults

`func NewInitiateAppVersionUploadRequestWithDefaults() *InitiateAppVersionUploadRequest`

NewInitiateAppVersionUploadRequestWithDefaults instantiates a new InitiateAppVersionUploadRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFilename

`func (o *InitiateAppVersionUploadRequest) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *InitiateAppVersionUploadRequest) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *InitiateAppVersionUploadRequest) SetFilename(v string)`

SetFilename sets Filename field to given value.


### GetReleaseChannelId

`func (o *InitiateAppVersionUploadRequest) GetReleaseChannelId() string`

GetReleaseChannelId returns the ReleaseChannelId field if non-nil, zero value otherwise.

### GetReleaseChannelIdOk

`func (o *InitiateAppVersionUploadRequest) GetReleaseChannelIdOk() (*string, bool)`

GetReleaseChannelIdOk returns a tuple with the ReleaseChannelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseChannelId

`func (o *InitiateAppVersionUploadRequest) SetReleaseChannelId(v string)`

SetReleaseChannelId sets ReleaseChannelId field to given value.

### HasReleaseChannelId

`func (o *InitiateAppVersionUploadRequest) HasReleaseChannelId() bool`

HasReleaseChannelId returns a boolean if a field has been set.

### GetNewReleaseChannelTitle

`func (o *InitiateAppVersionUploadRequest) GetNewReleaseChannelTitle() string`

GetNewReleaseChannelTitle returns the NewReleaseChannelTitle field if non-nil, zero value otherwise.

### GetNewReleaseChannelTitleOk

`func (o *InitiateAppVersionUploadRequest) GetNewReleaseChannelTitleOk() (*string, bool)`

GetNewReleaseChannelTitleOk returns a tuple with the NewReleaseChannelTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewReleaseChannelTitle

`func (o *InitiateAppVersionUploadRequest) SetNewReleaseChannelTitle(v string)`

SetNewReleaseChannelTitle sets NewReleaseChannelTitle field to given value.

### HasNewReleaseChannelTitle

`func (o *InitiateAppVersionUploadRequest) HasNewReleaseChannelTitle() bool`

HasNewReleaseChannelTitle returns a boolean if a field has been set.

### GetAppBuildType

`func (o *InitiateAppVersionUploadRequest) GetAppBuildType() string`

GetAppBuildType returns the AppBuildType field if non-nil, zero value otherwise.

### GetAppBuildTypeOk

`func (o *InitiateAppVersionUploadRequest) GetAppBuildTypeOk() (*string, bool)`

GetAppBuildTypeOk returns a tuple with the AppBuildType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppBuildType

`func (o *InitiateAppVersionUploadRequest) SetAppBuildType(v string)`

SetAppBuildType sets AppBuildType field to given value.

### HasAppBuildType

`func (o *InitiateAppVersionUploadRequest) HasAppBuildType() bool`

HasAppBuildType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


