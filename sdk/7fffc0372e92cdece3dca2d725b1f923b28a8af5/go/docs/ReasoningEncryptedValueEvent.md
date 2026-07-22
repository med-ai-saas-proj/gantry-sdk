# ReasoningEncryptedValueEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "REASONING_ENCRYPTED_VALUE"]
**Timestamp** | Pointer to **NullableInt32** |  | [optional] 
**RawEvent** | Pointer to [**NullableAnyOf**](anyOf&lt;&gt;.md) |  | [optional] 
**Subtype** | **string** |  | 
**EntityId** | **string** |  | 
**EncryptedValue** | **string** |  | 

## Methods

### NewReasoningEncryptedValueEvent

`func NewReasoningEncryptedValueEvent(subtype string, entityId string, encryptedValue string, ) *ReasoningEncryptedValueEvent`

NewReasoningEncryptedValueEvent instantiates a new ReasoningEncryptedValueEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReasoningEncryptedValueEventWithDefaults

`func NewReasoningEncryptedValueEventWithDefaults() *ReasoningEncryptedValueEvent`

NewReasoningEncryptedValueEventWithDefaults instantiates a new ReasoningEncryptedValueEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ReasoningEncryptedValueEvent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ReasoningEncryptedValueEvent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ReasoningEncryptedValueEvent) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ReasoningEncryptedValueEvent) HasType() bool`

HasType returns a boolean if a field has been set.

### GetTimestamp

`func (o *ReasoningEncryptedValueEvent) GetTimestamp() int32`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *ReasoningEncryptedValueEvent) GetTimestampOk() (*int32, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *ReasoningEncryptedValueEvent) SetTimestamp(v int32)`

SetTimestamp sets Timestamp field to given value.

### HasTimestamp

`func (o *ReasoningEncryptedValueEvent) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.

### SetTimestampNil

`func (o *ReasoningEncryptedValueEvent) SetTimestampNil(b bool)`

 SetTimestampNil sets the value for Timestamp to be an explicit nil

### UnsetTimestamp
`func (o *ReasoningEncryptedValueEvent) UnsetTimestamp()`

UnsetTimestamp ensures that no value is present for Timestamp, not even an explicit nil
### GetRawEvent

`func (o *ReasoningEncryptedValueEvent) GetRawEvent() AnyOf`

GetRawEvent returns the RawEvent field if non-nil, zero value otherwise.

### GetRawEventOk

`func (o *ReasoningEncryptedValueEvent) GetRawEventOk() (*AnyOf, bool)`

GetRawEventOk returns a tuple with the RawEvent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawEvent

`func (o *ReasoningEncryptedValueEvent) SetRawEvent(v AnyOf)`

SetRawEvent sets RawEvent field to given value.

### HasRawEvent

`func (o *ReasoningEncryptedValueEvent) HasRawEvent() bool`

HasRawEvent returns a boolean if a field has been set.

### SetRawEventNil

`func (o *ReasoningEncryptedValueEvent) SetRawEventNil(b bool)`

 SetRawEventNil sets the value for RawEvent to be an explicit nil

### UnsetRawEvent
`func (o *ReasoningEncryptedValueEvent) UnsetRawEvent()`

UnsetRawEvent ensures that no value is present for RawEvent, not even an explicit nil
### GetSubtype

`func (o *ReasoningEncryptedValueEvent) GetSubtype() string`

GetSubtype returns the Subtype field if non-nil, zero value otherwise.

### GetSubtypeOk

`func (o *ReasoningEncryptedValueEvent) GetSubtypeOk() (*string, bool)`

GetSubtypeOk returns a tuple with the Subtype field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtype

`func (o *ReasoningEncryptedValueEvent) SetSubtype(v string)`

SetSubtype sets Subtype field to given value.


### GetEntityId

`func (o *ReasoningEncryptedValueEvent) GetEntityId() string`

GetEntityId returns the EntityId field if non-nil, zero value otherwise.

### GetEntityIdOk

`func (o *ReasoningEncryptedValueEvent) GetEntityIdOk() (*string, bool)`

GetEntityIdOk returns a tuple with the EntityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityId

`func (o *ReasoningEncryptedValueEvent) SetEntityId(v string)`

SetEntityId sets EntityId field to given value.


### GetEncryptedValue

`func (o *ReasoningEncryptedValueEvent) GetEncryptedValue() string`

GetEncryptedValue returns the EncryptedValue field if non-nil, zero value otherwise.

### GetEncryptedValueOk

`func (o *ReasoningEncryptedValueEvent) GetEncryptedValueOk() (*string, bool)`

GetEncryptedValueOk returns a tuple with the EncryptedValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncryptedValue

`func (o *ReasoningEncryptedValueEvent) SetEncryptedValue(v string)`

SetEncryptedValue sets EncryptedValue field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


