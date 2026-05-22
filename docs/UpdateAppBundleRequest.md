# UpdateAppBundleRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Label** | Pointer to **NullableString** | The label for the app bundle. Set to null to remove. | [optional] 

## Methods

### NewUpdateAppBundleRequest

`func NewUpdateAppBundleRequest() *UpdateAppBundleRequest`

NewUpdateAppBundleRequest instantiates a new UpdateAppBundleRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateAppBundleRequestWithDefaults

`func NewUpdateAppBundleRequestWithDefaults() *UpdateAppBundleRequest`

NewUpdateAppBundleRequestWithDefaults instantiates a new UpdateAppBundleRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLabel

`func (o *UpdateAppBundleRequest) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *UpdateAppBundleRequest) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *UpdateAppBundleRequest) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *UpdateAppBundleRequest) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### SetLabelNil

`func (o *UpdateAppBundleRequest) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *UpdateAppBundleRequest) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


