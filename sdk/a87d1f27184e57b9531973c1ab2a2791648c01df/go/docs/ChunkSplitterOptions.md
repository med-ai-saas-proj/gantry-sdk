# ChunkSplitterOptions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Separator** | Pointer to **string** |  | [optional] 
**IsSeparatorRegex** | Pointer to **bool** |  | [optional] 
**ChunkSize** | Pointer to **int32** |  | [optional] 
**ChunkOverlap** | Pointer to **int32** |  | [optional] 
**KeepSeparator** | Pointer to [**KeepSeparator**](KeepSeparator.md) |  | [optional] 
**Separators** | Pointer to **[]string** |  | [optional] 
**EncodingName** | Pointer to **string** |  | [optional] 
**ModelName** | Pointer to **string** |  | [optional] 
**AllowedSpecial** | Pointer to [**NullableAllowedSpecial**](AllowedSpecial.md) |  | [optional] 
**DisallowedSpecial** | Pointer to [**DisallowedSpecial**](DisallowedSpecial.md) |  | [optional] 
**HeadersToSplitOn** | Pointer to **[][]interface{}** |  | [optional] 
**ReturnEachLine** | Pointer to **bool** |  | [optional] 
**StripHeaders** | Pointer to **bool** |  | [optional] 
**CustomHeaderPatterns** | Pointer to **map[string]int32** |  | [optional] 
**ReturnEachElement** | Pointer to **bool** |  | [optional] 
**MaxChunkSize** | Pointer to **int32** |  | [optional] 
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
**MinChunkSize** | Pointer to **int32** |  | [optional] 
**ConvertLists** | Pointer to **bool** |  | [optional] 
**Language** | Pointer to **string** |  | [optional] 
**UseSpanTokenize** | Pointer to **bool** |  | [optional] 
**Pipeline** | Pointer to **string** |  | [optional] 
**MaxLength** | Pointer to **int32** |  | [optional] 
**StripWhitespace** | Pointer to **bool** |  | [optional] 
**TokensPerChunk** | Pointer to **int32** |  | [optional] 
**ModelKwargs** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewChunkSplitterOptions

`func NewChunkSplitterOptions() *ChunkSplitterOptions`

NewChunkSplitterOptions instantiates a new ChunkSplitterOptions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChunkSplitterOptionsWithDefaults

`func NewChunkSplitterOptionsWithDefaults() *ChunkSplitterOptions`

NewChunkSplitterOptionsWithDefaults instantiates a new ChunkSplitterOptions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSeparator

`func (o *ChunkSplitterOptions) GetSeparator() string`

GetSeparator returns the Separator field if non-nil, zero value otherwise.

### GetSeparatorOk

`func (o *ChunkSplitterOptions) GetSeparatorOk() (*string, bool)`

GetSeparatorOk returns a tuple with the Separator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeparator

`func (o *ChunkSplitterOptions) SetSeparator(v string)`

SetSeparator sets Separator field to given value.

### HasSeparator

`func (o *ChunkSplitterOptions) HasSeparator() bool`

HasSeparator returns a boolean if a field has been set.

### GetIsSeparatorRegex

`func (o *ChunkSplitterOptions) GetIsSeparatorRegex() bool`

GetIsSeparatorRegex returns the IsSeparatorRegex field if non-nil, zero value otherwise.

### GetIsSeparatorRegexOk

`func (o *ChunkSplitterOptions) GetIsSeparatorRegexOk() (*bool, bool)`

GetIsSeparatorRegexOk returns a tuple with the IsSeparatorRegex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSeparatorRegex

`func (o *ChunkSplitterOptions) SetIsSeparatorRegex(v bool)`

SetIsSeparatorRegex sets IsSeparatorRegex field to given value.

### HasIsSeparatorRegex

`func (o *ChunkSplitterOptions) HasIsSeparatorRegex() bool`

HasIsSeparatorRegex returns a boolean if a field has been set.

### GetChunkSize

`func (o *ChunkSplitterOptions) GetChunkSize() int32`

GetChunkSize returns the ChunkSize field if non-nil, zero value otherwise.

### GetChunkSizeOk

`func (o *ChunkSplitterOptions) GetChunkSizeOk() (*int32, bool)`

GetChunkSizeOk returns a tuple with the ChunkSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkSize

