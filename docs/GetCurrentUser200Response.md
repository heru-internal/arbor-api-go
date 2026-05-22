# GetCurrentUser200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**FirstName** | Pointer to **string** |  | [optional] 
**LastName** | Pointer to **string** |  | [optional] 
**Email** | Pointer to **string** |  | [optional] 
**AccessControls** | Pointer to [**[]GetCurrentUser200ResponseAccessControlsInner**](GetCurrentUser200ResponseAccessControlsInner.md) |  | [optional] 
**CreatedAt** | Pointer to **Time** |  | [optional] 
**UpdatedAt** | Pointer to **Time** |  | [optional] 

## Methods

### NewGetCurrentUser200Response

`func NewGetCurrentUser200Response() *GetCurrentUser200Response`

NewGetCurrentUser200Response instantiates a new GetCurrentUser200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetCurrentUser200ResponseWithDefaults

`func NewGetCurrentUser200ResponseWithDefaults() *GetCurrentUser200Response`

NewGetCurrentUser200ResponseWithDefaults instantiates a new GetCurrentUser200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetCurrentUser200Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetCurrentUser200Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetCurrentUser200Response) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *GetCurrentUser200Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetFirstName

`func (o *GetCurrentUser200Response) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *GetCurrentUser200Response) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *GetCurrentUser200Response) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *GetCurrentUser200Response) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetLastName

`func (o *GetCurrentUser200Response) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *GetCurrentUser200Response) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *GetCurrentUser200Response) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *GetCurrentUser200Response) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetEmail

`func (o *GetCurrentUser200Response) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *GetCurrentUser200Response) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *GetCurrentUser200Response) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *GetCurrentUser200Response) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetAccessControls

`func (o *GetCurrentUser200Response) GetAccessControls() []GetCurrentUser200ResponseAccessControlsInner`

GetAccessControls returns the AccessControls field if non-nil, zero value otherwise.

### GetAccessControlsOk

`func (o *GetCurrentUser200Response) GetAccessControlsOk() (*[]GetCurrentUser200ResponseAccessControlsInner, bool)`

GetAccessControlsOk returns a tuple with the AccessControls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessControls

`func (o *GetCurrentUser200Response) SetAccessControls(v []GetCurrentUser200ResponseAccessControlsInner)`

SetAccessControls sets AccessControls field to given value.

### HasAccessControls

`func (o *GetCurrentUser200Response) HasAccessControls() bool`

HasAccessControls returns a boolean if a field has been set.

### GetCreatedAt

`func (o *GetCurrentUser200Response) GetCreatedAt() Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetCurrentUser200Response) GetCreatedAtOk() (*Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetCurrentUser200Response) SetCreatedAt(v Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *GetCurrentUser200Response) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *GetCurrentUser200Response) GetUpdatedAt() Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetCurrentUser200Response) GetUpdatedAtOk() (*Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetCurrentUser200Response) SetUpdatedAt(v Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *GetCurrentUser200Response) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


