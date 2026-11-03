# PasswordAuthentication

Use email and password to authenticate with LinkedIn.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**username** | **str** | Email or phone of the LinkedIn account. | 
**password** | **str** | Password of the LinkedIn account. | 
**user_agent** | **str** | A custom user agent if you need the session to be started from a specific browser. You can easily get it in the browser&#39;s console with this command : &#x60;console.log(navigator.userAgent)&#x60; | [optional] 

## Example

```python
from unipile.models.password_authentication import PasswordAuthentication

# TODO update the JSON string below
json = "{}"
# create an instance of PasswordAuthentication from a JSON string
password_authentication_instance = PasswordAuthentication.from_json(json)
# print the JSON string representation of the object
print(PasswordAuthentication.to_json())

# convert the object into a dict
password_authentication_dict = password_authentication_instance.to_dict()
# create an instance of PasswordAuthentication from a dict
password_authentication_from_dict = PasswordAuthentication.from_dict(password_authentication_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


