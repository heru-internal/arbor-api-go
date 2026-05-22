# GetVideoDeviceStatuses200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]GetFileDeviceStatuses200ResponseDataInner**](GetFileDeviceStatuses200ResponseDataInner.md) |  | [optional] 
**Links** | Pointer to [**GetVideoDeviceStatuses200ResponseLinks**](GetVideoDeviceStatuses200ResponseLinks.md) |  | [optional] 
**Meta** | Pointer to [**GetVideoDeviceStatuses200ResponseMeta**](GetVideoDeviceStatuses200ResponseMeta.md) |  | [optional] 

## Methods

### NewGetVideoDeviceStatuses200Response

`func NewGetVideoDeviceStatuses200Response() *GetVideoDeviceStatuses200Response`

NewGetVideoDeviceStatuses200Response instantiates a new GetVideoDeviceStatuses200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetVideoDeviceStatuses200ResponseWithDefaults

`func NewGetVideoDeviceStatuses200ResponseWithDefaults() *GetVideoDeviceStatuses200Response`

NewGetVideoDeviceStatuses200ResponseWithDefaults instantiates a new GetVideoDeviceStatuses200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetVideoDeviceStatuses200Response) GetData() []GetFileDeviceStatuses200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetVideoDeviceStatuses200Response) GetDataOk() (*[]GetFileDeviceStatuses200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetVideoDeviceStatuses200Response) SetData(v []GetFileDeviceStatuses200ResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *GetVideoDeviceStatuses200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetLinks

`func (o *GetVideoDeviceStatuses200Response) GetLinks() GetVideoDeviceStatuses200ResponseLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *GetVideoDeviceStatuses200Response) GetLinksOk() (*GetVideoDeviceStatuses200ResponseLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *GetVideoDeviceStatuses200Response) SetLinks(v GetVideoDeviceStatuses200ResponseLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *GetVideoDeviceStatuses200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *GetVideoDeviceStatuses200Response) GetMeta() GetVideoDeviceStatuses200ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetVideoDeviceStatuses200Response) GetMetaOk() (*GetVideoDeviceStatuses200ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetVideoDeviceStatuses200Response) SetMeta(v GetVideoDeviceStatuses200ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetVideoDeviceStatuses200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


