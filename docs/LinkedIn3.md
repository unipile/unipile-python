# LinkedIn3

Start the authentication intent with LinkedIn provider.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**provider** | **str** | The provider to authenticate with. | 
**user_timezone** | **str** | The time zone of the current user can be used on a few specific features (e.g. scheduled actions). Setting it at authentication avoids having to do it on a case-by-case basis later on. | [optional] 
**user_language** | **str** | Primary browser language captured with the session cookies. | [optional] 
**user_languages** | **List[str]** | Ordered browser language preferences captured with the session cookies. | [optional] 
**credentials** | [**LinkedIn3Credentials**](LinkedIn3Credentials.md) |  | 
**config** | [**LinkedIn3Config**](LinkedIn3Config.md) |  | [optional] 

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


