# TextMessageChunkEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "TEXT_MESSAGE_CHUNK"]
**Timestamp** | Pointer to **NullableInt32** |  | [optional] 
**RawEvent** | Pointer to [**NullableAnyOf**](anyOf&lt;&gt;.md) |  | [optional] 
**MessageId** | Pointer to **NullableString** |  | [optional] 
**Role** | Pointer to **NullableString** |  | [optional] 
**Delta** | Pointer to **NullableString** |  | [optional] 
**Name** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewTextMessageChunkEvent

`func NewTextMessageChunkEvent() *TextMessageChunkEvent`

NewTextMessageChunkEvent instantiates a new TextMessageChunkEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTextMessageChunkEventWithDefaults

`func NewTextMessageChunkEventWithDefaults() *TextMessageChunkEvent`

NewTextMessageChunkEventWithDefaults instantiates a new TextMessageChunkEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *TextMessageChunkEvent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TextMessageChunkEvent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TextMessageChunkEvent) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *TextMessageChunkEvent) HasType() bool`

HasType returns a boolean if a field has been set.

### GetTimestamp

`func (o *TextMessageChunkEvent) GetTimestamp() int32`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *TextMessageChunkEvent) GetTimestampOk() (*int32, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *TextMessageChunkEvent) SetTimestamp(v int32)`

SetTimestamp sets Timestamp field to given value.

### HasTimestamp

`func (o *TextMessageChunkEvent) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.

### SetTimestampNil

`func (o *TextMessageChunkEvent) SetTimestampNil(b bool)`

 SetTimestampNil sets the value for Timestamp to be an explicit nil

### UnsetTimestamp
`func (o *TextMessageChunkEvent) UnsetTimestamp()`

UnsetTimestamp ensures that no value is present for Timestamp, not even an explicit nil
### GetRawEvent

`func (o *TextMessageChunkEvent) GetRawEvent() AnyOf`

GetRawEvent returns the RawEvent field if non-nil, zero value otherwise.

### GetRawEventOk

`func (o *TextMessageChunkEvent) GetRawEventOk() (*AnyOf, bool)`

GetRawEventOk returns a tuple with the RawEvent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawEvent

`func (o *TextMessageChunkEvent) SetRawEvent(v AnyOf)`

SetRawEvent sets RawEvent field to given value.

### HasRawEvent

`func (o *TextMessageChunkEvent) HasRawEvent() bool`

HasRawEvent returns a boolean if a field has been set.

### SetRawEventNil

`func (o *TextMessageChunkEvent) SetRawEventNil(b bool)`

 SetRawEventNil sets the value for RawEvent to be an explicit nil

### UnsetRawEvent
`func (o *TextMessageChunkEvent) UnsetRawEvent()`

UnsetRawEvent ensures that no value is present for RawEvent, not even an explicit nil
### GetMessageId

`func (o *TextMessageChunkEvent) GetMessageId() string`

GetMessageId returns the MessageId field if non-nil, zero value otherwise.

### GetMessageIdOk

`func (o *TextMessageChunkEvent) GetMessageIdOk() (*string, bool)`

GetMessageIdOk returns a tuple with the MessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageId

`func (o *TextMessageChunkEvent) SetMessageId(v string)`

SetMessageId sets MessageId field to given value.

### HasMessageId

`func (o *TextMessageChunkEvent) HasMessageId() bool`

HasMessageId returns a boolean if a field has been set.

### SetMessageIdNil

`func (o *TextMessageChunkEvent) SetMessageIdNil(b bool)`

 SetMessageIdNil sets the value for MessageId to be an explicit nil

### UnsetMessageId
`func (o *TextMessageChunkEvent) UnsetMessageId()`

UnsetMessageId ensures that no value is present for MessageId, not even an explicit nil
### GetRole

`func (o *TextMessageChunkEvent) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *TextMessageChunkEvent) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *TextMessageChunkEvent) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *TextMessageChunkEvent) HasRole() bool`

HasRole returns a boolean if a field has been set.

### SetRoleNil

`func (o *TextMessageChunkEvent) SetRoleNil(b bool)`

 SetRoleNil sets the value for Role to be an explicit nil

### UnsetRole
`func (o *TextMessageChunkEvent) UnsetRole()`

UnsetRole ensures that no value is present for Role, not even an explicit nil
### GetDelta

`func (o *TextMessageChunkEvent) GetDelta() string`

GetDelta returns the Delta field if non-nil, zero value otherwise.

### GetDeltaOk

`func (o *TextMessageChunkEvent) GetDeltaOk() (*string, bool)`

GetDeltaOk returns a tuple with the Delta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelta

`func (o *TextMessageChunkEvent) SetDelta(v string)`

SetDelta sets Delta field to given value.

### HasDelta

`func (o *TextMessageChunkEvent) HasDelta() bool`

HasDelta returns a boolean if a field has been set.

### SetDeltaNil

`func (o *TextMessageChunkEvent) SetDeltaNil(b bool)`

 SetDeltaNil sets the value for Delta to be an explicit nil

### UnsetDelta
`func (o *TextMessageChunkEvent) UnsetDelta()`

UnsetDelta ensures that no value is present for Delta, not even an explicit nil
### GetName

`func (o *TextMessageChunkEvent) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TextMessageChunkEvent) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TextMessageChunkEvent) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *TextMessageChunkEvent) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *TextMessageChunkEvent) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *TextMessageChunkEvent) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


