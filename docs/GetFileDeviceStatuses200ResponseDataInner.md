# GetFileDeviceStatuses200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | **string** |  | 
**Status** | **string** |  | 
**StatusTimestamp** | **NullableTime** |  | 

## Methods

### NewGetFileDeviceStatuses200ResponseDataInner

`func NewGetFileDeviceStatuses200ResponseDataInner(deviceId string, status string, statusTimestamp NullableTime, ) *GetFileDeviceStatuses200ResponseDataInner`

NewGetFileDeviceStatuses200ResponseDataInner instantiates a new GetFileDeviceStatuses200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetFileDeviceStatuses200ResponseDataInnerWithDefaults

`func NewGetFileDeviceStatuses200ResponseDataInnerWithDefaults() *GetFileDeviceStatuses200ResponseDataInner`

NewGetFileDeviceStatuses200ResponseDataInnerWithDefaults instantiates a new GetFileDeviceStatuses200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *GetFileDeviceStatuses200ResponseDataInner) GetDeviceId() string`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *GetFileDeviceStatuses200ResponseDataInner) GetDeviceIdOk() (*string, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *GetFileDeviceStatuses200ResponseDataInner) SetDeviceId(v string)`

SetDeviceId sets DeviceId field to given value.


### GetStatus

`func (o *GetFileDeviceStatuses200ResponseDataInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GetFileDeviceStatuses200ResponseDataInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GetFileDeviceStatuses200ResponseDataInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStatusTimestamp

`func (o *GetFileDeviceStatuses200ResponseDataInner) GetStatusTimestamp() Time`

GetStatusTimestamp returns the StatusTimestamp field if non-nil, zero value otherwise.

### GetStatusTimestampOk

`func (o *GetFileDeviceStatuses200ResponseDataInner) GetStatusTimestampOk() (*Time, bool)`

GetStatusTimestampOk returns a tuple with the StatusTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusTimestamp

`func (o *GetFileDeviceStatuses200ResponseDataInner) SetStatusTimestamp(v Time)`

SetStatusTimestamp sets StatusTimestamp field to given value.


### SetStatusTimestampNil

`func (o *GetFileDeviceStatuses200ResponseDataInner) SetStatusTimestampNil(b bool)`

 SetStatusTimestampNil sets the value for StatusTimestamp to be an explicit nil

### UnsetStatusTimestamp
`func (o *GetFileDeviceStatuses200ResponseDataInner) UnsetStatusTimestamp()`

UnsetStatusTimestamp ensures that no value is present for StatusTimestamp, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


