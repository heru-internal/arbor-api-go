# GetAuditLogs200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | The unique identifier of the audit log entry. | [optional] 
**Description** | **string** | Human-readable description of the action performed. | 
**Action** | **string** | The specific action that was performed. | 
**Type** | **string** | The type of action or category. | 
**ResourceId** | Pointer to **NullableString** | The unique identifier of the resource that was acted upon. | [optional] 
**ResourceType** | Pointer to **NullableString** | The type of resource that was acted upon (e.g., &#39;device&#39;, &#39;user&#39;). | [optional] 
**ResourceName** | Pointer to **NullableString** | The name of the resource that was acted upon. | [optional] 
**UserId** | Pointer to **NullableString** | The unique identifier of the user. | [optional] 
**UserEmail** | **string** | The email address of the user, or &#39;System&#39; for system actions, or &#39;ArborXR&#39; for admin/impersonation actions. | 
**UserIpAddress** | Pointer to **NullableString** | IP address from which the action was performed. | [optional] 
**CreatedAt** | **Time** |  | 
**UpdatedAt** | **Time** |  | 

## Methods

### NewGetAuditLogs200ResponseDataInner

`func NewGetAuditLogs200ResponseDataInner(description string, action string, type_ string, userEmail string, createdAt Time, updatedAt Time, ) *GetAuditLogs200ResponseDataInner`

NewGetAuditLogs200ResponseDataInner instantiates a new GetAuditLogs200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetAuditLogs200ResponseDataInnerWithDefaults

`func NewGetAuditLogs200ResponseDataInnerWithDefaults() *GetAuditLogs200ResponseDataInner`

NewGetAuditLogs200ResponseDataInnerWithDefaults instantiates a new GetAuditLogs200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetAuditLogs200ResponseDataInner) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetAuditLogs200ResponseDataInner) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetAuditLogs200ResponseDataInner) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *GetAuditLogs200ResponseDataInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetDescription

`func (o *GetAuditLogs200ResponseDataInner) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *GetAuditLogs200ResponseDataInner) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *GetAuditLogs200ResponseDataInner) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetAction

`func (o *GetAuditLogs200ResponseDataInner) GetAction() string`

GetAction returns the Action field if non-nil, zero value otherwise.

### GetActionOk

`func (o *GetAuditLogs200ResponseDataInner) GetActionOk() (*string, bool)`

GetActionOk returns a tuple with the Action field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAction

`func (o *GetAuditLogs200ResponseDataInner) SetAction(v string)`

SetAction sets Action field to given value.


### GetType

`func (o *GetAuditLogs200ResponseDataInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *GetAuditLogs200ResponseDataInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *GetAuditLogs200ResponseDataInner) SetType(v string)`

SetType sets Type field to given value.


### GetResourceId

`func (o *GetAuditLogs200ResponseDataInner) GetResourceId() string`

GetResourceId returns the ResourceId field if non-nil, zero value otherwise.

### GetResourceIdOk

`func (o *GetAuditLogs200ResponseDataInner) GetResourceIdOk() (*string, bool)`

GetResourceIdOk returns a tuple with the ResourceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceId

`func (o *GetAuditLogs200ResponseDataInner) SetResourceId(v string)`

SetResourceId sets ResourceId field to given value.

### HasResourceId

`func (o *GetAuditLogs200ResponseDataInner) HasResourceId() bool`

HasResourceId returns a boolean if a field has been set.

### SetResourceIdNil

`func (o *GetAuditLogs200ResponseDataInner) SetResourceIdNil(b bool)`

 SetResourceIdNil sets the value for ResourceId to be an explicit nil

### UnsetResourceId
`func (o *GetAuditLogs200ResponseDataInner) UnsetResourceId()`

UnsetResourceId ensures that no value is present for ResourceId, not even an explicit nil
### GetResourceType

`func (o *GetAuditLogs200ResponseDataInner) GetResourceType() string`

GetResourceType returns the ResourceType field if non-nil, zero value otherwise.

### GetResourceTypeOk

`func (o *GetAuditLogs200ResponseDataInner) GetResourceTypeOk() (*string, bool)`

GetResourceTypeOk returns a tuple with the ResourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceType

`func (o *GetAuditLogs200ResponseDataInner) SetResourceType(v string)`

SetResourceType sets ResourceType field to given value.

### HasResourceType

`func (o *GetAuditLogs200ResponseDataInner) HasResourceType() bool`

HasResourceType returns a boolean if a field has been set.

### SetResourceTypeNil

`func (o *GetAuditLogs200ResponseDataInner) SetResourceTypeNil(b bool)`

 SetResourceTypeNil sets the value for ResourceType to be an explicit nil

### UnsetResourceType
`func (o *GetAuditLogs200ResponseDataInner) UnsetResourceType()`

UnsetResourceType ensures that no value is present for ResourceType, not even an explicit nil
### GetResourceName

`func (o *GetAuditLogs200ResponseDataInner) GetResourceName() string`

GetResourceName returns the ResourceName field if non-nil, zero value otherwise.

### GetResourceNameOk

`func (o *GetAuditLogs200ResponseDataInner) GetResourceNameOk() (*string, bool)`

GetResourceNameOk returns a tuple with the ResourceName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResourceName

`func (o *GetAuditLogs200ResponseDataInner) SetResourceName(v string)`

SetResourceName sets ResourceName field to given value.

### HasResourceName

`func (o *GetAuditLogs200ResponseDataInner) HasResourceName() bool`

HasResourceName returns a boolean if a field has been set.

### SetResourceNameNil

`func (o *GetAuditLogs200ResponseDataInner) SetResourceNameNil(b bool)`

 SetResourceNameNil sets the value for ResourceName to be an explicit nil

### UnsetResourceName
`func (o *GetAuditLogs200ResponseDataInner) UnsetResourceName()`

UnsetResourceName ensures that no value is present for ResourceName, not even an explicit nil
### GetUserId

`func (o *GetAuditLogs200ResponseDataInner) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *GetAuditLogs200ResponseDataInner) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *GetAuditLogs200ResponseDataInner) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *GetAuditLogs200ResponseDataInner) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### SetUserIdNil

