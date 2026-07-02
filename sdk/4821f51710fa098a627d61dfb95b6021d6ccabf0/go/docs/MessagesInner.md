# MessagesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Role** | Pointer to **string** |  | [optional] [default to "reasoning"]
**Content** | **string** |  | 
**Name** | Pointer to **string** |  | [optional] 
**EncryptedValue** | Pointer to **string** |  | [optional] 
**ToolCalls** | Pointer to [**[]ToolCall**](ToolCall.md) |  | [optional] 
**ToolCallId** | **string** |  | 
**Error** | Pointer to **string** |  | [optional] 
**ActivityType** | **string** |  | 

## Methods

### NewMessagesInner

`func NewMessagesInner(id string, content string, toolCallId string, activityType string, ) *MessagesInner`

NewMessagesInner instantiates a new MessagesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessagesInnerWithDefaults

`func NewMessagesInnerWithDefaults() *MessagesInner`

NewMessagesInnerWithDefaults instantiates a new MessagesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *MessagesInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MessagesInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MessagesInner) SetId(v string)`

SetId sets Id field to given value.


### GetRole

`func (o *MessagesInner) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *MessagesInner) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *MessagesInner) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *MessagesInner) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetContent

`func (o *MessagesInner) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *MessagesInner) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *MessagesInner) SetContent(v string)`

SetContent sets Content field to given value.


### GetName

`func (o *MessagesInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *MessagesInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *MessagesInner) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *MessagesInner) HasName() bool`

HasName returns a boolean if a field has been set.

### GetEncryptedValue

`func (o *MessagesInner) GetEncryptedValue() string`

GetEncryptedValue returns the EncryptedValue field if non-nil, zero value otherwise.

### GetEncryptedValueOk

`func (o *MessagesInner) GetEncryptedValueOk() (*string, bool)`

GetEncryptedValueOk returns a tuple with the EncryptedValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncryptedValue

`func (o *MessagesInner) SetEncryptedValue(v string)`

SetEncryptedValue sets EncryptedValue field to given value.

### HasEncryptedValue

`func (o *MessagesInner) HasEncryptedValue() bool`

HasEncryptedValue returns a boolean if a field has been set.

### GetToolCalls

`func (o *MessagesInner) GetToolCalls() []ToolCall`

GetToolCalls returns the ToolCalls field if non-nil, zero value otherwise.

### GetToolCallsOk

`func (o *MessagesInner) GetToolCallsOk() (*[]ToolCall, bool)`

GetToolCallsOk returns a tuple with the ToolCalls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolCalls

`func (o *MessagesInner) SetToolCalls(v []ToolCall)`

SetToolCalls sets ToolCalls field to given value.

### HasToolCalls

`func (o *MessagesInner) HasToolCalls() bool`

HasToolCalls returns a boolean if a field has been set.

### GetToolCallId

`func (o *MessagesInner) GetToolCallId() string`

GetToolCallId returns the ToolCallId field if non-nil, zero value otherwise.

### GetToolCallIdOk

`func (o *MessagesInner) GetToolCallIdOk() (*string, bool)`

GetToolCallIdOk returns a tuple with the ToolCallId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolCallId

`func (o *MessagesInner) SetToolCallId(v string)`

SetToolCallId sets ToolCallId field to given value.


### GetError

`func (o *MessagesInner) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *MessagesInner) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *MessagesInner) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *MessagesInner) HasError() bool`

HasError returns a boolean if a field has been set.

### GetActivityType

`func (o *MessagesInner) GetActivityType() string`

GetActivityType returns the ActivityType field if non-nil, zero value otherwise.

### GetActivityTypeOk

`func (o *MessagesInner) GetActivityTypeOk() (*string, bool)`

GetActivityTypeOk returns a tuple with the ActivityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityType

`func (o *MessagesInner) SetActivityType(v string)`

SetActivityType sets ActivityType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


