# FilePresignedURLResponse

DTO for file presigned URL response.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**url** | **str** |  | 

## Example

```python
from openapi_client.models.file_presigned_url_response import FilePresignedURLResponse

# TODO update the JSON string below
json = "{}"
# create an instance of FilePresignedURLResponse from a JSON string
file_presigned_url_response_instance = FilePresignedURLResponse.from_json(json)
# print the JSON string representation of the object
print(FilePresignedURLResponse.to_json())

# convert the object into a dict
file_presigned_url_response_dict = file_presigned_url_response_instance.to_dict()
# create an instance of FilePresignedURLResponse from a dict
file_presigned_url_response_from_dict = FilePresignedURLResponse.from_dict(file_presigned_url_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


