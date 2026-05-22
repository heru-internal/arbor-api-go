# GetStatuses200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceId** | **string** |  | 
**ContentType** | **string** |  | 
**Status** | **string** |  | 
**StatusTimestamp** | **NullableTime** |  | 
**ErrorDescription** | **NullableString** | Human-readable description of the failure when the status is one of the failed-* values. Null otherwise. | 
**Content** | [**GetStatuses200ResponseDataInnerContent**](GetStatuses200ResponseDataInnerContent.md) |  | 

## Methods

### NewGetStatuses200ResponseDataInner

`func NewGetStatuses200ResponseDataInner(deviceId string, contentType string, status string, statusTimestamp NullableTime, errorDescription NullableString, content GetStatuses200ResponseDataInnerContent, ) *GetStatuses200ResponseDataInner`

NewGetStatuses200ResponseDataInner instantiates a new GetStatuses200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetStatuses200ResponseDataInnerWithDefaults

`func NewGetStatuses200ResponseDataInnerWithDefaults() *GetStatuses200ResponseDataInner`

NewGetStatuses200ResponseDataInnerWithDefaults instantiates a new GetStatuses200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeviceId

`func (o *GetStatuses200ResponseDataInner) GetDeviceId() string`

GetDeviceId returns the DeviceId field if non-nil, zero value otherwise.

### GetDeviceIdOk

`func (o *GetStatuses200ResponseDataInner) GetDeviceIdOk() (*string, bool)`

GetDeviceIdOk returns a tuple with the DeviceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceId

`func (o *GetStatuses200ResponseDataInner) SetDeviceId(v string)`

SetDeviceId sets DeviceId field to given value.


### GetContentType

`func (o *GetStatuses200ResponseDataInner) GetContentType() string`

GetContentType returns the ContentType field if non-nil, zero value otherwise.

### GetContentTypeOk

`func (o *GetStatuses200ResponseDataInner) GetContentTypeOk() (*string, bool)`

GetContentTypeOk returns a tuple with the ContentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentType

`func (o *GetStatuses200ResponseDataInner) SetContentType(v string)`

SetContentType sets ContentType field to given value.


### GetStatus

`func (o *GetStatuses200ResponseDataInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GetStatuses200ResponseDataInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GetStatuses200ResponseDataInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStatusTimestamp

`func (o *GetStatuses200ResponseDataInner) GetStatusTimestamp() Time`

GetStatusTimestamp returns the StatusTimestamp field if non-nil, zero value otherwise.

### GetStatusTimestampOk

`func (o *GetStatuses200ResponseDataInner) GetStatusTimestampOk() (*Time, bool)`

GetStatusTimestampOk returns a tuple with the StatusTimestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusTimestamp

`func (o *GetStatuses200ResponseDataInner) SetStatusTimestamp(v Time)`

SetStatusTimestamp sets StatusTimestamp field to given value.


### SetStatusTimestampNil

`func (o *GetStatuses200ResponseDataInner) SetStatusTimestampNil(b bool)`

 SetStatusTimestampNil sets the value for StatusTimestamp to be an explicit nil

### UnsetStatusTimestamp
`func (o *GetStatuses200ResponseDataInner) UnsetStatusTimestamp()`

UnsetStatusTimestamp ensures that no value is present for StatusTimestamp, not even an explicit nil
### GetErrorDescription

`func (o *GetStatuses200ResponseDataInner) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *GetStatuses200ResponseDataInner) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *GetStatuses200ResponseDataInner) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.


### SetErrorDescriptionNil

`func (o *GetStatuses200ResponseDataInner) SetErrorDescriptionNil(b bool)`

 SetErrorDescriptionNil sets the value for ErrorDescription to be an explicit nil

### UnsetErrorDescription
`func (o *GetStatuses200ResponseDataInner) UnsetErrorDescription()`

UnsetErrorDescription ensures that no value is present for ErrorDescription, not even an explicit nil
### GetContent

`func (o *GetStatuses200ResponseDataInner) GetContent() GetStatuses200ResponseDataInnerContent`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *GetStatuses200ResponseDataInner) GetContentOk() (*GetStatuses200ResponseDataInnerContent, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *GetStatuses200ResponseDataInner) SetContent(v GetStatuses200ResponseDataInnerContent)`

SetContent sets Content field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


