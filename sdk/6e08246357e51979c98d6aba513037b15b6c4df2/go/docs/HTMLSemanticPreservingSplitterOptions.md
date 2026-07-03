# HTMLSemanticPreservingSplitterOptions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**HeadersToSplitOn** | Pointer to **[][]interface{}** |  | [optional] 
**MaxChunkSize** | Pointer to **int32** |  | [optional] 
**ChunkOverlap** | Pointer to **int32** |  | [optional] 
**Separators** | Pointer to **[]string** |  | [optional] 
**ElementsToPreserve** | Pointer to **[]string** |  | [optional] 
**PreserveLinks** | Pointer to **bool** |  | [optional] 
**PreserveImages** | Pointer to **bool** |  | [optional] 
**PreserveVideos** | Pointer to **bool** |  | [optional] 
**PreserveAudio** | Pointer to **bool** |  | [optional] 
**CustomHandlers** | Pointer to **map[string]interface{}** |  | [optional] 
**StopwordRemoval** | Pointer to **bool** |  | [optional] 
**StopwordLang** | Pointer to **string** |  | [optional] 
**NormalizeText** | Pointer to **bool** |  | [optional] 
**ExternalMetadata** | Pointer to **map[string]string** |  | [optional] 
**AllowlistTags** | Pointer to **[]string** |  | [optional] 
**DenylistTags** | Pointer to **[]string** |  | [optional] 
**PreserveParentMetadata** | Pointer to **bool** |  | [optional] 
**KeepSeparator** | Pointer to [**KeepSeparator**](KeepSeparator.md) |  | [optional] 

## Methods

### NewHTMLSemanticPreservingSplitterOptions

`func NewHTMLSemanticPreservingSplitterOptions() *HTMLSemanticPreservingSplitterOptions`

NewHTMLSemanticPreservingSplitterOptions instantiates a new HTMLSemanticPreservingSplitterOptions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHTMLSemanticPreservingSplitterOptionsWithDefaults

`func NewHTMLSemanticPreservingSplitterOptionsWithDefaults() *HTMLSemanticPreservingSplitterOptions`

NewHTMLSemanticPreservingSplitterOptionsWithDefaults instantiates a new HTMLSemanticPreservingSplitterOptions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHeadersToSplitOn

`func (o *HTMLSemanticPreservingSplitterOptions) GetHeadersToSplitOn() [][]interface{}`

GetHeadersToSplitOn returns the HeadersToSplitOn field if non-nil, zero value otherwise.

### GetHeadersToSplitOnOk

`func (o *HTMLSemanticPreservingSplitterOptions) GetHeadersToSplitOnOk() (*[][]interface{}, bool)`

GetHeadersToSplitOnOk returns a tuple with the HeadersToSplitOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeadersToSplitOn

`func (o *HTMLSemanticPreservingSplitterOptions) SetHeadersToSplitOn(v [][]interface{})`

SetHeadersToSplitOn sets HeadersToSplitOn field to given value.

### HasHeadersToSplitOn

`func (o *HTMLSemanticPreservingSplitterOptions) HasHeadersToSplitOn() bool`

HasHeadersToSplitOn returns a boolean if a field has been set.

### GetMaxChunkSize

`func (o *HTMLSemanticPreservingSplitterOptions) GetMaxChunkSize() int32`

GetMaxChunkSize returns the MaxChunkSize field if non-nil, zero value otherwise.

### GetMaxChunkSizeOk

`func (o *HTMLSemanticPreservingSplitterOptions) GetMaxChunkSizeOk() (*int32, bool)`

GetMaxChunkSizeOk returns a tuple with the MaxChunkSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxChunkSize

`func (o *HTMLSemanticPreservingSplitterOptions) SetMaxChunkSize(v int32)`

SetMaxChunkSize sets MaxChunkSize field to given value.

### HasMaxChunkSize

`func (o *HTMLSemanticPreservingSplitterOptions) HasMaxChunkSize() bool`

HasMaxChunkSize returns a boolean if a field has been set.

### GetChunkOverlap

`func (o *HTMLSemanticPreservingSplitterOptions) GetChunkOverlap() int32`

GetChunkOverlap returns the ChunkOverlap field if non-nil, zero value otherwise.

