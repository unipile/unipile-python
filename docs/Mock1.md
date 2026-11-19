# Mock1

Start the authentication intent with Mock provider.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider to authenticate with. | 
**credentials** | **object** | Test accounts do not have credentials, leave this as empty object. | 

## Example

```python
from unipile.models.mock1 import Mock1

# TODO update the JSON string below
json = "{}"
# create an instance of Mock1 from a JSON string
mock1_instance = Mock1.from_json(json)
# print the JSON string representation of the object
print(Mock1.to_json())

# convert the object into a dict
mock1_dict = mock1_instance.to_dict()
# create an instance of Mock1 from a dict
mock1_from_dict = Mock1.from_dict(mock1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