`func (o *GetAuditLogs200ResponseDataInner) SetUserIdNil(b bool)`

 SetUserIdNil sets the value for UserId to be an explicit nil

### UnsetUserId
`func (o *GetAuditLogs200ResponseDataInner) UnsetUserId()`

UnsetUserId ensures that no value is present for UserId, not even an explicit nil
### GetUserEmail

`func (o *GetAuditLogs200ResponseDataInner) GetUserEmail() string`

GetUserEmail returns the UserEmail field if non-nil, zero value otherwise.

### GetUserEmailOk

`func (o *GetAuditLogs200ResponseDataInner) GetUserEmailOk() (*string, bool)`

GetUserEmailOk returns a tuple with the UserEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserEmail

`func (o *GetAuditLogs200ResponseDataInner) SetUserEmail(v string)`

SetUserEmail sets UserEmail field to given value.


### GetUserIpAddress

`func (o *GetAuditLogs200ResponseDataInner) GetUserIpAddress() string`

GetUserIpAddress returns the UserIpAddress field if non-nil, zero value otherwise.

### GetUserIpAddressOk

`func (o *GetAuditLogs200ResponseDataInner) GetUserIpAddressOk() (*string, bool)`

GetUserIpAddressOk returns a tuple with the UserIpAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserIpAddress

`func (o *GetAuditLogs200ResponseDataInner) SetUserIpAddress(v string)`

SetUserIpAddress sets UserIpAddress field to given value.

### HasUserIpAddress

`func (o *GetAuditLogs200ResponseDataInner) HasUserIpAddress() bool`

HasUserIpAddress returns a boolean if a field has been set.

### SetUserIpAddressNil

`func (o *GetAuditLogs200ResponseDataInner) SetUserIpAddressNil(b bool)`

 SetUserIpAddressNil sets the value for UserIpAddress to be an explicit nil

### UnsetUserIpAddress
`func (o *GetAuditLogs200ResponseDataInner) UnsetUserIpAddress()`

UnsetUserIpAddress ensures that no value is present for UserIpAddress, not even an explicit nil
### GetCreatedAt

`func (o *GetAuditLogs200ResponseDataInner) GetCreatedAt() Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetAuditLogs200ResponseDataInner) GetCreatedAtOk() (*Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetAuditLogs200ResponseDataInner) SetCreatedAt(v Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *GetAuditLogs200ResponseDataInner) GetUpdatedAt() Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetAuditLogs200ResponseDataInner) GetUpdatedAtOk() (*Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetAuditLogs200ResponseDataInner) SetUpdatedAt(v Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