### GetChunkOverlapOk

`func (o *HTMLSemanticPreservingSplitterOptions) GetChunkOverlapOk() (*int32, bool)`

GetChunkOverlapOk returns a tuple with the ChunkOverlap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkOverlap

`func (o *HTMLSemanticPreservingSplitterOptions) SetChunkOverlap(v int32)`

SetChunkOverlap sets ChunkOverlap field to given value.

### HasChunkOverlap

`func (o *HTMLSemanticPreservingSplitterOptions) HasChunkOverlap() bool`

HasChunkOverlap returns a boolean if a field has been set.

### GetSeparators

`func (o *HTMLSemanticPreservingSplitterOptions) GetSeparators() []string`

GetSeparators returns the Separators field if non-nil, zero value otherwise.

### GetSeparatorsOk

`func (o *HTMLSemanticPreservingSplitterOptions) GetSeparatorsOk() (*[]string, bool)`

GetSeparatorsOk returns a tuple with the Separators field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeparators

`func (o *HTMLSemanticPreservingSplitterOptions) SetSeparators(v []string)`

SetSeparators sets Separators field to given value.

### HasSeparators

`func (o *HTMLSemanticPreservingSplitterOptions) HasSeparators() bool`

HasSeparators returns a boolean if a field has been set.

### GetElementsToPreserve

`func (o *HTMLSemanticPreservingSplitterOptions) GetElementsToPreserve() []string`

GetElementsToPreserve returns the ElementsToPreserve field if non-nil, zero value otherwise.

### GetElementsToPreserveOk

`func (o *HTMLSemanticPreservingSplitterOptions) GetElementsToPreserveOk() (*[]string, bool)`

GetElementsToPreserveOk returns a tuple with the ElementsToPreserve field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetElementsToPreserve

`func (o *HTMLSemanticPreservingSplitterOptions) SetElementsToPreserve(v []string)`

SetElementsToPreserve sets ElementsToPreserve field to given value.

### HasElementsToPreserve

`func (o *HTMLSemanticPreservingSplitterOptions) HasElementsToPreserve() bool`

HasElementsToPreserve returns a boolean if a field has been set.

### GetPreserveLinks

`func (o *HTMLSemanticPreservingSplitterOptions) GetPreserveLinks() bool`

GetPreserveLinks returns the PreserveLinks field if non-nil, zero value otherwise.

### GetPreserveLinksOk

`func (o *HTMLSemanticPreservingSplitterOptions) GetPreserveLinksOk() (*bool, bool)`

GetPreserveLinksOk returns a tuple with the PreserveLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreserveLinks

`func (o *HTMLSemanticPreservingSplitterOptions) SetPreserveLinks(v bool)`

SetPreserveLinks sets PreserveLinks field to given value.

### HasPreserveLinks

`func (o *HTMLSemanticPreservingSplitterOptions) HasPreserveLinks() bool`

HasPreserveLinks returns a boolean if a field has been set.

### GetPreserveImages

`func (o *HTMLSemanticPreservingSplitterOptions) GetPreserveImages() bool`

GetPreserveImages returns the PreserveImages field if non-nil, zero value otherwise.

### GetPreserveImagesOk

`func (o *HTMLSemanticPreservingSplitterOptions) GetPreserveImagesOk() (*bool, bool)`

GetPreserveImagesOk returns a tuple with the PreserveImages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreserveImages

`func (o *HTMLSemanticPreservingSplitterOptions) SetPreserveImages(v bool)`

SetPreserveImages sets PreserveImages field to given value.

### HasPreserveImages

`func (o *HTMLSemanticPreservingSplitterOptions) HasPreserveImages() bool`

HasPreserveImages returns a boolean if a field has been set.

### GetPreserveVideos

`func (o *HTMLSemanticPreservingSplitterOptions) GetPreserveVideos() bool`

GetPreserveVideos returns the PreserveVideos field if non-nil, zero value otherwise.

### GetPreserveVideosOk

`func (o *HTMLSemanticPreservingSplitterOptions) GetPreserveVideosOk() (*bool, bool)`

GetPreserveVideosOk returns a tuple with the PreserveVideos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreserveVideos

`func (o *HTMLSemanticPreservingSplitterOptions) SetPreserveVideos(v bool)`

SetPreserveVideos sets PreserveVideos field to given value.

### HasPreserveVideos

`func (o *HTMLSemanticPreservingSplitterOptions) HasPreserveVideos() bool`

HasPreserveVideos returns a boolean if a field has been set.

### GetPreserveAudio

`func (o *HTMLSemanticPreservingSplitterOptions) GetPreserveAudio() bool`

GetPreserveAudio returns the PreserveAudio field if non-nil, zero value otherwise.

### GetPreserveAudioOk

`func (o *HTMLSemanticPreservingSplitterOptions) GetPreserveAudioOk() (*bool, bool)`

GetPreserveAudioOk returns a tuple with the PreserveAudio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreserveAudio

`func (o *HTMLSemanticPreservingSplitterOptions) SetPreserveAudio(v bool)`

SetPreserveAudio sets PreserveAudio field to given value.

### HasPreserveAudio

`func (o *HTMLSemanticPreservingSplitterOptions) HasPreserveAudio() bool`

HasPreserveAudio returns a boolean if a field has been set.

### GetCustomHandlers

`func (o *HTMLSemanticPreservingSplitterOptions) GetCustomHandlers() map[string]interface{}`

GetCustomHandlers returns the CustomHandlers field if non-nil, zero value otherwise.

### GetCustomHandlersOk

`func (o *HTMLSemanticPreservingSplitterOptions) GetCustomHandlersOk() (*map[string]interface{}, bool)`

GetCustomHandlersOk returns a tuple with the CustomHandlers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomHandlers

`func (o *HTMLSemanticPreservingSplitterOptions) SetCustomHandlers(v map[string]interface{})`

SetCustomHandlers sets CustomHandlers field to given value.

### HasCustomHandlers

`func (o *HTMLSemanticPreservingSplitterOptions) HasCustomHandlers() bool`

HasCustomHandlers returns a boolean if a field has been set.

### GetStopwordRemoval

`func (o *HTMLSemanticPreservingSplitterOptions) GetStopwordRemoval() bool`

GetStopwordRemoval returns the StopwordRemoval field if non-nil, zero value otherwise.

### GetStopwordRemovalOk

`func (o *HTMLSemanticPreservingSplitterOptions) GetStopwordRemovalOk() (*bool, bool)`

GetStopwordRemovalOk returns a tuple with the StopwordRemoval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopwordRemoval

`func (o *HTMLSemanticPreservingSplitterOptions) SetStopwordRemoval(v bool)`

SetStopwordRemoval sets StopwordRemoval field to given value.

### HasStopwordRemoval

`func (o *HTMLSemanticPreservingSplitterOptions) HasStopwordRemoval() bool`

HasStopwordRemoval returns a boolean if a field has been set.

### GetStopwordLang

`func (o *HTMLSemanticPreservingSplitterOptions) GetStopwordLang() string`

GetStopwordLang returns the StopwordLang field if non-nil, zero value otherwise.

### GetStopwordLangOk

`func (o *HTMLSemanticPreservingSplitterOptions) GetStopwordLangOk() (*string, bool)`

GetStopwordLangOk returns a tuple with the StopwordLang field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopwordLang

`func (o *HTMLSemanticPreservingSplitterOptions) SetStopwordLang(v string)`

SetStopwordLang sets StopwordLang field to given value.

### HasStopwordLang

`func (o *HTMLSemanticPreservingSplitterOptions) HasStopwordLang() bool`

HasStopwordLang returns a boolean if a field has been set.

### GetNormalizeText

`func (o *HTMLSemanticPreservingSplitterOptions) GetNormalizeText() bool`

GetNormalizeText returns the NormalizeText field if non-nil, zero value otherwise.

### GetNormalizeTextOk

`func (o *HTMLSemanticPreservingSplitterOptions) GetNormalizeTextOk() (*bool, bool)`

GetNormalizeTextOk returns a tuple with the NormalizeText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNormalizeText

`func (o *HTMLSemanticPreservingSplitterOptions) SetNormalizeText(v bool)`

SetNormalizeText sets NormalizeText field to given value.

### HasNormalizeText

`func (o *HTMLSemanticPreservingSplitterOptions) HasNormalizeText() bool`

