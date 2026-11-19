# LinkedIn3

Specific options to apply if the provider of the targeted account is Linkedin.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**password** | **str** | The password of the account. LinkedIn asks for it on every unblock and rejects the operation without it. It is only forwarded to the provider and never stored. | 

## Example

```python
from unipile.models.linked_in3 import LinkedIn3

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn3 from a JSON string
linked_in3_instance = LinkedIn3.from_json(json)
# print the JSON string representation of the object
print(LinkedIn3.to_json())

# convert the object into a dict
linked_in3_dict = linked_in3_instance.to_dict()
# create an instance of LinkedIn3 from a dict
linked_in3_from_dict = LinkedIn3.from_dict(linked_in3_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


