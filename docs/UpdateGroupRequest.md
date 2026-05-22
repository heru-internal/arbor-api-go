# UpdateGroupRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | The name of the group | 
**ParentId** | **NullableString** | The ID of the parent group (for nested groups). Must be an unconfigured group. Pass null to make this a root-level group. | 

## Methods

### NewUpdateGroupRequest

`func NewUpdateGroupRequest(name string, parentId NullableString, ) *UpdateGroupRequest`

NewUpdateGroupRequest instantiates a new UpdateGroupRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateGroupRequestWithDefaults

`func NewUpdateGroupRequestWithDefaults() *UpdateGroupRequest`

NewUpdateGroupRequestWithDefaults instantiates a new UpdateGroupRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateGroupRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateGroupRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateGroupRequest) SetName(v string)`

SetName sets Name field to given value.


### GetParentId

`func (o *UpdateGroupRequest) GetParentId() string`

GetParentId returns the ParentId field if non-nil, zero value otherwise.

### GetParentIdOk

`func (o *UpdateGroupRequest) GetParentIdOk() (*string, bool)`

GetParentIdOk returns a tuple with the ParentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentId

`func (o *UpdateGroupRequest) SetParentId(v string)`

SetParentId sets ParentId field to given value.


### SetParentIdNil

`func (o *UpdateGroupRequest) SetParentIdNil(b bool)`

 SetParentIdNil sets the value for ParentId to be an explicit nil

### UnsetParentId
`func (o *UpdateGroupRequest) UnsetParentId()`

UnsetParentId ensures that no value is present for ParentId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


