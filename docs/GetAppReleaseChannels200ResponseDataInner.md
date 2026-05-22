# GetAppReleaseChannels200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**App** | Pointer to [**GetApps200ResponseDataInner**](GetApps200ResponseDataInner.md) |  | [optional] 
**Version** | Pointer to [**CreateAppBundle201ResponseAppBuild**](CreateAppBundle201ResponseAppBuild.md) |  | [optional] 
**Bundle** | Pointer to [**CreateAppBundle201Response**](CreateAppBundle201Response.md) |  | [optional] 
**DeviceStatuses** | Pointer to [**[]GetAppReleaseChannels200ResponseDataInnerDeviceStatusesInner**](GetAppReleaseChannels200ResponseDataInnerDeviceStatusesInner.md) | Deprecated. Use the GET /apps/{appId}/release-channels/{releaseChannelId}/device-statuses endpoint instead. | [optional] 
**CreatedAt** | Pointer to **Time** |  | [optional] 
**UpdatedAt** | Pointer to **Time** |  | [optional] 

## Methods

### NewGetAppReleaseChannels200ResponseDataInner

`func NewGetAppReleaseChannels200ResponseDataInner() *GetAppReleaseChannels200ResponseDataInner`

NewGetAppReleaseChannels200ResponseDataInner instantiates a new GetAppReleaseChannels200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetAppReleaseChannels200ResponseDataInnerWithDefaults

`func NewGetAppReleaseChannels200ResponseDataInnerWithDefaults() *GetAppReleaseChannels200ResponseDataInner`

NewGetAppReleaseChannels200ResponseDataInnerWithDefaults instantiates a new GetAppReleaseChannels200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetAppReleaseChannels200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetAppReleaseChannels200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetAppReleaseChannels200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *GetAppReleaseChannels200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *GetAppReleaseChannels200ResponseDataInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GetAppReleaseChannels200ResponseDataInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GetAppReleaseChannels200ResponseDataInner) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *GetAppReleaseChannels200ResponseDataInner) HasName() bool`

HasName returns a boolean if a field has been set.

### GetApp

`func (o *GetAppReleaseChannels200ResponseDataInner) GetApp() GetApps200ResponseDataInner`

GetApp returns the App field if non-nil, zero value otherwise.

### GetAppOk

`func (o *GetAppReleaseChannels200ResponseDataInner) GetAppOk() (*GetApps200ResponseDataInner, bool)`

GetAppOk returns a tuple with the App field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApp

`func (o *GetAppReleaseChannels200ResponseDataInner) SetApp(v GetApps200ResponseDataInner)`

SetApp sets App field to given value.

### HasApp

`func (o *GetAppReleaseChannels200ResponseDataInner) HasApp() bool`

HasApp returns a boolean if a field has been set.

### GetVersion

`func (o *GetAppReleaseChannels200ResponseDataInner) GetVersion() CreateAppBundle201ResponseAppBuild`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *GetAppReleaseChannels200ResponseDataInner) GetVersionOk() (*CreateAppBundle201ResponseAppBuild, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *GetAppReleaseChannels200ResponseDataInner) SetVersion(v CreateAppBundle201ResponseAppBuild)`

SetVersion sets Version field to given value.

### HasVersion

`func (o *GetAppReleaseChannels200ResponseDataInner) HasVersion() bool`

HasVersion returns a boolean if a field has been set.

### GetBundle

`func (o *GetAppReleaseChannels200ResponseDataInner) GetBundle() CreateAppBundle201Response`

GetBundle returns the Bundle field if non-nil, zero value otherwise.

### GetBundleOk

`func (o *GetAppReleaseChannels200ResponseDataInner) GetBundleOk() (*CreateAppBundle201Response, bool)`

GetBundleOk returns a tuple with the Bundle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBundle

`func (o *GetAppReleaseChannels200ResponseDataInner) SetBundle(v CreateAppBundle201Response)`

SetBundle sets Bundle field to given value.

### HasBundle

`func (o *GetAppReleaseChannels200ResponseDataInner) HasBundle() bool`

HasBundle returns a boolean if a field has been set.

### GetDeviceStatuses

`func (o *GetAppReleaseChannels200ResponseDataInner) GetDeviceStatuses() []GetAppReleaseChannels200ResponseDataInnerDeviceStatusesInner`

GetDeviceStatuses returns the DeviceStatuses field if non-nil, zero value otherwise.

### GetDeviceStatusesOk

`func (o *GetAppReleaseChannels200ResponseDataInner) GetDeviceStatusesOk() (*[]GetAppReleaseChannels200ResponseDataInnerDeviceStatusesInner, bool)`

GetDeviceStatusesOk returns a tuple with the DeviceStatuses field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceStatuses

`func (o *GetAppReleaseChannels200ResponseDataInner) SetDeviceStatuses(v []GetAppReleaseChannels200ResponseDataInnerDeviceStatusesInner)`

SetDeviceStatuses sets DeviceStatuses field to given value.

### HasDeviceStatuses

`func (o *GetAppReleaseChannels200ResponseDataInner) HasDeviceStatuses() bool`

HasDeviceStatuses returns a boolean if a field has been set.

### GetCreatedAt

`func (o *GetAppReleaseChannels200ResponseDataInner) GetCreatedAt() Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetAppReleaseChannels200ResponseDataInner) GetCreatedAtOk() (*Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetAppReleaseChannels200ResponseDataInner) SetCreatedAt(v Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *GetAppReleaseChannels200ResponseDataInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *GetAppReleaseChannels200ResponseDataInner) GetUpdatedAt() Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetAppReleaseChannels200ResponseDataInner) GetUpdatedAtOk() (*Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetAppReleaseChannels200ResponseDataInner) SetUpdatedAt(v Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *GetAppReleaseChannels200ResponseDataInner) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


