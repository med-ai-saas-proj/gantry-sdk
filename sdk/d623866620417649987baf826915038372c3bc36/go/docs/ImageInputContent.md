# ImageInputContent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "image"]
**Source** | [**Source**](Source.md) |  | 
**Metadata** | Pointer to [**NullableAnyOf**](anyOf&lt;&gt;.md) |  | [optional] 

## Methods

### NewImageInputContent

`func NewImageInputContent(source Source, ) *ImageInputContent`

NewImageInputContent instantiates a new ImageInputContent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageInputContentWithDefaults

`func NewImageInputContentWithDefaults() *ImageInputContent`

NewImageInputContentWithDefaults instantiates a new ImageInputContent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ImageInputContent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ImageInputContent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ImageInputContent) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ImageInputContent) HasType() bool`

HasType returns a boolean if a field has been set.

### GetSource

`func (o *ImageInputContent) GetSource() Source`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ImageInputContent) GetSourceOk() (*Source, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ImageInputContent) SetSource(v Source)`

SetSource sets Source field to given value.


### GetMetadata

`func (o *ImageInputContent) GetMetadata() AnyOf`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ImageInputContent) GetMetadataOk() (*AnyOf, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ImageInputContent) SetMetadata(v AnyOf)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *ImageInputContent) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### SetMetadataNil

`func (o *ImageInputContent) SetMetadataNil(b bool)`

 SetMetadataNil sets the value for Metadata to be an explicit nil

### UnsetMetadata
`func (o *ImageInputContent) UnsetMetadata()`

UnsetMetadata ensures that no value is present for Metadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


