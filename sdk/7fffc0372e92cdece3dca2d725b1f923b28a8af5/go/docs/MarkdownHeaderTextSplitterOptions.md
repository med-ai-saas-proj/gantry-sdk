# MarkdownHeaderTextSplitterOptions

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**HeadersToSplitOn** | Pointer to **[][]interface{}** |  | [optional] 
**ReturnEachLine** | Pointer to **bool** |  | [optional] 
**StripHeaders** | Pointer to **bool** |  | [optional] 
**CustomHeaderPatterns** | Pointer to **map[string]int32** |  | [optional] 

## Methods

### NewMarkdownHeaderTextSplitterOptions

`func NewMarkdownHeaderTextSplitterOptions() *MarkdownHeaderTextSplitterOptions`

NewMarkdownHeaderTextSplitterOptions instantiates a new MarkdownHeaderTextSplitterOptions object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMarkdownHeaderTextSplitterOptionsWithDefaults

`func NewMarkdownHeaderTextSplitterOptionsWithDefaults() *MarkdownHeaderTextSplitterOptions`

NewMarkdownHeaderTextSplitterOptionsWithDefaults instantiates a new MarkdownHeaderTextSplitterOptions object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHeadersToSplitOn

`func (o *MarkdownHeaderTextSplitterOptions) GetHeadersToSplitOn() [][]interface{}`

GetHeadersToSplitOn returns the HeadersToSplitOn field if non-nil, zero value otherwise.

### GetHeadersToSplitOnOk

`func (o *MarkdownHeaderTextSplitterOptions) GetHeadersToSplitOnOk() (*[][]interface{}, bool)`

GetHeadersToSplitOnOk returns a tuple with the HeadersToSplitOn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeadersToSplitOn

`func (o *MarkdownHeaderTextSplitterOptions) SetHeadersToSplitOn(v [][]interface{})`

SetHeadersToSplitOn sets HeadersToSplitOn field to given value.

### HasHeadersToSplitOn

`func (o *MarkdownHeaderTextSplitterOptions) HasHeadersToSplitOn() bool`

HasHeadersToSplitOn returns a boolean if a field has been set.

### GetReturnEachLine

`func (o *MarkdownHeaderTextSplitterOptions) GetReturnEachLine() bool`

GetReturnEachLine returns the ReturnEachLine field if non-nil, zero value otherwise.

### GetReturnEachLineOk

`func (o *MarkdownHeaderTextSplitterOptions) GetReturnEachLineOk() (*bool, bool)`

GetReturnEachLineOk returns a tuple with the ReturnEachLine field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnEachLine

`func (o *MarkdownHeaderTextSplitterOptions) SetReturnEachLine(v bool)`

SetReturnEachLine sets ReturnEachLine field to given value.

### HasReturnEachLine

`func (o *MarkdownHeaderTextSplitterOptions) HasReturnEachLine() bool`

HasReturnEachLine returns a boolean if a field has been set.

### GetStripHeaders

`func (o *MarkdownHeaderTextSplitterOptions) GetStripHeaders() bool`

GetStripHeaders returns the StripHeaders field if non-nil, zero value otherwise.

### GetStripHeadersOk

`func (o *MarkdownHeaderTextSplitterOptions) GetStripHeadersOk() (*bool, bool)`

GetStripHeadersOk returns a tuple with the StripHeaders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStripHeaders

`func (o *MarkdownHeaderTextSplitterOptions) SetStripHeaders(v bool)`

SetStripHeaders sets StripHeaders field to given value.

### HasStripHeaders

`func (o *MarkdownHeaderTextSplitterOptions) HasStripHeaders() bool`

HasStripHeaders returns a boolean if a field has been set.

### GetCustomHeaderPatterns

`func (o *MarkdownHeaderTextSplitterOptions) GetCustomHeaderPatterns() map[string]int32`

GetCustomHeaderPatterns returns the CustomHeaderPatterns field if non-nil, zero value otherwise.

### GetCustomHeaderPatternsOk

`func (o *MarkdownHeaderTextSplitterOptions) GetCustomHeaderPatternsOk() (*map[string]int32, bool)`

GetCustomHeaderPatternsOk returns a tuple with the CustomHeaderPatterns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomHeaderPatterns

`func (o *MarkdownHeaderTextSplitterOptions) SetCustomHeaderPatterns(v map[string]int32)`

SetCustomHeaderPatterns sets CustomHeaderPatterns field to given value.

### HasCustomHeaderPatterns

`func (o *MarkdownHeaderTextSplitterOptions) HasCustomHeaderPatterns() bool`

HasCustomHeaderPatterns returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


