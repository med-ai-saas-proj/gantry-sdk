# VideoInputContent

A video input content fragment.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'video']
**source** | [**Source**](Source.md) |  | 
**metadata** | [**AnyOf**](AnyOf.md) |  | [optional] 

## Example

```python
from openapi_client.models.video_input_content import VideoInputContent

# TODO update the JSON string below
json = "{}"
# create an instance of VideoInputContent from a JSON string
video_input_content_instance = VideoInputContent.from_json(json)
# print the JSON string representation of the object
print(VideoInputContent.to_json())

# convert the object into a dict
video_input_content_dict = video_input_content_instance.to_dict()
# create an instance of VideoInputContent from a dict
video_input_content_from_dict = VideoInputContent.from_dict(video_input_content_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


