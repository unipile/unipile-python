# PasswordAuthenticationAutomaticServerSettings

Basic authentication, our servers will try to guess the correct IMAP/SMTP connection parameters for your IMAP provider. If this fails, an error will be returned and you should use the full authentication method.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**user** | **str** | Username | 
**password** | **str** | Password | 

## Example

```python
from unipile.models.password_authentication_automatic_server_settings import PasswordAuthenticationAutomaticServerSettings

# TODO update the JSON string below
json = "{}"
# create an instance of PasswordAuthenticationAutomaticServerSettings from a JSON string
password_authentication_automatic_server_settings_instance = PasswordAuthenticationAutomaticServerSettings.from_json(json)
# print the JSON string representation of the object
print(PasswordAuthenticationAutomaticServerSettings.to_json())

# convert the object into a dict
password_authentication_automatic_server_settings_dict = password_authentication_automatic_server_settings_instance.to_dict()
# create an instance of PasswordAuthenticationAutomaticServerSettings from a dict
password_authentication_automatic_server_settings_from_dict = PasswordAuthenticationAutomaticServerSettings.from_dict(password_authentication_automatic_server_settings_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


