# RunAgentInput

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

## Methods

### NewRunAgentInput

`func NewRunAgentInput(threadId string, runId string, state interface{}, messages []MessagesInner, tools []Tool, context []Context, forwardedProps interface{}, ) *RunAgentInput`

NewRunAgentInput instantiates a new RunAgentInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRunAgentInputWithDefaults

`func NewRunAgentInputWithDefaults() *RunAgentInput`

NewRunAgentInputWithDefaults instantiates a new RunAgentInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetThreadId

`func (o *RunAgentInput) GetThreadId() string`

GetThreadId returns the ThreadId field if non-nil, zero value otherwise.

### GetThreadIdOk

`func (o *RunAgentInput) GetThreadIdOk() (*string, bool)`

GetThreadIdOk returns a tuple with the ThreadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreadId

`func (o *RunAgentInput) SetThreadId(v string)`

SetThreadId sets ThreadId field to given value.


### GetRunId

`func (o *RunAgentInput) GetRunId() string`

GetRunId returns the RunId field if non-nil, zero value otherwise.

### GetRunIdOk

`func (o *RunAgentInput) GetRunIdOk() (*string, bool)`

GetRunIdOk returns a tuple with the RunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunId

`func (o *RunAgentInput) SetRunId(v string)`

SetRunId sets RunId field to given value.


### GetParentRunId

`func (o *RunAgentInput) GetParentRunId() string`

GetParentRunId returns the ParentRunId field if non-nil, zero value otherwise.

### GetParentRunIdOk

`func (o *RunAgentInput) GetParentRunIdOk() (*string, bool)`

GetParentRunIdOk returns a tuple with the ParentRunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentRunId

`func (o *RunAgentInput) SetParentRunId(v string)`

SetParentRunId sets ParentRunId field to given value.

### HasParentRunId

`func (o *RunAgentInput) HasParentRunId() bool`

HasParentRunId returns a boolean if a field has been set.

### SetParentRunIdNil

`func (o *RunAgentInput) SetParentRunIdNil(b bool)`

 SetParentRunIdNil sets the value for ParentRunId to be an explicit nil

### UnsetParentRunId
`func (o *RunAgentInput) UnsetParentRunId()`

UnsetParentRunId ensures that no value is present for ParentRunId, not even an explicit nil
### GetState

`func (o *RunAgentInput) GetState() interface{}`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *RunAgentInput) GetStateOk() (*interface{}, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *RunAgentInput) SetState(v interface{})`

SetState sets State field to given value.


### SetStateNil

`func (o *RunAgentInput) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *RunAgentInput) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetMessages

`func (o *RunAgentInput) GetMessages() []MessagesInner`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *RunAgentInput) GetMessagesOk() (*[]MessagesInner, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *RunAgentInput) SetMessages(v []MessagesInner)`

SetMessages sets Messages field to given value.


### GetTools

`func (o *RunAgentInput) GetTools() []Tool`

GetTools returns the Tools field if non-nil, zero value otherwise.

### GetToolsOk

`func (o *RunAgentInput) GetToolsOk() (*[]Tool, bool)`

GetToolsOk returns a tuple with the Tools field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTools

`func (o *RunAgentInput) SetTools(v []Tool)`

SetTools sets Tools field to given value.


### GetContext

`func (o *RunAgentInput) GetContext() []Context`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *RunAgentInput) GetContextOk() (*[]Context, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *RunAgentInput) SetContext(v []Context)`

SetContext sets Context field to given value.


### GetForwardedProps

`func (o *RunAgentInput) GetForwardedProps() interface{}`

GetForwardedProps returns the ForwardedProps field if non-nil, zero value otherwise.

### GetForwardedPropsOk

`func (o *RunAgentInput) GetForwardedPropsOk() (*interface{}, bool)`

GetForwardedPropsOk returns a tuple with the ForwardedProps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForwardedProps

`func (o *RunAgentInput) SetForwardedProps(v interface{})`

SetForwardedProps sets ForwardedProps field to given value.


### SetForwardedPropsNil

`func (o *RunAgentInput) SetForwardedPropsNil(b bool)`

 SetForwardedPropsNil sets the value for ForwardedProps to be an explicit nil

### UnsetForwardedProps
`func (o *RunAgentInput) UnsetForwardedProps()`

UnsetForwardedProps ensures that no value is present for ForwardedProps, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


