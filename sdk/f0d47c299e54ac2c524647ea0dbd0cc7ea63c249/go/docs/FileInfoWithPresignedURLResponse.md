# FileInfoWithPresignedURLResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** |  | 
**Id** | **string** |  | 
**Filename** | **string** |  | 
**MimeType** | **string** |  | 
**Size** | **int32** |  | 
**CreatedAt** | **time.Time** |  | 
**ExtraMetadata** | **map[string]interface{}** |  | 

## Methods

### NewFileInfoWithPresignedURLResponse

`func NewFileInfoWithPresignedURLResponse(url string, id string, filename string, mimeType string, size int32, createdAt time.Time, extraMetadata map[string]interface{}, ) *FileInfoWithPresignedURLResponse`

NewFileInfoWithPresignedURLResponse instantiates a new FileInfoWithPresignedURLResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFileInfoWithPresignedURLResponseWithDefaults

`func NewFileInfoWithPresignedURLResponseWithDefaults() *FileInfoWithPresignedURLResponse`

NewFileInfoWithPresignedURLResponseWithDefaults instantiates a new FileInfoWithPresignedURLResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *FileInfoWithPresignedURLResponse) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *FileInfoWithPresignedURLResponse) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *FileInfoWithPresignedURLResponse) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetId

`func (o *FileInfoWithPresignedURLResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *FileInfoWithPresignedURLResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *FileInfoWithPresignedURLResponse) SetId(v string)`

SetId sets Id field to given value.


### GetFilename

`func (o *FileInfoWithPresignedURLResponse) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *FileInfoWithPresignedURLResponse) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *FileInfoWithPresignedURLResponse) SetFilename(v string)`

SetFilename sets Filename field to given value.


### GetMimeType

`func (o *FileInfoWithPresignedURLResponse) GetMimeType() string`

GetMimeType returns the MimeType field if non-nil, zero value otherwise.

### GetMimeTypeOk

`func (o *FileInfoWithPresignedURLResponse) GetMimeTypeOk() (*string, bool)`

GetMimeTypeOk returns a tuple with the MimeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMimeType

`func (o *FileInfoWithPresignedURLResponse) SetMimeType(v string)`

SetMimeType sets MimeType field to given value.


### GetSize

`func (o *FileInfoWithPresignedURLResponse) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *FileInfoWithPresignedURLResponse) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *FileInfoWithPresignedURLResponse) SetSize(v int32)`

SetSize sets Size field to given value.


### GetCreatedAt

`func (o *FileInfoWithPresignedURLResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *FileInfoWithPresignedURLResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *FileInfoWithPresignedURLResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetExtraMetadata

`func (o *FileInfoWithPresignedURLResponse) GetExtraMetadata() map[string]interface{}`

GetExtraMetadata returns the ExtraMetadata field if non-nil, zero value otherwise.

### GetExtraMetadataOk

`func (o *FileInfoWithPresignedURLResponse) GetExtraMetadataOk() (*map[string]interface{}, bool)`

GetExtraMetadataOk returns a tuple with the ExtraMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtraMetadata

`func (o *FileInfoWithPresignedURLResponse) SetExtraMetadata(v map[string]interface{})`

SetExtraMetadata sets ExtraMetadata field to given value.


### SetExtraMetadataNil

`func (o *FileInfoWithPresignedURLResponse) SetExtraMetadataNil(b bool)`

 SetExtraMetadataNil sets the value for ExtraMetadata to be an explicit nil

### UnsetExtraMetadata
`func (o *FileInfoWithPresignedURLResponse) UnsetExtraMetadata()`

UnsetExtraMetadata ensures that no value is present for ExtraMetadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


