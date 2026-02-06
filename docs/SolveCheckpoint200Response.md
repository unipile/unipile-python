# SolveCheckpoint200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**checkpoint** | [**CheckpointCheckpoint**](CheckpointCheckpoint.md) |  | 
**intent_id** | **str** | The ID of the auth intent. This should be used to listen for the QR Code scan with Solve Checkpoint. | 
**qrcode** | **str** | The QR Code to scan. | 
**url** | **str** | The URL to redirect to start the oauth flow of the provider. | 
**user_id** | **str** | The ID of the user that owns the account for the provider. | 
**name** | **str** | The name of the account. This is usually the display name or public identifier (phone number, email address, etc.) of the user that owns the account. | [optional] 
**created_at** | **str** | The date and time the account was linked with Unipile. | 
**id** | **str** | ID of the account. | 
**application_id** | **str** | ID of the parent application. | 
**status** | **str** | The current status of the account.     - &#x60;running&#x60; is Operational.     - &#x60;error&#x60; is Service Interuption.     - &#x60;disconnected&#x60; is Require Authentication..     - &#x60;paused&#x60; is Paused.     Learn more about [Status &amp; Lifecycle](https://developer.unipile.com/v2.0/docs/status-lifecycle). | 
**provider** | **str** | The provider&#39;s of the Account.     - &#x60;mock&#x60; is mock.     - &#x60;whatsapp&#x60; is WhatsApp.     - &#x60;linkedin&#x60; is LinkedIn.     - &#x60;instagram&#x60; is Instagram.     - &#x60;google&#x60; is Google.     - &#x60;outlook&#x60; is Outlook.     - &#x60;telegram&#x60; is Telegram.     - &#x60;imap&#x60; is IMAP. | 
**oauth_scope** | **str** | If the provider is OAuth, this is the scope of comma-separated permissions granted to the account. | [optional] 
**metadata** | **Dict[str, str]** | Metadata of the account. | [optional] 
**initial_sync** | [**AccountInitialSync**](AccountInitialSync.md) |  | [optional] 
**proxy** | [**AccountProxy**](AccountProxy.md) |  | [optional] 

## Example

```python
from unipile.models.solve_checkpoint200_response import SolveCheckpoint200Response

# TODO update the JSON string below
json = "{}"
# create an instance of SolveCheckpoint200Response from a JSON string
solve_checkpoint200_response_instance = SolveCheckpoint200Response.from_json(json)
# print the JSON string representation of the object
print(SolveCheckpoint200Response.to_json())

# convert the object into a dict
solve_checkpoint200_response_dict = solve_checkpoint200_response_instance.to_dict()
# create an instance of SolveCheckpoint200Response from a dict
solve_checkpoint200_response_from_dict = SolveCheckpoint200Response.from_dict(solve_checkpoint200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


