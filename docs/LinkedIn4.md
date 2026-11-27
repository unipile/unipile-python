# LinkedIn4

Specific options to apply if the provider of the targeted account is Linkedin.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**password** | **str** | The password of the account. LinkedIn asks for it on every unblock and rejects the operation without it. It is only forwarded to the provider and never stored. | 

## Example

```python
from unipile.models.linked_in4 import LinkedIn4

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn4 from a JSON string
linked_in4_instance = LinkedIn4.from_json(json)
# print the JSON string representation of the object
print(LinkedIn4.to_json())

# convert the object into a dict
linked_in4_dict = linked_in4_instance.to_dict()
# create an instance of LinkedIn4 from a dict
linked_in4_from_dict = LinkedIn4.from_dict(linked_in4_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


