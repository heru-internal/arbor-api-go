# GetDevices200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Organization** | Pointer to [**GetCurrentOrganization200Response**](GetCurrentOrganization200Response.md) |  | [optional] 
**Name** | **string** |  | 
**SerialNumber** | **string** |  | 
**Group** | Pointer to [**GetDevices200ResponseDataInnerGroup**](GetDevices200ResponseDataInnerGroup.md) |  | [optional] 
**DeviceModel** | [**GetApps200ResponseDataInnerDeviceModelsInner**](GetApps200ResponseDataInnerDeviceModelsInner.md) |  | 
**Tags** | **[]string** |  | 
**LastCommunicatedAt** | Pointer to **NullableTime** |  | [optional] 
**IsOnline** | **bool** |  | 
**ClientVersion** | Pointer to **NullableString** |  | [optional] 
**LauncherVersion** | Pointer to **NullableString** |  | [optional] 
**EnrollmentDate** | **NullableTime** |  | 
**SystemVersion** | Pointer to **NullableString** |  | [optional] 
**OsVersion** | Pointer to **NullableString** |  | [optional] 
**Ssid** | Pointer to **NullableString** |  | [optional] 
**MacAddress** | Pointer to **NullableString** |  | [optional] 
**RandomizedMacAddress** | Pointer to **NullableString** |  | [optional] 
**StorageSpaceFreeBytes** | Pointer to **NullableInt64** | Free storage space in bytes | [optional] 
**StorageSpaceTotalBytes** | Pointer to **NullableInt64** | Total storage space in bytes | [optional] 
**BatteryHealth** | Pointer to **NullableString** |  | [optional] 
**BatteryCharging** | Pointer to **NullableBool** |  | [optional] 
**BatteryPercentage** | Pointer to **NullableInt32** |  | [optional] 
**BatteryTemperatureC** | Pointer to **NullableFloat32** |  | [optional] 
**IpAddress** | Pointer to **NullableString** |  | [optional] 
**SignalStrength** | Pointer to **NullableFloat32** |  | [optional] 
**FrequencyMhz** | Pointer to **NullableInt32** |  | [optional] 
**LinkSpeedMbps** | Pointer to **NullableInt32** |  | [optional] 
**LastLocationLatitude** | Pointer to **NullableFloat32** |  | [optional] 
**LastLocationLongitude** | Pointer to **NullableFloat32** |  | [optional] 
**LastLocationAt** | Pointer to **NullableTime** |  | [optional] 
**RunningApp** | Pointer to [**NullableGetDevices200ResponseDataInnerRunningApp**](GetDevices200ResponseDataInnerRunningApp.md) |  | [optional] 
**CustomFields** | [**[]GetDevices200ResponseDataInnerCustomFieldsInner**](GetDevices200ResponseDataInnerCustomFieldsInner.md) |  | 
**ComplianceStatus** | **string** |  | 
**Controllers** | [**[]GetDevices200ResponseDataInnerControllersInner**](GetDevices200ResponseDataInnerControllersInner.md) | Currently, only PICO &amp; Meta Hms devices report this data. | 
**CreatedAt** | **Time** |  | 
**UpdatedAt** | **Time** |  | 

## Methods

### NewGetDevices200ResponseDataInner

`func NewGetDevices200ResponseDataInner(id string, name string, serialNumber string, deviceModel GetApps200ResponseDataInnerDeviceModelsInner, tags []string, isOnline bool, enrollmentDate NullableTime, customFields []GetDevices200ResponseDataInnerCustomFieldsInner, complianceStatus string, controllers []GetDevices200ResponseDataInnerControllersInner, createdAt Time, updatedAt Time, ) *GetDevices200ResponseDataInner`

NewGetDevices200ResponseDataInner instantiates a new GetDevices200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetDevices200ResponseDataInnerWithDefaults

`func NewGetDevices200ResponseDataInnerWithDefaults() *GetDevices200ResponseDataInner`

NewGetDevices200ResponseDataInnerWithDefaults instantiates a new GetDevices200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetDevices200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetDevices200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetDevices200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.


### GetOrganization

`func (o *GetDevices200ResponseDataInner) GetOrganization() GetCurrentOrganization200Response`

GetOrganization returns the Organization field if non-nil, zero value otherwise.

### GetOrganizationOk

`func (o *GetDevices200ResponseDataInner) GetOrganizationOk() (*GetCurrentOrganization200Response, bool)`

GetOrganizationOk returns a tuple with the Organization field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganization

`func (o *GetDevices200ResponseDataInner) SetOrganization(v GetCurrentOrganization200Response)`

SetOrganization sets Organization field to given value.

### HasOrganization

