# GetAppUsage200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**App** | Pointer to [**GetAppUsage200ResponseDataInnerApp**](GetAppUsage200ResponseDataInnerApp.md) |  | [optional] 
**TotalSessions** | Pointer to **int32** | The total number of sessions for the app within the specified date range. | [optional] 
**TotalSessionDuration** | Pointer to **int32** | The total duration of all sessions for the app within the specified date range, in seconds. | [optional] 
**TotalIdleDuration** | Pointer to **int32** | The total duration of idle time for the app within the specified date range, in seconds. | [optional] 
**TotalActiveDuration** | Pointer to **int32** | The total duration of active time for the app within the specified date range, in seconds. | [optional] 
**AverageActiveDuration** | Pointer to **int32** | The average duration of active time per session for the app within the specified date range, in seconds. | [optional] 
**MaxActiveDuration** | Pointer to **int32** | The maximum duration of active time for a single session of the app within the specified date range, in seconds. | [optional] 

## Methods

### NewGetAppUsage200ResponseDataInner

`func NewGetAppUsage200ResponseDataInner() *GetAppUsage200ResponseDataInner`

NewGetAppUsage200ResponseDataInner instantiates a new GetAppUsage200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetAppUsage200ResponseDataInnerWithDefaults

`func NewGetAppUsage200ResponseDataInnerWithDefaults() *GetAppUsage200ResponseDataInner`

NewGetAppUsage200ResponseDataInnerWithDefaults instantiates a new GetAppUsage200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApp

`func (o *GetAppUsage200ResponseDataInner) GetApp() GetAppUsage200ResponseDataInnerApp`

GetApp returns the App field if non-nil, zero value otherwise.

### GetAppOk

`func (o *GetAppUsage200ResponseDataInner) GetAppOk() (*GetAppUsage200ResponseDataInnerApp, bool)`

GetAppOk returns a tuple with the App field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApp

`func (o *GetAppUsage200ResponseDataInner) SetApp(v GetAppUsage200ResponseDataInnerApp)`

SetApp sets App field to given value.

### HasApp

`func (o *GetAppUsage200ResponseDataInner) HasApp() bool`

HasApp returns a boolean if a field has been set.

### GetTotalSessions

`func (o *GetAppUsage200ResponseDataInner) GetTotalSessions() int32`

GetTotalSessions returns the TotalSessions field if non-nil, zero value otherwise.

### GetTotalSessionsOk

`func (o *GetAppUsage200ResponseDataInner) GetTotalSessionsOk() (*int32, bool)`

GetTotalSessionsOk returns a tuple with the TotalSessions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalSessions

`func (o *GetAppUsage200ResponseDataInner) SetTotalSessions(v int32)`

SetTotalSessions sets TotalSessions field to given value.

### HasTotalSessions

`func (o *GetAppUsage200ResponseDataInner) HasTotalSessions() bool`

HasTotalSessions returns a boolean if a field has been set.

### GetTotalSessionDuration

`func (o *GetAppUsage200ResponseDataInner) GetTotalSessionDuration() int32`

GetTotalSessionDuration returns the TotalSessionDuration field if non-nil, zero value otherwise.

### GetTotalSessionDurationOk

`func (o *GetAppUsage200ResponseDataInner) GetTotalSessionDurationOk() (*int32, bool)`

GetTotalSessionDurationOk returns a tuple with the TotalSessionDuration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalSessionDuration

`func (o *GetAppUsage200ResponseDataInner) SetTotalSessionDuration(v int32)`

SetTotalSessionDuration sets TotalSessionDuration field to given value.

### HasTotalSessionDuration

`func (o *GetAppUsage200ResponseDataInner) HasTotalSessionDuration() bool`

HasTotalSessionDuration returns a boolean if a field has been set.

### GetTotalIdleDuration

`func (o *GetAppUsage200ResponseDataInner) GetTotalIdleDuration() int32`

GetTotalIdleDuration returns the TotalIdleDuration field if non-nil, zero value otherwise.

### GetTotalIdleDurationOk

`func (o *GetAppUsage200ResponseDataInner) GetTotalIdleDurationOk() (*int32, bool)`

GetTotalIdleDurationOk returns a tuple with the TotalIdleDuration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalIdleDuration

`func (o *GetAppUsage200ResponseDataInner) SetTotalIdleDuration(v int32)`

SetTotalIdleDuration sets TotalIdleDuration field to given value.

### HasTotalIdleDuration

`func (o *GetAppUsage200ResponseDataInner) HasTotalIdleDuration() bool`

HasTotalIdleDuration returns a boolean if a field has been set.

### GetTotalActiveDuration

`func (o *GetAppUsage200ResponseDataInner) GetTotalActiveDuration() int32`

GetTotalActiveDuration returns the TotalActiveDuration field if non-nil, zero value otherwise.

### GetTotalActiveDurationOk

`func (o *GetAppUsage200ResponseDataInner) GetTotalActiveDurationOk() (*int32, bool)`

GetTotalActiveDurationOk returns a tuple with the TotalActiveDuration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalActiveDuration

`func (o *GetAppUsage200ResponseDataInner) SetTotalActiveDuration(v int32)`

SetTotalActiveDuration sets TotalActiveDuration field to given value.

### HasTotalActiveDuration

`func (o *GetAppUsage200ResponseDataInner) HasTotalActiveDuration() bool`

HasTotalActiveDuration returns a boolean if a field has been set.

### GetAverageActiveDuration

`func (o *GetAppUsage200ResponseDataInner) GetAverageActiveDuration() int32`

GetAverageActiveDuration returns the AverageActiveDuration field if non-nil, zero value otherwise.

### GetAverageActiveDurationOk

`func (o *GetAppUsage200ResponseDataInner) GetAverageActiveDurationOk() (*int32, bool)`

GetAverageActiveDurationOk returns a tuple with the AverageActiveDuration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAverageActiveDuration

`func (o *GetAppUsage200ResponseDataInner) SetAverageActiveDuration(v int32)`

SetAverageActiveDuration sets AverageActiveDuration field to given value.

### HasAverageActiveDuration

`func (o *GetAppUsage200ResponseDataInner) HasAverageActiveDuration() bool`

HasAverageActiveDuration returns a boolean if a field has been set.

### GetMaxActiveDuration

`func (o *GetAppUsage200ResponseDataInner) GetMaxActiveDuration() int32`

GetMaxActiveDuration returns the MaxActiveDuration field if non-nil, zero value otherwise.

### GetMaxActiveDurationOk

`func (o *GetAppUsage200ResponseDataInner) GetMaxActiveDurationOk() (*int32, bool)`

GetMaxActiveDurationOk returns a tuple with the MaxActiveDuration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxActiveDuration

`func (o *GetAppUsage200ResponseDataInner) SetMaxActiveDuration(v int32)`

SetMaxActiveDuration sets MaxActiveDuration field to given value.

### HasMaxActiveDuration

`func (o *GetAppUsage200ResponseDataInner) HasMaxActiveDuration() bool`

HasMaxActiveDuration returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


