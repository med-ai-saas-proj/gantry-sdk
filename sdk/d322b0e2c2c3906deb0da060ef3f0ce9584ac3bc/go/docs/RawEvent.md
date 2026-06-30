# RawEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "RAW"]
**Timestamp** | Pointer to **NullableInt32** |  | [optional] 
**RawEvent** | Pointer to [**NullableAnyOf**](anyOf&lt;&gt;.md) |  | [optional] 
**Event** | **interface{}** |  | 
**Source** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewRawEvent

`func NewRawEvent(event interface{}, ) *RawEvent`

NewRawEvent instantiates a new RawEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRawEventWithDefaults

`func NewRawEventWithDefaults() *RawEvent`

NewRawEventWithDefaults instantiates a new RawEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *RawEvent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *RawEvent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *RawEvent) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *RawEvent) HasType() bool`

HasType returns a boolean if a field has been set.

### GetTimestamp

`func (o *RawEvent) GetTimestamp() int32`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *RawEvent) GetTimestampOk() (*int32, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *RawEvent) SetTimestamp(v int32)`

SetTimestamp sets Timestamp field to given value.

### HasTimestamp

`func (o *RawEvent) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.

### SetTimestampNil

`func (o *RawEvent) SetTimestampNil(b bool)`

 SetTimestampNil sets the value for Timestamp to be an explicit nil

### UnsetTimestamp
`func (o *RawEvent) UnsetTimestamp()`

UnsetTimestamp ensures that no value is present for Timestamp, not even an explicit nil
### GetRawEvent

`func (o *RawEvent) GetRawEvent() AnyOf`

GetRawEvent returns the RawEvent field if non-nil, zero value otherwise.

### GetRawEventOk

`func (o *RawEvent) GetRawEventOk() (*AnyOf, bool)`

GetRawEventOk returns a tuple with the RawEvent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawEvent

`func (o *RawEvent) SetRawEvent(v AnyOf)`

SetRawEvent sets RawEvent field to given value.

### HasRawEvent

`func (o *RawEvent) HasRawEvent() bool`

HasRawEvent returns a boolean if a field has been set.

### SetRawEventNil

`func (o *RawEvent) SetRawEventNil(b bool)`

 SetRawEventNil sets the value for RawEvent to be an explicit nil

### UnsetRawEvent
`func (o *RawEvent) UnsetRawEvent()`

UnsetRawEvent ensures that no value is present for RawEvent, not even an explicit nil
### GetEvent

`func (o *RawEvent) GetEvent() interface{}`

GetEvent returns the Event field if non-nil, zero value otherwise.

### GetEventOk

`func (o *RawEvent) GetEventOk() (*interface{}, bool)`

GetEventOk returns a tuple with the Event field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvent

`func (o *RawEvent) SetEvent(v interface{})`

SetEvent sets Event field to given value.


### SetEventNil

`func (o *RawEvent) SetEventNil(b bool)`

 SetEventNil sets the value for Event to be an explicit nil

### UnsetEvent
`func (o *RawEvent) UnsetEvent()`

UnsetEvent ensures that no value is present for Event, not even an explicit nil
### GetSource

`func (o *RawEvent) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *RawEvent) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *RawEvent) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *RawEvent) HasSource() bool`

HasSource returns a boolean if a field has been set.

### SetSourceNil

`func (o *RawEvent) SetSourceNil(b bool)`

 SetSourceNil sets the value for Source to be an explicit nil

### UnsetSource
`func (o *RawEvent) UnsetSource()`

UnsetSource ensures that no value is present for Source, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


