# LinkedIn4

Start the authentication intent with LinkedIn provider.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider to authenticate with. | 
**user_timezone** | **str** | The time zone of the current user can be used on a few specific features (e.g. scheduled actions). Setting it at authentication avoids having to do it on a case-by-case basis later on. | [optional] 
**user_language** | **str** | Primary browser language captured with the session cookies. | [optional] 
**user_languages** | **List[str]** | Ordered browser language preferences captured with the session cookies. | [optional] 
**credentials** | [**LinkedIn4Credentials**](LinkedIn4Credentials.md) |  | 
**config** | [**LinkedIn4Config**](LinkedIn4Config.md) |  | [optional] 

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


