# RecursiveCharacterTextSplitterOptions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Separators** | Pointer to **[]string** |  | [optional] 
**KeepSeparator** | Pointer to [**KeepSeparator**](KeepSeparator.md) |  | [optional] 
**IsSeparatorRegex** | Pointer to **bool** |  | [optional] 
**ChunkSize** | Pointer to **int32** |  | [optional] 
**ChunkOverlap** | Pointer to **int32** |  | [optional] 

## Methods

### NewRecursiveCharacterTextSplitterOptions

`func NewRecursiveCharacterTextSplitterOptions() *RecursiveCharacterTextSplitterOptions`

NewRecursiveCharacterTextSplitterOptions instantiates a new RecursiveCharacterTextSplitterOptions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecursiveCharacterTextSplitterOptionsWithDefaults

`func NewRecursiveCharacterTextSplitterOptionsWithDefaults() *RecursiveCharacterTextSplitterOptions`

NewRecursiveCharacterTextSplitterOptionsWithDefaults instantiates a new RecursiveCharacterTextSplitterOptions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSeparators

`func (o *RecursiveCharacterTextSplitterOptions) GetSeparators() []string`

GetSeparators returns the Separators field if non-nil, zero value otherwise.

### GetSeparatorsOk

`func (o *RecursiveCharacterTextSplitterOptions) GetSeparatorsOk() (*[]string, bool)`

GetSeparatorsOk returns a tuple with the Separators field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeparators

`func (o *RecursiveCharacterTextSplitterOptions) SetSeparators(v []string)`

SetSeparators sets Separators field to given value.

### HasSeparators

`func (o *RecursiveCharacterTextSplitterOptions) HasSeparators() bool`

HasSeparators returns a boolean if a field has been set.

### GetKeepSeparator

`func (o *RecursiveCharacterTextSplitterOptions) GetKeepSeparator() KeepSeparator`

GetKeepSeparator returns the KeepSeparator field if non-nil, zero value otherwise.

### GetKeepSeparatorOk

`func (o *RecursiveCharacterTextSplitterOptions) GetKeepSeparatorOk() (*KeepSeparator, bool)`

GetKeepSeparatorOk returns a tuple with the KeepSeparator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeepSeparator

`func (o *RecursiveCharacterTextSplitterOptions) SetKeepSeparator(v KeepSeparator)`

SetKeepSeparator sets KeepSeparator field to given value.

### HasKeepSeparator

`func (o *RecursiveCharacterTextSplitterOptions) HasKeepSeparator() bool`

HasKeepSeparator returns a boolean if a field has been set.

### GetIsSeparatorRegex

`func (o *RecursiveCharacterTextSplitterOptions) GetIsSeparatorRegex() bool`

GetIsSeparatorRegex returns the IsSeparatorRegex field if non-nil, zero value otherwise.

### GetIsSeparatorRegexOk

`func (o *RecursiveCharacterTextSplitterOptions) GetIsSeparatorRegexOk() (*bool, bool)`

GetIsSeparatorRegexOk returns a tuple with the IsSeparatorRegex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSeparatorRegex

`func (o *RecursiveCharacterTextSplitterOptions) SetIsSeparatorRegex(v bool)`

SetIsSeparatorRegex sets IsSeparatorRegex field to given value.

### HasIsSeparatorRegex

`func (o *RecursiveCharacterTextSplitterOptions) HasIsSeparatorRegex() bool`

HasIsSeparatorRegex returns a boolean if a field has been set.

### GetChunkSize

`func (o *RecursiveCharacterTextSplitterOptions) GetChunkSize() int32`

GetChunkSize returns the ChunkSize field if non-nil, zero value otherwise.

### GetChunkSizeOk

`func (o *RecursiveCharacterTextSplitterOptions) GetChunkSizeOk() (*int32, bool)`

GetChunkSizeOk returns a tuple with the ChunkSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkSize

`func (o *RecursiveCharacterTextSplitterOptions) SetChunkSize(v int32)`

SetChunkSize sets ChunkSize field to given value.

### HasChunkSize

`func (o *RecursiveCharacterTextSplitterOptions) HasChunkSize() bool`

HasChunkSize returns a boolean if a field has been set.

### GetChunkOverlap

`func (o *RecursiveCharacterTextSplitterOptions) GetChunkOverlap() int32`

GetChunkOverlap returns the ChunkOverlap field if non-nil, zero value otherwise.

### GetChunkOverlapOk

`func (o *RecursiveCharacterTextSplitterOptions) GetChunkOverlapOk() (*int32, bool)`

GetChunkOverlapOk returns a tuple with the ChunkOverlap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkOverlap

`func (o *RecursiveCharacterTextSplitterOptions) SetChunkOverlap(v int32)`

SetChunkOverlap sets ChunkOverlap field to given value.

### HasChunkOverlap

`func (o *RecursiveCharacterTextSplitterOptions) HasChunkOverlap() bool`

HasChunkOverlap returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


