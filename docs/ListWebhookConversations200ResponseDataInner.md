# ListWebhookConversations200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**first_attempt** | **bool** | Whether this delivery was the first attempt to send the webhook. &#x60;false&#x60; indicates a retry. | 
**event_type** | **str** | The type of the event that was delivered. | 
**created_at** | **str** | The date and time at which the delivery attempt was made, in ISO 8601 format. | 
**http_status** | **int** | The HTTP status code returned by the endpoint. | 
**endpoint_url** | **str** | The URL the webhook was delivered to. | 
**response_body** | **str** | The text content of the message, when available. | 
**latency_ms** | **int** | The time between the event occurrence and this delivery attempt, in milliseconds. | 
**response_time_ms** | **int** | The time between the event occurrence and this delivery attempt, in milliseconds. | 
**object** | **str** | The type of the returned object. | 
**id** | **str** | Unique identifier of the webhook conversation. | 
**endpoint_id** | **str** | Unique identifier of the webhook endpoint the event was delivered to. | 
**event_id** | **str** | Unique identifier of the event that was delivered. | 

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


