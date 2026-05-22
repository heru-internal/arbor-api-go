# UpdateUserRequestGroupRolesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RoleId** | **string** |  | 
**GroupId** | **string** |  | 
**Action** | **string** | Specify whether to attach or detach the group role from the user. | 

## Methods

### NewUpdateUserRequestGroupRolesInner

`func NewUpdateUserRequestGroupRolesInner(roleId string, groupId string, action string, ) *UpdateUserRequestGroupRolesInner`

NewUpdateUserRequestGroupRolesInner instantiates a new UpdateUserRequestGroupRolesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateUserRequestGroupRolesInnerWithDefaults

`func NewUpdateUserRequestGroupRolesInnerWithDefaults() *UpdateUserRequestGroupRolesInner`

NewUpdateUserRequestGroupRolesInnerWithDefaults instantiates a new UpdateUserRequestGroupRolesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRoleId

`func (o *UpdateUserRequestGroupRolesInner) GetRoleId() string`

GetRoleId returns the RoleId field if non-nil, zero value otherwise.

### GetRoleIdOk

`func (o *UpdateUserRequestGroupRolesInner) GetRoleIdOk() (*string, bool)`

GetRoleIdOk returns a tuple with the RoleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoleId

`func (o *UpdateUserRequestGroupRolesInner) SetRoleId(v string)`

SetRoleId sets RoleId field to given value.


### GetGroupId

`func (o *UpdateUserRequestGroupRolesInner) GetGroupId() string`

GetGroupId returns the GroupId field if non-nil, zero value otherwise.

### GetGroupIdOk

`func (o *UpdateUserRequestGroupRolesInner) GetGroupIdOk() (*string, bool)`

GetGroupIdOk returns a tuple with the GroupId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupId

`func (o *UpdateUserRequestGroupRolesInner) SetGroupId(v string)`

SetGroupId sets GroupId field to given value.


### GetAction

`func (o *UpdateUserRequestGroupRolesInner) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *UpdateUserRequestGroupRolesInner) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *UpdateUserRequestGroupRolesInner) SetAction(v string)`

SetAction sets Action field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


