# CharacterTextSplitterOptions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Separator** | Pointer to **string** |  | [optional] 
**IsSeparatorRegex** | Pointer to **bool** |  | [optional] 
**ChunkSize** | Pointer to **int32** |  | [optional] 
**ChunkOverlap** | Pointer to **int32** |  | [optional] 
**KeepSeparator** | Pointer to [**KeepSeparator**](KeepSeparator.md) |  | [optional] 

## Methods

### NewCharacterTextSplitterOptions

`func NewCharacterTextSplitterOptions() *CharacterTextSplitterOptions`

NewCharacterTextSplitterOptions instantiates a new CharacterTextSplitterOptions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCharacterTextSplitterOptionsWithDefaults

`func NewCharacterTextSplitterOptionsWithDefaults() *CharacterTextSplitterOptions`

NewCharacterTextSplitterOptionsWithDefaults instantiates a new CharacterTextSplitterOptions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSeparator

`func (o *CharacterTextSplitterOptions) GetSeparator() string`

GetSeparator returns the Separator field if non-nil, zero value otherwise.

### GetSeparatorOk

`func (o *CharacterTextSplitterOptions) GetSeparatorOk() (*string, bool)`

GetSeparatorOk returns a tuple with the Separator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeparator

`func (o *CharacterTextSplitterOptions) SetSeparator(v string)`

SetSeparator sets Separator field to given value.

### HasSeparator

`func (o *CharacterTextSplitterOptions) HasSeparator() bool`

HasSeparator returns a boolean if a field has been set.

### GetIsSeparatorRegex

`func (o *CharacterTextSplitterOptions) GetIsSeparatorRegex() bool`

GetIsSeparatorRegex returns the IsSeparatorRegex field if non-nil, zero value otherwise.

### GetIsSeparatorRegexOk

`func (o *CharacterTextSplitterOptions) GetIsSeparatorRegexOk() (*bool, bool)`

GetIsSeparatorRegexOk returns a tuple with the IsSeparatorRegex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSeparatorRegex

`func (o *CharacterTextSplitterOptions) SetIsSeparatorRegex(v bool)`

SetIsSeparatorRegex sets IsSeparatorRegex field to given value.

### HasIsSeparatorRegex

`func (o *CharacterTextSplitterOptions) HasIsSeparatorRegex() bool`

HasIsSeparatorRegex returns a boolean if a field has been set.

### GetChunkSize

`func (o *CharacterTextSplitterOptions) GetChunkSize() int32`

GetChunkSize returns the ChunkSize field if non-nil, zero value otherwise.

### GetChunkSizeOk

`func (o *CharacterTextSplitterOptions) GetChunkSizeOk() (*int32, bool)`

GetChunkSizeOk returns a tuple with the ChunkSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkSize

`func (o *CharacterTextSplitterOptions) SetChunkSize(v int32)`

SetChunkSize sets ChunkSize field to given value.

### HasChunkSize

`func (o *CharacterTextSplitterOptions) HasChunkSize() bool`

HasChunkSize returns a boolean if a field has been set.

### GetChunkOverlap

`func (o *CharacterTextSplitterOptions) GetChunkOverlap() int32`

GetChunkOverlap returns the ChunkOverlap field if non-nil, zero value otherwise.

### GetChunkOverlapOk

`func (o *CharacterTextSplitterOptions) GetChunkOverlapOk() (*int32, bool)`

GetChunkOverlapOk returns a tuple with the ChunkOverlap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkOverlap

`func (o *CharacterTextSplitterOptions) SetChunkOverlap(v int32)`

SetChunkOverlap sets ChunkOverlap field to given value.

### HasChunkOverlap

`func (o *CharacterTextSplitterOptions) HasChunkOverlap() bool`

HasChunkOverlap returns a boolean if a field has been set.

### GetKeepSeparator

`func (o *CharacterTextSplitterOptions) GetKeepSeparator() KeepSeparator`

GetKeepSeparator returns the KeepSeparator field if non-nil, zero value otherwise.

### GetKeepSeparatorOk

`func (o *CharacterTextSplitterOptions) GetKeepSeparatorOk() (*KeepSeparator, bool)`

GetKeepSeparatorOk returns a tuple with the KeepSeparator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeepSeparator

`func (o *CharacterTextSplitterOptions) SetKeepSeparator(v KeepSeparator)`

SetKeepSeparator sets KeepSeparator field to given value.

### HasKeepSeparator

`func (o *CharacterTextSplitterOptions) HasKeepSeparator() bool`

HasKeepSeparator returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


