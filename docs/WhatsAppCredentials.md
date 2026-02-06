# WhatsAppCredentials

The user credentials required by the provider to authenticate with.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**qrcode** | **bool** | This must be set to &#x60;true&#x60; | 

## Example

```python
from unipile.models.whats_app_credentials import WhatsAppCredentials

# TODO update the JSON string below
json = "{}"
# create an instance of WhatsAppCredentials from a JSON string
whats_app_credentials_instance = WhatsAppCredentials.from_json(json)
# print the JSON string representation of the object
print(WhatsAppCredentials.to_json())

# convert the object into a dict
whats_app_credentials_dict = whats_app_credentials_instance.to_dict()
# create an instance of WhatsAppCredentials from a dict
whats_app_credentials_from_dict = WhatsAppCredentials.from_dict(whats_app_credentials_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


