# GetRoles200ResponseMeta

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentPage** | Pointer to **int32** |  | [optional] 
**From** | Pointer to **NullableInt32** |  | [optional] 
**LastPage** | Pointer to **int32** |  | [optional] 
**Links** | Pointer to [**[]GetRoles200ResponseMetaLinksInner**](GetRoles200ResponseMetaLinksInner.md) |  | [optional] 
**Path** | Pointer to **string** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**To** | Pointer to **NullableInt32** |  | [optional] 
**Total** | Pointer to **int32** |  | [optional] 

## Methods

### NewGetRoles200ResponseMeta

`func NewGetRoles200ResponseMeta() *GetRoles200ResponseMeta`

NewGetRoles200ResponseMeta instantiates a new GetRoles200ResponseMeta object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetRoles200ResponseMetaWithDefaults

`func NewGetRoles200ResponseMetaWithDefaults() *GetRoles200ResponseMeta`

NewGetRoles200ResponseMetaWithDefaults instantiates a new GetRoles200ResponseMeta object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentPage

`func (o *GetRoles200ResponseMeta) GetCurrentPage() int32`

GetCurrentPage returns the CurrentPage field if non-nil, zero value otherwise.

### GetCurrentPageOk

`func (o *GetRoles200ResponseMeta) GetCurrentPageOk() (*int32, bool)`

GetCurrentPageOk returns a tuple with the CurrentPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPage

`func (o *GetRoles200ResponseMeta) SetCurrentPage(v int32)`

SetCurrentPage sets CurrentPage field to given value.

### HasCurrentPage

`func (o *GetRoles200ResponseMeta) HasCurrentPage() bool`

HasCurrentPage returns a boolean if a field has been set.

### GetFrom

`func (o *GetRoles200ResponseMeta) GetFrom() int32`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *GetRoles200ResponseMeta) GetFromOk() (*int32, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *GetRoles200ResponseMeta) SetFrom(v int32)`

SetFrom sets From field to given value.

### HasFrom

`func (o *GetRoles200ResponseMeta) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### SetFromNil

`func (o *GetRoles200ResponseMeta) SetFromNil(b bool)`

 SetFromNil sets the value for From to be an explicit nil

### UnsetFrom
`func (o *GetRoles200ResponseMeta) UnsetFrom()`

UnsetFrom ensures that no value is present for From, not even an explicit nil
### GetLastPage

`func (o *GetRoles200ResponseMeta) GetLastPage() int32`

GetLastPage returns the LastPage field if non-nil, zero value otherwise.

### GetLastPageOk

`func (o *GetRoles200ResponseMeta) GetLastPageOk() (*int32, bool)`

GetLastPageOk returns a tuple with the LastPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPage

`func (o *GetRoles200ResponseMeta) SetLastPage(v int32)`

SetLastPage sets LastPage field to given value.

### HasLastPage

`func (o *GetRoles200ResponseMeta) HasLastPage() bool`

HasLastPage returns a boolean if a field has been set.

### GetLinks

`func (o *GetRoles200ResponseMeta) GetLinks() []GetRoles200ResponseMetaLinksInner`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *GetRoles200ResponseMeta) GetLinksOk() (*[]GetRoles200ResponseMetaLinksInner, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *GetRoles200ResponseMeta) SetLinks(v []GetRoles200ResponseMetaLinksInner)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *GetRoles200ResponseMeta) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetPath

`func (o *GetRoles200ResponseMeta) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *GetRoles200ResponseMeta) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *GetRoles200ResponseMeta) SetPath(v string)`

SetPath sets Path field to given value.

### HasPath

`func (o *GetRoles200ResponseMeta) HasPath() bool`

HasPath returns a boolean if a field has been set.

### GetPerPage

`func (o *GetRoles200ResponseMeta) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *GetRoles200ResponseMeta) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *GetRoles200ResponseMeta) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *GetRoles200ResponseMeta) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetTo

`func (o *GetRoles200ResponseMeta) GetTo() int32`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *GetRoles200ResponseMeta) GetToOk() (*int32, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *GetRoles200ResponseMeta) SetTo(v int32)`

SetTo sets To field to given value.

### HasTo

`func (o *GetRoles200ResponseMeta) HasTo() bool`

HasTo returns a boolean if a field has been set.

### SetToNil

`func (o *GetRoles200ResponseMeta) SetToNil(b bool)`

 SetToNil sets the value for To to be an explicit nil

### UnsetTo
`func (o *GetRoles200ResponseMeta) UnsetTo()`

UnsetTo ensures that no value is present for To, not even an explicit nil
### GetTotal

`func (o *GetRoles200ResponseMeta) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *GetRoles200ResponseMeta) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *GetRoles200ResponseMeta) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *GetRoles200ResponseMeta) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


