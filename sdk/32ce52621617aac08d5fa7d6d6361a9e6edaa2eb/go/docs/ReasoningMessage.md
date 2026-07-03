# ReasoningMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Role** | Pointer to **string** |  | [optional] [default to "reasoning"]
**Content** | **string** |  | 
**EncryptedValue** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewReasoningMessage

`func NewReasoningMessage(id string, content string, ) *ReasoningMessage`

NewReasoningMessage instantiates a new ReasoningMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReasoningMessageWithDefaults

`func NewReasoningMessageWithDefaults() *ReasoningMessage`

NewReasoningMessageWithDefaults instantiates a new ReasoningMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ReasoningMessage) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ReasoningMessage) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ReasoningMessage) SetId(v string)`

SetId sets Id field to given value.


### GetRole

`func (o *ReasoningMessage) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *ReasoningMessage) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *ReasoningMessage) SetRole(v string)`

SetRole sets Role field to given value.

### HasRole

`func (o *ReasoningMessage) HasRole() bool`

HasRole returns a boolean if a field has been set.

### GetContent

`func (o *ReasoningMessage) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *ReasoningMessage) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *ReasoningMessage) SetContent(v string)`

SetContent sets Content field to given value.


### GetEncryptedValue

`func (o *ReasoningMessage) GetEncryptedValue() string`

GetEncryptedValue returns the EncryptedValue field if non-nil, zero value otherwise.

### GetEncryptedValueOk

`func (o *ReasoningMessage) GetEncryptedValueOk() (*string, bool)`

GetEncryptedValueOk returns a tuple with the EncryptedValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncryptedValue

`func (o *ReasoningMessage) SetEncryptedValue(v string)`

SetEncryptedValue sets EncryptedValue field to given value.

### HasEncryptedValue

`func (o *ReasoningMessage) HasEncryptedValue() bool`

HasEncryptedValue returns a boolean if a field has been set.

### SetEncryptedValueNil

`func (o *ReasoningMessage) SetEncryptedValueNil(b bool)`

 SetEncryptedValueNil sets the value for EncryptedValue to be an explicit nil

### UnsetEncryptedValue
`func (o *ReasoningMessage) UnsetEncryptedValue()`

UnsetEncryptedValue ensures that no value is present for EncryptedValue, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


