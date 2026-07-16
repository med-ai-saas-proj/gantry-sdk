# AddTextToRagRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | [**Text**](Text.md) |  | 
**Lang** | Pointer to **string** |  | [optional] [default to "simple"]
**ChunkSplitter** | Pointer to [**ChunkSplitterType**](ChunkSplitterType.md) |  | [optional] [default to RECURSIVE]
**ChunkSplitterOptions** | Pointer to [**ChunkSplitterOptions**](ChunkSplitterOptions.md) |  | [optional] 
**ChunkSize** | Pointer to **int32** |  | [optional] [default to 1000]
**ChunkOverlap** | Pointer to **int32** |  | [optional] [default to 150]
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewAddTextToRagRequest

`func NewAddTextToRagRequest(text Text, ) *AddTextToRagRequest`

NewAddTextToRagRequest instantiates a new AddTextToRagRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAddTextToRagRequestWithDefaults

`func NewAddTextToRagRequestWithDefaults() *AddTextToRagRequest`

NewAddTextToRagRequestWithDefaults instantiates a new AddTextToRagRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *AddTextToRagRequest) GetText() Text`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *AddTextToRagRequest) GetTextOk() (*Text, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *AddTextToRagRequest) SetText(v Text)`

SetText sets Text field to given value.


### GetLang

`func (o *AddTextToRagRequest) GetLang() string`

GetLang returns the Lang field if non-nil, zero value otherwise.

### GetLangOk

`func (o *AddTextToRagRequest) GetLangOk() (*string, bool)`

GetLangOk returns a tuple with the Lang field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLang

`func (o *AddTextToRagRequest) SetLang(v string)`

SetLang sets Lang field to given value.

### HasLang

`func (o *AddTextToRagRequest) HasLang() bool`

HasLang returns a boolean if a field has been set.

### GetChunkSplitter

`func (o *AddTextToRagRequest) GetChunkSplitter() ChunkSplitterType`

GetChunkSplitter returns the ChunkSplitter field if non-nil, zero value otherwise.

### GetChunkSplitterOk

`func (o *AddTextToRagRequest) GetChunkSplitterOk() (*ChunkSplitterType, bool)`

GetChunkSplitterOk returns a tuple with the ChunkSplitter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkSplitter

`func (o *AddTextToRagRequest) SetChunkSplitter(v ChunkSplitterType)`

SetChunkSplitter sets ChunkSplitter field to given value.

### HasChunkSplitter

`func (o *AddTextToRagRequest) HasChunkSplitter() bool`

HasChunkSplitter returns a boolean if a field has been set.

### GetChunkSplitterOptions

`func (o *AddTextToRagRequest) GetChunkSplitterOptions() ChunkSplitterOptions`

GetChunkSplitterOptions returns the ChunkSplitterOptions field if non-nil, zero value otherwise.

### GetChunkSplitterOptionsOk

`func (o *AddTextToRagRequest) GetChunkSplitterOptionsOk() (*ChunkSplitterOptions, bool)`

GetChunkSplitterOptionsOk returns a tuple with the ChunkSplitterOptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkSplitterOptions

`func (o *AddTextToRagRequest) SetChunkSplitterOptions(v ChunkSplitterOptions)`

SetChunkSplitterOptions sets ChunkSplitterOptions field to given value.

### HasChunkSplitterOptions

`func (o *AddTextToRagRequest) HasChunkSplitterOptions() bool`

HasChunkSplitterOptions returns a boolean if a field has been set.

### GetChunkSize

`func (o *AddTextToRagRequest) GetChunkSize() int32`

GetChunkSize returns the ChunkSize field if non-nil, zero value otherwise.

### GetChunkSizeOk

`func (o *AddTextToRagRequest) GetChunkSizeOk() (*int32, bool)`

GetChunkSizeOk returns a tuple with the ChunkSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkSize

`func (o *AddTextToRagRequest) SetChunkSize(v int32)`

SetChunkSize sets ChunkSize field to given value.

### HasChunkSize

`func (o *AddTextToRagRequest) HasChunkSize() bool`

HasChunkSize returns a boolean if a field has been set.

### GetChunkOverlap

`func (o *AddTextToRagRequest) GetChunkOverlap() int32`

GetChunkOverlap returns the ChunkOverlap field if non-nil, zero value otherwise.

### GetChunkOverlapOk

`func (o *AddTextToRagRequest) GetChunkOverlapOk() (*int32, bool)`

GetChunkOverlapOk returns a tuple with the ChunkOverlap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkOverlap

`func (o *AddTextToRagRequest) SetChunkOverlap(v int32)`

SetChunkOverlap sets ChunkOverlap field to given value.

### HasChunkOverlap

`func (o *AddTextToRagRequest) HasChunkOverlap() bool`

HasChunkOverlap returns a boolean if a field has been set.

### GetMetadata

`func (o *AddTextToRagRequest) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *AddTextToRagRequest) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *AddTextToRagRequest) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *AddTextToRagRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *AddTextToRagRequest) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *AddTextToRagRequest) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


