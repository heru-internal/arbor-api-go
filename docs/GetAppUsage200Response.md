# GetAppUsage200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]GetAppUsage200ResponseDataInner**](GetAppUsage200ResponseDataInner.md) |  | [optional] 
**Links** | Pointer to [**GetUsers200ResponseLinks**](GetUsers200ResponseLinks.md) |  | [optional] 
**Meta** | Pointer to [**GetUsers200ResponseMeta**](GetUsers200ResponseMeta.md) |  | [optional] 

## Methods

### NewGetAppUsage200Response

`func NewGetAppUsage200Response() *GetAppUsage200Response`

NewGetAppUsage200Response instantiates a new GetAppUsage200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetAppUsage200ResponseWithDefaults

`func NewGetAppUsage200ResponseWithDefaults() *GetAppUsage200Response`

NewGetAppUsage200ResponseWithDefaults instantiates a new GetAppUsage200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetAppUsage200Response) GetData() []GetAppUsage200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetAppUsage200Response) GetDataOk() (*[]GetAppUsage200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetAppUsage200Response) SetData(v []GetAppUsage200ResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *GetAppUsage200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetLinks

`func (o *GetAppUsage200Response) GetLinks() GetUsers200ResponseLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *GetAppUsage200Response) GetLinksOk() (*GetUsers200ResponseLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *GetAppUsage200Response) SetLinks(v GetUsers200ResponseLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *GetAppUsage200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *GetAppUsage200Response) GetMeta() GetUsers200ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetAppUsage200Response) GetMetaOk() (*GetUsers200ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetAppUsage200Response) SetMeta(v GetUsers200ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetAppUsage200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