`func (o *ChunkSplitterOptions) SetChunkSize(v int32)`

SetChunkSize sets ChunkSize field to given value.

### HasChunkSize

`func (o *ChunkSplitterOptions) HasChunkSize() bool`

HasChunkSize returns a boolean if a field has been set.

### GetChunkOverlap

`func (o *ChunkSplitterOptions) GetChunkOverlap() int32`

GetChunkOverlap returns the ChunkOverlap field if non-nil, zero value otherwise.

### GetChunkOverlapOk

`func (o *ChunkSplitterOptions) GetChunkOverlapOk() (*int32, bool)`

GetChunkOverlapOk returns a tuple with the ChunkOverlap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChunkOverlap

`func (o *ChunkSplitterOptions) SetChunkOverlap(v int32)`

SetChunkOverlap sets ChunkOverlap field to given value.

### HasChunkOverlap

`func (o *ChunkSplitterOptions) HasChunkOverlap() bool`

HasChunkOverlap returns a boolean if a field has been set.

### GetKeepSeparator

`func (o *ChunkSplitterOptions) GetKeepSeparator() KeepSeparator`

GetKeepSeparator returns the KeepSeparator field if non-nil, zero value otherwise.

### GetKeepSeparatorOk

`func (o *ChunkSplitterOptions) GetKeepSeparatorOk() (*KeepSeparator, bool)`

GetKeepSeparatorOk returns a tuple with the KeepSeparator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeepSeparator

`func (o *ChunkSplitterOptions) SetKeepSeparator(v KeepSeparator)`

SetKeepSeparator sets KeepSeparator field to given value.

### HasKeepSeparator

`func (o *ChunkSplitterOptions) HasKeepSeparator() bool`

HasKeepSeparator returns a boolean if a field has been set.

### GetSeparators

`func (o *ChunkSplitterOptions) GetSeparators() []string`

GetSeparators returns the Separators field if non-nil, zero value otherwise.

### GetSeparatorsOk

`func (o *ChunkSplitterOptions) GetSeparatorsOk() (*[]string, bool)`

GetSeparatorsOk returns a tuple with the Separators field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeparators

`func (o *ChunkSplitterOptions) SetSeparators(v []string)`

SetSeparators sets Separators field to given value.

### HasSeparators

`func (o *ChunkSplitterOptions) HasSeparators() bool`

HasSeparators returns a boolean if a field has been set.

### GetEncodingName

`func (o *ChunkSplitterOptions) GetEncodingName() string`

GetEncodingName returns the EncodingName field if non-nil, zero value otherwise.

### GetEncodingNameOk

`func (o *ChunkSplitterOptions) GetEncodingNameOk() (*string, bool)`

GetEncodingNameOk returns a tuple with the EncodingName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncodingName

`func (o *ChunkSplitterOptions) SetEncodingName(v string)`

SetEncodingName sets EncodingName field to given value.

### HasEncodingName

`func (o *ChunkSplitterOptions) HasEncodingName() bool`

HasEncodingName returns a boolean if a field has been set.

### GetModelName

`func (o *ChunkSplitterOptions) GetModelName() string`

GetModelName returns the ModelName field if non-nil, zero value otherwise.

### GetModelNameOk

`func (o *ChunkSplitterOptions) GetModelNameOk() (*string, bool)`

GetModelNameOk returns a tuple with the ModelName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelName

`func (o *ChunkSplitterOptions) SetModelName(v string)`

SetModelName sets ModelName field to given value.

### HasModelName

`func (o *ChunkSplitterOptions) HasModelName() bool`

HasModelName returns a boolean if a field has been set.

### GetAllowedSpecial

`func (o *ChunkSplitterOptions) GetAllowedSpecial() AllowedSpecial`

GetAllowedSpecial returns the AllowedSpecial field if non-nil, zero value otherwise.

### GetAllowedSpecialOk

`func (o *ChunkSplitterOptions) GetAllowedSpecialOk() (*AllowedSpecial, bool)`

GetAllowedSpecialOk returns a tuple with the AllowedSpecial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowedSpecial

`func (o *ChunkSplitterOptions) SetAllowedSpecial(v AllowedSpecial)`

SetAllowedSpecial sets AllowedSpecial field to given value.

