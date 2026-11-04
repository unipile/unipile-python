# LinkedIn2

Specific options to apply if the provider of the targeted account is Linkedin.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**password** | **str** | The password of the account. LinkedIn asks for it on every unblock and rejects the operation without it. It is only forwarded to the provider and never stored. | 

## Example

```python
from unipile.models.linked_in2 import LinkedIn2

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn2 from a JSON string
linked_in2_instance = LinkedIn2.from_json(json)
# print the JSON string representation of the object
print(LinkedIn2.to_json())

# convert the object into a dict
linked_in2_dict = linked_in2_instance.to_dict()
# create an instance of LinkedIn2 from a dict
linked_in2_from_dict = LinkedIn2.from_dict(linked_in2_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


