# ListWebhookConversations200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**first_attempt** | **bool** |  | 
**event_type** | **str** |  | 
**created_at** | **str** | The ID of the Company. | 
**http_status** | **int** |  | 
**endpoint_url** | **str** | The ID of the Company. | 
**response_body** | **str** | The ID of the Company. | 
**object** | **str** |  | 
**id** | **str** |  | 
**endpoint_id** | **str** |  | 
**event_id** | **str** |  | 

## Example

```python
from unipile.models.list_webhook_conversations200_response_data_inner import ListWebhookConversations200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of ListWebhookConversations200ResponseDataInner from a JSON string
list_webhook_conversations200_response_data_inner_instance = ListWebhookConversations200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(ListWebhookConversations200ResponseDataInner.to_json())

# convert the object into a dict
list_webhook_conversations200_response_data_inner_dict = list_webhook_conversations200_response_data_inner_instance.to_dict()
# create an instance of ListWebhookConversations200ResponseDataInner from a dict
list_webhook_conversations200_response_data_inner_from_dict = ListWebhookConversations200ResponseDataInner.from_dict(list_webhook_conversations200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


