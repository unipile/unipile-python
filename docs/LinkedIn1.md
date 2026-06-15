# LinkedIn1

Start the authentication intent with LinkedIn provider.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider to authenticate with. | 
**user_timezone** | **str** | The time zone of the current user can be used on a few specific features (e.g. scheduled actions). Setting it at authentication avoids having to do it on a case-by-case basis later on. | [optional] 
**credentials** | [**LinkedIn1Credentials**](LinkedIn1Credentials.md) |  | 
**config** | [**LinkedIn1Config**](LinkedIn1Config.md) |  | [optional] 

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


