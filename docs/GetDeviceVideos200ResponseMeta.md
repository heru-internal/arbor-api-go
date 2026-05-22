# GetDeviceVideos200ResponseMeta

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CurrentPage** | Pointer to **int32** |  | [optional] 
**From** | Pointer to **NullableInt32** |  | [optional] 
**LastPage** | Pointer to **int32** |  | [optional] 
**Links** | Pointer to [**[]GetDeviceVideos200ResponseMetaLinksInner**](GetDeviceVideos200ResponseMetaLinksInner.md) |  | [optional] 
**Path** | Pointer to **string** |  | [optional] 
**PerPage** | Pointer to **int32** |  | [optional] 
**To** | Pointer to **NullableInt32** |  | [optional] 
**Total** | Pointer to **int32** |  | [optional] 

## Methods

### NewGetDeviceVideos200ResponseMeta

`func NewGetDeviceVideos200ResponseMeta() *GetDeviceVideos200ResponseMeta`

NewGetDeviceVideos200ResponseMeta instantiates a new GetDeviceVideos200ResponseMeta object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetDeviceVideos200ResponseMetaWithDefaults

`func NewGetDeviceVideos200ResponseMetaWithDefaults() *GetDeviceVideos200ResponseMeta`

NewGetDeviceVideos200ResponseMetaWithDefaults instantiates a new GetDeviceVideos200ResponseMeta object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrentPage

`func (o *GetDeviceVideos200ResponseMeta) GetCurrentPage() int32`

GetCurrentPage returns the CurrentPage field if non-nil, zero value otherwise.

### GetCurrentPageOk

`func (o *GetDeviceVideos200ResponseMeta) GetCurrentPageOk() (*int32, bool)`

GetCurrentPageOk returns a tuple with the CurrentPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPage

`func (o *GetDeviceVideos200ResponseMeta) SetCurrentPage(v int32)`

SetCurrentPage sets CurrentPage field to given value.

### HasCurrentPage

`func (o *GetDeviceVideos200ResponseMeta) HasCurrentPage() bool`

HasCurrentPage returns a boolean if a field has been set.

### GetFrom

`func (o *GetDeviceVideos200ResponseMeta) GetFrom() int32`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *GetDeviceVideos200ResponseMeta) GetFromOk() (*int32, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *GetDeviceVideos200ResponseMeta) SetFrom(v int32)`

SetFrom sets From field to given value.

### HasFrom

`func (o *GetDeviceVideos200ResponseMeta) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### SetFromNil

`func (o *GetDeviceVideos200ResponseMeta) SetFromNil(b bool)`

 SetFromNil sets the value for From to be an explicit nil

### UnsetFrom
`func (o *GetDeviceVideos200ResponseMeta) UnsetFrom()`

UnsetFrom ensures that no value is present for From, not even an explicit nil
### GetLastPage

`func (o *GetDeviceVideos200ResponseMeta) GetLastPage() int32`

GetLastPage returns the LastPage field if non-nil, zero value otherwise.

### GetLastPageOk

`func (o *GetDeviceVideos200ResponseMeta) GetLastPageOk() (*int32, bool)`

GetLastPageOk returns a tuple with the LastPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPage

`func (o *GetDeviceVideos200ResponseMeta) SetLastPage(v int32)`

SetLastPage sets LastPage field to given value.

### HasLastPage

`func (o *GetDeviceVideos200ResponseMeta) HasLastPage() bool`

HasLastPage returns a boolean if a field has been set.

### GetLinks

`func (o *GetDeviceVideos200ResponseMeta) GetLinks() []GetDeviceVideos200ResponseMetaLinksInner`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *GetDeviceVideos200ResponseMeta) GetLinksOk() (*[]GetDeviceVideos200ResponseMetaLinksInner, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *GetDeviceVideos200ResponseMeta) SetLinks(v []GetDeviceVideos200ResponseMetaLinksInner)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *GetDeviceVideos200ResponseMeta) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetPath

`func (o *GetDeviceVideos200ResponseMeta) GetPath() string`

GetPath returns the Path field if non-nil, zero value otherwise.

### GetPathOk

`func (o *GetDeviceVideos200ResponseMeta) GetPathOk() (*string, bool)`

GetPathOk returns a tuple with the Path field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPath

`func (o *GetDeviceVideos200ResponseMeta) SetPath(v string)`

SetPath sets Path field to given value.

### HasPath

`func (o *GetDeviceVideos200ResponseMeta) HasPath() bool`

HasPath returns a boolean if a field has been set.

### GetPerPage

`func (o *GetDeviceVideos200ResponseMeta) GetPerPage() int32`

GetPerPage returns the PerPage field if non-nil, zero value otherwise.

### GetPerPageOk

`func (o *GetDeviceVideos200ResponseMeta) GetPerPageOk() (*int32, bool)`

GetPerPageOk returns a tuple with the PerPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPage

`func (o *GetDeviceVideos200ResponseMeta) SetPerPage(v int32)`

SetPerPage sets PerPage field to given value.

### HasPerPage

`func (o *GetDeviceVideos200ResponseMeta) HasPerPage() bool`

HasPerPage returns a boolean if a field has been set.

### GetTo

`func (o *GetDeviceVideos200ResponseMeta) GetTo() int32`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *GetDeviceVideos200ResponseMeta) GetToOk() (*int32, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *GetDeviceVideos200ResponseMeta) SetTo(v int32)`

SetTo sets To field to given value.

### HasTo

`func (o *GetDeviceVideos200ResponseMeta) HasTo() bool`

HasTo returns a boolean if a field has been set.

### SetToNil

`func (o *GetDeviceVideos200ResponseMeta) SetToNil(b bool)`

 SetToNil sets the value for To to be an explicit nil

### UnsetTo
`func (o *GetDeviceVideos200ResponseMeta) UnsetTo()`

UnsetTo ensures that no value is present for To, not even an explicit nil
### GetTotal

`func (o *GetDeviceVideos200ResponseMeta) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *GetDeviceVideos200ResponseMeta) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *GetDeviceVideos200ResponseMeta) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *GetDeviceVideos200ResponseMeta) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


