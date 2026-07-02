# ToolCall

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Type** | Pointer to **string** |  | [optional] [default to "function"]
**Function** | [**FunctionCall**](FunctionCall.md) |  | 
**EncryptedValue** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewToolCall

`func NewToolCall(id string, function FunctionCall, ) *ToolCall`

NewToolCall instantiates a new ToolCall object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewToolCallWithDefaults

`func NewToolCallWithDefaults() *ToolCall`

NewToolCallWithDefaults instantiates a new ToolCall object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ToolCall) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ToolCall) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ToolCall) SetId(v string)`

SetId sets Id field to given value.


### GetType

`func (o *ToolCall) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ToolCall) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ToolCall) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ToolCall) HasType() bool`

HasType returns a boolean if a field has been set.

### GetFunction

`func (o *ToolCall) GetFunction() FunctionCall`

GetFunction returns the Function field if non-nil, zero value otherwise.

### GetFunctionOk

`func (o *ToolCall) GetFunctionOk() (*FunctionCall, bool)`

GetFunctionOk returns a tuple with the Function field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFunction

`func (o *ToolCall) SetFunction(v FunctionCall)`

SetFunction sets Function field to given value.


### GetEncryptedValue

`func (o *ToolCall) GetEncryptedValue() string`

GetEncryptedValue returns the EncryptedValue field if non-nil, zero value otherwise.

### GetEncryptedValueOk

`func (o *ToolCall) GetEncryptedValueOk() (*string, bool)`

GetEncryptedValueOk returns a tuple with the EncryptedValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncryptedValue

`func (o *ToolCall) SetEncryptedValue(v string)`

SetEncryptedValue sets EncryptedValue field to given value.

### HasEncryptedValue

`func (o *ToolCall) HasEncryptedValue() bool`

HasEncryptedValue returns a boolean if a field has been set.

### SetEncryptedValueNil

`func (o *ToolCall) SetEncryptedValueNil(b bool)`

 SetEncryptedValueNil sets the value for EncryptedValue to be an explicit nil

### UnsetEncryptedValue
`func (o *ToolCall) UnsetEncryptedValue()`

UnsetEncryptedValue ensures that no value is present for EncryptedValue, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


