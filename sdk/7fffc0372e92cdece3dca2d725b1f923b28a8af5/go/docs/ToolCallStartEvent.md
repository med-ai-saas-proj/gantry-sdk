# ToolCallStartEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "TOOL_CALL_START"]
**Timestamp** | Pointer to **NullableInt32** |  | [optional] 
**RawEvent** | Pointer to [**NullableAnyOf**](anyOf&lt;&gt;.md) |  | [optional] 
**ToolCallId** | **string** |  | 
**ToolCallName** | **string** |  | 
**ParentMessageId** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewToolCallStartEvent

`func NewToolCallStartEvent(toolCallId string, toolCallName string, ) *ToolCallStartEvent`

NewToolCallStartEvent instantiates a new ToolCallStartEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewToolCallStartEventWithDefaults

`func NewToolCallStartEventWithDefaults() *ToolCallStartEvent`

NewToolCallStartEventWithDefaults instantiates a new ToolCallStartEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ToolCallStartEvent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ToolCallStartEvent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ToolCallStartEvent) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ToolCallStartEvent) HasType() bool`

HasType returns a boolean if a field has been set.

### GetTimestamp

`func (o *ToolCallStartEvent) GetTimestamp() int32`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *ToolCallStartEvent) GetTimestampOk() (*int32, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *ToolCallStartEvent) SetTimestamp(v int32)`

SetTimestamp sets Timestamp field to given value.

### HasTimestamp

`func (o *ToolCallStartEvent) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.

### SetTimestampNil

`func (o *ToolCallStartEvent) SetTimestampNil(b bool)`

 SetTimestampNil sets the value for Timestamp to be an explicit nil

### UnsetTimestamp
`func (o *ToolCallStartEvent) UnsetTimestamp()`

UnsetTimestamp ensures that no value is present for Timestamp, not even an explicit nil
### GetRawEvent

`func (o *ToolCallStartEvent) GetRawEvent() AnyOf`

GetRawEvent returns the RawEvent field if non-nil, zero value otherwise.

### GetRawEventOk

`func (o *ToolCallStartEvent) GetRawEventOk() (*AnyOf, bool)`

GetRawEventOk returns a tuple with the RawEvent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawEvent

`func (o *ToolCallStartEvent) SetRawEvent(v AnyOf)`

SetRawEvent sets RawEvent field to given value.

### HasRawEvent

`func (o *ToolCallStartEvent) HasRawEvent() bool`

HasRawEvent returns a boolean if a field has been set.

### SetRawEventNil

`func (o *ToolCallStartEvent) SetRawEventNil(b bool)`

 SetRawEventNil sets the value for RawEvent to be an explicit nil

### UnsetRawEvent
`func (o *ToolCallStartEvent) UnsetRawEvent()`

UnsetRawEvent ensures that no value is present for RawEvent, not even an explicit nil
### GetToolCallId

`func (o *ToolCallStartEvent) GetToolCallId() string`

GetToolCallId returns the ToolCallId field if non-nil, zero value otherwise.

### GetToolCallIdOk

`func (o *ToolCallStartEvent) GetToolCallIdOk() (*string, bool)`

GetToolCallIdOk returns a tuple with the ToolCallId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolCallId

`func (o *ToolCallStartEvent) SetToolCallId(v string)`

SetToolCallId sets ToolCallId field to given value.


### GetToolCallName

`func (o *ToolCallStartEvent) GetToolCallName() string`

GetToolCallName returns the ToolCallName field if non-nil, zero value otherwise.

### GetToolCallNameOk

`func (o *ToolCallStartEvent) GetToolCallNameOk() (*string, bool)`

GetToolCallNameOk returns a tuple with the ToolCallName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolCallName

`func (o *ToolCallStartEvent) SetToolCallName(v string)`

SetToolCallName sets ToolCallName field to given value.


### GetParentMessageId

`func (o *ToolCallStartEvent) GetParentMessageId() string`

GetParentMessageId returns the ParentMessageId field if non-nil, zero value otherwise.

### GetParentMessageIdOk

`func (o *ToolCallStartEvent) GetParentMessageIdOk() (*string, bool)`

GetParentMessageIdOk returns a tuple with the ParentMessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentMessageId

`func (o *ToolCallStartEvent) SetParentMessageId(v string)`

SetParentMessageId sets ParentMessageId field to given value.

### HasParentMessageId

`func (o *ToolCallStartEvent) HasParentMessageId() bool`

HasParentMessageId returns a boolean if a field has been set.

### SetParentMessageIdNil

`func (o *ToolCallStartEvent) SetParentMessageIdNil(b bool)`

 SetParentMessageIdNil sets the value for ParentMessageId to be an explicit nil

### UnsetParentMessageId
`func (o *ToolCallStartEvent) UnsetParentMessageId()`

UnsetParentMessageId ensures that no value is present for ParentMessageId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


