# CreateAppBundle201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Unique identifier for the app bundle | [optional] 
**Label** | Pointer to **NullableString** | Auto-generated label of the app bundle. First bundle has no label, subsequent bundles get &#39;Original&#39; and &#39;Copy N&#39; labels. | [optional] 
**Status** | Pointer to **string** | Current status of the app bundle | [optional] 
**AppBuild** | Pointer to [**CreateAppBundle201ResponseAppBuild**](CreateAppBundle201ResponseAppBuild.md) |  | [optional] 
**CreatedAt** | Pointer to **Time** | Timestamp when the bundle was created | [optional] 
**UpdatedAt** | Pointer to **Time** | Timestamp when the bundle was last updated | [optional] 

## Methods

### NewCreateAppBundle201Response

`func NewCreateAppBundle201Response() *CreateAppBundle201Response`

NewCreateAppBundle201Response instantiates a new CreateAppBundle201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateAppBundle201ResponseWithDefaults

`func NewCreateAppBundle201ResponseWithDefaults() *CreateAppBundle201Response`

NewCreateAppBundle201ResponseWithDefaults instantiates a new CreateAppBundle201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateAppBundle201Response) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateAppBundle201Response) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateAppBundle201Response) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CreateAppBundle201Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLabel

`func (o *CreateAppBundle201Response) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *CreateAppBundle201Response) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *CreateAppBundle201Response) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *CreateAppBundle201Response) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### SetLabelNil

`func (o *CreateAppBundle201Response) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *CreateAppBundle201Response) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil
### GetStatus

`func (o *CreateAppBundle201Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CreateAppBundle201Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CreateAppBundle201Response) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CreateAppBundle201Response) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetAppBuild

`func (o *CreateAppBundle201Response) GetAppBuild() CreateAppBundle201ResponseAppBuild`

GetAppBuild returns the AppBuild field if non-nil, zero value otherwise.

### GetAppBuildOk

`func (o *CreateAppBundle201Response) GetAppBuildOk() (*CreateAppBundle201ResponseAppBuild, bool)`

GetAppBuildOk returns a tuple with the AppBuild field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppBuild

`func (o *CreateAppBundle201Response) SetAppBuild(v CreateAppBundle201ResponseAppBuild)`

SetAppBuild sets AppBuild field to given value.

### HasAppBuild

`func (o *CreateAppBundle201Response) HasAppBuild() bool`

HasAppBuild returns a boolean if a field has been set.

### GetCreatedAt

`func (o *CreateAppBundle201Response) GetCreatedAt() Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateAppBundle201Response) GetCreatedAtOk() (*Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateAppBundle201Response) SetCreatedAt(v Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *CreateAppBundle201Response) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *CreateAppBundle201Response) GetUpdatedAt() Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CreateAppBundle201Response) GetUpdatedAtOk() (*Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CreateAppBundle201Response) SetUpdatedAt(v Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *CreateAppBundle201Response) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


