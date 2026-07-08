# GetTags200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]GetTags200ResponseDataInner**](GetTags200ResponseDataInner.md) |  | [optional] 
**Links** | Pointer to [**GetUsers200ResponseLinks**](GetUsers200ResponseLinks.md) |  | [optional] 
**Meta** | Pointer to [**GetUsers200ResponseMeta**](GetUsers200ResponseMeta.md) |  | [optional] 

## Methods

### NewGetTags200Response

`func NewGetTags200Response() *GetTags200Response`

NewGetTags200Response instantiates a new GetTags200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetTags200ResponseWithDefaults

`func NewGetTags200ResponseWithDefaults() *GetTags200Response`

NewGetTags200ResponseWithDefaults instantiates a new GetTags200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetTags200Response) GetData() []GetTags200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetTags200Response) GetDataOk() (*[]GetTags200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetTags200Response) SetData(v []GetTags200ResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *GetTags200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetLinks

`func (o *GetTags200Response) GetLinks() GetUsers200ResponseLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *GetTags200Response) GetLinksOk() (*GetUsers200ResponseLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *GetTags200Response) SetLinks(v GetUsers200ResponseLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *GetTags200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *GetTags200Response) GetMeta() GetUsers200ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetTags200Response) GetMetaOk() (*GetUsers200ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetTags200Response) SetMeta(v GetUsers200ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetTags200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