`func (o *GetDevices200ResponseDataInner) HasOrganization() bool`

HasOrganization returns a boolean if a field has been set.

### GetName

`func (o *GetDevices200ResponseDataInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GetDevices200ResponseDataInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GetDevices200ResponseDataInner) SetName(v string)`

SetName sets Name field to given value.


### GetSerialNumber

`func (o *GetDevices200ResponseDataInner) GetSerialNumber() string`

GetSerialNumber returns the SerialNumber field if non-nil, zero value otherwise.

### GetSerialNumberOk

`func (o *GetDevices200ResponseDataInner) GetSerialNumberOk() (*string, bool)`

GetSerialNumberOk returns a tuple with the SerialNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNumber

`func (o *GetDevices200ResponseDataInner) SetSerialNumber(v string)`

SetSerialNumber sets SerialNumber field to given value.


### GetGroup

`func (o *GetDevices200ResponseDataInner) GetGroup() GetDevices200ResponseDataInnerGroup`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *GetDevices200ResponseDataInner) GetGroupOk() (*GetDevices200ResponseDataInnerGroup, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *GetDevices200ResponseDataInner) SetGroup(v GetDevices200ResponseDataInnerGroup)`

SetGroup sets Group field to given value.

### HasGroup

`func (o *GetDevices200ResponseDataInner) HasGroup() bool`

HasGroup returns a boolean if a field has been set.

### GetDeviceModel

`func (o *GetDevices200ResponseDataInner) GetDeviceModel() GetApps200ResponseDataInnerDeviceModelsInner`

GetDeviceModel returns the DeviceModel field if non-nil, zero value otherwise.

### GetDeviceModelOk

`func (o *GetDevices200ResponseDataInner) GetDeviceModelOk() (*GetApps200ResponseDataInnerDeviceModelsInner, bool)`

GetDeviceModelOk returns a tuple with the DeviceModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceModel

`func (o *GetDevices200ResponseDataInner) SetDeviceModel(v GetApps200ResponseDataInnerDeviceModelsInner)`

SetDeviceModel sets DeviceModel field to given value.


### GetTags

`func (o *GetDevices200ResponseDataInner) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *GetDevices200ResponseDataInner) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *GetDevices200ResponseDataInner) SetTags(v []string)`

SetTags sets Tags field to given value.


### GetLastCommunicatedAt

`func (o *GetDevices200ResponseDataInner) GetLastCommunicatedAt() Time`

GetLastCommunicatedAt returns the LastCommunicatedAt field if non-nil, zero value otherwise.

### GetLastCommunicatedAtOk

`func (o *GetDevices200ResponseDataInner) GetLastCommunicatedAtOk() (*Time, bool)`

GetLastCommunicatedAtOk returns a tuple with the LastCommunicatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastCommunicatedAt

`func (o *GetDevices200ResponseDataInner) SetLastCommunicatedAt(v Time)`

SetLastCommunicatedAt sets LastCommunicatedAt field to given value.

### HasLastCommunicatedAt

`func (o *GetDevices200ResponseDataInner) HasLastCommunicatedAt() bool`

HasLastCommunicatedAt returns a boolean if a field has been set.

### SetLastCommunicatedAtNil

`func (o *GetDevices200ResponseDataInner) SetLastCommunicatedAtNil(b bool)`

 SetLastCommunicatedAtNil sets the value for LastCommunicatedAt to be an explicit nil

### UnsetLastCommunicatedAt
`func (o *GetDevices200ResponseDataInner) UnsetLastCommunicatedAt()`

UnsetLastCommunicatedAt ensures that no value is present for LastCommunicatedAt, not even an explicit nil
### GetIsOnline

`func (o *GetDevices200ResponseDataInner) GetIsOnline() bool`

GetIsOnline returns the IsOnline field if non-nil, zero value otherwise.

### GetIsOnlineOk

`func (o *GetDevices200ResponseDataInner) GetIsOnlineOk() (*bool, bool)`

GetIsOnlineOk returns a tuple with the IsOnline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOnline

`func (o *GetDevices200ResponseDataInner) SetIsOnline(v bool)`

SetIsOnline sets IsOnline field to given value.


### GetClientVersion

`func (o *GetDevices200ResponseDataInner) GetClientVersion() string`

GetClientVersion returns the ClientVersion field if non-nil, zero value otherwise.

### GetClientVersionOk

`func (o *GetDevices200ResponseDataInner) GetClientVersionOk() (*string, bool)`

GetClientVersionOk returns a tuple with the ClientVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientVersion

`func (o *GetDevices200ResponseDataInner) SetClientVersion(v string)`

SetClientVersion sets ClientVersion field to given value.

### HasClientVersion

`func (o *GetDevices200ResponseDataInner) HasClientVersion() bool`

HasClientVersion returns a boolean if a field has been set.

### SetClientVersionNil

`func (o *GetDevices200ResponseDataInner) SetClientVersionNil(b bool)`

 SetClientVersionNil sets the value for ClientVersion to be an explicit nil

### UnsetClientVersion
`func (o *GetDevices200ResponseDataInner) UnsetClientVersion()`

UnsetClientVersion ensures that no value is present for ClientVersion, not even an explicit nil
### GetLauncherVersion

`func (o *GetDevices200ResponseDataInner) GetLauncherVersion() string`

GetLauncherVersion returns the LauncherVersion field if non-nil, zero value otherwise.

### GetLauncherVersionOk

`func (o *GetDevices200ResponseDataInner) GetLauncherVersionOk() (*string, bool)`

GetLauncherVersionOk returns a tuple with the LauncherVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLauncherVersion

`func (o *GetDevices200ResponseDataInner) SetLauncherVersion(v string)`

SetLauncherVersion sets LauncherVersion field to given value.

### HasLauncherVersion

`func (o *GetDevices200ResponseDataInner) HasLauncherVersion() bool`

HasLauncherVersion returns a boolean if a field has been set.

### SetLauncherVersionNil

`func (o *GetDevices200ResponseDataInner) SetLauncherVersionNil(b bool)`

 SetLauncherVersionNil sets the value for LauncherVersion to be an explicit nil

### UnsetLauncherVersion
`func (o *GetDevices200ResponseDataInner) UnsetLauncherVersion()`

UnsetLauncherVersion ensures that no value is present for LauncherVersion, not even an explicit nil
### GetEnrollmentDate

`func (o *GetDevices200ResponseDataInner) GetEnrollmentDate() Time`

GetEnrollmentDate returns the EnrollmentDate field if non-nil, zero value otherwise.

### GetEnrollmentDateOk

`func (o *GetDevices200ResponseDataInner) GetEnrollmentDateOk() (*Time, bool)`

GetEnrollmentDateOk returns a tuple with the EnrollmentDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnrollmentDate

`func (o *GetDevices200ResponseDataInner) SetEnrollmentDate(v Time)`

SetEnrollmentDate sets EnrollmentDate field to given value.


### SetEnrollmentDateNil

`func (o *GetDevices200ResponseDataInner) SetEnrollmentDateNil(b bool)`

 SetEnrollmentDateNil sets the value for EnrollmentDate to be an explicit nil

### UnsetEnrollmentDate
`func (o *GetDevices200ResponseDataInner) UnsetEnrollmentDate()`

UnsetEnrollmentDate ensures that no value is present for EnrollmentDate, not even an explicit nil
### GetSystemVersion

`func (o *GetDevices200ResponseDataInner) GetSystemVersion() string`

GetSystemVersion returns the SystemVersion field if non-nil, zero value otherwise.

### GetSystemVersionOk

`func (o *GetDevices200ResponseDataInner) GetSystemVersionOk() (*string, bool)`

GetSystemVersionOk returns a tuple with the SystemVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemVersion

`func (o *GetDevices200ResponseDataInner) SetSystemVersion(v string)`

SetSystemVersion sets SystemVersion field to given value.

### HasSystemVersion

`func (o *GetDevices200ResponseDataInner) HasSystemVersion() bool`

HasSystemVersion returns a boolean if a field has been set.

### SetSystemVersionNil

`func (o *GetDevices200ResponseDataInner) SetSystemVersionNil(b bool)`

 SetSystemVersionNil sets the value for SystemVersion to be an explicit nil

### UnsetSystemVersion
`func (o *GetDevices200ResponseDataInner) UnsetSystemVersion()`

UnsetSystemVersion ensures that no value is present for SystemVersion, not even an explicit nil
### GetOsVersion

`func (o *GetDevices200ResponseDataInner) GetOsVersion() string`

GetOsVersion returns the OsVersion field if non-nil, zero value otherwise.

### GetOsVersionOk

`func (o *GetDevices200ResponseDataInner) GetOsVersionOk() (*string, bool)`

GetOsVersionOk returns a tuple with the OsVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOsVersion

`func (o *GetDevices200ResponseDataInner) SetOsVersion(v string)`

SetOsVersion sets OsVersion field to given value.

### HasOsVersion

`func (o *GetDevices200ResponseDataInner) HasOsVersion() bool`

HasOsVersion returns a boolean if a field has been set.

### SetOsVersionNil

`func (o *GetDevices200ResponseDataInner) SetOsVersionNil(b bool)`

 SetOsVersionNil sets the value for OsVersion to be an explicit nil

### UnsetOsVersion
`func (o *GetDevices200ResponseDataInner) UnsetOsVersion()`

UnsetOsVersion ensures that no value is present for OsVersion, not even an explicit nil
### GetSsid

`func (o *GetDevices200ResponseDataInner) GetSsid() string`

GetSsid returns the Ssid field if non-nil, zero value otherwise.

### GetSsidOk

`func (o *GetDevices200ResponseDataInner) GetSsidOk() (*string, bool)`

GetSsidOk returns a tuple with the Ssid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSsid

`func (o *GetDevices200ResponseDataInner) SetSsid(v string)`

SetSsid sets Ssid field to given value.

### HasSsid

`func (o *GetDevices200ResponseDataInner) HasSsid() bool`

HasSsid returns a boolean if a field has been set.

### SetSsidNil

`func (o *GetDevices200ResponseDataInner) SetSsidNil(b bool)`

 SetSsidNil sets the value for Ssid to be an explicit nil

### UnsetSsid
`func (o *GetDevices200ResponseDataInner) UnsetSsid()`

UnsetSsid ensures that no value is present for Ssid, not even an explicit nil
### GetMacAddress

`func (o *GetDevices200ResponseDataInner) GetMacAddress() string`

GetMacAddress returns the MacAddress field if non-nil, zero value otherwise.

### GetMacAddressOk

`func (o *GetDevices200ResponseDataInner) GetMacAddressOk() (*string, bool)`

GetMacAddressOk returns a tuple with the MacAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMacAddress

`func (o *GetDevices200ResponseDataInner) SetMacAddress(v string)`

SetMacAddress sets MacAddress field to given value.

### HasMacAddress

`func (o *GetDevices200ResponseDataInner) HasMacAddress() bool`

HasMacAddress returns a boolean if a field has been set.

### SetMacAddressNil

`func (o *GetDevices200ResponseDataInner) SetMacAddressNil(b bool)`

 SetMacAddressNil sets the value for MacAddress to be an explicit nil

### UnsetMacAddress
`func (o *GetDevices200ResponseDataInner) UnsetMacAddress()`

UnsetMacAddress ensures that no value is present for MacAddress, not even an explicit nil
### GetRandomizedMacAddress

`func (o *GetDevices200ResponseDataInner) GetRandomizedMacAddress() string`

GetRandomizedMacAddress returns the RandomizedMacAddress field if non-nil, zero value otherwise.

### GetRandomizedMacAddressOk

`func (o *GetDevices200ResponseDataInner) GetRandomizedMacAddressOk() (*string, bool)`

GetRandomizedMacAddressOk returns a tuple with the RandomizedMacAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRandomizedMacAddress

`func (o *GetDevices200ResponseDataInner) SetRandomizedMacAddress(v string)`

SetRandomizedMacAddress sets RandomizedMacAddress field to given value.

### HasRandomizedMacAddress

`func (o *GetDevices200ResponseDataInner) HasRandomizedMacAddress() bool`

HasRandomizedMacAddress returns a boolean if a field has been set.

### SetRandomizedMacAddressNil

`func (o *GetDevices200ResponseDataInner) SetRandomizedMacAddressNil(b bool)`

 SetRandomizedMacAddressNil sets the value for RandomizedMacAddress to be an explicit nil

### UnsetRandomizedMacAddress
`func (o *GetDevices200ResponseDataInner) UnsetRandomizedMacAddress()`

UnsetRandomizedMacAddress ensures that no value is present for RandomizedMacAddress, not even an explicit nil
### GetStorageSpaceFreeBytes

`func (o *GetDevices200ResponseDataInner) GetStorageSpaceFreeBytes() int64`

GetStorageSpaceFreeBytes returns the StorageSpaceFreeBytes field if non-nil, zero value otherwise.

### GetStorageSpaceFreeBytesOk

`func (o *GetDevices200ResponseDataInner) GetStorageSpaceFreeBytesOk() (*int64, bool)`

GetStorageSpaceFreeBytesOk returns a tuple with the StorageSpaceFreeBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageSpaceFreeBytes

`func (o *GetDevices200ResponseDataInner) SetStorageSpaceFreeBytes(v int64)`

SetStorageSpaceFreeBytes sets StorageSpaceFreeBytes field to given value.

### HasStorageSpaceFreeBytes

`func (o *GetDevices200ResponseDataInner) HasStorageSpaceFreeBytes() bool`

HasStorageSpaceFreeBytes returns a boolean if a field has been set.

### SetStorageSpaceFreeBytesNil

`func (o *GetDevices200ResponseDataInner) SetStorageSpaceFreeBytesNil(b bool)`

 SetStorageSpaceFreeBytesNil sets the value for StorageSpaceFreeBytes to be an explicit nil

### UnsetStorageSpaceFreeBytes
`func (o *GetDevices200ResponseDataInner) UnsetStorageSpaceFreeBytes()`

UnsetStorageSpaceFreeBytes ensures that no value is present for StorageSpaceFreeBytes, not even an explicit nil
### GetStorageSpaceTotalBytes

`func (o *GetDevices200ResponseDataInner) GetStorageSpaceTotalBytes() int64`

GetStorageSpaceTotalBytes returns the StorageSpaceTotalBytes field if non-nil, zero value otherwise.

### GetStorageSpaceTotalBytesOk

`func (o *GetDevices200ResponseDataInner) GetStorageSpaceTotalBytesOk() (*int64, bool)`

GetStorageSpaceTotalBytesOk returns a tuple with the StorageSpaceTotalBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageSpaceTotalBytes

`func (o *GetDevices200ResponseDataInner) SetStorageSpaceTotalBytes(v int64)`

SetStorageSpaceTotalBytes sets StorageSpaceTotalBytes field to given value.

### HasStorageSpaceTotalBytes

`func (o *GetDevices200ResponseDataInner) HasStorageSpaceTotalBytes() bool`

HasStorageSpaceTotalBytes returns a boolean if a field has been set.

### SetStorageSpaceTotalBytesNil

`func (o *GetDevices200ResponseDataInner) SetStorageSpaceTotalBytesNil(b bool)`

 SetStorageSpaceTotalBytesNil sets the value for StorageSpaceTotalBytes to be an explicit nil

### UnsetStorageSpaceTotalBytes
`func (o *GetDevices200ResponseDataInner) UnsetStorageSpaceTotalBytes()`

UnsetStorageSpaceTotalBytes ensures that no value is present for StorageSpaceTotalBytes, not even an explicit nil
### GetBatteryHealth

`func (o *GetDevices200ResponseDataInner) GetBatteryHealth() string`

GetBatteryHealth returns the BatteryHealth field if non-nil, zero value otherwise.

### GetBatteryHealthOk

`func (o *GetDevices200ResponseDataInner) GetBatteryHealthOk() (*string, bool)`

GetBatteryHealthOk returns a tuple with the BatteryHealth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatteryHealth

`func (o *GetDevices200ResponseDataInner) SetBatteryHealth(v string)`

SetBatteryHealth sets BatteryHealth field to given value.

### HasBatteryHealth

`func (o *GetDevices200ResponseDataInner) HasBatteryHealth() bool`

HasBatteryHealth returns a boolean if a field has been set.

### SetBatteryHealthNil

`func (o *GetDevices200ResponseDataInner) SetBatteryHealthNil(b bool)`

 SetBatteryHealthNil sets the value for BatteryHealth to be an explicit nil

### UnsetBatteryHealth
`func (o *GetDevices200ResponseDataInner) UnsetBatteryHealth()`

UnsetBatteryHealth ensures that no value is present for BatteryHealth, not even an explicit nil
### GetBatteryCharging

`func (o *GetDevices200ResponseDataInner) GetBatteryCharging() bool`

GetBatteryCharging returns the BatteryCharging field if non-nil, zero value otherwise.

### GetBatteryChargingOk

`func (o *GetDevices200ResponseDataInner) GetBatteryChargingOk() (*bool, bool)`

GetBatteryChargingOk returns a tuple with the BatteryCharging field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatteryCharging

`func (o *GetDevices200ResponseDataInner) SetBatteryCharging(v bool)`

SetBatteryCharging sets BatteryCharging field to given value.

### HasBatteryCharging

`func (o *GetDevices200ResponseDataInner) HasBatteryCharging() bool`

HasBatteryCharging returns a boolean if a field has been set.

### SetBatteryChargingNil

`func (o *GetDevices200ResponseDataInner) SetBatteryChargingNil(b bool)`

 SetBatteryChargingNil sets the value for BatteryCharging to be an explicit nil

### UnsetBatteryCharging
`func (o *GetDevices200ResponseDataInner) UnsetBatteryCharging()`

UnsetBatteryCharging ensures that no value is present for BatteryCharging, not even an explicit nil
### GetBatteryPercentage

`func (o *GetDevices200ResponseDataInner) GetBatteryPercentage() int32`

GetBatteryPercentage returns the BatteryPercentage field if non-nil, zero value otherwise.

### GetBatteryPercentageOk

`func (o *GetDevices200ResponseDataInner) GetBatteryPercentageOk() (*int32, bool)`

GetBatteryPercentageOk returns a tuple with the BatteryPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatteryPercentage

`func (o *GetDevices200ResponseDataInner) SetBatteryPercentage(v int32)`

SetBatteryPercentage sets BatteryPercentage field to given value.

### HasBatteryPercentage

`func (o *GetDevices200ResponseDataInner) HasBatteryPercentage() bool`

HasBatteryPercentage returns a boolean if a field has been set.

### SetBatteryPercentageNil

`func (o *GetDevices200ResponseDataInner) SetBatteryPercentageNil(b bool)`

 SetBatteryPercentageNil sets the value for BatteryPercentage to be an explicit nil

### UnsetBatteryPercentage
`func (o *GetDevices200ResponseDataInner) UnsetBatteryPercentage()`

UnsetBatteryPercentage ensures that no value is present for BatteryPercentage, not even an explicit nil
### GetBatteryTemperatureC

`func (o *GetDevices200ResponseDataInner) GetBatteryTemperatureC() float32`

GetBatteryTemperatureC returns the BatteryTemperatureC field if non-nil, zero value otherwise.

### GetBatteryTemperatureCOk

`func (o *GetDevices200ResponseDataInner) GetBatteryTemperatureCOk() (*float32, bool)`

GetBatteryTemperatureCOk returns a tuple with the BatteryTemperatureC field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatteryTemperatureC

`func (o *GetDevices200ResponseDataInner) SetBatteryTemperatureC(v float32)`

SetBatteryTemperatureC sets BatteryTemperatureC field to given value.

### HasBatteryTemperatureC

`func (o *GetDevices200ResponseDataInner) HasBatteryTemperatureC() bool`

HasBatteryTemperatureC returns a boolean if a field has been set.

### SetBatteryTemperatureCNil

`func (o *GetDevices200ResponseDataInner) SetBatteryTemperatureCNil(b bool)`

 SetBatteryTemperatureCNil sets the value for BatteryTemperatureC to be an explicit nil

### UnsetBatteryTemperatureC
`func (o *GetDevices200ResponseDataInner) UnsetBatteryTemperatureC()`

UnsetBatteryTemperatureC ensures that no value is present for BatteryTemperatureC, not even an explicit nil
### GetIpAddress

`func (o *GetDevices200ResponseDataInner) GetIpAddress() string`

GetIpAddress returns the IpAddress field if non-nil, zero value otherwise.

### GetIpAddressOk

`func (o *GetDevices200ResponseDataInner) GetIpAddressOk() (*string, bool)`

GetIpAddressOk returns a tuple with the IpAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpAddress

`func (o *GetDevices200ResponseDataInner) SetIpAddress(v string)`

SetIpAddress sets IpAddress field to given value.

### HasIpAddress

`func (o *GetDevices200ResponseDataInner) HasIpAddress() bool`

HasIpAddress returns a boolean if a field has been set.

### SetIpAddressNil

`func (o *GetDevices200ResponseDataInner) SetIpAddressNil(b bool)`

 SetIpAddressNil sets the value for IpAddress to be an explicit nil

### UnsetIpAddress
`func (o *GetDevices200ResponseDataInner) UnsetIpAddress()`

UnsetIpAddress ensures that no value is present for IpAddress, not even an explicit nil
### GetSignalStrength

`func (o *GetDevices200ResponseDataInner) GetSignalStrength() float32`

GetSignalStrength returns the SignalStrength field if non-nil, zero value otherwise.

### GetSignalStrengthOk

`func (o *GetDevices200ResponseDataInner) GetSignalStrengthOk() (*float32, bool)`

GetSignalStrengthOk returns a tuple with the SignalStrength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignalStrength

`func (o *GetDevices200ResponseDataInner) SetSignalStrength(v float32)`

SetSignalStrength sets SignalStrength field to given value.

### HasSignalStrength

`func (o *GetDevices200ResponseDataInner) HasSignalStrength() bool`

HasSignalStrength returns a boolean if a field has been set.

### SetSignalStrengthNil

`func (o *GetDevices200ResponseDataInner) SetSignalStrengthNil(b bool)`

 SetSignalStrengthNil sets the value for SignalStrength to be an explicit nil

### UnsetSignalStrength
`func (o *GetDevices200ResponseDataInner) UnsetSignalStrength()`

UnsetSignalStrength ensures that no value is present for SignalStrength, not even an explicit nil
### GetFrequencyMhz

`func (o *GetDevices200ResponseDataInner) GetFrequencyMhz() int32`

GetFrequencyMhz returns the FrequencyMhz field if non-nil, zero value otherwise.

### GetFrequencyMhzOk

`func (o *GetDevices200ResponseDataInner) GetFrequencyMhzOk() (*int32, bool)`

GetFrequencyMhzOk returns a tuple with the FrequencyMhz field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrequencyMhz

`func (o *GetDevices200ResponseDataInner) SetFrequencyMhz(v int32)`

SetFrequencyMhz sets FrequencyMhz field to given value.

### HasFrequencyMhz

`func (o *GetDevices200ResponseDataInner) HasFrequencyMhz() bool`

HasFrequencyMhz returns a boolean if a field has been set.

### SetFrequencyMhzNil

`func (o *GetDevices200ResponseDataInner) SetFrequencyMhzNil(b bool)`

 SetFrequencyMhzNil sets the value for FrequencyMhz to be an explicit nil

### UnsetFrequencyMhz
`func (o *GetDevices200ResponseDataInner) UnsetFrequencyMhz()`

UnsetFrequencyMhz ensures that no value is present for FrequencyMhz, not even an explicit nil
### GetLinkSpeedMbps

`func (o *GetDevices200ResponseDataInner) GetLinkSpeedMbps() int32`

GetLinkSpeedMbps returns the LinkSpeedMbps field if non-nil, zero value otherwise.

### GetLinkSpeedMbpsOk

`func (o *GetDevices200ResponseDataInner) GetLinkSpeedMbpsOk() (*int32, bool)`

GetLinkSpeedMbpsOk returns a tuple with the LinkSpeedMbps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkSpeedMbps

`func (o *GetDevices200ResponseDataInner) SetLinkSpeedMbps(v int32)`

SetLinkSpeedMbps sets LinkSpeedMbps field to given value.

### HasLinkSpeedMbps

`func (o *GetDevices200ResponseDataInner) HasLinkSpeedMbps() bool`

HasLinkSpeedMbps returns a boolean if a field has been set.

### SetLinkSpeedMbpsNil

`func (o *GetDevices200ResponseDataInner) SetLinkSpeedMbpsNil(b bool)`

 SetLinkSpeedMbpsNil sets the value for LinkSpeedMbps to be an explicit nil

### UnsetLinkSpeedMbps
`func (o *GetDevices200ResponseDataInner) UnsetLinkSpeedMbps()`

UnsetLinkSpeedMbps ensures that no value is present for LinkSpeedMbps, not even an explicit nil
### GetLastLocationLatitude

`func (o *GetDevices200ResponseDataInner) GetLastLocationLatitude() float32`

GetLastLocationLatitude returns the LastLocationLatitude field if non-nil, zero value otherwise.

### GetLastLocationLatitudeOk

`func (o *GetDevices200ResponseDataInner) GetLastLocationLatitudeOk() (*float32, bool)`

GetLastLocationLatitudeOk returns a tuple with the LastLocationLatitude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastLocationLatitude

`func (o *GetDevices200ResponseDataInner) SetLastLocationLatitude(v float32)`

SetLastLocationLatitude sets LastLocationLatitude field to given value.

### HasLastLocationLatitude

`func (o *GetDevices200ResponseDataInner) HasLastLocationLatitude() bool`

HasLastLocationLatitude returns a boolean if a field has been set.

### SetLastLocationLatitudeNil

`func (o *GetDevices200ResponseDataInner) SetLastLocationLatitudeNil(b bool)`

 SetLastLocationLatitudeNil sets the value for LastLocationLatitude to be an explicit nil

### UnsetLastLocationLatitude
`func (o *GetDevices200ResponseDataInner) UnsetLastLocationLatitude()`

UnsetLastLocationLatitude ensures that no value is present for LastLocationLatitude, not even an explicit nil
### GetLastLocationLongitude

`func (o *GetDevices200ResponseDataInner) GetLastLocationLongitude() float32`

GetLastLocationLongitude returns the LastLocationLongitude field if non-nil, zero value otherwise.

### GetLastLocationLongitudeOk

`func (o *GetDevices200ResponseDataInner) GetLastLocationLongitudeOk() (*float32, bool)`

GetLastLocationLongitudeOk returns a tuple with the LastLocationLongitude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastLocationLongitude

`func (o *GetDevices200ResponseDataInner) SetLastLocationLongitude(v float32)`

SetLastLocationLongitude sets LastLocationLongitude field to given value.

### HasLastLocationLongitude

`func (o *GetDevices200ResponseDataInner) HasLastLocationLongitude() bool`

HasLastLocationLongitude returns a boolean if a field has been set.

### SetLastLocationLongitudeNil

`func (o *GetDevices200ResponseDataInner) SetLastLocationLongitudeNil(b bool)`

 SetLastLocationLongitudeNil sets the value for LastLocationLongitude to be an explicit nil

### UnsetLastLocationLongitude
`func (o *GetDevices200ResponseDataInner) UnsetLastLocationLongitude()`

UnsetLastLocationLongitude ensures that no value is present for LastLocationLongitude, not even an explicit nil
### GetLastLocationAt

`func (o *GetDevices200ResponseDataInner) GetLastLocationAt() Time`

GetLastLocationAt returns the LastLocationAt field if non-nil, zero value otherwise.

### GetLastLocationAtOk

`func (o *GetDevices200ResponseDataInner) GetLastLocationAtOk() (*Time, bool)`

GetLastLocationAtOk returns a tuple with the LastLocationAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastLocationAt

`func (o *GetDevices200ResponseDataInner) SetLastLocationAt(v Time)`

SetLastLocationAt sets LastLocationAt field to given value.

### HasLastLocationAt

`func (o *GetDevices200ResponseDataInner) HasLastLocationAt() bool`

HasLastLocationAt returns a boolean if a field has been set.

### SetLastLocationAtNil

`func (o *GetDevices200ResponseDataInner) SetLastLocationAtNil(b bool)`

 SetLastLocationAtNil sets the value for LastLocationAt to be an explicit nil

### UnsetLastLocationAt
`func (o *GetDevices200ResponseDataInner) UnsetLastLocationAt()`

UnsetLastLocationAt ensures that no value is present for LastLocationAt, not even an explicit nil
### GetRunningApp

`func (o *GetDevices200ResponseDataInner) GetRunningApp() GetDevices200ResponseDataInnerRunningApp`

GetRunningApp returns the RunningApp field if non-nil, zero value otherwise.

### GetRunningAppOk

`func (o *GetDevices200ResponseDataInner) GetRunningAppOk() (*GetDevices200ResponseDataInnerRunningApp, bool)`

GetRunningAppOk returns a tuple with the RunningApp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunningApp

`func (o *GetDevices200ResponseDataInner) SetRunningApp(v GetDevices200ResponseDataInnerRunningApp)`

SetRunningApp sets RunningApp field to given value.

### HasRunningApp

`func (o *GetDevices200ResponseDataInner) HasRunningApp() bool`

HasRunningApp returns a boolean if a field has been set.

### SetRunningAppNil

`func (o *GetDevices200ResponseDataInner) SetRunningAppNil(b bool)`

 SetRunningAppNil sets the value for RunningApp to be an explicit nil

### UnsetRunningApp
`func (o *GetDevices200ResponseDataInner) UnsetRunningApp()`

UnsetRunningApp ensures that no value is present for RunningApp, not even an explicit nil
### GetCustomFields

`func (o *GetDevices200ResponseDataInner) GetCustomFields() []GetDevices200ResponseDataInnerCustomFieldsInner`

GetCustomFields returns the CustomFields field if non-nil, zero value otherwise.

### GetCustomFieldsOk

`func (o *GetDevices200ResponseDataInner) GetCustomFieldsOk() (*[]GetDevices200ResponseDataInnerCustomFieldsInner, bool)`

GetCustomFieldsOk returns a tuple with the CustomFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomFields

`func (o *GetDevices200ResponseDataInner) SetCustomFields(v []GetDevices200ResponseDataInnerCustomFieldsInner)`

SetCustomFields sets CustomFields field to given value.


### GetComplianceStatus

`func (o *GetDevices200ResponseDataInner) GetComplianceStatus() string`

GetComplianceStatus returns the ComplianceStatus field if non-nil, zero value otherwise.

### GetComplianceStatusOk

`func (o *GetDevices200ResponseDataInner) GetComplianceStatusOk() (*string, bool)`

GetComplianceStatusOk returns a tuple with the ComplianceStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComplianceStatus

`func (o *GetDevices200ResponseDataInner) SetComplianceStatus(v string)`

SetComplianceStatus sets ComplianceStatus field to given value.


### GetControllers

`func (o *GetDevices200ResponseDataInner) GetControllers() []GetDevices200ResponseDataInnerControllersInner`

GetControllers returns the Controllers field if non-nil, zero value otherwise.

### GetControllersOk

`func (o *GetDevices200ResponseDataInner) GetControllersOk() (*[]GetDevices200ResponseDataInnerControllersInner, bool)`

GetControllersOk returns a tuple with the Controllers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControllers

`func (o *GetDevices200ResponseDataInner) SetControllers(v []GetDevices200ResponseDataInnerControllersInner)`

SetControllers sets Controllers field to given value.


### GetCreatedAt

`func (o *GetDevices200ResponseDataInner) GetCreatedAt() Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetDevices200ResponseDataInner) GetCreatedAtOk() (*Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetDevices200ResponseDataInner) SetCreatedAt(v Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *GetDevices200ResponseDataInner) GetUpdatedAt() Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetDevices200ResponseDataInner) GetUpdatedAtOk() (*Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetDevices200ResponseDataInner) SetUpdatedAt(v Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


