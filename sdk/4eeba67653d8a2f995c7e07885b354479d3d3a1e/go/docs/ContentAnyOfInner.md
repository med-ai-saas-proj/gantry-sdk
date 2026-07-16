# ContentAnyOfInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "text"]
**Text** | **string** |  | 
**Source** | [**Source**](Source.md) |  | 
**Metadata** | Pointer to [**NullableAnyOf**](anyOf&lt;&gt;.md) |  | [optional] 
**MimeType** | **string** |  | 
**Id** | Pointer to **string** |  | [optional] 
**Url** | Pointer to **string** |  | [optional] 
**Data** | Pointer to **string** |  | [optional] 
**Filename** | Pointer to **string** |  | [optional] 

## Methods

### NewContentAnyOfInner

`func NewContentAnyOfInner(text string, source Source, mimeType string, ) *ContentAnyOfInner`

NewContentAnyOfInner instantiates a new ContentAnyOfInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContentAnyOfInnerWithDefaults

`func NewContentAnyOfInnerWithDefaults() *ContentAnyOfInner`

NewContentAnyOfInnerWithDefaults instantiates a new ContentAnyOfInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ContentAnyOfInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContentAnyOfInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContentAnyOfInner) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ContentAnyOfInner) HasType() bool`

HasType returns a boolean if a field has been set.

### GetText

`func (o *ContentAnyOfInner) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *ContentAnyOfInner) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *ContentAnyOfInner) SetText(v string)`

SetText sets Text field to given value.


### GetSource

`func (o *ContentAnyOfInner) GetSource() Source`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ContentAnyOfInner) GetSourceOk() (*Source, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ContentAnyOfInner) SetSource(v Source)`

SetSource sets Source field to given value.


### GetMetadata

`func (o *ContentAnyOfInner) GetMetadata() AnyOf`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ContentAnyOfInner) GetMetadataOk() (*AnyOf, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ContentAnyOfInner) SetMetadata(v AnyOf)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *ContentAnyOfInner) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *ContentAnyOfInner) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *ContentAnyOfInner) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil
### GetMimeType

`func (o *ContentAnyOfInner) GetMimeType() string`

GetMimeType returns the MimeType field if non-nil, zero value otherwise.

### GetMimeTypeOk

`func (o *ContentAnyOfInner) GetMimeTypeOk() (*string, bool)`

GetMimeTypeOk returns a tuple with the MimeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMimeType

`func (o *ContentAnyOfInner) SetMimeType(v string)`

SetMimeType sets MimeType field to given value.


### GetId

`func (o *ContentAnyOfInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ContentAnyOfInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ContentAnyOfInner) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ContentAnyOfInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetUrl

`func (o *ContentAnyOfInner) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ContentAnyOfInner) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ContentAnyOfInner) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *ContentAnyOfInner) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetData

`func (o *ContentAnyOfInner) GetData() string`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ContentAnyOfInner) GetDataOk() (*string, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ContentAnyOfInner) SetData(v string)`

SetData sets Data field to given value.

### HasData

`func (o *ContentAnyOfInner) HasData() bool`

HasData returns a boolean if a field has been set.

### GetFilename

`func (o *ContentAnyOfInner) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *ContentAnyOfInner) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *ContentAnyOfInner) SetFilename(v string)`

SetFilename sets Filename field to given value.

### HasFilename

`func (o *ContentAnyOfInner) HasFilename() bool`

HasFilename returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


