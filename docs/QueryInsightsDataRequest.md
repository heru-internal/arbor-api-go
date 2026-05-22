# QueryInsightsDataRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**OrganizationIds** | Pointer to **[]string** | Filter by organization IDs. | [optional] 
**Page** | Pointer to **int32** | Page number for pagination. | [optional] 
**PageSize** | Pointer to **int32** | Number of items per page. | [optional] 
**StartDate** | Pointer to **string** | Filter data from this date. | [optional] 
**EndDate** | Pointer to **string** | Filter data until this date. | [optional] 
**Collection** | Pointer to **string** | The data collection to query. | [optional] 
**GroupBy** | Pointer to **[]string** | Fields to group results by. | [optional] 
**Aggregate** | Pointer to **string** | Aggregation function to apply. | [optional] 
**AggregateField** | Pointer to **string** | The field to aggregate on. Required when aggregate is specified. | [optional] 
**Timezone** | Pointer to **string** | Timezone for date-based operations. | [optional] 
**FilterQuery** | Pointer to **map[string]interface{}** | Filter criteria for the query. | [optional] 
**SearchTerm** | Pointer to **string** | Search term to filter results. | [optional] 
**GroupIds** | Pointer to **[]string** | Filter by group IDs. | [optional] 
**DeviceIds** | Pointer to **[]string** | Filter by device IDs. | [optional] 

## Methods

### NewQueryInsightsDataRequest

`func NewQueryInsightsDataRequest() *QueryInsightsDataRequest`

NewQueryInsightsDataRequest instantiates a new QueryInsightsDataRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueryInsightsDataRequestWithDefaults

`func NewQueryInsightsDataRequestWithDefaults() *QueryInsightsDataRequest`

NewQueryInsightsDataRequestWithDefaults instantiates a new QueryInsightsDataRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrganizationIds

`func (o *QueryInsightsDataRequest) GetOrganizationIds() []string`

GetOrganizationIds returns the OrganizationIds field if non-nil, zero value otherwise.

### GetOrganizationIdsOk

`func (o *QueryInsightsDataRequest) GetOrganizationIdsOk() (*[]string, bool)`

GetOrganizationIdsOk returns a tuple with the OrganizationIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationIds

`func (o *QueryInsightsDataRequest) SetOrganizationIds(v []string)`

SetOrganizationIds sets OrganizationIds field to given value.

### HasOrganizationIds

`func (o *QueryInsightsDataRequest) HasOrganizationIds() bool`

HasOrganizationIds returns a boolean if a field has been set.

### GetPage

`func (o *QueryInsightsDataRequest) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *QueryInsightsDataRequest) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *QueryInsightsDataRequest) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *QueryInsightsDataRequest) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetPageSize

`func (o *QueryInsightsDataRequest) GetPageSize() int32`

GetPageSize returns the PageSize field if non-nil, zero value otherwise.

### GetPageSizeOk

`func (o *QueryInsightsDataRequest) GetPageSizeOk() (*int32, bool)`

GetPageSizeOk returns a tuple with the PageSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageSize

`func (o *QueryInsightsDataRequest) SetPageSize(v int32)`

SetPageSize sets PageSize field to given value.

### HasPageSize

`func (o *QueryInsightsDataRequest) HasPageSize() bool`

HasPageSize returns a boolean if a field has been set.

### GetStartDate

`func (o *QueryInsightsDataRequest) GetStartDate() string`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *QueryInsightsDataRequest) GetStartDateOk() (*string, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *QueryInsightsDataRequest) SetStartDate(v string)`

SetStartDate sets StartDate field to given value.

### HasStartDate

`func (o *QueryInsightsDataRequest) HasStartDate() bool`

HasStartDate returns a boolean if a field has been set.

### GetEndDate

