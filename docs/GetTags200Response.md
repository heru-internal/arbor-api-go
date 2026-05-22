# GetTags200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]GetTags200ResponseDataInner**](GetTags200ResponseDataInner.md) |  | [optional] 
**Links** | Pointer to [**GetTags200ResponseLinks**](GetTags200ResponseLinks.md) |  | [optional] 
**Meta** | Pointer to [**GetTags200ResponseMeta**](GetTags200ResponseMeta.md) |  | [optional] 

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

`func (o *GetTags200Response) GetLinks() GetTags200ResponseLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *GetTags200Response) GetLinksOk() (*GetTags200ResponseLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *GetTags200Response) SetLinks(v GetTags200ResponseLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *GetTags200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *GetTags200Response) GetMeta() GetTags200ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetTags200Response) GetMetaOk() (*GetTags200ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetTags200Response) SetMeta(v GetTags200ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetTags200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


