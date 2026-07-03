# ReasoningMessageChunkEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "REASONING_MESSAGE_CHUNK"]
**Timestamp** | Pointer to **NullableInt32** |  | [optional] 
**RawEvent** | Pointer to [**NullableAnyOf**](anyOf&lt;&gt;.md) |  | [optional] 
**MessageId** | Pointer to **NullableString** |  | [optional] 
**Delta** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewReasoningMessageChunkEvent

`func NewReasoningMessageChunkEvent() *ReasoningMessageChunkEvent`

NewReasoningMessageChunkEvent instantiates a new ReasoningMessageChunkEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReasoningMessageChunkEventWithDefaults

`func NewReasoningMessageChunkEventWithDefaults() *ReasoningMessageChunkEvent`

NewReasoningMessageChunkEventWithDefaults instantiates a new ReasoningMessageChunkEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ReasoningMessageChunkEvent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ReasoningMessageChunkEvent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ReasoningMessageChunkEvent) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ReasoningMessageChunkEvent) HasType() bool`

HasType returns a boolean if a field has been set.

### GetTimestamp

`func (o *ReasoningMessageChunkEvent) GetTimestamp() int32`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *ReasoningMessageChunkEvent) GetTimestampOk() (*int32, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *ReasoningMessageChunkEvent) SetTimestamp(v int32)`

SetTimestamp sets Timestamp field to given value.

### HasTimestamp

`func (o *ReasoningMessageChunkEvent) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.

### SetTimestampNil

`func (o *ReasoningMessageChunkEvent) SetTimestampNil(b bool)`

 SetTimestampNil sets the value for Timestamp to be an explicit nil

### UnsetTimestamp
`func (o *ReasoningMessageChunkEvent) UnsetTimestamp()`

UnsetTimestamp ensures that no value is present for Timestamp, not even an explicit nil
### GetRawEvent

`func (o *ReasoningMessageChunkEvent) GetRawEvent() AnyOf`

GetRawEvent returns the RawEvent field if non-nil, zero value otherwise.

### GetRawEventOk

`func (o *ReasoningMessageChunkEvent) GetRawEventOk() (*AnyOf, bool)`

GetRawEventOk returns a tuple with the RawEvent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawEvent

`func (o *ReasoningMessageChunkEvent) SetRawEvent(v AnyOf)`

SetRawEvent sets RawEvent field to given value.

### HasRawEvent

`func (o *ReasoningMessageChunkEvent) HasRawEvent() bool`

HasRawEvent returns a boolean if a field has been set.

### SetRawEventNil

`func (o *ReasoningMessageChunkEvent) SetRawEventNil(b bool)`

 SetRawEventNil sets the value for RawEvent to be an explicit nil

### UnsetRawEvent
`func (o *ReasoningMessageChunkEvent) UnsetRawEvent()`

UnsetRawEvent ensures that no value is present for RawEvent, not even an explicit nil
### GetMessageId

`func (o *ReasoningMessageChunkEvent) GetMessageId() string`

GetMessageId returns the MessageId field if non-nil, zero value otherwise.

### GetMessageIdOk

`func (o *ReasoningMessageChunkEvent) GetMessageIdOk() (*string, bool)`

GetMessageIdOk returns a tuple with the MessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageId

`func (o *ReasoningMessageChunkEvent) SetMessageId(v string)`

SetMessageId sets MessageId field to given value.

### HasMessageId

`func (o *ReasoningMessageChunkEvent) HasMessageId() bool`

HasMessageId returns a boolean if a field has been set.

### SetMessageIdNil

`func (o *ReasoningMessageChunkEvent) SetMessageIdNil(b bool)`

 SetMessageIdNil sets the value for MessageId to be an explicit nil

### UnsetMessageId
`func (o *ReasoningMessageChunkEvent) UnsetMessageId()`

UnsetMessageId ensures that no value is present for MessageId, not even an explicit nil
### GetDelta

`func (o *ReasoningMessageChunkEvent) GetDelta() string`

GetDelta returns the Delta field if non-nil, zero value otherwise.

### GetDeltaOk

`func (o *ReasoningMessageChunkEvent) GetDeltaOk() (*string, bool)`

GetDeltaOk returns a tuple with the Delta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelta

`func (o *ReasoningMessageChunkEvent) SetDelta(v string)`

SetDelta sets Delta field to given value.

### HasDelta

`func (o *ReasoningMessageChunkEvent) HasDelta() bool`

HasDelta returns a boolean if a field has been set.

### SetDeltaNil

`func (o *ReasoningMessageChunkEvent) SetDeltaNil(b bool)`

 SetDeltaNil sets the value for Delta to be an explicit nil

### UnsetDelta
`func (o *ReasoningMessageChunkEvent) UnsetDelta()`

UnsetDelta ensures that no value is present for Delta, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


