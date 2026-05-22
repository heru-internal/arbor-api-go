# UpdateDeviceCustomFieldsRequestCustomFieldsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | The name of the custom field | 
**Value** | Pointer to **string** | The value of the custom field (required for attach and sync actions) | [optional] 

## Methods

### NewUpdateDeviceCustomFieldsRequestCustomFieldsInner

`func NewUpdateDeviceCustomFieldsRequestCustomFieldsInner(name string, ) *UpdateDeviceCustomFieldsRequestCustomFieldsInner`

NewUpdateDeviceCustomFieldsRequestCustomFieldsInner instantiates a new UpdateDeviceCustomFieldsRequestCustomFieldsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateDeviceCustomFieldsRequestCustomFieldsInnerWithDefaults

`func NewUpdateDeviceCustomFieldsRequestCustomFieldsInnerWithDefaults() *UpdateDeviceCustomFieldsRequestCustomFieldsInner`

NewUpdateDeviceCustomFieldsRequestCustomFieldsInnerWithDefaults instantiates a new UpdateDeviceCustomFieldsRequestCustomFieldsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateDeviceCustomFieldsRequestCustomFieldsInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateDeviceCustomFieldsRequestCustomFieldsInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateDeviceCustomFieldsRequestCustomFieldsInner) SetName(v string)`

SetName sets Name field to given value.


### GetValue

`func (o *UpdateDeviceCustomFieldsRequestCustomFieldsInner) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *UpdateDeviceCustomFieldsRequestCustomFieldsInner) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *UpdateDeviceCustomFieldsRequestCustomFieldsInner) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *UpdateDeviceCustomFieldsRequestCustomFieldsInner) HasValue() bool`

HasValue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


