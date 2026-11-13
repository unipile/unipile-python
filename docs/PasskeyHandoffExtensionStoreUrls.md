# PasskeyHandoffExtensionStoreUrls

Official extension store links.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chrome** | **str** | Chrome extension store URL. | [optional] 
**edge** | **str** | Edge extension store URL. | [optional] 
**firefox** | **str** | Firefox extension store URL. | [optional] 
**safari** | **str** | Safari extension store URL. | [optional] 

## Example

```python
from unipile.models.passkey_handoff_extension_store_urls import PasskeyHandoffExtensionStoreUrls

# TODO update the JSON string below
json = "{}"
# create an instance of PasskeyHandoffExtensionStoreUrls from a JSON string
passkey_handoff_extension_store_urls_instance = PasskeyHandoffExtensionStoreUrls.from_json(json)
# print the JSON string representation of the object
print(PasskeyHandoffExtensionStoreUrls.to_json())

# convert the object into a dict
passkey_handoff_extension_store_urls_dict = passkey_handoff_extension_store_urls_instance.to_dict()
# create an instance of PasskeyHandoffExtensionStoreUrls from a dict
passkey_handoff_extension_store_urls_from_dict = PasskeyHandoffExtensionStoreUrls.from_dict(passkey_handoff_extension_store_urls_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


