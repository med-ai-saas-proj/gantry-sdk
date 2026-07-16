# UpdateFileMetadataRequest

DTO for updating file metadata.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**extra_metadata** | [**Dict[str, UpdateFileMetadataRequestExtraMetadataValue]**](UpdateFileMetadataRequestExtraMetadataValue.md) |  | 

## Example

```python
from openapi_client.models.update_file_metadata_request import UpdateFileMetadataRequest

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateFileMetadataRequest from a JSON string
update_file_metadata_request_instance = UpdateFileMetadataRequest.from_json(json)
# print the JSON string representation of the object
print(UpdateFileMetadataRequest.to_json())

# convert the object into a dict
update_file_metadata_request_dict = update_file_metadata_request_instance.to_dict()
# create an instance of UpdateFileMetadataRequest from a dict
update_file_metadata_request_from_dict = UpdateFileMetadataRequest.from_dict(update_file_metadata_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


