# ReasoningStartEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "REASONING_START"]
**Timestamp** | Pointer to **NullableInt32** |  | [optional] 
**RawEvent** | Pointer to [**NullableAnyOf**](anyOf&lt;&gt;.md) |  | [optional] 
**MessageId** | **string** |  | 

## Methods

### NewReasoningStartEvent

`func NewReasoningStartEvent(messageId string, ) *ReasoningStartEvent`

NewReasoningStartEvent instantiates a new ReasoningStartEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReasoningStartEventWithDefaults

`func NewReasoningStartEventWithDefaults() *ReasoningStartEvent`

NewReasoningStartEventWithDefaults instantiates a new ReasoningStartEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ReasoningStartEvent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ReasoningStartEvent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ReasoningStartEvent) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ReasoningStartEvent) HasType() bool`

HasType returns a boolean if a field has been set.

### GetTimestamp

`func (o *ReasoningStartEvent) GetTimestamp() int32`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *ReasoningStartEvent) GetTimestampOk() (*int32, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *ReasoningStartEvent) SetTimestamp(v int32)`

SetTimestamp sets Timestamp field to given value.

### HasTimestamp

`func (o *ReasoningStartEvent) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.

### SetTimestampNil

`func (o *ReasoningStartEvent) SetTimestampNil(b bool)`

 SetTimestampNil sets the value for Timestamp to be an explicit nil

### UnsetTimestamp
`func (o *ReasoningStartEvent) UnsetTimestamp()`

UnsetTimestamp ensures that no value is present for Timestamp, not even an explicit nil
### GetRawEvent

`func (o *ReasoningStartEvent) GetRawEvent() AnyOf`

GetRawEvent returns the RawEvent field if non-nil, zero value otherwise.

### GetRawEventOk

`func (o *ReasoningStartEvent) GetRawEventOk() (*AnyOf, bool)`

GetRawEventOk returns a tuple with the RawEvent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawEvent

`func (o *ReasoningStartEvent) SetRawEvent(v AnyOf)`

SetRawEvent sets RawEvent field to given value.

### HasRawEvent

`func (o *ReasoningStartEvent) HasRawEvent() bool`

HasRawEvent returns a boolean if a field has been set.

### SetRawEventNil

`func (o *ReasoningStartEvent) SetRawEventNil(b bool)`

 SetRawEventNil sets the value for RawEvent to be an explicit nil

### UnsetRawEvent
`func (o *ReasoningStartEvent) UnsetRawEvent()`

UnsetRawEvent ensures that no value is present for RawEvent, not even an explicit nil
### GetMessageId

`func (o *ReasoningStartEvent) GetMessageId() string`

GetMessageId returns the MessageId field if non-nil, zero value otherwise.

### GetMessageIdOk

`func (o *ReasoningStartEvent) GetMessageIdOk() (*string, bool)`

GetMessageIdOk returns a tuple with the MessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageId

`func (o *ReasoningStartEvent) SetMessageId(v string)`

SetMessageId sets MessageId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


