# GetRoles200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]GetCurrentUser200ResponseAccessControlsInnerRole**](GetCurrentUser200ResponseAccessControlsInnerRole.md) |  | [optional] 
**Links** | Pointer to [**GetRoles200ResponseLinks**](GetRoles200ResponseLinks.md) |  | [optional] 
**Meta** | Pointer to [**GetRoles200ResponseMeta**](GetRoles200ResponseMeta.md) |  | [optional] 

## Methods

### NewGetRoles200Response

`func NewGetRoles200Response() *GetRoles200Response`

NewGetRoles200Response instantiates a new GetRoles200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetRoles200ResponseWithDefaults

`func NewGetRoles200ResponseWithDefaults() *GetRoles200Response`

NewGetRoles200ResponseWithDefaults instantiates a new GetRoles200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetRoles200Response) GetData() []GetCurrentUser200ResponseAccessControlsInnerRole`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetRoles200Response) GetDataOk() (*[]GetCurrentUser200ResponseAccessControlsInnerRole, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetRoles200Response) SetData(v []GetCurrentUser200ResponseAccessControlsInnerRole)`

SetData sets Data field to given value.

### HasData

`func (o *GetRoles200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetLinks

`func (o *GetRoles200Response) GetLinks() GetRoles200ResponseLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *GetRoles200Response) GetLinksOk() (*GetRoles200ResponseLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *GetRoles200Response) SetLinks(v GetRoles200ResponseLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *GetRoles200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *GetRoles200Response) GetMeta() GetRoles200ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetRoles200Response) GetMetaOk() (*GetRoles200ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetRoles200Response) SetMeta(v GetRoles200ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetRoles200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


