# ResponseAgUiGatewayAiGatewayAgUiModelPost

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "TEXT_MESSAGE_START"]
**Timestamp** | Pointer to **int32** |  | [optional] 
**RawEvent** | Pointer to [**NullableAnyOf**](anyOf&lt;&gt;.md) |  | [optional] 
**MessageId** | **string** |  | 
**Role** | **string** |  | 
**Name** | **string** |  | 
**Delta** | **string** |  | 
**ToolCallId** | **string** |  | 
**ToolCallName** | **string** |  | 
**ParentMessageId** | Pointer to **string** |  | [optional] 
**Content** | **interface{}** |  | 
**Title** | Pointer to **string** |  | [optional] 
**Snapshot** | **interface{}** |  | 
**Messages** | [**[]MessagesInner**](MessagesInner.md) |  | 
**ActivityType** | **string** |  | 
**Replace** | Pointer to **bool** |  | [optional] [default to true]
**Patch** | **[]interface{}** |  | 
**Event** | **interface{}** |  | 
**Source** | Pointer to **string** |  | [optional] 
**Value** | **interface{}** |  | 
**ThreadId** | **string** |  | 
**RunId** | **string** |  | 
**ParentRunId** | Pointer to **string** |  | [optional] 
**Input** | Pointer to [**RunAgentInput**](RunAgentInput.md) |  | [optional] 
**Result** | Pointer to [**NullableAnyOf**](anyOf&lt;&gt;.md) |  | [optional] 
**Message** | **string** |  | 
**Code** | Pointer to **string** |  | [optional] 
**StepName** | **string** |  | 
**Subtype** | **string** |  | 
**EntityId** | **string** |  | 
**EncryptedValue** | **string** |  | 

## Methods

### NewResponseAgUiGatewayAiGatewayAgUiModelPost

`func NewResponseAgUiGatewayAiGatewayAgUiModelPost(messageId string, role string, name string, delta string, toolCallId string, toolCallName string, content interface{}, snapshot interface{}, messages []MessagesInner, activityType string, patch []interface{}, event interface{}, value interface{}, threadId string, runId string, message string, stepName string, subtype string, entityId string, encryptedValue string, ) *ResponseAgUiGatewayAiGatewayAgUiModelPost`

NewResponseAgUiGatewayAiGatewayAgUiModelPost instantiates a new ResponseAgUiGatewayAiGatewayAgUiModelPost object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponseAgUiGatewayAiGatewayAgUiModelPostWithDefaults

`func NewResponseAgUiGatewayAiGatewayAgUiModelPostWithDefaults() *ResponseAgUiGatewayAiGatewayAgUiModelPost`

NewResponseAgUiGatewayAiGatewayAgUiModelPostWithDefaults instantiates a new ResponseAgUiGatewayAiGatewayAgUiModelPost object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) HasType() bool`

HasType returns a boolean if a field has been set.

### GetTimestamp

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetTimestamp() int32`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetTimestampOk() (*int32, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetTimestamp(v int32)`

SetTimestamp sets Timestamp field to given value.

### HasTimestamp

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) HasTimestamp() bool`

HasTimestamp returns a boolean if a field has been set.

### GetRawEvent

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetRawEvent() AnyOf`

GetRawEvent returns the RawEvent field if non-nil, zero value otherwise.

### GetRawEventOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetRawEventOk() (*AnyOf, bool)`

GetRawEventOk returns a tuple with the RawEvent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRawEvent

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetRawEvent(v AnyOf)`

SetRawEvent sets RawEvent field to given value.

### HasRawEvent

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) HasRawEvent() bool`

HasRawEvent returns a boolean if a field has been set.

### SetRawEventNil

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetRawEventNil(b bool)`

 SetRawEventNil sets the value for RawEvent to be an explicit nil

### UnsetRawEvent
`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) UnsetRawEvent()`

UnsetRawEvent ensures that no value is present for RawEvent, not even an explicit nil
### GetMessageId

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetMessageId() string`

GetMessageId returns the MessageId field if non-nil, zero value otherwise.

### GetMessageIdOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetMessageIdOk() (*string, bool)`

