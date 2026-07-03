# ImageInputContent

An image input content fragment.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'image']
**source** | [**Source**](Source.md) |  | 
**metadata** | [**AnyOf**](AnyOf.md) |  | [optional] 

## Example

```python
from openapi_client.models.image_input_content import ImageInputContent

# TODO update the JSON string below
json = "{}"
# create an instance of ImageInputContent from a JSON string
image_input_content_instance = ImageInputContent.from_json(json)
# print the JSON string representation of the object
print(ImageInputContent.to_json())

# convert the object into a dict
image_input_content_dict = image_input_content_instance.to_dict()
# create an instance of ImageInputContent from a dict
image_input_content_from_dict = ImageInputContent.from_dict(image_input_content_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


