# RunStartedEvent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "RUN_STARTED"]
**Timestamp** | Pointer to **NullableInt32** |  | [optional] 
**RawEvent** | Pointer to [**NullableAnyOf**](anyOf&lt;&gt;.md) |  | [optional] 
**ThreadId** | **string** |  | 
**RunId** | **string** |  | 
**ParentRunId** | Pointer to **NullableString** |  | [optional] 
**Input** | Pointer to [**NullableRunAgentInput**](RunAgentInput.md) |  | [optional] 

## Methods

### NewRunStartedEvent

`func NewRunStartedEvent(threadId string, runId string, ) *RunStartedEvent`

NewRunStartedEvent instantiates a new RunStartedEvent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRunStartedEventWithDefaults

`func NewRunStartedEventWithDefaults() *RunStartedEvent`

NewRunStartedEventWithDefaults instantiates a new RunStartedEvent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *RunStartedEvent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *RunStartedEvent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *RunStartedEvent) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *RunStartedEvent) HasType() bool`

HasType returns a boolean if a field has been set.

### GetTimestamp

`func (o *RunStartedEvent) GetTimestamp() int32`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *RunStartedEvent) GetTimestampOk() (*int32, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *RunStartedEvent) SetTimestamp(v int32)`

SetTimestamp sets Timestamp field to given value.

### HasTimestamp

`func (o *RunStartedEvent) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.

### SetTimestampNil

`func (o *RunStartedEvent) SetTimestampNil(b bool)`

 SetTimestampNil sets the value for Timestamp to be an explicit nil

### UnsetTimestamp
`func (o *RunStartedEvent) UnsetTimestamp()`

UnsetTimestamp ensures that no value is present for Timestamp, not even an explicit nil
### GetRawEvent

`func (o *RunStartedEvent) GetRawEvent() AnyOf`

GetRawEvent returns the RawEvent field if non-nil, zero value otherwise.

### GetRawEventOk

`func (o *RunStartedEvent) GetRawEventOk() (*AnyOf, bool)`

GetRawEventOk returns a tuple with the RawEvent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawEvent

`func (o *RunStartedEvent) SetRawEvent(v AnyOf)`

SetRawEvent sets RawEvent field to given value.

### HasRawEvent

`func (o *RunStartedEvent) HasRawEvent() bool`

HasRawEvent returns a boolean if a field has been set.

### SetRawEventNil

`func (o *RunStartedEvent) SetRawEventNil(b bool)`

 SetRawEventNil sets the value for RawEvent to be an explicit nil

### UnsetRawEvent
`func (o *RunStartedEvent) UnsetRawEvent()`

UnsetRawEvent ensures that no value is present for RawEvent, not even an explicit nil
### GetThreadId

`func (o *RunStartedEvent) GetThreadId() string`

GetThreadId returns the ThreadId field if non-nil, zero value otherwise.

### GetThreadIdOk

`func (o *RunStartedEvent) GetThreadIdOk() (*string, bool)`

GetThreadIdOk returns a tuple with the ThreadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreadId

`func (o *RunStartedEvent) SetThreadId(v string)`

SetThreadId sets ThreadId field to given value.


### GetRunId

`func (o *RunStartedEvent) GetRunId() string`

GetRunId returns the RunId field if non-nil, zero value otherwise.

### GetRunIdOk

`func (o *RunStartedEvent) GetRunIdOk() (*string, bool)`

GetRunIdOk returns a tuple with the RunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunId

`func (o *RunStartedEvent) SetRunId(v string)`

SetRunId sets RunId field to given value.


### GetParentRunId

`func (o *RunStartedEvent) GetParentRunId() string`

GetParentRunId returns the ParentRunId field if non-nil, zero value otherwise.

### GetParentRunIdOk

`func (o *RunStartedEvent) GetParentRunIdOk() (*string, bool)`

GetParentRunIdOk returns a tuple with the ParentRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentRunId

`func (o *RunStartedEvent) SetParentRunId(v string)`

SetParentRunId sets ParentRunId field to given value.

### HasParentRunId

`func (o *RunStartedEvent) HasParentRunId() bool`

HasParentRunId returns a boolean if a field has been set.

### SetParentRunIdNil

`func (o *RunStartedEvent) SetParentRunIdNil(b bool)`

 SetParentRunIdNil sets the value for ParentRunId to be an explicit nil

### UnsetParentRunId
`func (o *RunStartedEvent) UnsetParentRunId()`

UnsetParentRunId ensures that no value is present for ParentRunId, not even an explicit nil
### GetInput

`func (o *RunStartedEvent) GetInput() RunAgentInput`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *RunStartedEvent) GetInputOk() (*RunAgentInput, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *RunStartedEvent) SetInput(v RunAgentInput)`

SetInput sets Input field to given value.

### HasInput

`func (o *RunStartedEvent) HasInput() bool`

HasInput returns a boolean if a field has been set.

### SetInputNil

`func (o *RunStartedEvent) SetInputNil(b bool)`

 SetInputNil sets the value for Input to be an explicit nil

### UnsetInput
`func (o *RunStartedEvent) UnsetInput()`

UnsetInput ensures that no value is present for Input, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


