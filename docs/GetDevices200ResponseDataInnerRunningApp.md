# GetDevices200ResponseDataInnerRunningApp

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PackageName** | **string** | Android package name reported by the device. | 
**Name** | Pointer to **NullableString** | Human-readable app name resolved from the organization&#39;s managed apps, unmanaged apps, or a tracked-package label. Null when no such mapping exists. | [optional] 

## Methods

### NewGetDevices200ResponseDataInnerRunningApp

`func NewGetDevices200ResponseDataInnerRunningApp(packageName string, ) *GetDevices200ResponseDataInnerRunningApp`

NewGetDevices200ResponseDataInnerRunningApp instantiates a new GetDevices200ResponseDataInnerRunningApp object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetDevices200ResponseDataInnerRunningAppWithDefaults

`func NewGetDevices200ResponseDataInnerRunningAppWithDefaults() *GetDevices200ResponseDataInnerRunningApp`

NewGetDevices200ResponseDataInnerRunningAppWithDefaults instantiates a new GetDevices200ResponseDataInnerRunningApp object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPackageName

`func (o *GetDevices200ResponseDataInnerRunningApp) GetPackageName() string`

GetPackageName returns the PackageName field if non-nil, zero value otherwise.

### GetPackageNameOk

`func (o *GetDevices200ResponseDataInnerRunningApp) GetPackageNameOk() (*string, bool)`

GetPackageNameOk returns a tuple with the PackageName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPackageName

`func (o *GetDevices200ResponseDataInnerRunningApp) SetPackageName(v string)`

SetPackageName sets PackageName field to given value.


### GetName

`func (o *GetDevices200ResponseDataInnerRunningApp) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GetDevices200ResponseDataInnerRunningApp) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GetDevices200ResponseDataInnerRunningApp) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *GetDevices200ResponseDataInnerRunningApp) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *GetDevices200ResponseDataInnerRunningApp) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *GetDevices200ResponseDataInnerRunningApp) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


