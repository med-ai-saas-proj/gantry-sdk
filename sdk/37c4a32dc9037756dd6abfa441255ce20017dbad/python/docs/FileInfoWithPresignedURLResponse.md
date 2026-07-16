# FileInfoWithPresignedURLResponse

DTO for file info with URL response.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**url** | **str** |  | 
**id** | **str** |  | 
**filename** | **str** |  | 
**mime_type** | **str** |  | 
**size** | **int** |  | 
**created_at** | **datetime** |  | 
**extra_metadata** | **Dict[str, object]** |  | 

## Example

```python
from openapi_client.models.file_info_with_presigned_url_response import FileInfoWithPresignedURLResponse

# TODO update the JSON string below
json = "{}"
# create an instance of FileInfoWithPresignedURLResponse from a JSON string
file_info_with_presigned_url_response_instance = FileInfoWithPresignedURLResponse.from_json(json)
# print the JSON string representation of the object
print(FileInfoWithPresignedURLResponse.to_json())

# convert the object into a dict
file_info_with_presigned_url_response_dict = file_info_with_presigned_url_response_instance.to_dict()
# create an instance of FileInfoWithPresignedURLResponse from a dict
file_info_with_presigned_url_response_from_dict = FileInfoWithPresignedURLResponse.from_dict(file_info_with_presigned_url_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


