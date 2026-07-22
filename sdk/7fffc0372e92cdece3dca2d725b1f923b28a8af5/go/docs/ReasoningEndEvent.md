# ReasoningEndEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "REASONING_END"]
**Timestamp** | Pointer to **NullableInt32** |  | [optional] 
**RawEvent** | Pointer to [**NullableAnyOf**](anyOf&lt;&gt;.md) |  | [optional] 
**MessageId** | **string** |  | 

## Methods

### NewReasoningEndEvent

`func NewReasoningEndEvent(messageId string, ) *ReasoningEndEvent`

NewReasoningEndEvent instantiates a new ReasoningEndEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReasoningEndEventWithDefaults

`func NewReasoningEndEventWithDefaults() *ReasoningEndEvent`

NewReasoningEndEventWithDefaults instantiates a new ReasoningEndEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ReasoningEndEvent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ReasoningEndEvent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ReasoningEndEvent) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ReasoningEndEvent) HasType() bool`

HasType returns a boolean if a field has been set.

### GetTimestamp

`func (o *ReasoningEndEvent) GetTimestamp() int32`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *ReasoningEndEvent) GetTimestampOk() (*int32, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *ReasoningEndEvent) SetTimestamp(v int32)`

SetTimestamp sets Timestamp field to given value.

### HasTimestamp

`func (o *ReasoningEndEvent) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.

### SetTimestampNil

`func (o *ReasoningEndEvent) SetTimestampNil(b bool)`

 SetTimestampNil sets the value for Timestamp to be an explicit nil

### UnsetTimestamp
`func (o *ReasoningEndEvent) UnsetTimestamp()`

UnsetTimestamp ensures that no value is present for Timestamp, not even an explicit nil
### GetRawEvent

`func (o *ReasoningEndEvent) GetRawEvent() AnyOf`

GetRawEvent returns the RawEvent field if non-nil, zero value otherwise.

### GetRawEventOk

`func (o *ReasoningEndEvent) GetRawEventOk() (*AnyOf, bool)`

GetRawEventOk returns a tuple with the RawEvent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawEvent

`func (o *ReasoningEndEvent) SetRawEvent(v AnyOf)`

SetRawEvent sets RawEvent field to given value.

### HasRawEvent

`func (o *ReasoningEndEvent) HasRawEvent() bool`

HasRawEvent returns a boolean if a field has been set.

### SetRawEventNil

`func (o *ReasoningEndEvent) SetRawEventNil(b bool)`

 SetRawEventNil sets the value for RawEvent to be an explicit nil

### UnsetRawEvent
`func (o *ReasoningEndEvent) UnsetRawEvent()`

UnsetRawEvent ensures that no value is present for RawEvent, not even an explicit nil
### GetMessageId

`func (o *ReasoningEndEvent) GetMessageId() string`

GetMessageId returns the MessageId field if non-nil, zero value otherwise.

### GetMessageIdOk

`func (o *ReasoningEndEvent) GetMessageIdOk() (*string, bool)`

GetMessageIdOk returns a tuple with the MessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageId

`func (o *ReasoningEndEvent) SetMessageId(v string)`

SetMessageId sets MessageId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


