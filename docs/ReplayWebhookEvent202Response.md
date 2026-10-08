# ReplayWebhookEvent202Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**event_id** | **str** |  | 
**endpoint_ids** | **List[str]** |  | 

## Example

```python
from unipile.models.replay_webhook_event202_response import ReplayWebhookEvent202Response

# TODO update the JSON string below
json = "{}"
# create an instance of ReplayWebhookEvent202Response from a JSON string
replay_webhook_event202_response_instance = ReplayWebhookEvent202Response.from_json(json)
# print the JSON string representation of the object
print(ReplayWebhookEvent202Response.to_json())

# convert the object into a dict
replay_webhook_event202_response_dict = replay_webhook_event202_response_instance.to_dict()
# create an instance of ReplayWebhookEvent202Response from a dict
replay_webhook_event202_response_from_dict = ReplayWebhookEvent202Response.from_dict(replay_webhook_event202_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


