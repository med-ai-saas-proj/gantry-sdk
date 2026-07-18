# EmbeddingTaskResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TaskId** | **string** |  | 
**FileUid** | **NullableString** |  | 
**Text** | [**NullableText1**](Text1.md) |  | 
**Metadata** | **map[string]interface{}** |  | 
**Type** | **string** |  | 
**ProjectUuid** | **string** |  | 
**ChunkSplitter** | [**ChunkSplitterType**](ChunkSplitterType.md) |  | 
**ChunkSplitterOptions** | Pointer to [**ChunkSplitterOptions**](ChunkSplitterOptions.md) |  | [optional] 
**ChunkSize** | **int32** |  | 
**ChunkOverlap** | **int32** |  | 
**FailedReason** | Pointer to **NullableString** |  | [optional] 
**Status** | **string** |  | 

## Methods

### NewEmbeddingTaskResponse

`func NewEmbeddingTaskResponse(taskId string, fileUid NullableString, text NullableText1, metadata map[string]interface{}, type_ string, projectUuid string, chunkSplitter ChunkSplitterType, chunkSize int32, chunkOverlap int32, status string, ) *EmbeddingTaskResponse`

NewEmbeddingTaskResponse instantiates a new EmbeddingTaskResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmbeddingTaskResponseWithDefaults

`func NewEmbeddingTaskResponseWithDefaults() *EmbeddingTaskResponse`

NewEmbeddingTaskResponseWithDefaults instantiates a new EmbeddingTaskResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTaskId

`func (o *EmbeddingTaskResponse) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *EmbeddingTaskResponse) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *EmbeddingTaskResponse) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### GetFileUid

`func (o *EmbeddingTaskResponse) GetFileUid() string`

GetFileUid returns the FileUid field if non-nil, zero value otherwise.

### GetFileUidOk

`func (o *EmbeddingTaskResponse) GetFileUidOk() (*string, bool)`

GetFileUidOk returns a tuple with the FileUid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileUid

`func (o *EmbeddingTaskResponse) SetFileUid(v string)`

SetFileUid sets FileUid field to given value.


### SetFileUidNil

`func (o *EmbeddingTaskResponse) SetFileUidNil(b bool)`

 SetFileUidNil sets the value for FileUid to be an explicit nil

### UnsetFileUid
`func (o *EmbeddingTaskResponse) UnsetFileUid()`

UnsetFileUid ensures that no value is present for FileUid, not even an explicit nil
### GetText

`func (o *EmbeddingTaskResponse) GetText() Text1`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *EmbeddingTaskResponse) GetTextOk() (*Text1, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *EmbeddingTaskResponse) SetText(v Text1)`

SetText sets Text field to given value.


### SetTextNil

`func (o *EmbeddingTaskResponse) SetTextNil(b bool)`

 SetTextNil sets the value for Text to be an explicit nil

### UnsetText
`func (o *EmbeddingTaskResponse) UnsetText()`

UnsetText ensures that no value is present for Text, not even an explicit nil
### GetMetadata

`func (o *EmbeddingTaskResponse) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *EmbeddingTaskResponse) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *EmbeddingTaskResponse) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.


### SetMetadataNil

`func (o *EmbeddingTaskResponse) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *EmbeddingTaskResponse) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetType

`func (o *EmbeddingTaskResponse) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *EmbeddingTaskResponse) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *EmbeddingTaskResponse) SetType(v string)`

SetType sets Type field to given value.


### GetProjectUuid

`func (o *EmbeddingTaskResponse) GetProjectUuid() string`

GetProjectUuid returns the ProjectUuid field if non-nil, zero value otherwise.

### GetProjectUuidOk

`func (o *EmbeddingTaskResponse) GetProjectUuidOk() (*string, bool)`

GetProjectUuidOk returns a tuple with the ProjectUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectUuid

`func (o *EmbeddingTaskResponse) SetProjectUuid(v string)`

