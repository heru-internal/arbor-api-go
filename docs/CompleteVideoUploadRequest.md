# CompleteVideoUploadRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | **string** |  | 
**UploadId** | **string** |  | 
**Parts** | [**[]CompleteAppVersionUploadRequestPartsInner**](CompleteAppVersionUploadRequestPartsInner.md) |  | 

## Methods

### NewCompleteVideoUploadRequest

`func NewCompleteVideoUploadRequest(key string, uploadId string, parts []CompleteAppVersionUploadRequestPartsInner, ) *CompleteVideoUploadRequest`

NewCompleteVideoUploadRequest instantiates a new CompleteVideoUploadRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompleteVideoUploadRequestWithDefaults

`func NewCompleteVideoUploadRequestWithDefaults() *CompleteVideoUploadRequest`

NewCompleteVideoUploadRequestWithDefaults instantiates a new CompleteVideoUploadRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *CompleteVideoUploadRequest) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *CompleteVideoUploadRequest) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *CompleteVideoUploadRequest) SetKey(v string)`

SetKey sets Key field to given value.


### GetUploadId

`func (o *CompleteVideoUploadRequest) GetUploadId() string`

GetUploadId returns the UploadId field if non-nil, zero value otherwise.

### GetUploadIdOk

`func (o *CompleteVideoUploadRequest) GetUploadIdOk() (*string, bool)`

GetUploadIdOk returns a tuple with the UploadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUploadId

`func (o *CompleteVideoUploadRequest) SetUploadId(v string)`

SetUploadId sets UploadId field to given value.


### GetParts

`func (o *CompleteVideoUploadRequest) GetParts() []CompleteAppVersionUploadRequestPartsInner`

GetParts returns the Parts field if non-nil, zero value otherwise.

### GetPartsOk

`func (o *CompleteVideoUploadRequest) GetPartsOk() (*[]CompleteAppVersionUploadRequestPartsInner, bool)`

GetPartsOk returns a tuple with the Parts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParts

`func (o *CompleteVideoUploadRequest) SetParts(v []CompleteAppVersionUploadRequestPartsInner)`

SetParts sets Parts field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


