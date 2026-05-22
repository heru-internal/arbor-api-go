# CompleteCustom3DEnvironmentUploadRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | **string** | The key returned from the initiate upload request | 
**UploadId** | **string** | The upload ID returned from the initiate upload request | 
**Parts** | [**[]CompleteCustom3DEnvironmentUploadRequestPartsInner**](CompleteCustom3DEnvironmentUploadRequestPartsInner.md) | Array of completed parts with their ETags | 

## Methods

### NewCompleteCustom3DEnvironmentUploadRequest

`func NewCompleteCustom3DEnvironmentUploadRequest(key string, uploadId string, parts []CompleteCustom3DEnvironmentUploadRequestPartsInner, ) *CompleteCustom3DEnvironmentUploadRequest`

NewCompleteCustom3DEnvironmentUploadRequest instantiates a new CompleteCustom3DEnvironmentUploadRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompleteCustom3DEnvironmentUploadRequestWithDefaults

`func NewCompleteCustom3DEnvironmentUploadRequestWithDefaults() *CompleteCustom3DEnvironmentUploadRequest`

NewCompleteCustom3DEnvironmentUploadRequestWithDefaults instantiates a new CompleteCustom3DEnvironmentUploadRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *CompleteCustom3DEnvironmentUploadRequest) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *CompleteCustom3DEnvironmentUploadRequest) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *CompleteCustom3DEnvironmentUploadRequest) SetKey(v string)`

SetKey sets Key field to given value.


### GetUploadId

`func (o *CompleteCustom3DEnvironmentUploadRequest) GetUploadId() string`

GetUploadId returns the UploadId field if non-nil, zero value otherwise.

### GetUploadIdOk

`func (o *CompleteCustom3DEnvironmentUploadRequest) GetUploadIdOk() (*string, bool)`

GetUploadIdOk returns a tuple with the UploadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUploadId

`func (o *CompleteCustom3DEnvironmentUploadRequest) SetUploadId(v string)`

SetUploadId sets UploadId field to given value.


### GetParts

`func (o *CompleteCustom3DEnvironmentUploadRequest) GetParts() []CompleteCustom3DEnvironmentUploadRequestPartsInner`

GetParts returns the Parts field if non-nil, zero value otherwise.

### GetPartsOk

`func (o *CompleteCustom3DEnvironmentUploadRequest) GetPartsOk() (*[]CompleteCustom3DEnvironmentUploadRequestPartsInner, bool)`

GetPartsOk returns a tuple with the Parts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParts

`func (o *CompleteCustom3DEnvironmentUploadRequest) SetParts(v []CompleteCustom3DEnvironmentUploadRequestPartsInner)`

SetParts sets Parts field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


