# AssistantMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Role** | Pointer to **string** |  | [optional] [default to "assistant"]
**Content** | Pointer to **NullableString** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 
**EncryptedValue** | Pointer to **NullableString** |  | [optional] 
**ToolCalls** | Pointer to [**[]ToolCall**](ToolCall.md) |  | [optional] 

## Methods

### NewAssistantMessage

`func NewAssistantMessage(id string, ) *AssistantMessage`

NewAssistantMessage instantiates a new AssistantMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssistantMessageWithDefaults

`func NewAssistantMessageWithDefaults() *AssistantMessage`

NewAssistantMessageWithDefaults instantiates a new AssistantMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AssistantMessage) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AssistantMessage) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AssistantMessage) SetId(v string)`

SetId sets Id field to given value.


### GetRole

`func (o *AssistantMessage) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *AssistantMessage) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *AssistantMessage) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *AssistantMessage) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetContent

`func (o *AssistantMessage) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *AssistantMessage) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *AssistantMessage) SetContent(v string)`

SetContent sets Content field to given value.

### HasContent

`func (o *AssistantMessage) HasContent() bool`

HasContent returns a boolean if a field has been set.

### SetContentNil

`func (o *AssistantMessage) SetContentNil(b bool)`

 SetContentNil sets the value for Content to be an explicit nil

### UnsetContent
`func (o *AssistantMessage) UnsetContent()`

UnsetContent ensures that no value is present for Content, not even an explicit nil
### GetName

`func (o *AssistantMessage) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AssistantMessage) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AssistantMessage) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *AssistantMessage) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *AssistantMessage) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *AssistantMessage) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetEncryptedValue

`func (o *AssistantMessage) GetEncryptedValue() string`

GetEncryptedValue returns the EncryptedValue field if non-nil, zero value otherwise.

### GetEncryptedValueOk

`func (o *AssistantMessage) GetEncryptedValueOk() (*string, bool)`

GetEncryptedValueOk returns a tuple with the EncryptedValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncryptedValue

`func (o *AssistantMessage) SetEncryptedValue(v string)`

SetEncryptedValue sets EncryptedValue field to given value.

### HasEncryptedValue

`func (o *AssistantMessage) HasEncryptedValue() bool`

HasEncryptedValue returns a boolean if a field has been set.

### SetEncryptedValueNil

`func (o *AssistantMessage) SetEncryptedValueNil(b bool)`

 SetEncryptedValueNil sets the value for EncryptedValue to be an explicit nil

### UnsetEncryptedValue
`func (o *AssistantMessage) UnsetEncryptedValue()`

UnsetEncryptedValue ensures that no value is present for EncryptedValue, not even an explicit nil
### GetToolCalls

`func (o *AssistantMessage) GetToolCalls() []ToolCall`

GetToolCalls returns the ToolCalls field if non-nil, zero value otherwise.

### GetToolCallsOk

`func (o *AssistantMessage) GetToolCallsOk() (*[]ToolCall, bool)`

GetToolCallsOk returns a tuple with the ToolCalls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolCalls

`func (o *AssistantMessage) SetToolCalls(v []ToolCall)`

SetToolCalls sets ToolCalls field to given value.

### HasToolCalls

`func (o *AssistantMessage) HasToolCalls() bool`

HasToolCalls returns a boolean if a field has been set.

### SetToolCallsNil

`func (o *AssistantMessage) SetToolCallsNil(b bool)`

 SetToolCallsNil sets the value for ToolCalls to be an explicit nil

### UnsetToolCalls
`func (o *AssistantMessage) UnsetToolCalls()`

UnsetToolCalls ensures that no value is present for ToolCalls, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


