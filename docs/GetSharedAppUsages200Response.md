# GetSharedAppUsages200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]GetAppUsage200ResponseDataInner**](GetAppUsage200ResponseDataInner.md) |  | [optional] 
**Links** | Pointer to [**GetSharedAppUsages200ResponseLinks**](GetSharedAppUsages200ResponseLinks.md) |  | [optional] 
**Meta** | Pointer to [**GetSharedAppUsages200ResponseMeta**](GetSharedAppUsages200ResponseMeta.md) |  | [optional] 

## Methods

### NewGetSharedAppUsages200Response

`func NewGetSharedAppUsages200Response() *GetSharedAppUsages200Response`

NewGetSharedAppUsages200Response instantiates a new GetSharedAppUsages200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetSharedAppUsages200ResponseWithDefaults

`func NewGetSharedAppUsages200ResponseWithDefaults() *GetSharedAppUsages200Response`

NewGetSharedAppUsages200ResponseWithDefaults instantiates a new GetSharedAppUsages200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetSharedAppUsages200Response) GetData() []GetAppUsage200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetSharedAppUsages200Response) GetDataOk() (*[]GetAppUsage200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetSharedAppUsages200Response) SetData(v []GetAppUsage200ResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *GetSharedAppUsages200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetLinks

`func (o *GetSharedAppUsages200Response) GetLinks() GetSharedAppUsages200ResponseLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *GetSharedAppUsages200Response) GetLinksOk() (*GetSharedAppUsages200ResponseLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *GetSharedAppUsages200Response) SetLinks(v GetSharedAppUsages200ResponseLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *GetSharedAppUsages200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *GetSharedAppUsages200Response) GetMeta() GetSharedAppUsages200ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetSharedAppUsages200Response) GetMetaOk() (*GetSharedAppUsages200ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetSharedAppUsages200Response) SetMeta(v GetSharedAppUsages200ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetSharedAppUsages200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


