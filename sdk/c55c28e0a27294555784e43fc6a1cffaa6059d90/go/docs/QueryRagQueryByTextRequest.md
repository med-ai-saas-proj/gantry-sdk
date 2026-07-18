# QueryRagQueryByTextRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**QueryText** | **string** |  | 
**TopK** | Pointer to **int32** |  | [optional] [default to 5]
**Filters** | Pointer to [**NullableFilters**](Filters.md) |  | [optional] 
**HybridSearch** | Pointer to **bool** | Whether to perform a hybrid search that combines vector similarity and BM25 text search. If true, the service will first use BM25 + semantic search to filter candidates and then rerank them using vector similarity. | [optional] [default to false]
**HybridSearchBm25TopK** | Pointer to **int32** | When hybrid_search is true, this parameter controls the number of top candidates to retrieve using BM25 before reranking with vector similarity. A higher value may improve recall but increase latency. | [optional] [default to 5]
**HybridSearchSemanticTopK** | Pointer to **int32** | When hybrid_search is true, this parameter controls the number of top candidates to retrieve using semantic search before reranking with vector similarity. A higher value may improve recall but increase latency. | [optional] [default to 5]
**HybridSearchBm25Lang** | Pointer to **string** | When hybrid_search is true, this parameter specifies the language to use for BM25 search. This can affect tokenization and stopword removal, which in turn can impact search results. The default &#39;simple&#39; option applies basic tokenization and is suitable for many languages, but you may want to specify a particular language for better results with certain languages. | [optional] [default to "simple"]

## Methods

### NewQueryRagQueryByTextRequest

`func NewQueryRagQueryByTextRequest(queryText string, ) *QueryRagQueryByTextRequest`

NewQueryRagQueryByTextRequest instantiates a new QueryRagQueryByTextRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueryRagQueryByTextRequestWithDefaults

`func NewQueryRagQueryByTextRequestWithDefaults() *QueryRagQueryByTextRequest`

NewQueryRagQueryByTextRequestWithDefaults instantiates a new QueryRagQueryByTextRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQueryText

`func (o *QueryRagQueryByTextRequest) GetQueryText() string`

GetQueryText returns the QueryText field if non-nil, zero value otherwise.

### GetQueryTextOk

`func (o *QueryRagQueryByTextRequest) GetQueryTextOk() (*string, bool)`

GetQueryTextOk returns a tuple with the QueryText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueryText

`func (o *QueryRagQueryByTextRequest) SetQueryText(v string)`

SetQueryText sets QueryText field to given value.


### GetTopK

`func (o *QueryRagQueryByTextRequest) GetTopK() int32`

GetTopK returns the TopK field if non-nil, zero value otherwise.

### GetTopKOk

`func (o *QueryRagQueryByTextRequest) GetTopKOk() (*int32, bool)`

GetTopKOk returns a tuple with the TopK field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopK

`func (o *QueryRagQueryByTextRequest) SetTopK(v int32)`

SetTopK sets TopK field to given value.

### HasTopK

`func (o *QueryRagQueryByTextRequest) HasTopK() bool`

HasTopK returns a boolean if a field has been set.

### GetFilters

`func (o *QueryRagQueryByTextRequest) GetFilters() Filters`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *QueryRagQueryByTextRequest) GetFiltersOk() (*Filters, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *QueryRagQueryByTextRequest) SetFilters(v Filters)`

SetFilters sets Filters field to given value.

### HasFilters

`func (o *QueryRagQueryByTextRequest) HasFilters() bool`

HasFilters returns a boolean if a field has been set.

### SetFiltersNil

`func (o *QueryRagQueryByTextRequest) SetFiltersNil(b bool)`

 SetFiltersNil sets the value for Filters to be an explicit nil

### UnsetFilters
`func (o *QueryRagQueryByTextRequest) UnsetFilters()`

UnsetFilters ensures that no value is present for Filters, not even an explicit nil
### GetHybridSearch

`func (o *QueryRagQueryByTextRequest) GetHybridSearch() bool`

GetHybridSearch returns the HybridSearch field if non-nil, zero value otherwise.

### GetHybridSearchOk

`func (o *QueryRagQueryByTextRequest) GetHybridSearchOk() (*bool, bool)`

GetHybridSearchOk returns a tuple with the HybridSearch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHybridSearch

`func (o *QueryRagQueryByTextRequest) SetHybridSearch(v bool)`

SetHybridSearch sets HybridSearch field to given value.

### HasHybridSearch

`func (o *QueryRagQueryByTextRequest) HasHybridSearch() bool`

HasHybridSearch returns a boolean if a field has been set.

### GetHybridSearchBm25TopK

`func (o *QueryRagQueryByTextRequest) GetHybridSearchBm25TopK() int32`

GetHybridSearchBm25TopK returns the HybridSearchBm25TopK field if non-nil, zero value otherwise.

### GetHybridSearchBm25TopKOk

`func (o *QueryRagQueryByTextRequest) GetHybridSearchBm25TopKOk() (*int32, bool)`

GetHybridSearchBm25TopKOk returns a tuple with the HybridSearchBm25TopK field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHybridSearchBm25TopK

`func (o *QueryRagQueryByTextRequest) SetHybridSearchBm25TopK(v int32)`

SetHybridSearchBm25TopK sets HybridSearchBm25TopK field to given value.

### HasHybridSearchBm25TopK

`func (o *QueryRagQueryByTextRequest) HasHybridSearchBm25TopK() bool`

HasHybridSearchBm25TopK returns a boolean if a field has been set.

### GetHybridSearchSemanticTopK

`func (o *QueryRagQueryByTextRequest) GetHybridSearchSemanticTopK() int32`

GetHybridSearchSemanticTopK returns the HybridSearchSemanticTopK field if non-nil, zero value otherwise.

### GetHybridSearchSemanticTopKOk

`func (o *QueryRagQueryByTextRequest) GetHybridSearchSemanticTopKOk() (*int32, bool)`

GetHybridSearchSemanticTopKOk returns a tuple with the HybridSearchSemanticTopK field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHybridSearchSemanticTopK

`func (o *QueryRagQueryByTextRequest) SetHybridSearchSemanticTopK(v int32)`

SetHybridSearchSemanticTopK sets HybridSearchSemanticTopK field to given value.

### HasHybridSearchSemanticTopK

`func (o *QueryRagQueryByTextRequest) HasHybridSearchSemanticTopK() bool`

HasHybridSearchSemanticTopK returns a boolean if a field has been set.

### GetHybridSearchBm25Lang

`func (o *QueryRagQueryByTextRequest) GetHybridSearchBm25Lang() string`

GetHybridSearchBm25Lang returns the HybridSearchBm25Lang field if non-nil, zero value otherwise.

### GetHybridSearchBm25LangOk

`func (o *QueryRagQueryByTextRequest) GetHybridSearchBm25LangOk() (*string, bool)`

GetHybridSearchBm25LangOk returns a tuple with the HybridSearchBm25Lang field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHybridSearchBm25Lang

`func (o *QueryRagQueryByTextRequest) SetHybridSearchBm25Lang(v string)`

SetHybridSearchBm25Lang sets HybridSearchBm25Lang field to given value.

### HasHybridSearchBm25Lang

`func (o *QueryRagQueryByTextRequest) HasHybridSearchBm25Lang() bool`

HasHybridSearchBm25Lang returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