### HasAllowedSpecial

`func (o *ChunkSplitterOptions) HasAllowedSpecial() bool`

HasAllowedSpecial returns a boolean if a field has been set.

### SetAllowedSpecialNil

`func (o *ChunkSplitterOptions) SetAllowedSpecialNil(b bool)`

 SetAllowedSpecialNil sets the value for AllowedSpecial to be an explicit nil

### UnsetAllowedSpecial
`func (o *ChunkSplitterOptions) UnsetAllowedSpecial()`

UnsetAllowedSpecial ensures that no value is present for AllowedSpecial, not even an explicit nil
### GetDisallowedSpecial

`func (o *ChunkSplitterOptions) GetDisallowedSpecial() DisallowedSpecial`

GetDisallowedSpecial returns the DisallowedSpecial field if non-nil, zero value otherwise.

### GetDisallowedSpecialOk

`func (o *ChunkSplitterOptions) GetDisallowedSpecialOk() (*DisallowedSpecial, bool)`

GetDisallowedSpecialOk returns a tuple with the DisallowedSpecial field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisallowedSpecial

`func (o *ChunkSplitterOptions) SetDisallowedSpecial(v DisallowedSpecial)`

SetDisallowedSpecial sets DisallowedSpecial field to given value.

### HasDisallowedSpecial

`func (o *ChunkSplitterOptions) HasDisallowedSpecial() bool`

HasDisallowedSpecial returns a boolean if a field has been set.

### GetHeadersToSplitOn

`func (o *ChunkSplitterOptions) GetHeadersToSplitOn() [][]interface{}`

GetHeadersToSplitOn returns the HeadersToSplitOn field if non-nil, zero value otherwise.

### GetHeadersToSplitOnOk

`func (o *ChunkSplitterOptions) GetHeadersToSplitOnOk() (*[][]interface{}, bool)`

GetHeadersToSplitOnOk returns a tuple with the HeadersToSplitOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeadersToSplitOn

`func (o *ChunkSplitterOptions) SetHeadersToSplitOn(v [][]interface{})`

SetHeadersToSplitOn sets HeadersToSplitOn field to given value.

### HasHeadersToSplitOn

`func (o *ChunkSplitterOptions) HasHeadersToSplitOn() bool`

HasHeadersToSplitOn returns a boolean if a field has been set.

### GetReturnEachLine

`func (o *ChunkSplitterOptions) GetReturnEachLine() bool`

GetReturnEachLine returns the ReturnEachLine field if non-nil, zero value otherwise.

### GetReturnEachLineOk

`func (o *ChunkSplitterOptions) GetReturnEachLineOk() (*bool, bool)`

GetReturnEachLineOk returns a tuple with the ReturnEachLine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnEachLine

`func (o *ChunkSplitterOptions) SetReturnEachLine(v bool)`

SetReturnEachLine sets ReturnEachLine field to given value.

### HasReturnEachLine

`func (o *ChunkSplitterOptions) HasReturnEachLine() bool`

HasReturnEachLine returns a boolean if a field has been set.

### GetStripHeaders

`func (o *ChunkSplitterOptions) GetStripHeaders() bool`

GetStripHeaders returns the StripHeaders field if non-nil, zero value otherwise.

### GetStripHeadersOk

`func (o *ChunkSplitterOptions) GetStripHeadersOk() (*bool, bool)`

GetStripHeadersOk returns a tuple with the StripHeaders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStripHeaders

`func (o *ChunkSplitterOptions) SetStripHeaders(v bool)`

SetStripHeaders sets StripHeaders field to given value.

### HasStripHeaders

`func (o *ChunkSplitterOptions) HasStripHeaders() bool`

HasStripHeaders returns a boolean if a field has been set.

### GetCustomHeaderPatterns

`func (o *ChunkSplitterOptions) GetCustomHeaderPatterns() map[string]int32`

GetCustomHeaderPatterns returns the CustomHeaderPatterns field if non-nil, zero value otherwise.

### GetCustomHeaderPatternsOk

`func (o *ChunkSplitterOptions) GetCustomHeaderPatternsOk() (*map[string]int32, bool)`

GetCustomHeaderPatternsOk returns a tuple with the CustomHeaderPatterns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomHeaderPatterns

