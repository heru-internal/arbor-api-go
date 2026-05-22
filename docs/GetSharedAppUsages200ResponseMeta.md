# GetSharedAppUsages200ResponseMeta

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentPage** | Pointer to **int32** |  | [optional] 
**From** | Pointer to **NullableInt32** |  | [optional] 
**LastPage** | Pointer to **int32** |  | [optional] 
**Links** | Pointer to [**[]GetSharedAppUsages200ResponseMetaLinksInner**](GetSharedAppUsages200ResponseMetaLinksInner.md) |  | [optional] 
**Path** | Pointer to **string** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**To** | Pointer to **NullableInt32** |  | [optional] 
**Total** | Pointer to **int32** |  | [optional] 

## Methods

### NewGetSharedAppUsages200ResponseMeta

`func NewGetSharedAppUsages200ResponseMeta() *GetSharedAppUsages200ResponseMeta`

NewGetSharedAppUsages200ResponseMeta instantiates a new GetSharedAppUsages200ResponseMeta object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetSharedAppUsages200ResponseMetaWithDefaults

`func NewGetSharedAppUsages200ResponseMetaWithDefaults() *GetSharedAppUsages200ResponseMeta`

NewGetSharedAppUsages200ResponseMetaWithDefaults instantiates a new GetSharedAppUsages200ResponseMeta object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentPage

`func (o *GetSharedAppUsages200ResponseMeta) GetCurrentPage() int32`

GetCurrentPage returns the CurrentPage field if non-nil, zero value otherwise.

### GetCurrentPageOk

`func (o *GetSharedAppUsages200ResponseMeta) GetCurrentPageOk() (*int32, bool)`

GetCurrentPageOk returns a tuple with the CurrentPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPage

`func (o *GetSharedAppUsages200ResponseMeta) SetCurrentPage(v int32)`

SetCurrentPage sets CurrentPage field to given value.

### HasCurrentPage

`func (o *GetSharedAppUsages200ResponseMeta) HasCurrentPage() bool`

HasCurrentPage returns a boolean if a field has been set.

### GetFrom

`func (o *GetSharedAppUsages200ResponseMeta) GetFrom() int32`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *GetSharedAppUsages200ResponseMeta) GetFromOk() (*int32, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *GetSharedAppUsages200ResponseMeta) SetFrom(v int32)`

SetFrom sets From field to given value.

### HasFrom

`func (o *GetSharedAppUsages200ResponseMeta) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### SetFromNil

`func (o *GetSharedAppUsages200ResponseMeta) SetFromNil(b bool)`

 SetFromNil sets the value for From to be an explicit nil

### UnsetFrom
`func (o *GetSharedAppUsages200ResponseMeta) UnsetFrom()`

UnsetFrom ensures that no value is present for From, not even an explicit nil
### GetLastPage

`func (o *GetSharedAppUsages200ResponseMeta) GetLastPage() int32`

GetLastPage returns the LastPage field if non-nil, zero value otherwise.

### GetLastPageOk

`func (o *GetSharedAppUsages200ResponseMeta) GetLastPageOk() (*int32, bool)`

GetLastPageOk returns a tuple with the LastPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPage

`func (o *GetSharedAppUsages200ResponseMeta) SetLastPage(v int32)`

SetLastPage sets LastPage field to given value.

### HasLastPage

`func (o *GetSharedAppUsages200ResponseMeta) HasLastPage() bool`

HasLastPage returns a boolean if a field has been set.

### GetLinks

`func (o *GetSharedAppUsages200ResponseMeta) GetLinks() []GetSharedAppUsages200ResponseMetaLinksInner`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *GetSharedAppUsages200ResponseMeta) GetLinksOk() (*[]GetSharedAppUsages200ResponseMetaLinksInner, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *GetSharedAppUsages200ResponseMeta) SetLinks(v []GetSharedAppUsages200ResponseMetaLinksInner)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *GetSharedAppUsages200ResponseMeta) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetPath

`func (o *GetSharedAppUsages200ResponseMeta) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *GetSharedAppUsages200ResponseMeta) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *GetSharedAppUsages200ResponseMeta) SetPath(v string)`

SetPath sets Path field to given value.

### HasPath

`func (o *GetSharedAppUsages200ResponseMeta) HasPath() bool`

HasPath returns a boolean if a field has been set.

### GetPerPage

`func (o *GetSharedAppUsages200ResponseMeta) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *GetSharedAppUsages200ResponseMeta) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *GetSharedAppUsages200ResponseMeta) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *GetSharedAppUsages200ResponseMeta) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetTo

`func (o *GetSharedAppUsages200ResponseMeta) GetTo() int32`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *GetSharedAppUsages200ResponseMeta) GetToOk() (*int32, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *GetSharedAppUsages200ResponseMeta) SetTo(v int32)`

SetTo sets To field to given value.

### HasTo

`func (o *GetSharedAppUsages200ResponseMeta) HasTo() bool`

HasTo returns a boolean if a field has been set.

### SetToNil

`func (o *GetSharedAppUsages200ResponseMeta) SetToNil(b bool)`

 SetToNil sets the value for To to be an explicit nil

### UnsetTo
`func (o *GetSharedAppUsages200ResponseMeta) UnsetTo()`

UnsetTo ensures that no value is present for To, not even an explicit nil
### GetTotal

`func (o *GetSharedAppUsages200ResponseMeta) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *GetSharedAppUsages200ResponseMeta) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *GetSharedAppUsages200ResponseMeta) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *GetSharedAppUsages200ResponseMeta) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


