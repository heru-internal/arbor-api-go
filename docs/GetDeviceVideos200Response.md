# GetDeviceVideos200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]GetVideos200ResponseDataInner**](GetVideos200ResponseDataInner.md) |  | [optional] 
**Links** | Pointer to [**GetDeviceVideos200ResponseLinks**](GetDeviceVideos200ResponseLinks.md) |  | [optional] 
**Meta** | Pointer to [**GetDeviceVideos200ResponseMeta**](GetDeviceVideos200ResponseMeta.md) |  | [optional] 

## Methods

### NewGetDeviceVideos200Response

`func NewGetDeviceVideos200Response() *GetDeviceVideos200Response`

NewGetDeviceVideos200Response instantiates a new GetDeviceVideos200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetDeviceVideos200ResponseWithDefaults

`func NewGetDeviceVideos200ResponseWithDefaults() *GetDeviceVideos200Response`

NewGetDeviceVideos200ResponseWithDefaults instantiates a new GetDeviceVideos200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetDeviceVideos200Response) GetData() []GetVideos200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetDeviceVideos200Response) GetDataOk() (*[]GetVideos200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetDeviceVideos200Response) SetData(v []GetVideos200ResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *GetDeviceVideos200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetLinks

`func (o *GetDeviceVideos200Response) GetLinks() GetDeviceVideos200ResponseLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *GetDeviceVideos200Response) GetLinksOk() (*GetDeviceVideos200ResponseLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *GetDeviceVideos200Response) SetLinks(v GetDeviceVideos200ResponseLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *GetDeviceVideos200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *GetDeviceVideos200Response) GetMeta() GetDeviceVideos200ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetDeviceVideos200Response) GetMetaOk() (*GetDeviceVideos200ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetDeviceVideos200Response) SetMeta(v GetDeviceVideos200ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetDeviceVideos200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


