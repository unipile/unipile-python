# LinkedIn1


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | The category of the message: a regular message, an email, a connection invitation, or an InMail lifecycle event. | 
**subject** | **str** | The subject of the message. | [optional] 

## Example

```python
from unipile.models.linked_in1 import LinkedIn1

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn1 from a JSON string
linked_in1_instance = LinkedIn1.from_json(json)
# print the JSON string representation of the object
print(LinkedIn1.to_json())

# convert the object into a dict
linked_in1_dict = linked_in1_instance.to_dict()
# create an instance of LinkedIn1 from a dict
linked_in1_from_dict = LinkedIn1.from_dict(linked_in1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


