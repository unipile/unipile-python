# StartAuthIntent200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**checkpoint** | [**StartAuthIntent200ResponseAnyOf1Checkpoint**](StartAuthIntent200ResponseAnyOf1Checkpoint.md) |  | 
**intent_id** | **str** |  | 
**qrcode** | **str** | The QR Code to scan. | 
**url** | **str** | The URL to redirect to start the oauth flow of the provider. | 
**user_id** | **str** | The ID of the user that owns the account for the provider. | 
**name** | **str** | The name of the account. This is usually the display name or public identifier (phone number, email address, etc.) of the user that owns the account. | [optional] 
**created_at** | **str** | The date and time the account was linked with Unipile. | 
**id** | **str** | ID of the account. | 
**application_id** | **str** | ID of the parent application. | 
**account_scope_id** | **str** | ID of the Scope assigned to the Account. Once assigned, the Scope cannot be removed or replaced. | [optional] 
**status** | **str** | The current status of the account.     - &#x60;running&#x60; is Operational.     - &#x60;errored&#x60; is Service Interuption.     - &#x60;disconnected&#x60; requires authentication.     - &#x60;degraded&#x60; means at least one product is running while another is errored; inspect &#x60;metadata.products_connection_status&#x60;.     - &#x60;partial&#x60; means at least one product is running while another requires authentication; inspect &#x60;metadata.products_connection_status&#x60;.     Learn more about [Status &amp; Lifecycle](https://developer.unipile.com/v2.0/docs/status-lifecycle). | 
**is_locked** | **bool** | Whether API access to the account is locked. | 
**provider** | **str** | The provider&#39;s of the Account.     - &#x60;mock&#x60; is mock.     - &#x60;whatsapp&#x60; is WhatsApp.     - &#x60;linkedin&#x60; is LinkedIn.     - &#x60;instagram&#x60; is Instagram.     - &#x60;facebook&#x60; is Facebook.     - &#x60;google&#x60; is Google.     - &#x60;outlook&#x60; is Outlook.     - &#x60;telegram&#x60; is Telegram.     - &#x60;imap&#x60; is IMAP. | 
**oauth_scope** | **str** | If the provider is OAuth, this is the scope of comma-separated permissions granted to the account. | [optional] 
**metadata** | [**Account1Metadata**](Account1Metadata.md) |  | 
**initial_sync** | [**AccountInitialSync**](AccountInitialSync.md) |  | [optional] 
**proxy** | [**Account1Proxy**](Account1Proxy.md) |  | [optional] 
**account_id** | **str** |  | 

## Example

```python
from unipile.models.start_auth_intent200_response import StartAuthIntent200Response

# TODO update the JSON string below
json = "{}"
# create an instance of StartAuthIntent200Response from a JSON string
start_auth_intent200_response_instance = StartAuthIntent200Response.from_json(json)
# print the JSON string representation of the object
print(StartAuthIntent200Response.to_json())

# convert the object into a dict
start_auth_intent200_response_dict = start_auth_intent200_response_instance.to_dict()
# create an instance of StartAuthIntent200Response from a dict
start_auth_intent200_response_from_dict = StartAuthIntent200Response.from_dict(start_auth_intent200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


