# GetGroupDeviceExperience200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **NullableString** |  | 
**Mode** | **string** |  | 
**VisibleContents** | [**[]GetGroupDeviceExperience200ResponseOneOfVisibleContentsInner**](GetGroupDeviceExperience200ResponseOneOfVisibleContentsInner.md) |  | 
**CreatedAt** | **NullableTime** |  | 
**UpdatedAt** | **NullableTime** |  | 
**LauncherContent** | [**NullableGetGroupDeviceExperience200ResponseOneOf1LauncherContent**](GetGroupDeviceExperience200ResponseOneOf1LauncherContent.md) |  | 

## Methods

### NewGetGroupDeviceExperience200Response

`func NewGetGroupDeviceExperience200Response(id NullableString, mode string, visibleContents []GetGroupDeviceExperience200ResponseOneOfVisibleContentsInner, createdAt NullableTime, updatedAt NullableTime, launcherContent NullableGetGroupDeviceExperience200ResponseOneOf1LauncherContent, ) *GetGroupDeviceExperience200Response`

NewGetGroupDeviceExperience200Response instantiates a new GetGroupDeviceExperience200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetGroupDeviceExperience200ResponseWithDefaults

`func NewGetGroupDeviceExperience200ResponseWithDefaults() *GetGroupDeviceExperience200Response`

NewGetGroupDeviceExperience200ResponseWithDefaults instantiates a new GetGroupDeviceExperience200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetGroupDeviceExperience200Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetGroupDeviceExperience200Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetGroupDeviceExperience200Response) SetId(v string)`

SetId sets Id field to given value.


### SetIdNil

`func (o *GetGroupDeviceExperience200Response) SetIdNil(b bool)`

 SetIdNil sets the value for Id to be an explicit nil

### UnsetId
`func (o *GetGroupDeviceExperience200Response) UnsetId()`

UnsetId ensures that no value is present for Id, not even an explicit nil
### GetMode

`func (o *GetGroupDeviceExperience200Response) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *GetGroupDeviceExperience200Response) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *GetGroupDeviceExperience200Response) SetMode(v string)`

SetMode sets Mode field to given value.


### GetVisibleContents

`func (o *GetGroupDeviceExperience200Response) GetVisibleContents() []GetGroupDeviceExperience200ResponseOneOfVisibleContentsInner`

GetVisibleContents returns the VisibleContents field if non-nil, zero value otherwise.

### GetVisibleContentsOk

`func (o *GetGroupDeviceExperience200Response) GetVisibleContentsOk() (*[]GetGroupDeviceExperience200ResponseOneOfVisibleContentsInner, bool)`

GetVisibleContentsOk returns a tuple with the VisibleContents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibleContents

`func (o *GetGroupDeviceExperience200Response) SetVisibleContents(v []GetGroupDeviceExperience200ResponseOneOfVisibleContentsInner)`

SetVisibleContents sets VisibleContents field to given value.


### GetCreatedAt

`func (o *GetGroupDeviceExperience200Response) GetCreatedAt() Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetGroupDeviceExperience200Response) GetCreatedAtOk() (*Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetGroupDeviceExperience200Response) SetCreatedAt(v Time)`

SetCreatedAt sets CreatedAt field to given value.


### SetCreatedAtNil

`func (o *GetGroupDeviceExperience200Response) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *GetGroupDeviceExperience200Response) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetUpdatedAt

`func (o *GetGroupDeviceExperience200Response) GetUpdatedAt() Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetGroupDeviceExperience200Response) GetUpdatedAtOk() (*Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetGroupDeviceExperience200Response) SetUpdatedAt(v Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### SetUpdatedAtNil

`func (o *GetGroupDeviceExperience200Response) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *GetGroupDeviceExperience200Response) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetLauncherContent

`func (o *GetGroupDeviceExperience200Response) GetLauncherContent() GetGroupDeviceExperience200ResponseOneOf1LauncherContent`

GetLauncherContent returns the LauncherContent field if non-nil, zero value otherwise.

### GetLauncherContentOk

`func (o *GetGroupDeviceExperience200Response) GetLauncherContentOk() (*GetGroupDeviceExperience200ResponseOneOf1LauncherContent, bool)`

GetLauncherContentOk returns a tuple with the LauncherContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLauncherContent

`func (o *GetGroupDeviceExperience200Response) SetLauncherContent(v GetGroupDeviceExperience200ResponseOneOf1LauncherContent)`

SetLauncherContent sets LauncherContent field to given value.


### SetLauncherContentNil

`func (o *GetGroupDeviceExperience200Response) SetLauncherContentNil(b bool)`

 SetLauncherContentNil sets the value for LauncherContent to be an explicit nil

### UnsetLauncherContent
`func (o *GetGroupDeviceExperience200Response) UnsetLauncherContent()`

UnsetLauncherContent ensures that no value is present for LauncherContent, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


