# CreateUserRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FirstName** | **string** |  | 
**LastName** | **string** |  | 
**Email** | **string** |  | 
**DefaultRoleId** | **string** | The default role assigned to the user. Can be an organization role or a group role. | 
**GroupRoles** | Pointer to [**[]CreateUserRequestGroupRolesInner**](CreateUserRequestGroupRolesInner.md) | Optional group roles to assign to the user upon creation. | [optional] 

## Methods

### NewCreateUserRequest

`func NewCreateUserRequest(firstName string, lastName string, email string, defaultRoleId string, ) *CreateUserRequest`

NewCreateUserRequest instantiates a new CreateUserRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateUserRequestWithDefaults

`func NewCreateUserRequestWithDefaults() *CreateUserRequest`

NewCreateUserRequestWithDefaults instantiates a new CreateUserRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFirstName

`func (o *CreateUserRequest) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *CreateUserRequest) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *CreateUserRequest) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.


### GetLastName

`func (o *CreateUserRequest) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *CreateUserRequest) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *CreateUserRequest) SetLastName(v string)`

SetLastName sets LastName field to given value.


### GetEmail

`func (o *CreateUserRequest) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *CreateUserRequest) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *CreateUserRequest) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetDefaultRoleId

`func (o *CreateUserRequest) GetDefaultRoleId() string`

GetDefaultRoleId returns the DefaultRoleId field if non-nil, zero value otherwise.

### GetDefaultRoleIdOk

`func (o *CreateUserRequest) GetDefaultRoleIdOk() (*string, bool)`

GetDefaultRoleIdOk returns a tuple with the DefaultRoleId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultRoleId

`func (o *CreateUserRequest) SetDefaultRoleId(v string)`

SetDefaultRoleId sets DefaultRoleId field to given value.


### GetGroupRoles

`func (o *CreateUserRequest) GetGroupRoles() []CreateUserRequestGroupRolesInner`

GetGroupRoles returns the GroupRoles field if non-nil, zero value otherwise.

### GetGroupRolesOk

`func (o *CreateUserRequest) GetGroupRolesOk() (*[]CreateUserRequestGroupRolesInner, bool)`

GetGroupRolesOk returns a tuple with the GroupRoles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupRoles

`func (o *CreateUserRequest) SetGroupRoles(v []CreateUserRequestGroupRolesInner)`

SetGroupRoles sets GroupRoles field to given value.

### HasGroupRoles

`func (o *CreateUserRequest) HasGroupRoles() bool`

HasGroupRoles returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


