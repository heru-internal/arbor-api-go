# GetAppFiles200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]GetAppFiles200ResponseDataInner**](GetAppFiles200ResponseDataInner.md) |  | 
**Links** | [**GetAppBundles200ResponseLinks**](GetAppBundles200ResponseLinks.md) |  | 
**Meta** | [**GetAppBundles200ResponseMeta**](GetAppBundles200ResponseMeta.md) |  | 

## Methods

### NewGetAppFiles200Response

`func NewGetAppFiles200Response(data []GetAppFiles200ResponseDataInner, links GetAppBundles200ResponseLinks, meta GetAppBundles200ResponseMeta, ) *GetAppFiles200Response`

NewGetAppFiles200Response instantiates a new GetAppFiles200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetAppFiles200ResponseWithDefaults

`func NewGetAppFiles200ResponseWithDefaults() *GetAppFiles200Response`

NewGetAppFiles200ResponseWithDefaults instantiates a new GetAppFiles200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetAppFiles200Response) GetData() []GetAppFiles200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetAppFiles200Response) GetDataOk() (*[]GetAppFiles200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetAppFiles200Response) SetData(v []GetAppFiles200ResponseDataInner)`

SetData sets Data field to given value.


### GetLinks

`func (o *GetAppFiles200Response) GetLinks() GetAppBundles200ResponseLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *GetAppFiles200Response) GetLinksOk() (*GetAppBundles200ResponseLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *GetAppFiles200Response) SetLinks(v GetAppBundles200ResponseLinks)`

SetLinks sets Links field to given value.


### GetMeta

`func (o *GetAppFiles200Response) GetMeta() GetAppBundles200ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetAppFiles200Response) GetMetaOk() (*GetAppBundles200ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetAppFiles200Response) SetMeta(v GetAppBundles200ResponseMeta)`

SetMeta sets Meta field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


