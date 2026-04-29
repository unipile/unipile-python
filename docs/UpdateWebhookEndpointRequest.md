# UpdateWebhookEndpointRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**trigger_events** | **List[str]** | The events that will trigger the webhook endpoint.           Refer to [Events Types](https://developer.unipile.com/v2.0/reference/event-types-1) to see the list of available values. | [optional] 
**account_ids** | **List[str]** | Restrict the webhook to specific accounts. Leave empty or omit the field to listen to events from every account in the application. | [optional] 
**url** | **str** | The URL to send the webhook payload to. | [optional] 
**description** | **str** | A description of the webhook endpoint. | [optional] 
**enabled** | **bool** | Whether the webhook endpoint is enabled. | [optional] 

## Example

```python
from unipile.models.update_webhook_endpoint_request import UpdateWebhookEndpointRequest

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateWebhookEndpointRequest from a JSON string
update_webhook_endpoint_request_instance = UpdateWebhookEndpointRequest.from_json(json)
# print the JSON string representation of the object
print(UpdateWebhookEndpointRequest.to_json())

# convert the object into a dict
update_webhook_endpoint_request_dict = update_webhook_endpoint_request_instance.to_dict()
# create an instance of UpdateWebhookEndpointRequest from a dict
update_webhook_endpoint_request_from_dict = UpdateWebhookEndpointRequest.from_dict(update_webhook_endpoint_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


