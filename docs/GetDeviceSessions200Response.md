# GetDeviceSessions200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]GetAppSessions200ResponseDataInner**](GetAppSessions200ResponseDataInner.md) |  | [optional] 
**Links** | Pointer to [**GetDeviceSessions200ResponseLinks**](GetDeviceSessions200ResponseLinks.md) |  | [optional] 
**Meta** | Pointer to [**GetDeviceSessions200ResponseMeta**](GetDeviceSessions200ResponseMeta.md) |  | [optional] 

## Methods

### NewGetDeviceSessions200Response

`func NewGetDeviceSessions200Response() *GetDeviceSessions200Response`

NewGetDeviceSessions200Response instantiates a new GetDeviceSessions200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetDeviceSessions200ResponseWithDefaults

`func NewGetDeviceSessions200ResponseWithDefaults() *GetDeviceSessions200Response`

NewGetDeviceSessions200ResponseWithDefaults instantiates a new GetDeviceSessions200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetDeviceSessions200Response) GetData() []GetAppSessions200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetDeviceSessions200Response) GetDataOk() (*[]GetAppSessions200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetDeviceSessions200Response) SetData(v []GetAppSessions200ResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *GetDeviceSessions200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetLinks

`func (o *GetDeviceSessions200Response) GetLinks() GetDeviceSessions200ResponseLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *GetDeviceSessions200Response) GetLinksOk() (*GetDeviceSessions200ResponseLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *GetDeviceSessions200Response) SetLinks(v GetDeviceSessions200ResponseLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *GetDeviceSessions200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *GetDeviceSessions200Response) GetMeta() GetDeviceSessions200ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetDeviceSessions200Response) GetMetaOk() (*GetDeviceSessions200ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetDeviceSessions200Response) SetMeta(v GetDeviceSessions200ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetDeviceSessions200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


