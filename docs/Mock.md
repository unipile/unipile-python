# Mock

Start the authentication intent with Mock provider.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider to authenticate with. | 
**credentials** | **object** | Test accounts do not have credentials, leave this as empty object. | 

## Example

```python
from unipile.models.mock import Mock

# TODO update the JSON string below
json = "{}"
# create an instance of Mock from a JSON string
mock_instance = Mock.from_json(json)
# print the JSON string representation of the object
print(Mock.to_json())

# convert the object into a dict
mock_dict = mock_instance.to_dict()
# create an instance of Mock from a dict
mock_from_dict = Mock.from_dict(mock_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


