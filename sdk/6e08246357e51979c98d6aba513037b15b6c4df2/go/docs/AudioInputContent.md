# AudioInputContent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "audio"]
**Source** | [**Source**](Source.md) |  | 
**Metadata** | Pointer to [**NullableAnyOf**](anyOf&lt;&gt;.md) |  | [optional] 

## Methods

### NewAudioInputContent

`func NewAudioInputContent(source Source, ) *AudioInputContent`

NewAudioInputContent instantiates a new AudioInputContent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAudioInputContentWithDefaults

`func NewAudioInputContentWithDefaults() *AudioInputContent`

NewAudioInputContentWithDefaults instantiates a new AudioInputContent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *AudioInputContent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AudioInputContent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AudioInputContent) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *AudioInputContent) HasType() bool`

HasType returns a boolean if a field has been set.

### GetSource

`func (o *AudioInputContent) GetSource() Source`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *AudioInputContent) GetSourceOk() (*Source, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *AudioInputContent) SetSource(v Source)`

SetSource sets Source field to given value.


### GetMetadata

`func (o *AudioInputContent) GetMetadata() AnyOf`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *AudioInputContent) GetMetadataOk() (*AnyOf, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *AudioInputContent) SetMetadata(v AnyOf)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *AudioInputContent) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *AudioInputContent) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *AudioInputContent) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


