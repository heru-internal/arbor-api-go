# GetGroups200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]GetDevices200ResponseDataInnerGroup**](GetDevices200ResponseDataInnerGroup.md) |  | [optional] 
**Links** | Pointer to [**GetUsers200ResponseLinks**](GetUsers200ResponseLinks.md) |  | [optional] 
**Meta** | Pointer to [**GetUsers200ResponseMeta**](GetUsers200ResponseMeta.md) |  | [optional] 

## Methods

### NewGetGroups200Response

`func NewGetGroups200Response() *GetGroups200Response`

NewGetGroups200Response instantiates a new GetGroups200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetGroups200ResponseWithDefaults

`func NewGetGroups200ResponseWithDefaults() *GetGroups200Response`

NewGetGroups200ResponseWithDefaults instantiates a new GetGroups200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetGroups200Response) GetData() []GetDevices200ResponseDataInnerGroup`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetGroups200Response) GetDataOk() (*[]GetDevices200ResponseDataInnerGroup, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetGroups200Response) SetData(v []GetDevices200ResponseDataInnerGroup)`

SetData sets Data field to given value.

### HasData

`func (o *GetGroups200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetLinks

`func (o *GetGroups200Response) GetLinks() GetUsers200ResponseLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *GetGroups200Response) GetLinksOk() (*GetUsers200ResponseLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *GetGroups200Response) SetLinks(v GetUsers200ResponseLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *GetGroups200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *GetGroups200Response) GetMeta() GetUsers200ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetGroups200Response) GetMetaOk() (*GetUsers200ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetGroups200Response) SetMeta(v GetUsers200ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetGroups200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