SetProjectUuid sets ProjectUuid field to given value.


### GetChunkSplitter

`func (o *EmbeddingTaskResponse) GetChunkSplitter() ChunkSplitterType`

GetChunkSplitter returns the ChunkSplitter field if non-nil, zero value otherwise.

### GetChunkSplitterOk

`func (o *EmbeddingTaskResponse) GetChunkSplitterOk() (*ChunkSplitterType, bool)`

GetChunkSplitterOk returns a tuple with the ChunkSplitter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkSplitter

`func (o *EmbeddingTaskResponse) SetChunkSplitter(v ChunkSplitterType)`

SetChunkSplitter sets ChunkSplitter field to given value.


### GetChunkSplitterOptions

`func (o *EmbeddingTaskResponse) GetChunkSplitterOptions() ChunkSplitterOptions`

GetChunkSplitterOptions returns the ChunkSplitterOptions field if non-nil, zero value otherwise.

### GetChunkSplitterOptionsOk

`func (o *EmbeddingTaskResponse) GetChunkSplitterOptionsOk() (*ChunkSplitterOptions, bool)`

GetChunkSplitterOptionsOk returns a tuple with the ChunkSplitterOptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkSplitterOptions

`func (o *EmbeddingTaskResponse) SetChunkSplitterOptions(v ChunkSplitterOptions)`

SetChunkSplitterOptions sets ChunkSplitterOptions field to given value.

### HasChunkSplitterOptions

`func (o *EmbeddingTaskResponse) HasChunkSplitterOptions() bool`

HasChunkSplitterOptions returns a boolean if a field has been set.

### GetChunkSize

`func (o *EmbeddingTaskResponse) GetChunkSize() int32`

GetChunkSize returns the ChunkSize field if non-nil, zero value otherwise.

### GetChunkSizeOk

`func (o *EmbeddingTaskResponse) GetChunkSizeOk() (*int32, bool)`

GetChunkSizeOk returns a tuple with the ChunkSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkSize

`func (o *EmbeddingTaskResponse) SetChunkSize(v int32)`

SetChunkSize sets ChunkSize field to given value.


### GetChunkOverlap

`func (o *EmbeddingTaskResponse) GetChunkOverlap() int32`

GetChunkOverlap returns the ChunkOverlap field if non-nil, zero value otherwise.

### GetChunkOverlapOk

`func (o *EmbeddingTaskResponse) GetChunkOverlapOk() (*int32, bool)`

GetChunkOverlapOk returns a tuple with the ChunkOverlap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkOverlap

`func (o *EmbeddingTaskResponse) SetChunkOverlap(v int32)`

SetChunkOverlap sets ChunkOverlap field to given value.


### GetFailedReason

`func (o *EmbeddingTaskResponse) GetFailedReason() string`

GetFailedReason returns the FailedReason field if non-nil, zero value otherwise.

### GetFailedReasonOk

`func (o *EmbeddingTaskResponse) GetFailedReasonOk() (*string, bool)`

GetFailedReasonOk returns a tuple with the FailedReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailedReason

`func (o *EmbeddingTaskResponse) SetFailedReason(v string)`

SetFailedReason sets FailedReason field to given value.

### HasFailedReason

`func (o *EmbeddingTaskResponse) HasFailedReason() bool`

HasFailedReason returns a boolean if a field has been set.

### SetFailedReasonNil

`func (o *EmbeddingTaskResponse) SetFailedReasonNil(b bool)`

 SetFailedReasonNil sets the value for FailedReason to be an explicit nil

### UnsetFailedReason
`func (o *EmbeddingTaskResponse) UnsetFailedReason()`

UnsetFailedReason ensures that no value is present for FailedReason, not even an explicit nil
### GetStatus

`func (o *EmbeddingTaskResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *EmbeddingTaskResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *EmbeddingTaskResponse) SetStatus(v string)`

SetStatus sets Status field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


