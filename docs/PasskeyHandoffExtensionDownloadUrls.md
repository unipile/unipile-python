# PasskeyHandoffExtensionDownloadUrls

Official extension download links, for browsers without a store listing.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**edge** | **str** | Edge extension download URL. | [optional] 
**safari** | **str** | Safari extension download URL. | [optional] 

## Example

```python
from unipile.models.passkey_handoff_extension_download_urls import PasskeyHandoffExtensionDownloadUrls

# TODO update the JSON string below
json = "{}"
# create an instance of PasskeyHandoffExtensionDownloadUrls from a JSON string
passkey_handoff_extension_download_urls_instance = PasskeyHandoffExtensionDownloadUrls.from_json(json)
# print the JSON string representation of the object
print(PasskeyHandoffExtensionDownloadUrls.to_json())

# convert the object into a dict
passkey_handoff_extension_download_urls_dict = passkey_handoff_extension_download_urls_instance.to_dict()
# create an instance of PasskeyHandoffExtensionDownloadUrls from a dict
passkey_handoff_extension_download_urls_from_dict = PasskeyHandoffExtensionDownloadUrls.from_dict(passkey_handoff_extension_download_urls_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


