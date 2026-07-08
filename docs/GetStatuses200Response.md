# GetStatuses200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]GetStatuses200ResponseDataInner**](GetStatuses200ResponseDataInner.md) |  | [optional] 
**Links** | Pointer to [**GetUsers200ResponseLinks**](GetUsers200ResponseLinks.md) |  | [optional] 
**Meta** | Pointer to [**GetUsers200ResponseMeta**](GetUsers200ResponseMeta.md) |  | [optional] 

## Methods

### NewGetStatuses200Response

`func NewGetStatuses200Response() *GetStatuses200Response`

NewGetStatuses200Response instantiates a new GetStatuses200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetStatuses200ResponseWithDefaults

`func NewGetStatuses200ResponseWithDefaults() *GetStatuses200Response`

NewGetStatuses200ResponseWithDefaults instantiates a new GetStatuses200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetStatuses200Response) GetData() []GetStatuses200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetStatuses200Response) GetDataOk() (*[]GetStatuses200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetStatuses200Response) SetData(v []GetStatuses200ResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *GetStatuses200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetLinks

`func (o *GetStatuses200Response) GetLinks() GetUsers200ResponseLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *GetStatuses200Response) GetLinksOk() (*GetUsers200ResponseLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *GetStatuses200Response) SetLinks(v GetUsers200ResponseLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *GetStatuses200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *GetStatuses200Response) GetMeta() GetUsers200ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetStatuses200Response) GetMetaOk() (*GetUsers200ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetStatuses200Response) SetMeta(v GetUsers200ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetStatuses200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