`func (o *ChunkSplitterOptions) SetCustomHeaderPatterns(v map[string]int32)`

SetCustomHeaderPatterns sets CustomHeaderPatterns field to given value.

### HasCustomHeaderPatterns

`func (o *ChunkSplitterOptions) HasCustomHeaderPatterns() bool`

HasCustomHeaderPatterns returns a boolean if a field has been set.

### GetReturnEachElement

`func (o *ChunkSplitterOptions) GetReturnEachElement() bool`

GetReturnEachElement returns the ReturnEachElement field if non-nil, zero value otherwise.

### GetReturnEachElementOk

`func (o *ChunkSplitterOptions) GetReturnEachElementOk() (*bool, bool)`

GetReturnEachElementOk returns a tuple with the ReturnEachElement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnEachElement

`func (o *ChunkSplitterOptions) SetReturnEachElement(v bool)`

SetReturnEachElement sets ReturnEachElement field to given value.

### HasReturnEachElement

`func (o *ChunkSplitterOptions) HasReturnEachElement() bool`

HasReturnEachElement returns a boolean if a field has been set.

### GetMaxChunkSize

`func (o *ChunkSplitterOptions) GetMaxChunkSize() int32`

GetMaxChunkSize returns the MaxChunkSize field if non-nil, zero value otherwise.

### GetMaxChunkSizeOk

`func (o *ChunkSplitterOptions) GetMaxChunkSizeOk() (*int32, bool)`

GetMaxChunkSizeOk returns a tuple with the MaxChunkSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxChunkSize

`func (o *ChunkSplitterOptions) SetMaxChunkSize(v int32)`

SetMaxChunkSize sets MaxChunkSize field to given value.

### HasMaxChunkSize

`func (o *ChunkSplitterOptions) HasMaxChunkSize() bool`

HasMaxChunkSize returns a boolean if a field has been set.

### GetElementsToPreserve

`func (o *ChunkSplitterOptions) GetElementsToPreserve() []string`

GetElementsToPreserve returns the ElementsToPreserve field if non-nil, zero value otherwise.

### GetElementsToPreserveOk

`func (o *ChunkSplitterOptions) GetElementsToPreserveOk() (*[]string, bool)`

GetElementsToPreserveOk returns a tuple with the ElementsToPreserve field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetElementsToPreserve

`func (o *ChunkSplitterOptions) SetElementsToPreserve(v []string)`

SetElementsToPreserve sets ElementsToPreserve field to given value.

### HasElementsToPreserve

`func (o *ChunkSplitterOptions) HasElementsToPreserve() bool`

HasElementsToPreserve returns a boolean if a field has been set.

### GetPreserveLinks

`func (o *ChunkSplitterOptions) GetPreserveLinks() bool`

GetPreserveLinks returns the PreserveLinks field if non-nil, zero value otherwise.

### GetPreserveLinksOk

`func (o *ChunkSplitterOptions) GetPreserveLinksOk() (*bool, bool)`

GetPreserveLinksOk returns a tuple with the PreserveLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreserveLinks

`func (o *ChunkSplitterOptions) SetPreserveLinks(v bool)`

SetPreserveLinks sets PreserveLinks field to given value.

### HasPreserveLinks

`func (o *ChunkSplitterOptions) HasPreserveLinks() bool`

HasPreserveLinks returns a boolean if a field has been set.

### GetPreserveImages

`func (o *ChunkSplitterOptions) GetPreserveImages() bool`

GetPreserveImages returns the PreserveImages field if non-nil, zero value otherwise.

### GetPreserveImagesOk

`func (o *ChunkSplitterOptions) GetPreserveImagesOk() (*bool, bool)`

GetPreserveImagesOk returns a tuple with the PreserveImages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreserveImages

`func (o *ChunkSplitterOptions) SetPreserveImages(v bool)`

SetPreserveImages sets PreserveImages field to given value.

### HasPreserveImages

`func (o *ChunkSplitterOptions) HasPreserveImages() bool`

HasPreserveImages returns a boolean if a field has been set.

### GetPreserveVideos

`func (o *ChunkSplitterOptions) GetPreserveVideos() bool`

GetPreserveVideos returns the PreserveVideos field if non-nil, zero value otherwise.

### GetPreserveVideosOk

`func (o *ChunkSplitterOptions) GetPreserveVideosOk() (*bool, bool)`

