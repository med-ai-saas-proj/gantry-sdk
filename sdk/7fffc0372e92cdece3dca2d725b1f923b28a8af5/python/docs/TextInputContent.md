# TextInputContent

A text fragment in a multimodal user message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'text']
**text** | **str** |  | 

## Example

```python
from openapi_client.models.text_input_content import TextInputContent

# TODO update the JSON string below
json = "{}"
# create an instance of TextInputContent from a JSON string
text_input_content_instance = TextInputContent.from_json(json)
# print the JSON string representation of the object
print(TextInputContent.to_json())

# convert the object into a dict
text_input_content_dict = text_input_content_instance.to_dict()
# create an instance of TextInputContent from a dict
text_input_content_from_dict = TextInputContent.from_dict(text_input_content_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


