# CreateWebhookEndpoint200ResponseAccountTargetsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**account_name** | **str** |  | 
**account_provider** | **str** | The provider&#39;s of the Account.     - &#x60;mock&#x60; is mock.     - &#x60;whatsapp&#x60; is WhatsApp.     - &#x60;linkedin&#x60; is LinkedIn.     - &#x60;instagram&#x60; is Instagram.     - &#x60;facebook&#x60; is Facebook.     - &#x60;google&#x60; is Google.     - &#x60;outlook&#x60; is Outlook.     - &#x60;telegram&#x60; is Telegram.     - &#x60;imap&#x60; is IMAP. | 
**object** | **str** |  | 
**id** | **str** |  | 
**status** | **str** |  | 

## Example

```python
from unipile.models.create_webhook_endpoint200_response_account_targets_inner import CreateWebhookEndpoint200ResponseAccountTargetsInner

# TODO update the JSON string below
json = "{}"
# create an instance of CreateWebhookEndpoint200ResponseAccountTargetsInner from a JSON string
create_webhook_endpoint200_response_account_targets_inner_instance = CreateWebhookEndpoint200ResponseAccountTargetsInner.from_json(json)
# print the JSON string representation of the object
print(CreateWebhookEndpoint200ResponseAccountTargetsInner.to_json())

# convert the object into a dict
create_webhook_endpoint200_response_account_targets_inner_dict = create_webhook_endpoint200_response_account_targets_inner_instance.to_dict()
# create an instance of CreateWebhookEndpoint200ResponseAccountTargetsInner from a dict
create_webhook_endpoint200_response_account_targets_inner_from_dict = CreateWebhookEndpoint200ResponseAccountTargetsInner.from_dict(create_webhook_endpoint200_response_account_targets_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