GetPreserveVideosOk returns a tuple with the PreserveVideos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreserveVideos

`func (o *ChunkSplitterOptions) SetPreserveVideos(v bool)`

SetPreserveVideos sets PreserveVideos field to given value.

### HasPreserveVideos

`func (o *ChunkSplitterOptions) HasPreserveVideos() bool`

HasPreserveVideos returns a boolean if a field has been set.

### GetPreserveAudio

`func (o *ChunkSplitterOptions) GetPreserveAudio() bool`

GetPreserveAudio returns the PreserveAudio field if non-nil, zero value otherwise.

### GetPreserveAudioOk

`func (o *ChunkSplitterOptions) GetPreserveAudioOk() (*bool, bool)`

GetPreserveAudioOk returns a tuple with the PreserveAudio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreserveAudio

`func (o *ChunkSplitterOptions) SetPreserveAudio(v bool)`

SetPreserveAudio sets PreserveAudio field to given value.

### HasPreserveAudio

`func (o *ChunkSplitterOptions) HasPreserveAudio() bool`

HasPreserveAudio returns a boolean if a field has been set.

### GetCustomHandlers

`func (o *ChunkSplitterOptions) GetCustomHandlers() map[string]interface{}`

GetCustomHandlers returns the CustomHandlers field if non-nil, zero value otherwise.

### GetCustomHandlersOk

`func (o *ChunkSplitterOptions) GetCustomHandlersOk() (*map[string]interface{}, bool)`

GetCustomHandlersOk returns a tuple with the CustomHandlers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomHandlers

`func (o *ChunkSplitterOptions) SetCustomHandlers(v map[string]interface{})`

SetCustomHandlers sets CustomHandlers field to given value.

### HasCustomHandlers

`func (o *ChunkSplitterOptions) HasCustomHandlers() bool`

HasCustomHandlers returns a boolean if a field has been set.

### GetStopwordRemoval

`func (o *ChunkSplitterOptions) GetStopwordRemoval() bool`

GetStopwordRemoval returns the StopwordRemoval field if non-nil, zero value otherwise.

### GetStopwordRemovalOk

`func (o *ChunkSplitterOptions) GetStopwordRemovalOk() (*bool, bool)`

GetStopwordRemovalOk returns a tuple with the StopwordRemoval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopwordRemoval

`func (o *ChunkSplitterOptions) SetStopwordRemoval(v bool)`

SetStopwordRemoval sets StopwordRemoval field to given value.

### HasStopwordRemoval

`func (o *ChunkSplitterOptions) HasStopwordRemoval() bool`

HasStopwordRemoval returns a boolean if a field has been set.

### GetStopwordLang

`func (o *ChunkSplitterOptions) GetStopwordLang() string`

GetStopwordLang returns the StopwordLang field if non-nil, zero value otherwise.

### GetStopwordLangOk

`func (o *ChunkSplitterOptions) GetStopwordLangOk() (*string, bool)`

GetStopwordLangOk returns a tuple with the StopwordLang field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopwordLang

`func (o *ChunkSplitterOptions) SetStopwordLang(v string)`

SetStopwordLang sets StopwordLang field to given value.

### HasStopwordLang

`func (o *ChunkSplitterOptions) HasStopwordLang() bool`

HasStopwordLang returns a boolean if a field has been set.

### GetNormalizeText

`func (o *ChunkSplitterOptions) GetNormalizeText() bool`

GetNormalizeText returns the NormalizeText field if non-nil, zero value otherwise.

### GetNormalizeTextOk

`func (o *ChunkSplitterOptions) GetNormalizeTextOk() (*bool, bool)`

GetNormalizeTextOk returns a tuple with the NormalizeText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNormalizeText

`func (o *ChunkSplitterOptions) SetNormalizeText(v bool)`

SetNormalizeText sets NormalizeText field to given value.

### HasNormalizeText

`func (o *ChunkSplitterOptions) HasNormalizeText() bool`

HasNormalizeText returns a boolean if a field has been set.

### GetExternalMetadata

`func (o *ChunkSplitterOptions) GetExternalMetadata() map[string]string`

GetExternalMetadata returns the ExternalMetadata field if non-nil, zero value otherwise.

### GetExternalMetadataOk

