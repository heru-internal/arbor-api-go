# UpdateUserRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FirstName** | Pointer to **string** |  | [optional] 
**LastName** | Pointer to **string** |  | [optional] 
**DefaultRoleId** | Pointer to **string** |  | [optional] 
**GroupRoles** | Pointer to [**[]UpdateUserRequestGroupRolesInner**](UpdateUserRequestGroupRolesInner.md) | Group roles to attach or detach from the user. | [optional] 

## Methods

### NewUpdateUserRequest

`func NewUpdateUserRequest() *UpdateUserRequest`

NewUpdateUserRequest instantiates a new UpdateUserRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateUserRequestWithDefaults

`func NewUpdateUserRequestWithDefaults() *UpdateUserRequest`

NewUpdateUserRequestWithDefaults instantiates a new UpdateUserRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFirstName

`func (o *UpdateUserRequest) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *UpdateUserRequest) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *UpdateUserRequest) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *UpdateUserRequest) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *UpdateUserRequest) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *UpdateUserRequest) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *UpdateUserRequest) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *UpdateUserRequest) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetDefaultRoleId

`func (o *UpdateUserRequest) GetDefaultRoleId() string`

GetDefaultRoleId returns the DefaultRoleId field if non-nil, zero value otherwise.

### GetDefaultRoleIdOk

`func (o *UpdateUserRequest) GetDefaultRoleIdOk() (*string, bool)`

GetDefaultRoleIdOk returns a tuple with the DefaultRoleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultRoleId

`func (o *UpdateUserRequest) SetDefaultRoleId(v string)`

SetDefaultRoleId sets DefaultRoleId field to given value.

### HasDefaultRoleId

`func (o *UpdateUserRequest) HasDefaultRoleId() bool`

HasDefaultRoleId returns a boolean if a field has been set.

### GetGroupRoles

`func (o *UpdateUserRequest) GetGroupRoles() []UpdateUserRequestGroupRolesInner`

GetGroupRoles returns the GroupRoles field if non-nil, zero value otherwise.

### GetGroupRolesOk

`func (o *UpdateUserRequest) GetGroupRolesOk() (*[]UpdateUserRequestGroupRolesInner, bool)`

GetGroupRolesOk returns a tuple with the GroupRoles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupRoles

`func (o *UpdateUserRequest) SetGroupRoles(v []UpdateUserRequestGroupRolesInner)`

SetGroupRoles sets GroupRoles field to given value.

### HasGroupRoles

`func (o *UpdateUserRequest) HasGroupRoles() bool`

HasGroupRoles returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


