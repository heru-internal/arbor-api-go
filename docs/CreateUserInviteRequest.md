# CreateUserInviteRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Email** | **string** | The email address of the user to invite. | 
**IsSsoEnforced** | Pointer to **bool** | Should the user be required to authenticate using the organization&#39;s configured IdP? | [optional] 
**DefaultRoleId** | **string** | The default role assigned to the user. Can be an organization role or a group role. | 
**GroupRoles** | Pointer to [**[]CreateUserRequestGroupRolesInner**](CreateUserRequestGroupRolesInner.md) | Optional group roles to assign to the user upon invitation. | [optional] 

## Methods

### NewCreateUserInviteRequest

`func NewCreateUserInviteRequest(email string, defaultRoleId string, ) *CreateUserInviteRequest`

NewCreateUserInviteRequest instantiates a new CreateUserInviteRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateUserInviteRequestWithDefaults

`func NewCreateUserInviteRequestWithDefaults() *CreateUserInviteRequest`

NewCreateUserInviteRequestWithDefaults instantiates a new CreateUserInviteRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEmail

`func (o *CreateUserInviteRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CreateUserInviteRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CreateUserInviteRequest) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetIsSsoEnforced

`func (o *CreateUserInviteRequest) GetIsSsoEnforced() bool`

GetIsSsoEnforced returns the IsSsoEnforced field if non-nil, zero value otherwise.

### GetIsSsoEnforcedOk

`func (o *CreateUserInviteRequest) GetIsSsoEnforcedOk() (*bool, bool)`

GetIsSsoEnforcedOk returns a tuple with the IsSsoEnforced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSsoEnforced

`func (o *CreateUserInviteRequest) SetIsSsoEnforced(v bool)`

SetIsSsoEnforced sets IsSsoEnforced field to given value.

### HasIsSsoEnforced

`func (o *CreateUserInviteRequest) HasIsSsoEnforced() bool`

HasIsSsoEnforced returns a boolean if a field has been set.

### GetDefaultRoleId

`func (o *CreateUserInviteRequest) GetDefaultRoleId() string`

GetDefaultRoleId returns the DefaultRoleId field if non-nil, zero value otherwise.

### GetDefaultRoleIdOk

`func (o *CreateUserInviteRequest) GetDefaultRoleIdOk() (*string, bool)`

GetDefaultRoleIdOk returns a tuple with the DefaultRoleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultRoleId

`func (o *CreateUserInviteRequest) SetDefaultRoleId(v string)`

SetDefaultRoleId sets DefaultRoleId field to given value.


### GetGroupRoles

`func (o *CreateUserInviteRequest) GetGroupRoles() []CreateUserRequestGroupRolesInner`

GetGroupRoles returns the GroupRoles field if non-nil, zero value otherwise.

### GetGroupRolesOk

`func (o *CreateUserInviteRequest) GetGroupRolesOk() (*[]CreateUserRequestGroupRolesInner, bool)`

GetGroupRolesOk returns a tuple with the GroupRoles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupRoles

`func (o *CreateUserInviteRequest) SetGroupRoles(v []CreateUserRequestGroupRolesInner)`

SetGroupRoles sets GroupRoles field to given value.

### HasGroupRoles

`func (o *CreateUserInviteRequest) HasGroupRoles() bool`

HasGroupRoles returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