`func (o *QueryInsightsDataRequest) GetEndDate() string`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *QueryInsightsDataRequest) GetEndDateOk() (*string, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *QueryInsightsDataRequest) SetEndDate(v string)`

SetEndDate sets EndDate field to given value.

### HasEndDate

`func (o *QueryInsightsDataRequest) HasEndDate() bool`

HasEndDate returns a boolean if a field has been set.

### GetCollection

`func (o *QueryInsightsDataRequest) GetCollection() string`

GetCollection returns the Collection field if non-nil, zero value otherwise.

### GetCollectionOk

`func (o *QueryInsightsDataRequest) GetCollectionOk() (*string, bool)`

GetCollectionOk returns a tuple with the Collection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollection

`func (o *QueryInsightsDataRequest) SetCollection(v string)`

SetCollection sets Collection field to given value.

### HasCollection

`func (o *QueryInsightsDataRequest) HasCollection() bool`

HasCollection returns a boolean if a field has been set.

### GetGroupBy

`func (o *QueryInsightsDataRequest) GetGroupBy() []string`

GetGroupBy returns the GroupBy field if non-nil, zero value otherwise.

### GetGroupByOk

`func (o *QueryInsightsDataRequest) GetGroupByOk() (*[]string, bool)`

GetGroupByOk returns a tuple with the GroupBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupBy

`func (o *QueryInsightsDataRequest) SetGroupBy(v []string)`

SetGroupBy sets GroupBy field to given value.

### HasGroupBy

`func (o *QueryInsightsDataRequest) HasGroupBy() bool`

HasGroupBy returns a boolean if a field has been set.

### GetAggregate

`func (o *QueryInsightsDataRequest) GetAggregate() string`

GetAggregate returns the Aggregate field if non-nil, zero value otherwise.

### GetAggregateOk

`func (o *QueryInsightsDataRequest) GetAggregateOk() (*string, bool)`

GetAggregateOk returns a tuple with the Aggregate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggregate

`func (o *QueryInsightsDataRequest) SetAggregate(v string)`

SetAggregate sets Aggregate field to given value.

### HasAggregate

`func (o *QueryInsightsDataRequest) HasAggregate() bool`

HasAggregate returns a boolean if a field has been set.

### GetAggregateField

`func (o *QueryInsightsDataRequest) GetAggregateField() string`

GetAggregateField returns the AggregateField field if non-nil, zero value otherwise.

### GetAggregateFieldOk

`func (o *QueryInsightsDataRequest) GetAggregateFieldOk() (*string, bool)`

GetAggregateFieldOk returns a tuple with the AggregateField field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggregateField

`func (o *QueryInsightsDataRequest) SetAggregateField(v string)`

SetAggregateField sets AggregateField field to given value.

### HasAggregateField

`func (o *QueryInsightsDataRequest) HasAggregateField() bool`

HasAggregateField returns a boolean if a field has been set.

### GetTimezone

`func (o *QueryInsightsDataRequest) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *QueryInsightsDataRequest) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *QueryInsightsDataRequest) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *QueryInsightsDataRequest) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### GetFilterQuery

`func (o *QueryInsightsDataRequest) GetFilterQuery() map[string]interface{}`

GetFilterQuery returns the FilterQuery field if non-nil, zero value otherwise.

### GetFilterQueryOk

`func (o *QueryInsightsDataRequest) GetFilterQueryOk() (*map[string]interface{}, bool)`

GetFilterQueryOk returns a tuple with the FilterQuery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilterQuery

`func (o *QueryInsightsDataRequest) SetFilterQuery(v map[string]interface{})`

SetFilterQuery sets FilterQuery field to given value.

### HasFilterQuery

`func (o *QueryInsightsDataRequest) HasFilterQuery() bool`

HasFilterQuery returns a boolean if a field has been set.

### GetSearchTerm

`func (o *QueryInsightsDataRequest) GetSearchTerm() string`

GetSearchTerm returns the SearchTerm field if non-nil, zero value otherwise.

### GetSearchTermOk

`func (o *QueryInsightsDataRequest) GetSearchTermOk() (*string, bool)`

GetSearchTermOk returns a tuple with the SearchTerm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearchTerm

`func (o *QueryInsightsDataRequest) SetSearchTerm(v string)`

SetSearchTerm sets SearchTerm field to given value.

### HasSearchTerm

`func (o *QueryInsightsDataRequest) HasSearchTerm() bool`

HasSearchTerm returns a boolean if a field has been set.

### GetGroupIds

`func (o *QueryInsightsDataRequest) GetGroupIds() []string`

GetGroupIds returns the GroupIds field if non-nil, zero value otherwise.

### GetGroupIdsOk

`func (o *QueryInsightsDataRequest) GetGroupIdsOk() (*[]string, bool)`

GetGroupIdsOk returns a tuple with the GroupIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupIds

`func (o *QueryInsightsDataRequest) SetGroupIds(v []string)`

SetGroupIds sets GroupIds field to given value.

### HasGroupIds

`func (o *QueryInsightsDataRequest) HasGroupIds() bool`

HasGroupIds returns a boolean if a field has been set.

### GetDeviceIds

`func (o *QueryInsightsDataRequest) GetDeviceIds() []string`

GetDeviceIds returns the DeviceIds field if non-nil, zero value otherwise.

### GetDeviceIdsOk

`func (o *QueryInsightsDataRequest) GetDeviceIdsOk() (*[]string, bool)`

GetDeviceIdsOk returns a tuple with the DeviceIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeviceIds

`func (o *QueryInsightsDataRequest) SetDeviceIds(v []string)`

SetDeviceIds sets DeviceIds field to given value.

### HasDeviceIds

`func (o *QueryInsightsDataRequest) HasDeviceIds() bool`

HasDeviceIds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


