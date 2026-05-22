# GetVideos200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]GetVideos200ResponseDataInner**](GetVideos200ResponseDataInner.md) |  | [optional] 
**Links** | Pointer to [**GetVideos200ResponseLinks**](GetVideos200ResponseLinks.md) |  | [optional] 
**Meta** | Pointer to [**GetVideos200ResponseMeta**](GetVideos200ResponseMeta.md) |  | [optional] 

## Methods

### NewGetVideos200Response

`func NewGetVideos200Response() *GetVideos200Response`

NewGetVideos200Response instantiates a new GetVideos200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetVideos200ResponseWithDefaults

`func NewGetVideos200ResponseWithDefaults() *GetVideos200Response`

NewGetVideos200ResponseWithDefaults instantiates a new GetVideos200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *GetVideos200Response) GetData() []GetVideos200ResponseDataInner`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GetVideos200Response) GetDataOk() (*[]GetVideos200ResponseDataInner, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GetVideos200Response) SetData(v []GetVideos200ResponseDataInner)`

SetData sets Data field to given value.

### HasData

`func (o *GetVideos200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetLinks

`func (o *GetVideos200Response) GetLinks() GetVideos200ResponseLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *GetVideos200Response) GetLinksOk() (*GetVideos200ResponseLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *GetVideos200Response) SetLinks(v GetVideos200ResponseLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *GetVideos200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *GetVideos200Response) GetMeta() GetVideos200ResponseMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *GetVideos200Response) GetMetaOk() (*GetVideos200ResponseMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *GetVideos200Response) SetMeta(v GetVideos200ResponseMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *GetVideos200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