GetMessageIdOk returns a tuple with the MessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageId

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetMessageId(v string)`

SetMessageId sets MessageId field to given value.


### GetRole

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetRole(v string)`

SetRole sets Role field to given value.


### GetName

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetName(v string)`

SetName sets Name field to given value.


### GetDelta

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetDelta() string`

GetDelta returns the Delta field if non-nil, zero value otherwise.

### GetDeltaOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetDeltaOk() (*string, bool)`

GetDeltaOk returns a tuple with the Delta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelta

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetDelta(v string)`

SetDelta sets Delta field to given value.


### GetToolCallId

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetToolCallId() string`

GetToolCallId returns the ToolCallId field if non-nil, zero value otherwise.

### GetToolCallIdOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetToolCallIdOk() (*string, bool)`

GetToolCallIdOk returns a tuple with the ToolCallId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolCallId

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetToolCallId(v string)`

SetToolCallId sets ToolCallId field to given value.


### GetToolCallName

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetToolCallName() string`

GetToolCallName returns the ToolCallName field if non-nil, zero value otherwise.

### GetToolCallNameOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetToolCallNameOk() (*string, bool)`

GetToolCallNameOk returns a tuple with the ToolCallName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolCallName

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetToolCallName(v string)`

SetToolCallName sets ToolCallName field to given value.


### GetParentMessageId

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetParentMessageId() string`

GetParentMessageId returns the ParentMessageId field if non-nil, zero value otherwise.

### GetParentMessageIdOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetParentMessageIdOk() (*string, bool)`

GetParentMessageIdOk returns a tuple with the ParentMessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentMessageId

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetParentMessageId(v string)`

SetParentMessageId sets ParentMessageId field to given value.

### HasParentMessageId

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) HasParentMessageId() bool`

HasParentMessageId returns a boolean if a field has been set.

### GetContent

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetContent() interface{}`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetContentOk() (*interface{}, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetContent(v interface{})`

SetContent sets Content field to given value.


### SetContentNil

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetContentNil(b bool)`

 SetContentNil sets the value for Content to be an explicit nil

### UnsetContent
`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) UnsetContent()`

UnsetContent ensures that no value is present for Content, not even an explicit nil
### GetTitle

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetSnapshot

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetSnapshot() interface{}`

GetSnapshot returns the Snapshot field if non-nil, zero value otherwise.

### GetSnapshotOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetSnapshotOk() (*interface{}, bool)`

GetSnapshotOk returns a tuple with the Snapshot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnapshot

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetSnapshot(v interface{})`

SetSnapshot sets Snapshot field to given value.


### SetSnapshotNil

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetSnapshotNil(b bool)`

 SetSnapshotNil sets the value for Snapshot to be an explicit nil

### UnsetSnapshot
`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) UnsetSnapshot()`

UnsetSnapshot ensures that no value is present for Snapshot, not even an explicit nil
### GetMessages

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetMessages() []MessagesInner`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetMessagesOk() (*[]MessagesInner, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetMessages(v []MessagesInner)`

SetMessages sets Messages field to given value.


### GetActivityType

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetActivityType() string`

GetActivityType returns the ActivityType field if non-nil, zero value otherwise.

### GetActivityTypeOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetActivityTypeOk() (*string, bool)`

GetActivityTypeOk returns a tuple with the ActivityType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityType

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetActivityType(v string)`

SetActivityType sets ActivityType field to given value.


### GetReplace

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetReplace() bool`

GetReplace returns the Replace field if non-nil, zero value otherwise.

### GetReplaceOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetReplaceOk() (*bool, bool)`

GetReplaceOk returns a tuple with the Replace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplace

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetReplace(v bool)`

SetReplace sets Replace field to given value.

### HasReplace

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) HasReplace() bool`

HasReplace returns a boolean if a field has been set.

### GetPatch

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetPatch() []interface{}`

GetPatch returns the Patch field if non-nil, zero value otherwise.

### GetPatchOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetPatchOk() (*[]interface{}, bool)`

GetPatchOk returns a tuple with the Patch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatch

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetPatch(v []interface{})`

SetPatch sets Patch field to given value.


### GetEvent

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetEvent() interface{}`

