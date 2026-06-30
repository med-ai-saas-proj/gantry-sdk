# ActivitySnapshotEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "ACTIVITY_SNAPSHOT"]
**Timestamp** | Pointer to **NullableInt32** |  | [optional] 
**RawEvent** | Pointer to [**NullableAnyOf**](anyOf&lt;&gt;.md) |  | [optional] 
**MessageId** | **string** |  | 
**ActivityType** | **string** |  | 
**Content** | **interface{}** |  | 
**Replace** | Pointer to **bool** |  | [optional] [default to true]

## Methods

### NewActivitySnapshotEvent

`func NewActivitySnapshotEvent(messageId string, activityType string, content interface{}, ) *ActivitySnapshotEvent`

NewActivitySnapshotEvent instantiates a new ActivitySnapshotEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActivitySnapshotEventWithDefaults

`func NewActivitySnapshotEventWithDefaults() *ActivitySnapshotEvent`

NewActivitySnapshotEventWithDefaults instantiates a new ActivitySnapshotEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ActivitySnapshotEvent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ActivitySnapshotEvent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ActivitySnapshotEvent) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ActivitySnapshotEvent) HasType() bool`

HasType returns a boolean if a field has been set.

### GetTimestamp

`func (o *ActivitySnapshotEvent) GetTimestamp() int32`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *ActivitySnapshotEvent) GetTimestampOk() (*int32, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *ActivitySnapshotEvent) SetTimestamp(v int32)`

SetTimestamp sets Timestamp field to given value.

### HasTimestamp

`func (o *ActivitySnapshotEvent) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.

### SetTimestampNil

`func (o *ActivitySnapshotEvent) SetTimestampNil(b bool)`

 SetTimestampNil sets the value for Timestamp to be an explicit nil

### UnsetTimestamp
`func (o *ActivitySnapshotEvent) UnsetTimestamp()`

UnsetTimestamp ensures that no value is present for Timestamp, not even an explicit nil
### GetRawEvent

`func (o *ActivitySnapshotEvent) GetRawEvent() AnyOf`

GetRawEvent returns the RawEvent field if non-nil, zero value otherwise.

### GetRawEventOk

`func (o *ActivitySnapshotEvent) GetRawEventOk() (*AnyOf, bool)`

GetRawEventOk returns a tuple with the RawEvent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawEvent

`func (o *ActivitySnapshotEvent) SetRawEvent(v AnyOf)`

SetRawEvent sets RawEvent field to given value.

### HasRawEvent

`func (o *ActivitySnapshotEvent) HasRawEvent() bool`

HasRawEvent returns a boolean if a field has been set.

### SetRawEventNil

`func (o *ActivitySnapshotEvent) SetRawEventNil(b bool)`

 SetRawEventNil sets the value for RawEvent to be an explicit nil

### UnsetRawEvent
`func (o *ActivitySnapshotEvent) UnsetRawEvent()`

UnsetRawEvent ensures that no value is present for RawEvent, not even an explicit nil
### GetMessageId

`func (o *ActivitySnapshotEvent) GetMessageId() string`

GetMessageId returns the MessageId field if non-nil, zero value otherwise.

### GetMessageIdOk

`func (o *ActivitySnapshotEvent) GetMessageIdOk() (*string, bool)`

GetMessageIdOk returns a tuple with the MessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageId

`func (o *ActivitySnapshotEvent) SetMessageId(v string)`

SetMessageId sets MessageId field to given value.


### GetActivityType

`func (o *ActivitySnapshotEvent) GetActivityType() string`

GetActivityType returns the ActivityType field if non-nil, zero value otherwise.

### GetActivityTypeOk

`func (o *ActivitySnapshotEvent) GetActivityTypeOk() (*string, bool)`

GetActivityTypeOk returns a tuple with the ActivityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityType

`func (o *ActivitySnapshotEvent) SetActivityType(v string)`

SetActivityType sets ActivityType field to given value.


### GetContent

`func (o *ActivitySnapshotEvent) GetContent() interface{}`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *ActivitySnapshotEvent) GetContentOk() (*interface{}, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *ActivitySnapshotEvent) SetContent(v interface{})`

SetContent sets Content field to given value.


### SetContentNil

`func (o *ActivitySnapshotEvent) SetContentNil(b bool)`

 SetContentNil sets the value for Content to be an explicit nil

### UnsetContent
`func (o *ActivitySnapshotEvent) UnsetContent()`

UnsetContent ensures that no value is present for Content, not even an explicit nil
### GetReplace

`func (o *ActivitySnapshotEvent) GetReplace() bool`

GetReplace returns the Replace field if non-nil, zero value otherwise.

### GetReplaceOk

`func (o *ActivitySnapshotEvent) GetReplaceOk() (*bool, bool)`

GetReplaceOk returns a tuple with the Replace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplace

`func (o *ActivitySnapshotEvent) SetReplace(v bool)`

SetReplace sets Replace field to given value.

### HasReplace

`func (o *ActivitySnapshotEvent) HasReplace() bool`

HasReplace returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


