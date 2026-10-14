# WhatsApp4Credentials

The user credentials required by the provider to authenticate with.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**qrcode** | **bool** | This must be set to &#x60;true&#x60; | 
**phone_number** | **str** | Phone number to link, in international format with digits only (no &#x60;+&#x60;, spaces or separators), e.g. &#x60;33612345678&#x60;. A pairing code will be returned to enter on this phone. | 

## Example

```python
from unipile.models.whats_app4_credentials import WhatsApp4Credentials

# TODO update the JSON string below
json = "{}"
# create an instance of WhatsApp4Credentials from a JSON string
whats_app4_credentials_instance = WhatsApp4Credentials.from_json(json)
# print the JSON string representation of the object
print(WhatsApp4Credentials.to_json())

# convert the object into a dict
whats_app4_credentials_dict = whats_app4_credentials_instance.to_dict()
# create an instance of WhatsApp4Credentials from a dict
whats_app4_credentials_from_dict = WhatsApp4Credentials.from_dict(whats_app4_credentials_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


