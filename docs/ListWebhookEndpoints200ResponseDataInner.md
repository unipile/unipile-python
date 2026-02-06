# ListWebhookEndpoints200ResponseDataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**enabled** | **bool** |  | 
**description** | **str** |  | 
**url** | **str** |  | 
**trigger_events** | **List[str]** |  | 
**secret** | **str** |  | 
**object** | **str** |  | 
**id** | **str** |  | 
**application_id** | **str** |  | 

## Example

```python
from unipile.models.list_webhook_endpoints200_response_data_inner import ListWebhookEndpoints200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of ListWebhookEndpoints200ResponseDataInner from a JSON string
list_webhook_endpoints200_response_data_inner_instance = ListWebhookEndpoints200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(ListWebhookEndpoints200ResponseDataInner.to_json())

# convert the object into a dict
list_webhook_endpoints200_response_data_inner_dict = list_webhook_endpoints200_response_data_inner_instance.to_dict()
# create an instance of ListWebhookEndpoints200ResponseDataInner from a dict
list_webhook_endpoints200_response_data_inner_from_dict = ListWebhookEndpoints200ResponseDataInner.from_dict(list_webhook_endpoints200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


