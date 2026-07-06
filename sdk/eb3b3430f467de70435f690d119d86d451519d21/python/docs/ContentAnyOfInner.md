# ContentAnyOfInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | [optional] [default to 'text']
**text** | **str** |  | 
**source** | [**Source**](Source.md) |  | 
**metadata** | [**AnyOf**](AnyOf.md) |  | [optional] 
**mime_type** | **str** |  | 
**id** | **str** |  | [optional] 
**url** | **str** |  | [optional] 
**data** | **str** |  | [optional] 
**filename** | **str** |  | [optional] 

## Example

```python
from openapi_client.models.content_any_of_inner import ContentAnyOfInner

# TODO update the JSON string below
json = "{}"
# create an instance of ContentAnyOfInner from a JSON string
content_any_of_inner_instance = ContentAnyOfInner.from_json(json)
# print the JSON string representation of the object
print(ContentAnyOfInner.to_json())

# convert the object into a dict
content_any_of_inner_dict = content_any_of_inner_instance.to_dict()
# create an instance of ContentAnyOfInner from a dict
content_any_of_inner_from_dict = ContentAnyOfInner.from_dict(content_any_of_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


