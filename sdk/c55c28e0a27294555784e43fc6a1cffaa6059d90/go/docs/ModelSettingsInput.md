# ModelSettingsInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MaxTokens** | Pointer to **int32** |  | [optional] 
**Temperature** | Pointer to **float32** |  | [optional] 
**TopP** | Pointer to **float32** |  | [optional] 
**Timeout** | Pointer to **float32** |  | [optional] 
**ParallelToolCalls** | Pointer to **bool** |  | [optional] 
**Seed** | Pointer to **int32** |  | [optional] 
**PresencePenalty** | Pointer to **float32** |  | [optional] 
**FrequencyPenalty** | Pointer to **float32** |  | [optional] 
**LogitBias** | Pointer to **map[string]int32** |  | [optional] 
**StopSequences** | Pointer to **[]string** |  | [optional] 
**Thinking** | Pointer to [**Thinking**](Thinking.md) |  | [optional] 
**ServiceTier** | Pointer to **string** |  | [optional] 

## Methods

### NewModelSettingsInput

`func NewModelSettingsInput() *ModelSettingsInput`

NewModelSettingsInput instantiates a new ModelSettingsInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModelSettingsInputWithDefaults

`func NewModelSettingsInputWithDefaults() *ModelSettingsInput`

NewModelSettingsInputWithDefaults instantiates a new ModelSettingsInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMaxTokens

`func (o *ModelSettingsInput) GetMaxTokens() int32`

GetMaxTokens returns the MaxTokens field if non-nil, zero value otherwise.

### GetMaxTokensOk

`func (o *ModelSettingsInput) GetMaxTokensOk() (*int32, bool)`

GetMaxTokensOk returns a tuple with the MaxTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxTokens

`func (o *ModelSettingsInput) SetMaxTokens(v int32)`

SetMaxTokens sets MaxTokens field to given value.

### HasMaxTokens

`func (o *ModelSettingsInput) HasMaxTokens() bool`

HasMaxTokens returns a boolean if a field has been set.

### GetTemperature

`func (o *ModelSettingsInput) GetTemperature() float32`

GetTemperature returns the Temperature field if non-nil, zero value otherwise.

### GetTemperatureOk

`func (o *ModelSettingsInput) GetTemperatureOk() (*float32, bool)`

GetTemperatureOk returns a tuple with the Temperature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemperature

`func (o *ModelSettingsInput) SetTemperature(v float32)`

SetTemperature sets Temperature field to given value.

### HasTemperature

`func (o *ModelSettingsInput) HasTemperature() bool`

HasTemperature returns a boolean if a field has been set.

### GetTopP

`func (o *ModelSettingsInput) GetTopP() float32`

GetTopP returns the TopP field if non-nil, zero value otherwise.

### GetTopPOk

`func (o *ModelSettingsInput) GetTopPOk() (*float32, bool)`

GetTopPOk returns a tuple with the TopP field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopP

`func (o *ModelSettingsInput) SetTopP(v float32)`

SetTopP sets TopP field to given value.

### HasTopP

`func (o *ModelSettingsInput) HasTopP() bool`

HasTopP returns a boolean if a field has been set.

### GetTimeout

`func (o *ModelSettingsInput) GetTimeout() float32`

GetTimeout returns the Timeout field if non-nil, zero value otherwise.

### GetTimeoutOk

`func (o *ModelSettingsInput) GetTimeoutOk() (*float32, bool)`

GetTimeoutOk returns a tuple with the Timeout field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeout

`func (o *ModelSettingsInput) SetTimeout(v float32)`

SetTimeout sets Timeout field to given value.

### HasTimeout

`func (o *ModelSettingsInput) HasTimeout() bool`

HasTimeout returns a boolean if a field has been set.

### GetParallelToolCalls

`func (o *ModelSettingsInput) GetParallelToolCalls() bool`

GetParallelToolCalls returns the ParallelToolCalls field if non-nil, zero value otherwise.

### GetParallelToolCallsOk

`func (o *ModelSettingsInput) GetParallelToolCallsOk() (*bool, bool)`

GetParallelToolCallsOk returns a tuple with the ParallelToolCalls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParallelToolCalls

`func (o *ModelSettingsInput) SetParallelToolCalls(v bool)`

SetParallelToolCalls sets ParallelToolCalls field to given value.

### HasParallelToolCalls

`func (o *ModelSettingsInput) HasParallelToolCalls() bool`

HasParallelToolCalls returns a boolean if a field has been set.

### GetSeed

