# GetAppSessions200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The unique identifier of the app session. | [optional] 
**TotalDuration** | Pointer to **int32** | The total duration of the app session in seconds. | [optional] 
**IdleDuration** | Pointer to **int32** | The idle duration of the app session in seconds. | [optional] 
**ActiveDuration** | Pointer to **int32** | The active duration of the app session in seconds. | [optional] 
**StartedAt** | Pointer to **NullableTime** |  | [optional] 
**EndedAt** | Pointer to **NullableTime** |  | [optional] 
**Device** | Pointer to [**GetAppSessions200ResponseDataInnerDevice**](GetAppSessions200ResponseDataInnerDevice.md) |  | [optional] 
**App** | Pointer to [**GetAppSessions200ResponseDataInnerApp**](GetAppSessions200ResponseDataInnerApp.md) |  | [optional] 

## Methods

### NewGetAppSessions200ResponseDataInner

`func NewGetAppSessions200ResponseDataInner() *GetAppSessions200ResponseDataInner`

NewGetAppSessions200ResponseDataInner instantiates a new GetAppSessions200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetAppSessions200ResponseDataInnerWithDefaults

`func NewGetAppSessions200ResponseDataInnerWithDefaults() *GetAppSessions200ResponseDataInner`

NewGetAppSessions200ResponseDataInnerWithDefaults instantiates a new GetAppSessions200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetAppSessions200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetAppSessions200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetAppSessions200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *GetAppSessions200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTotalDuration

`func (o *GetAppSessions200ResponseDataInner) GetTotalDuration() int32`

GetTotalDuration returns the TotalDuration field if non-nil, zero value otherwise.

### GetTotalDurationOk

`func (o *GetAppSessions200ResponseDataInner) GetTotalDurationOk() (*int32, bool)`

GetTotalDurationOk returns a tuple with the TotalDuration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalDuration

`func (o *GetAppSessions200ResponseDataInner) SetTotalDuration(v int32)`

SetTotalDuration sets TotalDuration field to given value.

### HasTotalDuration

`func (o *GetAppSessions200ResponseDataInner) HasTotalDuration() bool`

HasTotalDuration returns a boolean if a field has been set.

### GetIdleDuration

`func (o *GetAppSessions200ResponseDataInner) GetIdleDuration() int32`

GetIdleDuration returns the IdleDuration field if non-nil, zero value otherwise.

### GetIdleDurationOk

`func (o *GetAppSessions200ResponseDataInner) GetIdleDurationOk() (*int32, bool)`

GetIdleDurationOk returns a tuple with the IdleDuration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdleDuration

`func (o *GetAppSessions200ResponseDataInner) SetIdleDuration(v int32)`

SetIdleDuration sets IdleDuration field to given value.

### HasIdleDuration

`func (o *GetAppSessions200ResponseDataInner) HasIdleDuration() bool`

HasIdleDuration returns a boolean if a field has been set.

### GetActiveDuration

`func (o *GetAppSessions200ResponseDataInner) GetActiveDuration() int32`

GetActiveDuration returns the ActiveDuration field if non-nil, zero value otherwise.

### GetActiveDurationOk

`func (o *GetAppSessions200ResponseDataInner) GetActiveDurationOk() (*int32, bool)`

GetActiveDurationOk returns a tuple with the ActiveDuration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActiveDuration

`func (o *GetAppSessions200ResponseDataInner) SetActiveDuration(v int32)`

SetActiveDuration sets ActiveDuration field to given value.

### HasActiveDuration

`func (o *GetAppSessions200ResponseDataInner) HasActiveDuration() bool`

HasActiveDuration returns a boolean if a field has been set.

### GetStartedAt

`func (o *GetAppSessions200ResponseDataInner) GetStartedAt() Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *GetAppSessions200ResponseDataInner) GetStartedAtOk() (*Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *GetAppSessions200ResponseDataInner) SetStartedAt(v Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *GetAppSessions200ResponseDataInner) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### SetStartedAtNil

`func (o *GetAppSessions200ResponseDataInner) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *GetAppSessions200ResponseDataInner) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetEndedAt

`func (o *GetAppSessions200ResponseDataInner) GetEndedAt() Time`

GetEndedAt returns the EndedAt field if non-nil, zero value otherwise.

### GetEndedAtOk

`func (o *GetAppSessions200ResponseDataInner) GetEndedAtOk() (*Time, bool)`

GetEndedAtOk returns a tuple with the EndedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndedAt

`func (o *GetAppSessions200ResponseDataInner) SetEndedAt(v Time)`

SetEndedAt sets EndedAt field to given value.

### HasEndedAt

`func (o *GetAppSessions200ResponseDataInner) HasEndedAt() bool`

HasEndedAt returns a boolean if a field has been set.

### SetEndedAtNil

`func (o *GetAppSessions200ResponseDataInner) SetEndedAtNil(b bool)`

 SetEndedAtNil sets the value for EndedAt to be an explicit nil

### UnsetEndedAt
`func (o *GetAppSessions200ResponseDataInner) UnsetEndedAt()`

UnsetEndedAt ensures that no value is present for EndedAt, not even an explicit nil
### GetDevice

`func (o *GetAppSessions200ResponseDataInner) GetDevice() GetAppSessions200ResponseDataInnerDevice`

GetDevice returns the Device field if non-nil, zero value otherwise.

### GetDeviceOk

`func (o *GetAppSessions200ResponseDataInner) GetDeviceOk() (*GetAppSessions200ResponseDataInnerDevice, bool)`

GetDeviceOk returns a tuple with the Device field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDevice

`func (o *GetAppSessions200ResponseDataInner) SetDevice(v GetAppSessions200ResponseDataInnerDevice)`

SetDevice sets Device field to given value.

### HasDevice

`func (o *GetAppSessions200ResponseDataInner) HasDevice() bool`

HasDevice returns a boolean if a field has been set.

### GetApp

`func (o *GetAppSessions200ResponseDataInner) GetApp() GetAppSessions200ResponseDataInnerApp`

GetApp returns the App field if non-nil, zero value otherwise.

### GetAppOk

`func (o *GetAppSessions200ResponseDataInner) GetAppOk() (*GetAppSessions200ResponseDataInnerApp, bool)`

GetAppOk returns a tuple with the App field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApp

`func (o *GetAppSessions200ResponseDataInner) SetApp(v GetAppSessions200ResponseDataInnerApp)`

SetApp sets App field to given value.

### HasApp

`func (o *GetAppSessions200ResponseDataInner) HasApp() bool`

HasApp returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


