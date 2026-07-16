# ToolCallChunkEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "TOOL_CALL_CHUNK"]
**Timestamp** | Pointer to **NullableInt32** |  | [optional] 
**RawEvent** | Pointer to [**NullableAnyOf**](anyOf&lt;&gt;.md) |  | [optional] 
**ToolCallId** | Pointer to **NullableString** |  | [optional] 
**ToolCallName** | Pointer to **NullableString** |  | [optional] 
**ParentMessageId** | Pointer to **NullableString** |  | [optional] 
**Delta** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewToolCallChunkEvent

`func NewToolCallChunkEvent() *ToolCallChunkEvent`

NewToolCallChunkEvent instantiates a new ToolCallChunkEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewToolCallChunkEventWithDefaults

`func NewToolCallChunkEventWithDefaults() *ToolCallChunkEvent`

NewToolCallChunkEventWithDefaults instantiates a new ToolCallChunkEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ToolCallChunkEvent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ToolCallChunkEvent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ToolCallChunkEvent) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ToolCallChunkEvent) HasType() bool`

HasType returns a boolean if a field has been set.

### GetTimestamp

`func (o *ToolCallChunkEvent) GetTimestamp() int32`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *ToolCallChunkEvent) GetTimestampOk() (*int32, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *ToolCallChunkEvent) SetTimestamp(v int32)`

SetTimestamp sets Timestamp field to given value.

### HasTimestamp

`func (o *ToolCallChunkEvent) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.

### SetTimestampNil

`func (o *ToolCallChunkEvent) SetTimestampNil(b bool)`

 SetTimestampNil sets the value for Timestamp to be an explicit nil

### UnsetTimestamp
`func (o *ToolCallChunkEvent) UnsetTimestamp()`

UnsetTimestamp ensures that no value is present for Timestamp, not even an explicit nil
### GetRawEvent

`func (o *ToolCallChunkEvent) GetRawEvent() AnyOf`

GetRawEvent returns the RawEvent field if non-nil, zero value otherwise.

### GetRawEventOk

`func (o *ToolCallChunkEvent) GetRawEventOk() (*AnyOf, bool)`

GetRawEventOk returns a tuple with the RawEvent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawEvent

`func (o *ToolCallChunkEvent) SetRawEvent(v AnyOf)`

SetRawEvent sets RawEvent field to given value.

### HasRawEvent

`func (o *ToolCallChunkEvent) HasRawEvent() bool`

HasRawEvent returns a boolean if a field has been set.

### SetRawEventNil

`func (o *ToolCallChunkEvent) SetRawEventNil(b bool)`

 SetRawEventNil sets the value for RawEvent to be an explicit nil

### UnsetRawEvent
`func (o *ToolCallChunkEvent) UnsetRawEvent()`

UnsetRawEvent ensures that no value is present for RawEvent, not even an explicit nil
### GetToolCallId

`func (o *ToolCallChunkEvent) GetToolCallId() string`

GetToolCallId returns the ToolCallId field if non-nil, zero value otherwise.

### GetToolCallIdOk

`func (o *ToolCallChunkEvent) GetToolCallIdOk() (*string, bool)`

GetToolCallIdOk returns a tuple with the ToolCallId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolCallId

`func (o *ToolCallChunkEvent) SetToolCallId(v string)`

SetToolCallId sets ToolCallId field to given value.

### HasToolCallId

`func (o *ToolCallChunkEvent) HasToolCallId() bool`

HasToolCallId returns a boolean if a field has been set.

### SetToolCallIdNil

`func (o *ToolCallChunkEvent) SetToolCallIdNil(b bool)`

 SetToolCallIdNil sets the value for ToolCallId to be an explicit nil

### UnsetToolCallId
`func (o *ToolCallChunkEvent) UnsetToolCallId()`

UnsetToolCallId ensures that no value is present for ToolCallId, not even an explicit nil
### GetToolCallName

`func (o *ToolCallChunkEvent) GetToolCallName() string`

GetToolCallName returns the ToolCallName field if non-nil, zero value otherwise.

### GetToolCallNameOk

`func (o *ToolCallChunkEvent) GetToolCallNameOk() (*string, bool)`

GetToolCallNameOk returns a tuple with the ToolCallName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolCallName

`func (o *ToolCallChunkEvent) SetToolCallName(v string)`

SetToolCallName sets ToolCallName field to given value.

### HasToolCallName

`func (o *ToolCallChunkEvent) HasToolCallName() bool`

HasToolCallName returns a boolean if a field has been set.

### SetToolCallNameNil

`func (o *ToolCallChunkEvent) SetToolCallNameNil(b bool)`

 SetToolCallNameNil sets the value for ToolCallName to be an explicit nil

### UnsetToolCallName
`func (o *ToolCallChunkEvent) UnsetToolCallName()`

UnsetToolCallName ensures that no value is present for ToolCallName, not even an explicit nil
### GetParentMessageId

`func (o *ToolCallChunkEvent) GetParentMessageId() string`

GetParentMessageId returns the ParentMessageId field if non-nil, zero value otherwise.

### GetParentMessageIdOk

`func (o *ToolCallChunkEvent) GetParentMessageIdOk() (*string, bool)`

GetParentMessageIdOk returns a tuple with the ParentMessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentMessageId

`func (o *ToolCallChunkEvent) SetParentMessageId(v string)`

SetParentMessageId sets ParentMessageId field to given value.

### HasParentMessageId

`func (o *ToolCallChunkEvent) HasParentMessageId() bool`

HasParentMessageId returns a boolean if a field has been set.

### SetParentMessageIdNil

`func (o *ToolCallChunkEvent) SetParentMessageIdNil(b bool)`

 SetParentMessageIdNil sets the value for ParentMessageId to be an explicit nil

### UnsetParentMessageId
`func (o *ToolCallChunkEvent) UnsetParentMessageId()`

UnsetParentMessageId ensures that no value is present for ParentMessageId, not even an explicit nil
### GetDelta

`func (o *ToolCallChunkEvent) GetDelta() string`

GetDelta returns the Delta field if non-nil, zero value otherwise.

### GetDeltaOk

`func (o *ToolCallChunkEvent) GetDeltaOk() (*string, bool)`

GetDeltaOk returns a tuple with the Delta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelta

`func (o *ToolCallChunkEvent) SetDelta(v string)`

SetDelta sets Delta field to given value.

### HasDelta

`func (o *ToolCallChunkEvent) HasDelta() bool`

HasDelta returns a boolean if a field has been set.

### SetDeltaNil

`func (o *ToolCallChunkEvent) SetDeltaNil(b bool)`

 SetDeltaNil sets the value for Delta to be an explicit nil

### UnsetDelta
`func (o *ToolCallChunkEvent) UnsetDelta()`

UnsetDelta ensures that no value is present for Delta, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


