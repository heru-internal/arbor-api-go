# GetAppBundles200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]CreateAppBundle201Response**](CreateAppBundle201Response.md) |  | 
**Links** | [**GetUsers200ResponseLinks**](GetUsers200ResponseLinks.md) |  | 
**Meta** | [**GetAppBundles200ResponseMeta**](GetAppBundles200ResponseMeta.md) |  | 

## Methods

### NewGetAppBundles200Response

`func NewGetAppBundles200Response(data []CreateAppBundle201Response, links GetUsers200ResponseLinks, meta GetAppBundles200ResponseMeta, ) *GetAppBundles200Response`

NewGetAppBundles200Response instantiates a new GetAppBundles200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetAppBundles200ResponseWithDefaults

`func NewGetAppBundles200ResponseWithDefaults() *GetAppBundles200Response`

NewGetAppBundles200ResponseWithDefaults instantiates a new GetAppBundles200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetAppBundles200Response) GetData() []CreateAppBundle201Response`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetAppBundles200Response) GetDataOk() (*[]CreateAppBundle201Response, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetAppBundles200Response) SetData(v []CreateAppBundle201Response)`

SetData sets Data field to given value.


### GetLinks

`func (o *GetAppBundles200Response) GetLinks() GetUsers200ResponseLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *GetAppBundles200Response) GetLinksOk() (*GetUsers200ResponseLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *GetAppBundles200Response) SetLinks(v GetUsers200ResponseLinks)`

SetLinks sets Links field to given value.


### GetMeta

`func (o *GetAppBundles200Response) GetMeta() GetAppBundles200ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetAppBundles200Response) GetMetaOk() (*GetAppBundles200ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetAppBundles200Response) SetMeta(v GetAppBundles200ResponseMeta)`

SetMeta sets Meta field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


