# QueryFilterByFileUid

DTO for querying RAG embeddings with file UID filters.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**file_uids** | **List[UUID]** |  | 

## Example

```python
from openapi_client.models.query_filter_by_file_uid import QueryFilterByFileUid

# TODO update the JSON string below
json = "{}"
# create an instance of QueryFilterByFileUid from a JSON string
query_filter_by_file_uid_instance = QueryFilterByFileUid.from_json(json)
# print the JSON string representation of the object
print(QueryFilterByFileUid.to_json())

# convert the object into a dict
query_filter_by_file_uid_dict = query_filter_by_file_uid_instance.to_dict()
# create an instance of QueryFilterByFileUid from a dict
query_filter_by_file_uid_from_dict = QueryFilterByFileUid.from_dict(query_filter_by_file_uid_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


