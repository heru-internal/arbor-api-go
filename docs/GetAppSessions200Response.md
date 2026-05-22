# GetAppSessions200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]GetAppSessions200ResponseDataInner**](GetAppSessions200ResponseDataInner.md) |  | [optional] 
**Links** | Pointer to [**GetAppSessions200ResponseLinks**](GetAppSessions200ResponseLinks.md) |  | [optional] 
**Meta** | Pointer to [**GetAppSessions200ResponseMeta**](GetAppSessions200ResponseMeta.md) |  | [optional] 

## Methods

### NewGetAppSessions200Response

`func NewGetAppSessions200Response() *GetAppSessions200Response`

NewGetAppSessions200Response instantiates a new GetAppSessions200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetAppSessions200ResponseWithDefaults

`func NewGetAppSessions200ResponseWithDefaults() *GetAppSessions200Response`

NewGetAppSessions200ResponseWithDefaults instantiates a new GetAppSessions200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetAppSessions200Response) GetData() []GetAppSessions200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetAppSessions200Response) GetDataOk() (*[]GetAppSessions200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetAppSessions200Response) SetData(v []GetAppSessions200ResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *GetAppSessions200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetLinks

`func (o *GetAppSessions200Response) GetLinks() GetAppSessions200ResponseLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *GetAppSessions200Response) GetLinksOk() (*GetAppSessions200ResponseLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *GetAppSessions200Response) SetLinks(v GetAppSessions200ResponseLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *GetAppSessions200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *GetAppSessions200Response) GetMeta() GetAppSessions200ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetAppSessions200Response) GetMetaOk() (*GetAppSessions200ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetAppSessions200Response) SetMeta(v GetAppSessions200ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetAppSessions200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


