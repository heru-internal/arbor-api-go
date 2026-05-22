# PreSignCustom3DEnvironmentUploadRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | **string** | The key returned from the initiate upload request | 
**UploadId** | **string** | The upload ID returned from the initiate upload request | 
**PartNumbers** | **[]int32** | Array of part numbers to pre-sign | 

## Methods

### NewPreSignCustom3DEnvironmentUploadRequest

`func NewPreSignCustom3DEnvironmentUploadRequest(key string, uploadId string, partNumbers []int32, ) *PreSignCustom3DEnvironmentUploadRequest`

NewPreSignCustom3DEnvironmentUploadRequest instantiates a new PreSignCustom3DEnvironmentUploadRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPreSignCustom3DEnvironmentUploadRequestWithDefaults

`func NewPreSignCustom3DEnvironmentUploadRequestWithDefaults() *PreSignCustom3DEnvironmentUploadRequest`

NewPreSignCustom3DEnvironmentUploadRequestWithDefaults instantiates a new PreSignCustom3DEnvironmentUploadRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *PreSignCustom3DEnvironmentUploadRequest) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *PreSignCustom3DEnvironmentUploadRequest) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *PreSignCustom3DEnvironmentUploadRequest) SetKey(v string)`

SetKey sets Key field to given value.


### GetUploadId

`func (o *PreSignCustom3DEnvironmentUploadRequest) GetUploadId() string`

GetUploadId returns the UploadId field if non-nil, zero value otherwise.

### GetUploadIdOk

`func (o *PreSignCustom3DEnvironmentUploadRequest) GetUploadIdOk() (*string, bool)`

GetUploadIdOk returns a tuple with the UploadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUploadId

`func (o *PreSignCustom3DEnvironmentUploadRequest) SetUploadId(v string)`

SetUploadId sets UploadId field to given value.


### GetPartNumbers

`func (o *PreSignCustom3DEnvironmentUploadRequest) GetPartNumbers() []int32`

GetPartNumbers returns the PartNumbers field if non-nil, zero value otherwise.

### GetPartNumbersOk

`func (o *PreSignCustom3DEnvironmentUploadRequest) GetPartNumbersOk() (*[]int32, bool)`

GetPartNumbersOk returns a tuple with the PartNumbers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartNumbers

`func (o *PreSignCustom3DEnvironmentUploadRequest) SetPartNumbers(v []int32)`

SetPartNumbers sets PartNumbers field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


