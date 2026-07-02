# DeveloperMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Role** | Pointer to **string** |  | [optional] [default to "developer"]
**Content** | **string** |  | 
**Name** | Pointer to **NullableString** |  | [optional] 
**EncryptedValue** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewDeveloperMessage

`func NewDeveloperMessage(id string, content string, ) *DeveloperMessage`

NewDeveloperMessage instantiates a new DeveloperMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeveloperMessageWithDefaults

`func NewDeveloperMessageWithDefaults() *DeveloperMessage`

NewDeveloperMessageWithDefaults instantiates a new DeveloperMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DeveloperMessage) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DeveloperMessage) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DeveloperMessage) SetId(v string)`

SetId sets Id field to given value.


### GetRole

`func (o *DeveloperMessage) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *DeveloperMessage) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *DeveloperMessage) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *DeveloperMessage) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetContent

`func (o *DeveloperMessage) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *DeveloperMessage) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *DeveloperMessage) SetContent(v string)`

SetContent sets Content field to given value.


### GetName

`func (o *DeveloperMessage) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *DeveloperMessage) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *DeveloperMessage) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *DeveloperMessage) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *DeveloperMessage) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *DeveloperMessage) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetEncryptedValue

`func (o *DeveloperMessage) GetEncryptedValue() string`

GetEncryptedValue returns the EncryptedValue field if non-nil, zero value otherwise.

### GetEncryptedValueOk

`func (o *DeveloperMessage) GetEncryptedValueOk() (*string, bool)`

GetEncryptedValueOk returns a tuple with the EncryptedValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncryptedValue

`func (o *DeveloperMessage) SetEncryptedValue(v string)`

SetEncryptedValue sets EncryptedValue field to given value.

### HasEncryptedValue

`func (o *DeveloperMessage) HasEncryptedValue() bool`

HasEncryptedValue returns a boolean if a field has been set.

### SetEncryptedValueNil

`func (o *DeveloperMessage) SetEncryptedValueNil(b bool)`

 SetEncryptedValueNil sets the value for EncryptedValue to be an explicit nil

### UnsetEncryptedValue
`func (o *DeveloperMessage) UnsetEncryptedValue()`

UnsetEncryptedValue ensures that no value is present for EncryptedValue, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


