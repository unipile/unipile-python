# Telegram1Credentials

The user credentials required by the provider to authenticate with.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**qrcode** | **bool** | This must be set to &#x60;true&#x60; | 
**twofa** | **str** | The 2FA code to authenticate with. | [optional] 

## Example

```python
from unipile.models.telegram1_credentials import Telegram1Credentials

# TODO update the JSON string below
json = "{}"
# create an instance of Telegram1Credentials from a JSON string
telegram1_credentials_instance = Telegram1Credentials.from_json(json)
# print the JSON string representation of the object
print(Telegram1Credentials.to_json())

# convert the object into a dict
telegram1_credentials_dict = telegram1_credentials_instance.to_dict()
# create an instance of Telegram1Credentials from a dict
telegram1_credentials_from_dict = Telegram1Credentials.from_dict(telegram1_credentials_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


