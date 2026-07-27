# LinkedIn2

Start the authentication intent with LinkedIn provider.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider to authenticate with. | 
**user_timezone** | **str** | The time zone of the current user can be used on a few specific features (e.g. scheduled actions). Setting it at authentication avoids having to do it on a case-by-case basis later on. | [optional] 
**credentials** | [**LinkedIn2Credentials**](LinkedIn2Credentials.md) |  | 
**config** | [**LinkedIn2Config**](LinkedIn2Config.md) |  | [optional] 

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


