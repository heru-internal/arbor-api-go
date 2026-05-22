# UpdateDeviceCustomFieldsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Action** | **string** | The action to perform on the custom fields | 
**CustomFields** | [**[]UpdateDeviceCustomFieldsRequestCustomFieldsInner**](UpdateDeviceCustomFieldsRequestCustomFieldsInner.md) | Array of custom fields to attach, detach, or sync | 

## Methods

### NewUpdateDeviceCustomFieldsRequest

`func NewUpdateDeviceCustomFieldsRequest(action string, customFields []UpdateDeviceCustomFieldsRequestCustomFieldsInner, ) *UpdateDeviceCustomFieldsRequest`

NewUpdateDeviceCustomFieldsRequest instantiates a new UpdateDeviceCustomFieldsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateDeviceCustomFieldsRequestWithDefaults

`func NewUpdateDeviceCustomFieldsRequestWithDefaults() *UpdateDeviceCustomFieldsRequest`

NewUpdateDeviceCustomFieldsRequestWithDefaults instantiates a new UpdateDeviceCustomFieldsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAction

`func (o *UpdateDeviceCustomFieldsRequest) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *UpdateDeviceCustomFieldsRequest) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *UpdateDeviceCustomFieldsRequest) SetAction(v string)`

SetAction sets Action field to given value.


### GetCustomFields

`func (o *UpdateDeviceCustomFieldsRequest) GetCustomFields() []UpdateDeviceCustomFieldsRequestCustomFieldsInner`

GetCustomFields returns the CustomFields field if non-nil, zero value otherwise.

### GetCustomFieldsOk

`func (o *UpdateDeviceCustomFieldsRequest) GetCustomFieldsOk() (*[]UpdateDeviceCustomFieldsRequestCustomFieldsInner, bool)`

GetCustomFieldsOk returns a tuple with the CustomFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomFields

`func (o *UpdateDeviceCustomFieldsRequest) SetCustomFields(v []UpdateDeviceCustomFieldsRequestCustomFieldsInner)`

SetCustomFields sets CustomFields field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


