# UniLogin

Complete authentication in the browser extension, then poll the connection using intent_id as the account identifier.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | Authentication must be completed through the browser extension. | 
**extension_code** | **str** | Temporary code to enter in the browser extension to authorize this connection. | 
**extension_code_expires_at** | **datetime** | Expiry of the extension code, in ISO 8601 format. | 
**expires_at** | **datetime** | Expiry of this connection attempt, in ISO 8601 format. | 
**extension_store_urls** | [**PasskeyHandoffExtensionStoreUrls**](PasskeyHandoffExtensionStoreUrls.md) |  | 
**extension_download_urls** | [**PasskeyHandoffExtensionDownloadUrls**](PasskeyHandoffExtensionDownloadUrls.md) |  | 

## Example

```python
from unipile.models.uni_login import UniLogin

# TODO update the JSON string below
json = "{}"
# create an instance of UniLogin from a JSON string
uni_login_instance = UniLogin.from_json(json)
# print the JSON string representation of the object
print(UniLogin.to_json())

# convert the object into a dict
uni_login_dict = uni_login_instance.to_dict()
# create an instance of UniLogin from a dict
uni_login_from_dict = UniLogin.from_dict(uni_login_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


