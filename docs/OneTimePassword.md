# OneTimePassword

A one-time password was sent to the user's phone or email address. The user needs to enter the code in the next checkpoint.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | 

## Example

```python
from unipile.models.one_time_password import OneTimePassword

# TODO update the JSON string below
json = "{}"
# create an instance of OneTimePassword from a JSON string
one_time_password_instance = OneTimePassword.from_json(json)
# print the JSON string representation of the object
print(OneTimePassword.to_json())

# convert the object into a dict
one_time_password_dict = one_time_password_instance.to_dict()
# create an instance of OneTimePassword from a dict
one_time_password_from_dict = OneTimePassword.from_dict(one_time_password_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


