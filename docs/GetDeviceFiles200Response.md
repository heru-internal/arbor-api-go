# GetDeviceFiles200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]GetAppFiles200ResponseDataInner**](GetAppFiles200ResponseDataInner.md) |  | [optional] 
**Links** | Pointer to [**GetDeviceFiles200ResponseLinks**](GetDeviceFiles200ResponseLinks.md) |  | [optional] 
**Meta** | Pointer to [**GetDeviceFiles200ResponseMeta**](GetDeviceFiles200ResponseMeta.md) |  | [optional] 

## Methods

### NewGetDeviceFiles200Response

`func NewGetDeviceFiles200Response() *GetDeviceFiles200Response`

NewGetDeviceFiles200Response instantiates a new GetDeviceFiles200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetDeviceFiles200ResponseWithDefaults

`func NewGetDeviceFiles200ResponseWithDefaults() *GetDeviceFiles200Response`

NewGetDeviceFiles200ResponseWithDefaults instantiates a new GetDeviceFiles200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetDeviceFiles200Response) GetData() []GetAppFiles200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetDeviceFiles200Response) GetDataOk() (*[]GetAppFiles200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetDeviceFiles200Response) SetData(v []GetAppFiles200ResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *GetDeviceFiles200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetLinks

`func (o *GetDeviceFiles200Response) GetLinks() GetDeviceFiles200ResponseLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *GetDeviceFiles200Response) GetLinksOk() (*GetDeviceFiles200ResponseLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *GetDeviceFiles200Response) SetLinks(v GetDeviceFiles200ResponseLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *GetDeviceFiles200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *GetDeviceFiles200Response) GetMeta() GetDeviceFiles200ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetDeviceFiles200Response) GetMetaOk() (*GetDeviceFiles200ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetDeviceFiles200Response) SetMeta(v GetDeviceFiles200ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetDeviceFiles200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