GetEvent returns the Event field if non-nil, zero value otherwise.

### GetEventOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetEventOk() (*interface{}, bool)`

GetEventOk returns a tuple with the Event field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvent

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetEvent(v interface{})`

SetEvent sets Event field to given value.


### SetEventNil

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetEventNil(b bool)`

 SetEventNil sets the value for Event to be an explicit nil

### UnsetEvent
`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) UnsetEvent()`

UnsetEvent ensures that no value is present for Event, not even an explicit nil
### GetSource

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetValue

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetValue() interface{}`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetValueOk() (*interface{}, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetValue(v interface{})`

SetValue sets Value field to given value.


### SetValueNil

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetValueNil(b bool)`

 SetValueNil sets the value for Value to be an explicit nil

### UnsetValue
`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) UnsetValue()`

UnsetValue ensures that no value is present for Value, not even an explicit nil
### GetThreadId

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetThreadId() string`

GetThreadId returns the ThreadId field if non-nil, zero value otherwise.

### GetThreadIdOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetThreadIdOk() (*string, bool)`

GetThreadIdOk returns a tuple with the ThreadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreadId

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetThreadId(v string)`

SetThreadId sets ThreadId field to given value.


### GetRunId

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetRunId() string`

GetRunId returns the RunId field if non-nil, zero value otherwise.

### GetRunIdOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetRunIdOk() (*string, bool)`

GetRunIdOk returns a tuple with the RunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunId

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetRunId(v string)`

SetRunId sets RunId field to given value.


### GetParentRunId

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetParentRunId() string`

GetParentRunId returns the ParentRunId field if non-nil, zero value otherwise.

### GetParentRunIdOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetParentRunIdOk() (*string, bool)`

GetParentRunIdOk returns a tuple with the ParentRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentRunId

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetParentRunId(v string)`

SetParentRunId sets ParentRunId field to given value.

### HasParentRunId

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) HasParentRunId() bool`

HasParentRunId returns a boolean if a field has been set.

### GetInput

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetInput() RunAgentInput`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetInputOk() (*RunAgentInput, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetInput(v RunAgentInput)`

SetInput sets Input field to given value.

### HasInput

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) HasInput() bool`

HasInput returns a boolean if a field has been set.

### GetResult

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetResult() AnyOf`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetResultOk() (*AnyOf, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetResult(v AnyOf)`

SetResult sets Result field to given value.

### HasResult

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) HasResult() bool`

HasResult returns a boolean if a field has been set.

### SetResultNil

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetResultNil(b bool)`

 SetResultNil sets the value for Result to be an explicit nil

### UnsetResult
`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) UnsetResult()`

UnsetResult ensures that no value is present for Result, not even an explicit nil
### GetMessage

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetCode

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetStepName

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetStepName() string`

GetStepName returns the StepName field if non-nil, zero value otherwise.

### GetStepNameOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetStepNameOk() (*string, bool)`

GetStepNameOk returns a tuple with the StepName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStepName

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetStepName(v string)`

SetStepName sets StepName field to given value.


### GetSubtype

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetSubtype() string`

GetSubtype returns the Subtype field if non-nil, zero value otherwise.

### GetSubtypeOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetSubtypeOk() (*string, bool)`

GetSubtypeOk returns a tuple with the Subtype field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubtype

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetSubtype(v string)`

SetSubtype sets Subtype field to given value.


### GetEntityId

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetEntityId() string`

GetEntityId returns the EntityId field if non-nil, zero value otherwise.

### GetEntityIdOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetEntityIdOk() (*string, bool)`

GetEntityIdOk returns a tuple with the EntityId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityId

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetEntityId(v string)`

SetEntityId sets EntityId field to given value.


### GetEncryptedValue

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetEncryptedValue() string`

GetEncryptedValue returns the EncryptedValue field if non-nil, zero value otherwise.

### GetEncryptedValueOk

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) GetEncryptedValueOk() (*string, bool)`

GetEncryptedValueOk returns a tuple with the EncryptedValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncryptedValue

`func (o *ResponseAgUiGatewayAiGatewayAgUiModelPost) SetEncryptedValue(v string)`

SetEncryptedValue sets EncryptedValue field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


