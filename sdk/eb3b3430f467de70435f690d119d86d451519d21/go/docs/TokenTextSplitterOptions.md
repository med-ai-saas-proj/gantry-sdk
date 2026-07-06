# TokenTextSplitterOptions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EncodingName** | Pointer to **string** |  | [optional] 
**ModelName** | Pointer to **NullableString** |  | [optional] 
**AllowedSpecial** | Pointer to [**NullableAllowedSpecial**](AllowedSpecial.md) |  | [optional] 
**DisallowedSpecial** | Pointer to [**DisallowedSpecial**](DisallowedSpecial.md) |  | [optional] 
**ChunkSize** | Pointer to **int32** |  | [optional] 
**ChunkOverlap** | Pointer to **int32** |  | [optional] 

## Methods

### NewTokenTextSplitterOptions

`func NewTokenTextSplitterOptions() *TokenTextSplitterOptions`

NewTokenTextSplitterOptions instantiates a new TokenTextSplitterOptions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTokenTextSplitterOptionsWithDefaults

`func NewTokenTextSplitterOptionsWithDefaults() *TokenTextSplitterOptions`

NewTokenTextSplitterOptionsWithDefaults instantiates a new TokenTextSplitterOptions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEncodingName

`func (o *TokenTextSplitterOptions) GetEncodingName() string`

GetEncodingName returns the EncodingName field if non-nil, zero value otherwise.

### GetEncodingNameOk

`func (o *TokenTextSplitterOptions) GetEncodingNameOk() (*string, bool)`

GetEncodingNameOk returns a tuple with the EncodingName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncodingName

`func (o *TokenTextSplitterOptions) SetEncodingName(v string)`

SetEncodingName sets EncodingName field to given value.

### HasEncodingName

`func (o *TokenTextSplitterOptions) HasEncodingName() bool`

HasEncodingName returns a boolean if a field has been set.

### GetModelName

`func (o *TokenTextSplitterOptions) GetModelName() string`

GetModelName returns the ModelName field if non-nil, zero value otherwise.

### GetModelNameOk

`func (o *TokenTextSplitterOptions) GetModelNameOk() (*string, bool)`

GetModelNameOk returns a tuple with the ModelName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelName

`func (o *TokenTextSplitterOptions) SetModelName(v string)`

SetModelName sets ModelName field to given value.

### HasModelName

`func (o *TokenTextSplitterOptions) HasModelName() bool`

HasModelName returns a boolean if a field has been set.

### SetModelNameNil

`func (o *TokenTextSplitterOptions) SetModelNameNil(b bool)`

 SetModelNameNil sets the value for ModelName to be an explicit nil

### UnsetModelName
`func (o *TokenTextSplitterOptions) UnsetModelName()`

UnsetModelName ensures that no value is present for ModelName, not even an explicit nil
### GetAllowedSpecial

`func (o *TokenTextSplitterOptions) GetAllowedSpecial() AllowedSpecial`

GetAllowedSpecial returns the AllowedSpecial field if non-nil, zero value otherwise.

### GetAllowedSpecialOk

`func (o *TokenTextSplitterOptions) GetAllowedSpecialOk() (*AllowedSpecial, bool)`

GetAllowedSpecialOk returns a tuple with the AllowedSpecial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowedSpecial

`func (o *TokenTextSplitterOptions) SetAllowedSpecial(v AllowedSpecial)`

SetAllowedSpecial sets AllowedSpecial field to given value.

### HasAllowedSpecial

`func (o *TokenTextSplitterOptions) HasAllowedSpecial() bool`

HasAllowedSpecial returns a boolean if a field has been set.

### SetAllowedSpecialNil

`func (o *TokenTextSplitterOptions) SetAllowedSpecialNil(b bool)`

 SetAllowedSpecialNil sets the value for AllowedSpecial to be an explicit nil

### UnsetAllowedSpecial
`func (o *TokenTextSplitterOptions) UnsetAllowedSpecial()`

UnsetAllowedSpecial ensures that no value is present for AllowedSpecial, not even an explicit nil
### GetDisallowedSpecial

`func (o *TokenTextSplitterOptions) GetDisallowedSpecial() DisallowedSpecial`

GetDisallowedSpecial returns the DisallowedSpecial field if non-nil, zero value otherwise.

### GetDisallowedSpecialOk

`func (o *TokenTextSplitterOptions) GetDisallowedSpecialOk() (*DisallowedSpecial, bool)`

GetDisallowedSpecialOk returns a tuple with the DisallowedSpecial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisallowedSpecial

`func (o *TokenTextSplitterOptions) SetDisallowedSpecial(v DisallowedSpecial)`

SetDisallowedSpecial sets DisallowedSpecial field to given value.

### HasDisallowedSpecial

`func (o *TokenTextSplitterOptions) HasDisallowedSpecial() bool`

HasDisallowedSpecial returns a boolean if a field has been set.

### GetChunkSize

`func (o *TokenTextSplitterOptions) GetChunkSize() int32`

GetChunkSize returns the ChunkSize field if non-nil, zero value otherwise.

### GetChunkSizeOk

`func (o *TokenTextSplitterOptions) GetChunkSizeOk() (*int32, bool)`

GetChunkSizeOk returns a tuple with the ChunkSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkSize

`func (o *TokenTextSplitterOptions) SetChunkSize(v int32)`

SetChunkSize sets ChunkSize field to given value.

### HasChunkSize

`func (o *TokenTextSplitterOptions) HasChunkSize() bool`

HasChunkSize returns a boolean if a field has been set.

### GetChunkOverlap

`func (o *TokenTextSplitterOptions) GetChunkOverlap() int32`

GetChunkOverlap returns the ChunkOverlap field if non-nil, zero value otherwise.

### GetChunkOverlapOk

`func (o *TokenTextSplitterOptions) GetChunkOverlapOk() (*int32, bool)`

GetChunkOverlapOk returns a tuple with the ChunkOverlap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkOverlap

`func (o *TokenTextSplitterOptions) SetChunkOverlap(v int32)`

SetChunkOverlap sets ChunkOverlap field to given value.

### HasChunkOverlap

`func (o *TokenTextSplitterOptions) HasChunkOverlap() bool`

HasChunkOverlap returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


