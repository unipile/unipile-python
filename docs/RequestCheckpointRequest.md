# RequestCheckpointRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**intent_id** | **str** | The ID of the intent for which a checkpoint must be requested. | 

## Example

```python
from unipile.models.request_checkpoint_request import RequestCheckpointRequest

# TODO update the JSON string below
json = "{}"
# create an instance of RequestCheckpointRequest from a JSON string
request_checkpoint_request_instance = RequestCheckpointRequest.from_json(json)
# print the JSON string representation of the object
print(RequestCheckpointRequest.to_json())

# convert the object into a dict
request_checkpoint_request_dict = request_checkpoint_request_instance.to_dict()
# create an instance of RequestCheckpointRequest from a dict
request_checkpoint_request_from_dict = RequestCheckpointRequest.from_dict(request_checkpoint_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