HasNormalizeText returns a boolean if a field has been set.

### GetExternalMetadata

`func (o *HTMLSemanticPreservingSplitterOptions) GetExternalMetadata() map[string]string`

GetExternalMetadata returns the ExternalMetadata field if non-nil, zero value otherwise.

### GetExternalMetadataOk

`func (o *HTMLSemanticPreservingSplitterOptions) GetExternalMetadataOk() (*map[string]string, bool)`

GetExternalMetadataOk returns a tuple with the ExternalMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalMetadata

`func (o *HTMLSemanticPreservingSplitterOptions) SetExternalMetadata(v map[string]string)`

SetExternalMetadata sets ExternalMetadata field to given value.

### HasExternalMetadata

`func (o *HTMLSemanticPreservingSplitterOptions) HasExternalMetadata() bool`

HasExternalMetadata returns a boolean if a field has been set.

### GetAllowlistTags

`func (o *HTMLSemanticPreservingSplitterOptions) GetAllowlistTags() []string`

GetAllowlistTags returns the AllowlistTags field if non-nil, zero value otherwise.

### GetAllowlistTagsOk

`func (o *HTMLSemanticPreservingSplitterOptions) GetAllowlistTagsOk() (*[]string, bool)`

GetAllowlistTagsOk returns a tuple with the AllowlistTags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowlistTags

`func (o *HTMLSemanticPreservingSplitterOptions) SetAllowlistTags(v []string)`

SetAllowlistTags sets AllowlistTags field to given value.

### HasAllowlistTags

`func (o *HTMLSemanticPreservingSplitterOptions) HasAllowlistTags() bool`

HasAllowlistTags returns a boolean if a field has been set.

### GetDenylistTags

`func (o *HTMLSemanticPreservingSplitterOptions) GetDenylistTags() []string`

GetDenylistTags returns the DenylistTags field if non-nil, zero value otherwise.

### GetDenylistTagsOk

`func (o *HTMLSemanticPreservingSplitterOptions) GetDenylistTagsOk() (*[]string, bool)`

GetDenylistTagsOk returns a tuple with the DenylistTags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDenylistTags

`func (o *HTMLSemanticPreservingSplitterOptions) SetDenylistTags(v []string)`

SetDenylistTags sets DenylistTags field to given value.

### HasDenylistTags

`func (o *HTMLSemanticPreservingSplitterOptions) HasDenylistTags() bool`

HasDenylistTags returns a boolean if a field has been set.

### GetPreserveParentMetadata

`func (o *HTMLSemanticPreservingSplitterOptions) GetPreserveParentMetadata() bool`

GetPreserveParentMetadata returns the PreserveParentMetadata field if non-nil, zero value otherwise.

### GetPreserveParentMetadataOk

`func (o *HTMLSemanticPreservingSplitterOptions) GetPreserveParentMetadataOk() (*bool, bool)`

GetPreserveParentMetadataOk returns a tuple with the PreserveParentMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreserveParentMetadata

`func (o *HTMLSemanticPreservingSplitterOptions) SetPreserveParentMetadata(v bool)`

SetPreserveParentMetadata sets PreserveParentMetadata field to given value.

### HasPreserveParentMetadata

`func (o *HTMLSemanticPreservingSplitterOptions) HasPreserveParentMetadata() bool`

HasPreserveParentMetadata returns a boolean if a field has been set.

### GetKeepSeparator

`func (o *HTMLSemanticPreservingSplitterOptions) GetKeepSeparator() KeepSeparator`

GetKeepSeparator returns the KeepSeparator field if non-nil, zero value otherwise.

### GetKeepSeparatorOk

`func (o *HTMLSemanticPreservingSplitterOptions) GetKeepSeparatorOk() (*KeepSeparator, bool)`

GetKeepSeparatorOk returns a tuple with the KeepSeparator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeepSeparator

`func (o *HTMLSemanticPreservingSplitterOptions) SetKeepSeparator(v KeepSeparator)`

SetKeepSeparator sets KeepSeparator field to given value.

### HasKeepSeparator

`func (o *HTMLSemanticPreservingSplitterOptions) HasKeepSeparator() bool`

HasKeepSeparator returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


