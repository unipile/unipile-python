# PhoneRegister

The user needs to register their phone number so an OTP can be sent.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | 

## Example

```python
from unipile.models.phone_register import PhoneRegister

# TODO update the JSON string below
json = "{}"
# create an instance of PhoneRegister from a JSON string
phone_register_instance = PhoneRegister.from_json(json)
# print the JSON string representation of the object
print(PhoneRegister.to_json())

# convert the object into a dict
phone_register_dict = phone_register_instance.to_dict()
# create an instance of PhoneRegister from a dict
phone_register_from_dict = PhoneRegister.from_dict(phone_register_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


