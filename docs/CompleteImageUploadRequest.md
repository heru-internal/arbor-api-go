# CompleteImageUploadRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | **string** |  | 
**UploadId** | **string** |  | 
**Parts** | [**[]CompleteImageUploadRequestPartsInner**](CompleteImageUploadRequestPartsInner.md) |  | 

## Methods

### NewCompleteImageUploadRequest

`func NewCompleteImageUploadRequest(key string, uploadId string, parts []CompleteImageUploadRequestPartsInner, ) *CompleteImageUploadRequest`

NewCompleteImageUploadRequest instantiates a new CompleteImageUploadRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompleteImageUploadRequestWithDefaults

`func NewCompleteImageUploadRequestWithDefaults() *CompleteImageUploadRequest`

NewCompleteImageUploadRequestWithDefaults instantiates a new CompleteImageUploadRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *CompleteImageUploadRequest) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *CompleteImageUploadRequest) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *CompleteImageUploadRequest) SetKey(v string)`

SetKey sets Key field to given value.


### GetUploadId

`func (o *CompleteImageUploadRequest) GetUploadId() string`

GetUploadId returns the UploadId field if non-nil, zero value otherwise.

### GetUploadIdOk

`func (o *CompleteImageUploadRequest) GetUploadIdOk() (*string, bool)`

GetUploadIdOk returns a tuple with the UploadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUploadId

`func (o *CompleteImageUploadRequest) SetUploadId(v string)`

SetUploadId sets UploadId field to given value.


### GetParts

`func (o *CompleteImageUploadRequest) GetParts() []CompleteImageUploadRequestPartsInner`

GetParts returns the Parts field if non-nil, zero value otherwise.

### GetPartsOk

`func (o *CompleteImageUploadRequest) GetPartsOk() (*[]CompleteImageUploadRequestPartsInner, bool)`

GetPartsOk returns a tuple with the Parts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParts

`func (o *CompleteImageUploadRequest) SetParts(v []CompleteImageUploadRequestPartsInner)`

SetParts sets Parts field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


