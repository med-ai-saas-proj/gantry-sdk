# ToolMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Role** | Pointer to **string** |  | [optional] [default to "tool"]
**Content** | **string** |  | 
**ToolCallId** | **string** |  | 
**Error** | Pointer to **NullableString** |  | [optional] 
**EncryptedValue** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewToolMessage

`func NewToolMessage(id string, content string, toolCallId string, ) *ToolMessage`

NewToolMessage instantiates a new ToolMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewToolMessageWithDefaults

`func NewToolMessageWithDefaults() *ToolMessage`

NewToolMessageWithDefaults instantiates a new ToolMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ToolMessage) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ToolMessage) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ToolMessage) SetId(v string)`

SetId sets Id field to given value.


### GetRole

`func (o *ToolMessage) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *ToolMessage) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *ToolMessage) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *ToolMessage) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetContent

`func (o *ToolMessage) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *ToolMessage) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *ToolMessage) SetContent(v string)`

SetContent sets Content field to given value.


### GetToolCallId

`func (o *ToolMessage) GetToolCallId() string`

GetToolCallId returns the ToolCallId field if non-nil, zero value otherwise.

### GetToolCallIdOk

`func (o *ToolMessage) GetToolCallIdOk() (*string, bool)`

GetToolCallIdOk returns a tuple with the ToolCallId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolCallId

`func (o *ToolMessage) SetToolCallId(v string)`

SetToolCallId sets ToolCallId field to given value.


### GetError

`func (o *ToolMessage) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ToolMessage) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ToolMessage) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *ToolMessage) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *ToolMessage) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ToolMessage) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetEncryptedValue

`func (o *ToolMessage) GetEncryptedValue() string`

GetEncryptedValue returns the EncryptedValue field if non-nil, zero value otherwise.

### GetEncryptedValueOk

`func (o *ToolMessage) GetEncryptedValueOk() (*string, bool)`

GetEncryptedValueOk returns a tuple with the EncryptedValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncryptedValue

`func (o *ToolMessage) SetEncryptedValue(v string)`

SetEncryptedValue sets EncryptedValue field to given value.

### HasEncryptedValue

`func (o *ToolMessage) HasEncryptedValue() bool`

HasEncryptedValue returns a boolean if a field has been set.

### SetEncryptedValueNil

`func (o *ToolMessage) SetEncryptedValueNil(b bool)`

 SetEncryptedValueNil sets the value for EncryptedValue to be an explicit nil

### UnsetEncryptedValue
`func (o *ToolMessage) UnsetEncryptedValue()`

UnsetEncryptedValue ensures that no value is present for EncryptedValue, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


