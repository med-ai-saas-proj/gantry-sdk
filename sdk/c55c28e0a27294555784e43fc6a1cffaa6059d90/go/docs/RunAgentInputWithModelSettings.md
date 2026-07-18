# RunAgentInputWithModelSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ThreadId** | **string** |  | 
**RunId** | **string** |  | 
**ParentRunId** | Pointer to **NullableString** |  | [optional] 
**State** | **interface{}** |  | 
**Messages** | [**[]MessagesInner**](MessagesInner.md) |  | 
**Tools** | [**[]Tool**](Tool.md) |  | 
**Context** | [**[]Context**](Context.md) |  | 
**ForwardedProps** | **interface{}** |  | 
**ModelSettings** | Pointer to [**NullableModelSettingsInput**](ModelSettingsInput.md) |  | [optional] 
**SystemPrompt** | Pointer to [**NullableSystemprompt**](Systemprompt.md) |  | [optional] 
**MaxTurns** | Pointer to **NullableInt32** |  | [optional] 
**ReservedTokens** | Pointer to **NullableInt32** |  | [optional] 

## Methods

### NewRunAgentInputWithModelSettings

`func NewRunAgentInputWithModelSettings(threadId string, runId string, state interface{}, messages []MessagesInner, tools []Tool, context []Context, forwardedProps interface{}, ) *RunAgentInputWithModelSettings`

NewRunAgentInputWithModelSettings instantiates a new RunAgentInputWithModelSettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRunAgentInputWithModelSettingsWithDefaults

`func NewRunAgentInputWithModelSettingsWithDefaults() *RunAgentInputWithModelSettings`

NewRunAgentInputWithModelSettingsWithDefaults instantiates a new RunAgentInputWithModelSettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetThreadId

`func (o *RunAgentInputWithModelSettings) GetThreadId() string`

GetThreadId returns the ThreadId field if non-nil, zero value otherwise.

### GetThreadIdOk

`func (o *RunAgentInputWithModelSettings) GetThreadIdOk() (*string, bool)`

GetThreadIdOk returns a tuple with the ThreadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreadId

`func (o *RunAgentInputWithModelSettings) SetThreadId(v string)`

SetThreadId sets ThreadId field to given value.


### GetRunId

`func (o *RunAgentInputWithModelSettings) GetRunId() string`

GetRunId returns the RunId field if non-nil, zero value otherwise.

### GetRunIdOk

`func (o *RunAgentInputWithModelSettings) GetRunIdOk() (*string, bool)`

GetRunIdOk returns a tuple with the RunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunId

`func (o *RunAgentInputWithModelSettings) SetRunId(v string)`

SetRunId sets RunId field to given value.


### GetParentRunId

`func (o *RunAgentInputWithModelSettings) GetParentRunId() string`

GetParentRunId returns the ParentRunId field if non-nil, zero value otherwise.

### GetParentRunIdOk

`func (o *RunAgentInputWithModelSettings) GetParentRunIdOk() (*string, bool)`

GetParentRunIdOk returns a tuple with the ParentRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentRunId

`func (o *RunAgentInputWithModelSettings) SetParentRunId(v string)`

SetParentRunId sets ParentRunId field to given value.

### HasParentRunId

`func (o *RunAgentInputWithModelSettings) HasParentRunId() bool`

HasParentRunId returns a boolean if a field has been set.

### SetParentRunIdNil

`func (o *RunAgentInputWithModelSettings) SetParentRunIdNil(b bool)`

 SetParentRunIdNil sets the value for ParentRunId to be an explicit nil

### UnsetParentRunId
`func (o *RunAgentInputWithModelSettings) UnsetParentRunId()`

UnsetParentRunId ensures that no value is present for ParentRunId, not even an explicit nil
### GetState

`func (o *RunAgentInputWithModelSettings) GetState() interface{}`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *RunAgentInputWithModelSettings) GetStateOk() (*interface{}, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *RunAgentInputWithModelSettings) SetState(v interface{})`

SetState sets State field to given value.


### SetStateNil

`func (o *RunAgentInputWithModelSettings) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *RunAgentInputWithModelSettings) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetMessages

`func (o *RunAgentInputWithModelSettings) GetMessages() []MessagesInner`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *RunAgentInputWithModelSettings) GetMessagesOk() (*[]MessagesInner, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *RunAgentInputWithModelSettings) SetMessages(v []MessagesInner)`

SetMessages sets Messages field to given value.


### GetTools

`func (o *RunAgentInputWithModelSettings) GetTools() []Tool`

GetTools returns the Tools field if non-nil, zero value otherwise.

### GetToolsOk

`func (o *RunAgentInputWithModelSettings) GetToolsOk() (*[]Tool, bool)`

GetToolsOk returns a tuple with the Tools field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTools

`func (o *RunAgentInputWithModelSettings) SetTools(v []Tool)`

SetTools sets Tools field to given value.


### GetContext

`func (o *RunAgentInputWithModelSettings) GetContext() []Context`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *RunAgentInputWithModelSettings) GetContextOk() (*[]Context, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *RunAgentInputWithModelSettings) SetContext(v []Context)`

SetContext sets Context field to given value.


### GetForwardedProps

`func (o *RunAgentInputWithModelSettings) GetForwardedProps() interface{}`

GetForwardedProps returns the ForwardedProps field if non-nil, zero value otherwise.

