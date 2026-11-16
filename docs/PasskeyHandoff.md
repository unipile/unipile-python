# PasskeyHandoff

Install or update UniLogin, then authorize this browser verification. No provider session is exported.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**request_id** | **str** | Identifier used by the extension bridge. | 
**handoff_token** | **str** | Short-lived capability for this verification; pass only to the trusted extension bridge. | 
**extension_code** | **str** | Code to enter in UniLogin when automatic extension detection is unavailable. | 
**expires_at** | **str** | Expiry of the extension handoff, in ISO 8601 format. | 
**extension_bridge_url** | **str** | Trusted UniLogin bridge URL for this attempt. | 
**extension_store_urls** | [**PasskeyHandoffExtensionStoreUrls**](PasskeyHandoffExtensionStoreUrls.md) |  | 
**extension_download_urls** | [**PasskeyHandoffExtensionDownloadUrls**](PasskeyHandoffExtensionDownloadUrls.md) |  | 

## Example

```python
from unipile.models.passkey_handoff import PasskeyHandoff

# TODO update the JSON string below
json = "{}"
# create an instance of PasskeyHandoff from a JSON string
passkey_handoff_instance = PasskeyHandoff.from_json(json)
# print the JSON string representation of the object
print(PasskeyHandoff.to_json())

# convert the object into a dict
passkey_handoff_dict = passkey_handoff_instance.to_dict()
# create an instance of PasskeyHandoff from a dict
passkey_handoff_from_dict = PasskeyHandoff.from_dict(passkey_handoff_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


