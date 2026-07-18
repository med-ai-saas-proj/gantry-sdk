# QueryFilterByFileMetadata

DTO for querying RAG embeddings with file metadata filters.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**file_metadata_filters** | [**Dict[str, FileMetadataFiltersValue]**](FileMetadataFiltersValue.md) |  | 

## Example

```python
from openapi_client.models.query_filter_by_file_metadata import QueryFilterByFileMetadata

# TODO update the JSON string below
json = "{}"
# create an instance of QueryFilterByFileMetadata from a JSON string
query_filter_by_file_metadata_instance = QueryFilterByFileMetadata.from_json(json)
# print the JSON string representation of the object
print(QueryFilterByFileMetadata.to_json())

# convert the object into a dict
query_filter_by_file_metadata_dict = query_filter_by_file_metadata_instance.to_dict()
# create an instance of QueryFilterByFileMetadata from a dict
query_filter_by_file_metadata_from_dict = QueryFilterByFileMetadata.from_dict(query_filter_by_file_metadata_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


