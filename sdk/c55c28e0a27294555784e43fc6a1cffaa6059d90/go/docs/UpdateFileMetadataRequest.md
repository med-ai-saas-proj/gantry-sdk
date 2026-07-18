# UpdateFileMetadataRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExtraMetadata** | [**map[string]UpdateFileMetadataRequestExtraMetadataValue**](UpdateFileMetadataRequestExtraMetadataValue.md) |  | 

## Methods

### NewUpdateFileMetadataRequest

`func NewUpdateFileMetadataRequest(extraMetadata map[string]UpdateFileMetadataRequestExtraMetadataValue, ) *UpdateFileMetadataRequest`

NewUpdateFileMetadataRequest instantiates a new UpdateFileMetadataRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateFileMetadataRequestWithDefaults

`func NewUpdateFileMetadataRequestWithDefaults() *UpdateFileMetadataRequest`

NewUpdateFileMetadataRequestWithDefaults instantiates a new UpdateFileMetadataRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExtraMetadata

`func (o *UpdateFileMetadataRequest) GetExtraMetadata() map[string]UpdateFileMetadataRequestExtraMetadataValue`

GetExtraMetadata returns the ExtraMetadata field if non-nil, zero value otherwise.

### GetExtraMetadataOk

`func (o *UpdateFileMetadataRequest) GetExtraMetadataOk() (*map[string]UpdateFileMetadataRequestExtraMetadataValue, bool)`

GetExtraMetadataOk returns a tuple with the ExtraMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtraMetadata

`func (o *UpdateFileMetadataRequest) SetExtraMetadata(v map[string]UpdateFileMetadataRequestExtraMetadataValue)`

SetExtraMetadata sets ExtraMetadata field to given value.


### SetExtraMetadataNil

`func (o *UpdateFileMetadataRequest) SetExtraMetadataNil(b bool)`

 SetExtraMetadataNil sets the value for ExtraMetadata to be an explicit nil

### UnsetExtraMetadata
`func (o *UpdateFileMetadataRequest) UnsetExtraMetadata()`

UnsetExtraMetadata ensures that no value is present for ExtraMetadata, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


