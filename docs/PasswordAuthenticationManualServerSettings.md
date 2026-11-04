# PasswordAuthenticationManualServerSettings

Full authentication, you can manually specify the IMAP/SMTP connection parameters. This is useful if the basic authentication method fails.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**imap** | [**IMAPConnectionsParameters**](IMAPConnectionsParameters.md) |  | 
**smtp** | [**SMTPConnectionsParameters**](SMTPConnectionsParameters.md) |  | 

## Example

```python
from unipile.models.password_authentication_manual_server_settings import PasswordAuthenticationManualServerSettings

# TODO update the JSON string below
json = "{}"
# create an instance of PasswordAuthenticationManualServerSettings from a JSON string
password_authentication_manual_server_settings_instance = PasswordAuthenticationManualServerSettings.from_json(json)
# print the JSON string representation of the object
print(PasswordAuthenticationManualServerSettings.to_json())

# convert the object into a dict
password_authentication_manual_server_settings_dict = password_authentication_manual_server_settings_instance.to_dict()
# create an instance of PasswordAuthenticationManualServerSettings from a dict
password_authentication_manual_server_settings_from_dict = PasswordAuthenticationManualServerSettings.from_dict(password_authentication_manual_server_settings_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


