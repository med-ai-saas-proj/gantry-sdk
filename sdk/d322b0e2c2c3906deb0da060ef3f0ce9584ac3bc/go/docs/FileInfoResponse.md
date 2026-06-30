# FileInfoResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Filename** | **string** |  | 
**MimeType** | **string** |  | 
**Size** | **int32** |  | 
**CreatedAt** | **time.Time** |  | 
**ExtraMetadata** | **map[string]interface{}** |  | 

## Methods

### NewFileInfoResponse

`func NewFileInfoResponse(id string, filename string, mimeType string, size int32, createdAt time.Time, extraMetadata map[string]interface{}, ) *FileInfoResponse`

NewFileInfoResponse instantiates a new FileInfoResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFileInfoResponseWithDefaults

`func NewFileInfoResponseWithDefaults() *FileInfoResponse`

NewFileInfoResponseWithDefaults instantiates a new FileInfoResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *FileInfoResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *FileInfoResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *FileInfoResponse) SetId(v string)`

SetId sets Id field to given value.


### GetFilename

`func (o *FileInfoResponse) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *FileInfoResponse) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *FileInfoResponse) SetFilename(v string)`

SetFilename sets Filename field to given value.


### GetMimeType

`func (o *FileInfoResponse) GetMimeType() string`

GetMimeType returns the MimeType field if non-nil, zero value otherwise.

### GetMimeTypeOk

`func (o *FileInfoResponse) GetMimeTypeOk() (*string, bool)`

GetMimeTypeOk returns a tuple with the MimeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMimeType

`func (o *FileInfoResponse) SetMimeType(v string)`

SetMimeType sets MimeType field to given value.


### GetSize

`func (o *FileInfoResponse) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *FileInfoResponse) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *FileInfoResponse) SetSize(v int32)`

SetSize sets Size field to given value.


### GetCreatedAt

`func (o *FileInfoResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *FileInfoResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *FileInfoResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetExtraMetadata

`func (o *FileInfoResponse) GetExtraMetadata() map[string]interface{}`

GetExtraMetadata returns the ExtraMetadata field if non-nil, zero value otherwise.

### GetExtraMetadataOk

`func (o *FileInfoResponse) GetExtraMetadataOk() (*map[string]interface{}, bool)`

GetExtraMetadataOk returns a tuple with the ExtraMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtraMetadata

`func (o *FileInfoResponse) SetExtraMetadata(v map[string]interface{})`

SetExtraMetadata sets ExtraMetadata field to given value.


### SetExtraMetadataNil

`func (o *FileInfoResponse) SetExtraMetadataNil(b bool)`

 SetExtraMetadataNil sets the value for ExtraMetadata to be an explicit nil

### UnsetExtraMetadata
`func (o *FileInfoResponse) UnsetExtraMetadata()`

UnsetExtraMetadata ensures that no value is present for ExtraMetadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


