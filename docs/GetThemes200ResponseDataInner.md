# GetThemes200ResponseDataInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Name** | **string** | The name of the theme | 
**IsSystemOwned** | **bool** | Whether this theme is owned by the system (true) or by the organization (false) | 
**Background1** | **string** | Primary background color (hex format) | 
**Background2** | **string** | Secondary background color (hex format) | 
**Text** | **string** | Text color (hex format) | 
**Accent1** | **string** | Primary accent color (hex format) | 
**Accent2** | **string** | Secondary accent color (hex format) | 
**Accent3** | **string** | Tertiary accent color (hex format) | 
**CreatedAt** | Pointer to **Time** |  | [optional] 
**UpdatedAt** | Pointer to **Time** |  | [optional] 

## Methods

### NewGetThemes200ResponseDataInner

`func NewGetThemes200ResponseDataInner(id string, name string, isSystemOwned bool, background1 string, background2 string, text string, accent1 string, accent2 string, accent3 string, ) *GetThemes200ResponseDataInner`

NewGetThemes200ResponseDataInner instantiates a new GetThemes200ResponseDataInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetThemes200ResponseDataInnerWithDefaults

`func NewGetThemes200ResponseDataInnerWithDefaults() *GetThemes200ResponseDataInner`

NewGetThemes200ResponseDataInnerWithDefaults instantiates a new GetThemes200ResponseDataInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetThemes200ResponseDataInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetThemes200ResponseDataInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetThemes200ResponseDataInner) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *GetThemes200ResponseDataInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GetThemes200ResponseDataInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GetThemes200ResponseDataInner) SetName(v string)`

SetName sets Name field to given value.


### GetIsSystemOwned

`func (o *GetThemes200ResponseDataInner) GetIsSystemOwned() bool`

GetIsSystemOwned returns the IsSystemOwned field if non-nil, zero value otherwise.

### GetIsSystemOwnedOk

`func (o *GetThemes200ResponseDataInner) GetIsSystemOwnedOk() (*bool, bool)`

GetIsSystemOwnedOk returns a tuple with the IsSystemOwned field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSystemOwned

`func (o *GetThemes200ResponseDataInner) SetIsSystemOwned(v bool)`

SetIsSystemOwned sets IsSystemOwned field to given value.


### GetBackground1

`func (o *GetThemes200ResponseDataInner) GetBackground1() string`

GetBackground1 returns the Background1 field if non-nil, zero value otherwise.

### GetBackground1Ok

`func (o *GetThemes200ResponseDataInner) GetBackground1Ok() (*string, bool)`

GetBackground1Ok returns a tuple with the Background1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackground1

`func (o *GetThemes200ResponseDataInner) SetBackground1(v string)`

SetBackground1 sets Background1 field to given value.


### GetBackground2

`func (o *GetThemes200ResponseDataInner) GetBackground2() string`

GetBackground2 returns the Background2 field if non-nil, zero value otherwise.

### GetBackground2Ok

`func (o *GetThemes200ResponseDataInner) GetBackground2Ok() (*string, bool)`

GetBackground2Ok returns a tuple with the Background2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackground2

`func (o *GetThemes200ResponseDataInner) SetBackground2(v string)`

SetBackground2 sets Background2 field to given value.


### GetText

`func (o *GetThemes200ResponseDataInner) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *GetThemes200ResponseDataInner) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *GetThemes200ResponseDataInner) SetText(v string)`

SetText sets Text field to given value.


### GetAccent1

`func (o *GetThemes200ResponseDataInner) GetAccent1() string`

GetAccent1 returns the Accent1 field if non-nil, zero value otherwise.

### GetAccent1Ok

`func (o *GetThemes200ResponseDataInner) GetAccent1Ok() (*string, bool)`

GetAccent1Ok returns a tuple with the Accent1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccent1

`func (o *GetThemes200ResponseDataInner) SetAccent1(v string)`

SetAccent1 sets Accent1 field to given value.


### GetAccent2

`func (o *GetThemes200ResponseDataInner) GetAccent2() string`

GetAccent2 returns the Accent2 field if non-nil, zero value otherwise.

### GetAccent2Ok

`func (o *GetThemes200ResponseDataInner) GetAccent2Ok() (*string, bool)`

GetAccent2Ok returns a tuple with the Accent2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccent2

`func (o *GetThemes200ResponseDataInner) SetAccent2(v string)`

SetAccent2 sets Accent2 field to given value.


### GetAccent3

`func (o *GetThemes200ResponseDataInner) GetAccent3() string`

GetAccent3 returns the Accent3 field if non-nil, zero value otherwise.

### GetAccent3Ok

`func (o *GetThemes200ResponseDataInner) GetAccent3Ok() (*string, bool)`

GetAccent3Ok returns a tuple with the Accent3 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccent3

`func (o *GetThemes200ResponseDataInner) SetAccent3(v string)`

SetAccent3 sets Accent3 field to given value.


### GetCreatedAt

`func (o *GetThemes200ResponseDataInner) GetCreatedAt() Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *GetThemes200ResponseDataInner) GetCreatedAtOk() (*Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *GetThemes200ResponseDataInner) SetCreatedAt(v Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *GetThemes200ResponseDataInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *GetThemes200ResponseDataInner) GetUpdatedAt() Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetThemes200ResponseDataInner) GetUpdatedAtOk() (*Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetThemes200ResponseDataInner) SetUpdatedAt(v Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *GetThemes200ResponseDataInner) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


