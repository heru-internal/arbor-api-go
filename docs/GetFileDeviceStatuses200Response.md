# GetFileDeviceStatuses200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]GetFileDeviceStatuses200ResponseDataInner**](GetFileDeviceStatuses200ResponseDataInner.md) |  | [optional] 
**Links** | Pointer to [**GetFileDeviceStatuses200ResponseLinks**](GetFileDeviceStatuses200ResponseLinks.md) |  | [optional] 
**Meta** | Pointer to [**GetFileDeviceStatuses200ResponseMeta**](GetFileDeviceStatuses200ResponseMeta.md) |  | [optional] 

## Methods

### NewGetFileDeviceStatuses200Response

`func NewGetFileDeviceStatuses200Response() *GetFileDeviceStatuses200Response`

NewGetFileDeviceStatuses200Response instantiates a new GetFileDeviceStatuses200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetFileDeviceStatuses200ResponseWithDefaults

`func NewGetFileDeviceStatuses200ResponseWithDefaults() *GetFileDeviceStatuses200Response`

NewGetFileDeviceStatuses200ResponseWithDefaults instantiates a new GetFileDeviceStatuses200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetFileDeviceStatuses200Response) GetData() []GetFileDeviceStatuses200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetFileDeviceStatuses200Response) GetDataOk() (*[]GetFileDeviceStatuses200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetFileDeviceStatuses200Response) SetData(v []GetFileDeviceStatuses200ResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *GetFileDeviceStatuses200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetLinks

`func (o *GetFileDeviceStatuses200Response) GetLinks() GetFileDeviceStatuses200ResponseLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *GetFileDeviceStatuses200Response) GetLinksOk() (*GetFileDeviceStatuses200ResponseLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *GetFileDeviceStatuses200Response) SetLinks(v GetFileDeviceStatuses200ResponseLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *GetFileDeviceStatuses200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *GetFileDeviceStatuses200Response) GetMeta() GetFileDeviceStatuses200ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetFileDeviceStatuses200Response) GetMetaOk() (*GetFileDeviceStatuses200ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetFileDeviceStatuses200Response) SetMeta(v GetFileDeviceStatuses200ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetFileDeviceStatuses200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


