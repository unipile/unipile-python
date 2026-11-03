# PasswordAuthentication1

Use Facebook credentials to authenticate with Meta messaging.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**username** | **str** | Email or username of the Facebook account. | 
**password** | **str** | Password of the Facebook account. | 

## Example

```python
from unipile.models.password_authentication1 import PasswordAuthentication1

# TODO update the JSON string below
json = "{}"
# create an instance of PasswordAuthentication1 from a JSON string
password_authentication1_instance = PasswordAuthentication1.from_json(json)
# print the JSON string representation of the object
print(PasswordAuthentication1.to_json())

# convert the object into a dict
password_authentication1_dict = password_authentication1_instance.to_dict()
# create an instance of PasswordAuthentication1 from a dict
password_authentication1_from_dict = PasswordAuthentication1.from_dict(password_authentication1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


