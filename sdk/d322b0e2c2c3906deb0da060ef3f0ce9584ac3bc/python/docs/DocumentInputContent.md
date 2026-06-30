# DocumentInputContent

A document input content fragment.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'document']
**source** | [**Source**](Source.md) |  | 
**metadata** | [**AnyOf**](AnyOf.md) |  | [optional] 

## Example

```python
from openapi_client.models.document_input_content import DocumentInputContent

# TODO update the JSON string below
json = "{}"
# create an instance of DocumentInputContent from a JSON string
document_input_content_instance = DocumentInputContent.from_json(json)
# print the JSON string representation of the object
print(DocumentInputContent.to_json())

# convert the object into a dict
document_input_content_dict = document_input_content_instance.to_dict()
# create an instance of DocumentInputContent from a dict
document_input_content_from_dict = DocumentInputContent.from_dict(document_input_content_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


