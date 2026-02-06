# ListWebhookEndpoints200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**data** | [**List[ListWebhookEndpoints200ResponseDataInner]**](ListWebhookEndpoints200ResponseDataInner.md) |  | 
**has_more** | **bool** |  | 

## Example

```python
from unipile.models.list_webhook_endpoints200_response import ListWebhookEndpoints200Response

# TODO update the JSON string below
json = "{}"
# create an instance of ListWebhookEndpoints200Response from a JSON string
list_webhook_endpoints200_response_instance = ListWebhookEndpoints200Response.from_json(json)
# print the JSON string representation of the object
print(ListWebhookEndpoints200Response.to_json())

# convert the object into a dict
list_webhook_endpoints200_response_dict = list_webhook_endpoints200_response_instance.to_dict()
# create an instance of ListWebhookEndpoints200Response from a dict
list_webhook_endpoints200_response_from_dict = ListWebhookEndpoints200Response.from_dict(list_webhook_endpoints200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


