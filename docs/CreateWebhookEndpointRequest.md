# CreateWebhookEndpointRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**trigger_events** | **List[str]** | The events that will trigger the webhook endpoint.       Refer to [Events Types](https://developer.unipile.com/v2.0/reference/event-types-1) to see the list of available values. | 
**account_ids** | **List[str]** | Restrict the webhook to specific accounts. Leave empty or omit the field to listen to events from every account in the application. | [optional] 
**url** | **str** | The HTTP or HTTPS URL to send the webhook payload to. | 
**description** | **str** | A description of the webhook endpoint. | [optional] 

## Example

```python
from unipile.models.create_webhook_endpoint_request import CreateWebhookEndpointRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CreateWebhookEndpointRequest from a JSON string
create_webhook_endpoint_request_instance = CreateWebhookEndpointRequest.from_json(json)
# print the JSON string representation of the object
print(CreateWebhookEndpointRequest.to_json())

# convert the object into a dict
create_webhook_endpoint_request_dict = create_webhook_endpoint_request_instance.to_dict()
# create an instance of CreateWebhookEndpointRequest from a dict
create_webhook_endpoint_request_from_dict = CreateWebhookEndpointRequest.from_dict(create_webhook_endpoint_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