`func (o *ModelSettingsInput) GetSeed() int32`

GetSeed returns the Seed field if non-nil, zero value otherwise.

### GetSeedOk

`func (o *ModelSettingsInput) GetSeedOk() (*int32, bool)`

GetSeedOk returns a tuple with the Seed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeed

`func (o *ModelSettingsInput) SetSeed(v int32)`

SetSeed sets Seed field to given value.

### HasSeed

`func (o *ModelSettingsInput) HasSeed() bool`

HasSeed returns a boolean if a field has been set.

### GetPresencePenalty

`func (o *ModelSettingsInput) GetPresencePenalty() float32`

GetPresencePenalty returns the PresencePenalty field if non-nil, zero value otherwise.

### GetPresencePenaltyOk

`func (o *ModelSettingsInput) GetPresencePenaltyOk() (*float32, bool)`

GetPresencePenaltyOk returns a tuple with the PresencePenalty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPresencePenalty

`func (o *ModelSettingsInput) SetPresencePenalty(v float32)`

SetPresencePenalty sets PresencePenalty field to given value.

### HasPresencePenalty

`func (o *ModelSettingsInput) HasPresencePenalty() bool`

HasPresencePenalty returns a boolean if a field has been set.

### GetFrequencyPenalty

`func (o *ModelSettingsInput) GetFrequencyPenalty() float32`

GetFrequencyPenalty returns the FrequencyPenalty field if non-nil, zero value otherwise.

### GetFrequencyPenaltyOk

`func (o *ModelSettingsInput) GetFrequencyPenaltyOk() (*float32, bool)`

GetFrequencyPenaltyOk returns a tuple with the FrequencyPenalty field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrequencyPenalty

`func (o *ModelSettingsInput) SetFrequencyPenalty(v float32)`

SetFrequencyPenalty sets FrequencyPenalty field to given value.

### HasFrequencyPenalty

`func (o *ModelSettingsInput) HasFrequencyPenalty() bool`

HasFrequencyPenalty returns a boolean if a field has been set.

### GetLogitBias

`func (o *ModelSettingsInput) GetLogitBias() map[string]int32`

GetLogitBias returns the LogitBias field if non-nil, zero value otherwise.

### GetLogitBiasOk

`func (o *ModelSettingsInput) GetLogitBiasOk() (*map[string]int32, bool)`

GetLogitBiasOk returns a tuple with the LogitBias field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogitBias

`func (o *ModelSettingsInput) SetLogitBias(v map[string]int32)`

SetLogitBias sets LogitBias field to given value.

### HasLogitBias

`func (o *ModelSettingsInput) HasLogitBias() bool`

HasLogitBias returns a boolean if a field has been set.

### GetStopSequences

`func (o *ModelSettingsInput) GetStopSequences() []string`

GetStopSequences returns the StopSequences field if non-nil, zero value otherwise.

### GetStopSequencesOk

`func (o *ModelSettingsInput) GetStopSequencesOk() (*[]string, bool)`

GetStopSequencesOk returns a tuple with the StopSequences field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopSequences

`func (o *ModelSettingsInput) SetStopSequences(v []string)`

SetStopSequences sets StopSequences field to given value.

### HasStopSequences

`func (o *ModelSettingsInput) HasStopSequences() bool`

HasStopSequences returns a boolean if a field has been set.

### GetThinking

`func (o *ModelSettingsInput) GetThinking() Thinking`

GetThinking returns the Thinking field if non-nil, zero value otherwise.

### GetThinkingOk

`func (o *ModelSettingsInput) GetThinkingOk() (*Thinking, bool)`

GetThinkingOk returns a tuple with the Thinking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThinking

`func (o *ModelSettingsInput) SetThinking(v Thinking)`

SetThinking sets Thinking field to given value.

### HasThinking

`func (o *ModelSettingsInput) HasThinking() bool`

HasThinking returns a boolean if a field has been set.

### GetServiceTier

`func (o *ModelSettingsInput) GetServiceTier() string`

GetServiceTier returns the ServiceTier field if non-nil, zero value otherwise.

### GetServiceTierOk

`func (o *ModelSettingsInput) GetServiceTierOk() (*string, bool)`

GetServiceTierOk returns a tuple with the ServiceTier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceTier

`func (o *ModelSettingsInput) SetServiceTier(v string)`

SetServiceTier sets ServiceTier field to given value.

### HasServiceTier

`func (o *ModelSettingsInput) HasServiceTier() bool`

HasServiceTier returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