### GetForwardedPropsOk

`func (o *RunAgentInputWithModelSettings) GetForwardedPropsOk() (*interface{}, bool)`

GetForwardedPropsOk returns a tuple with the ForwardedProps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForwardedProps

`func (o *RunAgentInputWithModelSettings) SetForwardedProps(v interface{})`

SetForwardedProps sets ForwardedProps field to given value.


### SetForwardedPropsNil

`func (o *RunAgentInputWithModelSettings) SetForwardedPropsNil(b bool)`

 SetForwardedPropsNil sets the value for ForwardedProps to be an explicit nil

### UnsetForwardedProps
`func (o *RunAgentInputWithModelSettings) UnsetForwardedProps()`

UnsetForwardedProps ensures that no value is present for ForwardedProps, not even an explicit nil
### GetModelSettings

`func (o *RunAgentInputWithModelSettings) GetModelSettings() ModelSettingsInput`

GetModelSettings returns the ModelSettings field if non-nil, zero value otherwise.

### GetModelSettingsOk

`func (o *RunAgentInputWithModelSettings) GetModelSettingsOk() (*ModelSettingsInput, bool)`

GetModelSettingsOk returns a tuple with the ModelSettings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelSettings

`func (o *RunAgentInputWithModelSettings) SetModelSettings(v ModelSettingsInput)`

SetModelSettings sets ModelSettings field to given value.

### HasModelSettings

`func (o *RunAgentInputWithModelSettings) HasModelSettings() bool`

HasModelSettings returns a boolean if a field has been set.

### SetModelSettingsNil

`func (o *RunAgentInputWithModelSettings) SetModelSettingsNil(b bool)`

 SetModelSettingsNil sets the value for ModelSettings to be an explicit nil

### UnsetModelSettings
`func (o *RunAgentInputWithModelSettings) UnsetModelSettings()`

UnsetModelSettings ensures that no value is present for ModelSettings, not even an explicit nil
### GetSystemPrompt

`func (o *RunAgentInputWithModelSettings) GetSystemPrompt() Systemprompt`

GetSystemPrompt returns the SystemPrompt field if non-nil, zero value otherwise.

### GetSystemPromptOk

`func (o *RunAgentInputWithModelSettings) GetSystemPromptOk() (*Systemprompt, bool)`

GetSystemPromptOk returns a tuple with the SystemPrompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemPrompt

`func (o *RunAgentInputWithModelSettings) SetSystemPrompt(v Systemprompt)`

SetSystemPrompt sets SystemPrompt field to given value.

### HasSystemPrompt

`func (o *RunAgentInputWithModelSettings) HasSystemPrompt() bool`

HasSystemPrompt returns a boolean if a field has been set.

### SetSystemPromptNil

`func (o *RunAgentInputWithModelSettings) SetSystemPromptNil(b bool)`

 SetSystemPromptNil sets the value for SystemPrompt to be an explicit nil

### UnsetSystemPrompt
`func (o *RunAgentInputWithModelSettings) UnsetSystemPrompt()`

UnsetSystemPrompt ensures that no value is present for SystemPrompt, not even an explicit nil
### GetMaxTurns

`func (o *RunAgentInputWithModelSettings) GetMaxTurns() int32`

GetMaxTurns returns the MaxTurns field if non-nil, zero value otherwise.

### GetMaxTurnsOk

`func (o *RunAgentInputWithModelSettings) GetMaxTurnsOk() (*int32, bool)`

GetMaxTurnsOk returns a tuple with the MaxTurns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxTurns

`func (o *RunAgentInputWithModelSettings) SetMaxTurns(v int32)`

SetMaxTurns sets MaxTurns field to given value.

### HasMaxTurns

`func (o *RunAgentInputWithModelSettings) HasMaxTurns() bool`

HasMaxTurns returns a boolean if a field has been set.

### SetMaxTurnsNil

`func (o *RunAgentInputWithModelSettings) SetMaxTurnsNil(b bool)`

 SetMaxTurnsNil sets the value for MaxTurns to be an explicit nil

### UnsetMaxTurns
`func (o *RunAgentInputWithModelSettings) UnsetMaxTurns()`

UnsetMaxTurns ensures that no value is present for MaxTurns, not even an explicit nil
### GetReservedTokens

`func (o *RunAgentInputWithModelSettings) GetReservedTokens() int32`

GetReservedTokens returns the ReservedTokens field if non-nil, zero value otherwise.

### GetReservedTokensOk

`func (o *RunAgentInputWithModelSettings) GetReservedTokensOk() (*int32, bool)`

GetReservedTokensOk returns a tuple with the ReservedTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReservedTokens

`func (o *RunAgentInputWithModelSettings) SetReservedTokens(v int32)`

SetReservedTokens sets ReservedTokens field to given value.

### HasReservedTokens

`func (o *RunAgentInputWithModelSettings) HasReservedTokens() bool`

HasReservedTokens returns a boolean if a field has been set.

### SetReservedTokensNil

`func (o *RunAgentInputWithModelSettings) SetReservedTokensNil(b bool)`

 SetReservedTokensNil sets the value for ReservedTokens to be an explicit nil

### UnsetReservedTokens
`func (o *RunAgentInputWithModelSettings) UnsetReservedTokens()`

UnsetReservedTokens ensures that no value is present for ReservedTokens, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