`func (o *ChunkSplitterOptions) GetExternalMetadataOk() (*map[string]string, bool)`

GetExternalMetadataOk returns a tuple with the ExternalMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalMetadata

`func (o *ChunkSplitterOptions) SetExternalMetadata(v map[string]string)`

SetExternalMetadata sets ExternalMetadata field to given value.

### HasExternalMetadata

`func (o *ChunkSplitterOptions) HasExternalMetadata() bool`

HasExternalMetadata returns a boolean if a field has been set.

### GetAllowlistTags

`func (o *ChunkSplitterOptions) GetAllowlistTags() []string`

GetAllowlistTags returns the AllowlistTags field if non-nil, zero value otherwise.

### GetAllowlistTagsOk

`func (o *ChunkSplitterOptions) GetAllowlistTagsOk() (*[]string, bool)`

GetAllowlistTagsOk returns a tuple with the AllowlistTags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowlistTags

`func (o *ChunkSplitterOptions) SetAllowlistTags(v []string)`

SetAllowlistTags sets AllowlistTags field to given value.

### HasAllowlistTags

`func (o *ChunkSplitterOptions) HasAllowlistTags() bool`

HasAllowlistTags returns a boolean if a field has been set.

### GetDenylistTags

`func (o *ChunkSplitterOptions) GetDenylistTags() []string`

GetDenylistTags returns the DenylistTags field if non-nil, zero value otherwise.

### GetDenylistTagsOk

`func (o *ChunkSplitterOptions) GetDenylistTagsOk() (*[]string, bool)`

GetDenylistTagsOk returns a tuple with the DenylistTags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDenylistTags

`func (o *ChunkSplitterOptions) SetDenylistTags(v []string)`

SetDenylistTags sets DenylistTags field to given value.

### HasDenylistTags

`func (o *ChunkSplitterOptions) HasDenylistTags() bool`

HasDenylistTags returns a boolean if a field has been set.

### GetPreserveParentMetadata

`func (o *ChunkSplitterOptions) GetPreserveParentMetadata() bool`

GetPreserveParentMetadata returns the PreserveParentMetadata field if non-nil, zero value otherwise.

### GetPreserveParentMetadataOk

`func (o *ChunkSplitterOptions) GetPreserveParentMetadataOk() (*bool, bool)`

GetPreserveParentMetadataOk returns a tuple with the PreserveParentMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreserveParentMetadata

`func (o *ChunkSplitterOptions) SetPreserveParentMetadata(v bool)`

SetPreserveParentMetadata sets PreserveParentMetadata field to given value.

### HasPreserveParentMetadata

`func (o *ChunkSplitterOptions) HasPreserveParentMetadata() bool`

HasPreserveParentMetadata returns a boolean if a field has been set.

### GetMinChunkSize

`func (o *ChunkSplitterOptions) GetMinChunkSize() int32`

GetMinChunkSize returns the MinChunkSize field if non-nil, zero value otherwise.

### GetMinChunkSizeOk

`func (o *ChunkSplitterOptions) GetMinChunkSizeOk() (*int32, bool)`

GetMinChunkSizeOk returns a tuple with the MinChunkSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinChunkSize

`func (o *ChunkSplitterOptions) SetMinChunkSize(v int32)`

SetMinChunkSize sets MinChunkSize field to given value.

### HasMinChunkSize

`func (o *ChunkSplitterOptions) HasMinChunkSize() bool`

HasMinChunkSize returns a boolean if a field has been set.

### GetConvertLists

`func (o *ChunkSplitterOptions) GetConvertLists() bool`

GetConvertLists returns the ConvertLists field if non-nil, zero value otherwise.

### GetConvertListsOk

`func (o *ChunkSplitterOptions) GetConvertListsOk() (*bool, bool)`

GetConvertListsOk returns a tuple with the ConvertLists field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConvertLists

`func (o *ChunkSplitterOptions) SetConvertLists(v bool)`

SetConvertLists sets ConvertLists field to given value.

### HasConvertLists

`func (o *ChunkSplitterOptions) HasConvertLists() bool`

HasConvertLists returns a boolean if a field has been set.

### GetLanguage

