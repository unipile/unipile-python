# ListWebhookEndpoints200ResponseDataInnerAccountTargetsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**account_name** | **str** |  | 
**account_provider** | **str** | The provider&#39;s of the Account.     - &#x60;mock&#x60; is mock.     - &#x60;whatsapp&#x60; is WhatsApp.     - &#x60;linkedin&#x60; is LinkedIn.     - &#x60;instagram&#x60; is Instagram.     - &#x60;google&#x60; is Google.     - &#x60;outlook&#x60; is Outlook.     - &#x60;telegram&#x60; is Telegram.     - &#x60;imap&#x60; is IMAP. | 
**object** | **str** |  | 
**id** | **str** |  | 
**status** | **str** |  | 

## Example

```python
from unipile.models.list_webhook_endpoints200_response_data_inner_account_targets_inner import ListWebhookEndpoints200ResponseDataInnerAccountTargetsInner

# TODO update the JSON string below
json = "{}"
# create an instance of ListWebhookEndpoints200ResponseDataInnerAccountTargetsInner from a JSON string
list_webhook_endpoints200_response_data_inner_account_targets_inner_instance = ListWebhookEndpoints200ResponseDataInnerAccountTargetsInner.from_json(json)
# print the JSON string representation of the object
print(ListWebhookEndpoints200ResponseDataInnerAccountTargetsInner.to_json())

# convert the object into a dict
list_webhook_endpoints200_response_data_inner_account_targets_inner_dict = list_webhook_endpoints200_response_data_inner_account_targets_inner_instance.to_dict()
# create an instance of ListWebhookEndpoints200ResponseDataInnerAccountTargetsInner from a dict
list_webhook_endpoints200_response_data_inner_account_targets_inner_from_dict = ListWebhookEndpoints200ResponseDataInnerAccountTargetsInner.from_dict(list_webhook_endpoints200_response_data_inner_account_targets_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


