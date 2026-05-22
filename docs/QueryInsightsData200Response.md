# QueryInsightsData200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to **[]map[string]interface{}** | Array of analytics data items. The schema of each item varies depending on the collection type and query parameters. | [optional] 
**NextPage** | Pointer to **NullableInt32** | The next page number, or null if there are no more pages. | [optional] 
**PrevPage** | Pointer to **NullableInt32** | The previous page number, or null if on the first page. | [optional] 

## Methods

### NewQueryInsightsData200Response

`func NewQueryInsightsData200Response() *QueryInsightsData200Response`

NewQueryInsightsData200Response instantiates a new QueryInsightsData200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueryInsightsData200ResponseWithDefaults

`func NewQueryInsightsData200ResponseWithDefaults() *QueryInsightsData200Response`

NewQueryInsightsData200ResponseWithDefaults instantiates a new QueryInsightsData200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *QueryInsightsData200Response) GetData() []map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *QueryInsightsData200Response) GetDataOk() (*[]map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *QueryInsightsData200Response) SetData(v []map[string]interface{})`

SetData sets Data field to given value.

### HasData

`func (o *QueryInsightsData200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetNextPage

`func (o *QueryInsightsData200Response) GetNextPage() int32`

GetNextPage returns the NextPage field if non-nil, zero value otherwise.

### GetNextPageOk

`func (o *QueryInsightsData200Response) GetNextPageOk() (*int32, bool)`

GetNextPageOk returns a tuple with the NextPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextPage

`func (o *QueryInsightsData200Response) SetNextPage(v int32)`

SetNextPage sets NextPage field to given value.

### HasNextPage

`func (o *QueryInsightsData200Response) HasNextPage() bool`

HasNextPage returns a boolean if a field has been set.

### SetNextPageNil

`func (o *QueryInsightsData200Response) SetNextPageNil(b bool)`

 SetNextPageNil sets the value for NextPage to be an explicit nil

### UnsetNextPage
`func (o *QueryInsightsData200Response) UnsetNextPage()`

UnsetNextPage ensures that no value is present for NextPage, not even an explicit nil
### GetPrevPage

`func (o *QueryInsightsData200Response) GetPrevPage() int32`

GetPrevPage returns the PrevPage field if non-nil, zero value otherwise.

### GetPrevPageOk

`func (o *QueryInsightsData200Response) GetPrevPageOk() (*int32, bool)`

GetPrevPageOk returns a tuple with the PrevPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrevPage

`func (o *QueryInsightsData200Response) SetPrevPage(v int32)`

SetPrevPage sets PrevPage field to given value.

### HasPrevPage

`func (o *QueryInsightsData200Response) HasPrevPage() bool`

HasPrevPage returns a boolean if a field has been set.

### SetPrevPageNil

`func (o *QueryInsightsData200Response) SetPrevPageNil(b bool)`

 SetPrevPageNil sets the value for PrevPage to be an explicit nil

### UnsetPrevPage
`func (o *QueryInsightsData200Response) UnsetPrevPage()`

UnsetPrevPage ensures that no value is present for PrevPage, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


