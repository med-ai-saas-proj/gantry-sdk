# Filters

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FileMetadataFilters** | [**map[string]FileMetadataFiltersValue**](FileMetadataFiltersValue.md) |  | 
**FileUids** | **[]string** |  | 

## Methods

### NewFilters

`func NewFilters(fileMetadataFilters map[string]FileMetadataFiltersValue, fileUids []string, ) *Filters`

NewFilters instantiates a new Filters object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFiltersWithDefaults

`func NewFiltersWithDefaults() *Filters`

NewFiltersWithDefaults instantiates a new Filters object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFileMetadataFilters

`func (o *Filters) GetFileMetadataFilters() map[string]FileMetadataFiltersValue`

GetFileMetadataFilters returns the FileMetadataFilters field if non-nil, zero value otherwise.

### GetFileMetadataFiltersOk

`func (o *Filters) GetFileMetadataFiltersOk() (*map[string]FileMetadataFiltersValue, bool)`

GetFileMetadataFiltersOk returns a tuple with the FileMetadataFilters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileMetadataFilters

`func (o *Filters) SetFileMetadataFilters(v map[string]FileMetadataFiltersValue)`

SetFileMetadataFilters sets FileMetadataFilters field to given value.


### GetFileUids

`func (o *Filters) GetFileUids() []string`

GetFileUids returns the FileUids field if non-nil, zero value otherwise.

### GetFileUidsOk

`func (o *Filters) GetFileUidsOk() (*[]string, bool)`

GetFileUidsOk returns a tuple with the FileUids field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileUids

`func (o *Filters) SetFileUids(v []string)`

SetFileUids sets FileUids field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


