# RagQueryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FileInfo** | [**NullableFileInfoResponse**](FileInfoResponse.md) |  | 
**Text** | **string** |  | 
**Embedding** | **[]float32** |  | 
**CreatedAt** | **time.Time** |  | 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 
**VectorDistance** | Pointer to **NullableFloat32** |  | [optional] 
**Bm25Score** | Pointer to **NullableFloat32** |  | [optional] 
**RerankScore** | Pointer to **NullableFloat32** |  | [optional] 

## Methods

### NewRagQueryResponse

`func NewRagQueryResponse(fileInfo NullableFileInfoResponse, text string, embedding []float32, createdAt time.Time, ) *RagQueryResponse`

NewRagQueryResponse instantiates a new RagQueryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRagQueryResponseWithDefaults

`func NewRagQueryResponseWithDefaults() *RagQueryResponse`

NewRagQueryResponseWithDefaults instantiates a new RagQueryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFileInfo

`func (o *RagQueryResponse) GetFileInfo() FileInfoResponse`

GetFileInfo returns the FileInfo field if non-nil, zero value otherwise.

### GetFileInfoOk

`func (o *RagQueryResponse) GetFileInfoOk() (*FileInfoResponse, bool)`

GetFileInfoOk returns a tuple with the FileInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileInfo

`func (o *RagQueryResponse) SetFileInfo(v FileInfoResponse)`

SetFileInfo sets FileInfo field to given value.


### SetFileInfoNil

`func (o *RagQueryResponse) SetFileInfoNil(b bool)`

 SetFileInfoNil sets the value for FileInfo to be an explicit nil

### UnsetFileInfo
`func (o *RagQueryResponse) UnsetFileInfo()`

UnsetFileInfo ensures that no value is present for FileInfo, not even an explicit nil
### GetText

`func (o *RagQueryResponse) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *RagQueryResponse) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *RagQueryResponse) SetText(v string)`

SetText sets Text field to given value.


### GetEmbedding

`func (o *RagQueryResponse) GetEmbedding() []float32`

GetEmbedding returns the Embedding field if non-nil, zero value otherwise.

### GetEmbeddingOk

`func (o *RagQueryResponse) GetEmbeddingOk() (*[]float32, bool)`

GetEmbeddingOk returns a tuple with the Embedding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmbedding

`func (o *RagQueryResponse) SetEmbedding(v []float32)`

SetEmbedding sets Embedding field to given value.


### GetCreatedAt

`func (o *RagQueryResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RagQueryResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RagQueryResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetMetadata

`func (o *RagQueryResponse) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *RagQueryResponse) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *RagQueryResponse) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *RagQueryResponse) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *RagQueryResponse) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *RagQueryResponse) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetVectorDistance

`func (o *RagQueryResponse) GetVectorDistance() float32`

GetVectorDistance returns the VectorDistance field if non-nil, zero value otherwise.

### GetVectorDistanceOk

`func (o *RagQueryResponse) GetVectorDistanceOk() (*float32, bool)`

GetVectorDistanceOk returns a tuple with the VectorDistance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVectorDistance

`func (o *RagQueryResponse) SetVectorDistance(v float32)`

SetVectorDistance sets VectorDistance field to given value.

### HasVectorDistance

`func (o *RagQueryResponse) HasVectorDistance() bool`

HasVectorDistance returns a boolean if a field has been set.

### SetVectorDistanceNil

`func (o *RagQueryResponse) SetVectorDistanceNil(b bool)`

 SetVectorDistanceNil sets the value for VectorDistance to be an explicit nil

### UnsetVectorDistance
`func (o *RagQueryResponse) UnsetVectorDistance()`

UnsetVectorDistance ensures that no value is present for VectorDistance, not even an explicit nil
### GetBm25Score

`func (o *RagQueryResponse) GetBm25Score() float32`

GetBm25Score returns the Bm25Score field if non-nil, zero value otherwise.

### GetBm25ScoreOk

`func (o *RagQueryResponse) GetBm25ScoreOk() (*float32, bool)`

GetBm25ScoreOk returns a tuple with the Bm25Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBm25Score

`func (o *RagQueryResponse) SetBm25Score(v float32)`

SetBm25Score sets Bm25Score field to given value.

### HasBm25Score

`func (o *RagQueryResponse) HasBm25Score() bool`

HasBm25Score returns a boolean if a field has been set.

### SetBm25ScoreNil

`func (o *RagQueryResponse) SetBm25ScoreNil(b bool)`

 SetBm25ScoreNil sets the value for Bm25Score to be an explicit nil

### UnsetBm25Score
`func (o *RagQueryResponse) UnsetBm25Score()`

UnsetBm25Score ensures that no value is present for Bm25Score, not even an explicit nil
### GetRerankScore

`func (o *RagQueryResponse) GetRerankScore() float32`

GetRerankScore returns the RerankScore field if non-nil, zero value otherwise.

### GetRerankScoreOk

`func (o *RagQueryResponse) GetRerankScoreOk() (*float32, bool)`

GetRerankScoreOk returns a tuple with the RerankScore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRerankScore

`func (o *RagQueryResponse) SetRerankScore(v float32)`

SetRerankScore sets RerankScore field to given value.

### HasRerankScore

`func (o *RagQueryResponse) HasRerankScore() bool`

HasRerankScore returns a boolean if a field has been set.

### SetRerankScoreNil

`func (o *RagQueryResponse) SetRerankScoreNil(b bool)`

 SetRerankScoreNil sets the value for RerankScore to be an explicit nil

### UnsetRerankScore
`func (o *RagQueryResponse) UnsetRerankScore()`

UnsetRerankScore ensures that no value is present for RerankScore, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


