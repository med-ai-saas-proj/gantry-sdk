# AddRagFileRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FileUid** | **string** |  | 
**Lang** | Pointer to **string** |  | [optional] [default to "simple"]
**ChunkSplitter** | Pointer to [**ChunkSplitterType**](ChunkSplitterType.md) |  | [optional] [default to RECURSIVE]
**ChunkSplitterOptions** | Pointer to [**ChunkSplitterOptions**](ChunkSplitterOptions.md) |  | [optional] 
**ChunkSize** | Pointer to **int32** |  | [optional] [default to 1000]
**ChunkOverlap** | Pointer to **int32** |  | [optional] [default to 150]

## Methods

### NewAddRagFileRequest

`func NewAddRagFileRequest(fileUid string, ) *AddRagFileRequest`

NewAddRagFileRequest instantiates a new AddRagFileRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAddRagFileRequestWithDefaults

`func NewAddRagFileRequestWithDefaults() *AddRagFileRequest`

NewAddRagFileRequestWithDefaults instantiates a new AddRagFileRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFileUid

`func (o *AddRagFileRequest) GetFileUid() string`

GetFileUid returns the FileUid field if non-nil, zero value otherwise.

### GetFileUidOk

`func (o *AddRagFileRequest) GetFileUidOk() (*string, bool)`

GetFileUidOk returns a tuple with the FileUid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileUid

`func (o *AddRagFileRequest) SetFileUid(v string)`

SetFileUid sets FileUid field to given value.


### GetLang

`func (o *AddRagFileRequest) GetLang() string`

GetLang returns the Lang field if non-nil, zero value otherwise.

### GetLangOk

`func (o *AddRagFileRequest) GetLangOk() (*string, bool)`

GetLangOk returns a tuple with the Lang field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLang

`func (o *AddRagFileRequest) SetLang(v string)`

SetLang sets Lang field to given value.

### HasLang

`func (o *AddRagFileRequest) HasLang() bool`

HasLang returns a boolean if a field has been set.

### GetChunkSplitter

`func (o *AddRagFileRequest) GetChunkSplitter() ChunkSplitterType`

GetChunkSplitter returns the ChunkSplitter field if non-nil, zero value otherwise.

### GetChunkSplitterOk

`func (o *AddRagFileRequest) GetChunkSplitterOk() (*ChunkSplitterType, bool)`

GetChunkSplitterOk returns a tuple with the ChunkSplitter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkSplitter

`func (o *AddRagFileRequest) SetChunkSplitter(v ChunkSplitterType)`

SetChunkSplitter sets ChunkSplitter field to given value.

### HasChunkSplitter

`func (o *AddRagFileRequest) HasChunkSplitter() bool`

HasChunkSplitter returns a boolean if a field has been set.

### GetChunkSplitterOptions

`func (o *AddRagFileRequest) GetChunkSplitterOptions() ChunkSplitterOptions`

GetChunkSplitterOptions returns the ChunkSplitterOptions field if non-nil, zero value otherwise.

### GetChunkSplitterOptionsOk

`func (o *AddRagFileRequest) GetChunkSplitterOptionsOk() (*ChunkSplitterOptions, bool)`

GetChunkSplitterOptionsOk returns a tuple with the ChunkSplitterOptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkSplitterOptions

`func (o *AddRagFileRequest) SetChunkSplitterOptions(v ChunkSplitterOptions)`

SetChunkSplitterOptions sets ChunkSplitterOptions field to given value.

### HasChunkSplitterOptions

`func (o *AddRagFileRequest) HasChunkSplitterOptions() bool`

HasChunkSplitterOptions returns a boolean if a field has been set.

### GetChunkSize

`func (o *AddRagFileRequest) GetChunkSize() int32`

GetChunkSize returns the ChunkSize field if non-nil, zero value otherwise.

### GetChunkSizeOk

`func (o *AddRagFileRequest) GetChunkSizeOk() (*int32, bool)`

GetChunkSizeOk returns a tuple with the ChunkSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkSize

`func (o *AddRagFileRequest) SetChunkSize(v int32)`

SetChunkSize sets ChunkSize field to given value.

### HasChunkSize

`func (o *AddRagFileRequest) HasChunkSize() bool`

HasChunkSize returns a boolean if a field has been set.

### GetChunkOverlap

`func (o *AddRagFileRequest) GetChunkOverlap() int32`

GetChunkOverlap returns the ChunkOverlap field if non-nil, zero value otherwise.

### GetChunkOverlapOk

`func (o *AddRagFileRequest) GetChunkOverlapOk() (*int32, bool)`

GetChunkOverlapOk returns a tuple with the ChunkOverlap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkOverlap

`func (o *AddRagFileRequest) SetChunkOverlap(v int32)`

SetChunkOverlap sets ChunkOverlap field to given value.

### HasChunkOverlap

`func (o *AddRagFileRequest) HasChunkOverlap() bool`

HasChunkOverlap returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