`func (o *ChunkSplitterOptions) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *ChunkSplitterOptions) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *ChunkSplitterOptions) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *ChunkSplitterOptions) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetUseSpanTokenize

`func (o *ChunkSplitterOptions) GetUseSpanTokenize() bool`

GetUseSpanTokenize returns the UseSpanTokenize field if non-nil, zero value otherwise.

### GetUseSpanTokenizeOk

`func (o *ChunkSplitterOptions) GetUseSpanTokenizeOk() (*bool, bool)`

GetUseSpanTokenizeOk returns a tuple with the UseSpanTokenize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseSpanTokenize

`func (o *ChunkSplitterOptions) SetUseSpanTokenize(v bool)`

SetUseSpanTokenize sets UseSpanTokenize field to given value.

### HasUseSpanTokenize

`func (o *ChunkSplitterOptions) HasUseSpanTokenize() bool`

HasUseSpanTokenize returns a boolean if a field has been set.

### GetPipeline

`func (o *ChunkSplitterOptions) GetPipeline() string`

GetPipeline returns the Pipeline field if non-nil, zero value otherwise.

### GetPipelineOk

`func (o *ChunkSplitterOptions) GetPipelineOk() (*string, bool)`

GetPipelineOk returns a tuple with the Pipeline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPipeline

`func (o *ChunkSplitterOptions) SetPipeline(v string)`

SetPipeline sets Pipeline field to given value.

### HasPipeline

`func (o *ChunkSplitterOptions) HasPipeline() bool`

HasPipeline returns a boolean if a field has been set.

### GetMaxLength

`func (o *ChunkSplitterOptions) GetMaxLength() int32`

GetMaxLength returns the MaxLength field if non-nil, zero value otherwise.

### GetMaxLengthOk

`func (o *ChunkSplitterOptions) GetMaxLengthOk() (*int32, bool)`

GetMaxLengthOk returns a tuple with the MaxLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxLength

`func (o *ChunkSplitterOptions) SetMaxLength(v int32)`

SetMaxLength sets MaxLength field to given value.

### HasMaxLength

`func (o *ChunkSplitterOptions) HasMaxLength() bool`

HasMaxLength returns a boolean if a field has been set.

### GetStripWhitespace

`func (o *ChunkSplitterOptions) GetStripWhitespace() bool`

GetStripWhitespace returns the StripWhitespace field if non-nil, zero value otherwise.

### GetStripWhitespaceOk

`func (o *ChunkSplitterOptions) GetStripWhitespaceOk() (*bool, bool)`

GetStripWhitespaceOk returns a tuple with the StripWhitespace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStripWhitespace

`func (o *ChunkSplitterOptions) SetStripWhitespace(v bool)`

SetStripWhitespace sets StripWhitespace field to given value.

### HasStripWhitespace

`func (o *ChunkSplitterOptions) HasStripWhitespace() bool`

HasStripWhitespace returns a boolean if a field has been set.

### GetTokensPerChunk

`func (o *ChunkSplitterOptions) GetTokensPerChunk() int32`

GetTokensPerChunk returns the TokensPerChunk field if non-nil, zero value otherwise.

### GetTokensPerChunkOk

`func (o *ChunkSplitterOptions) GetTokensPerChunkOk() (*int32, bool)`

GetTokensPerChunkOk returns a tuple with the TokensPerChunk field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokensPerChunk

`func (o *ChunkSplitterOptions) SetTokensPerChunk(v int32)`

SetTokensPerChunk sets TokensPerChunk field to given value.

### HasTokensPerChunk

`func (o *ChunkSplitterOptions) HasTokensPerChunk() bool`

HasTokensPerChunk returns a boolean if a field has been set.

### GetModelKwargs

`func (o *ChunkSplitterOptions) GetModelKwargs() map[string]interface{}`

GetModelKwargs returns the ModelKwargs field if non-nil, zero value otherwise.

### GetModelKwargsOk

`func (o *ChunkSplitterOptions) GetModelKwargsOk() (*map[string]interface{}, bool)`

GetModelKwargsOk returns a tuple with the ModelKwargs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelKwargs

`func (o *ChunkSplitterOptions) SetModelKwargs(v map[string]interface{})`

SetModelKwargs sets ModelKwargs field to given value.

### HasModelKwargs

`func (o *ChunkSplitterOptions) HasModelKwargs() bool`

HasModelKwargs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


