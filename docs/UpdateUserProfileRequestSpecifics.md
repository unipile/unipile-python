# UpdateUserProfileRequestSpecifics


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**linkedin** | [**UpdateUserProfileRequestSpecificsAllOfLinkedin**](UpdateUserProfileRequestSpecificsAllOfLinkedin.md) |  | [optional] 

## Example

```python
from unipile.models.update_user_profile_request_specifics import UpdateUserProfileRequestSpecifics

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateUserProfileRequestSpecifics from a JSON string
update_user_profile_request_specifics_instance = UpdateUserProfileRequestSpecifics.from_json(json)
# print the JSON string representation of the object
print(UpdateUserProfileRequestSpecifics.to_json())

# convert the object into a dict
update_user_profile_request_specifics_dict = update_user_profile_request_specifics_instance.to_dict()
# create an instance of UpdateUserProfileRequestSpecifics from a dict
update_user_profile_request_specifics_from_dict = UpdateUserProfileRequestSpecifics.from_dict(update_user_profile_request_specifics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


