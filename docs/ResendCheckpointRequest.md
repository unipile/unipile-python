# ResendCheckpointRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**intent_id** | **str** | The ID of the intent for which a checkpoint must be resent. | 

## Example

```python
from unipile.models.resend_checkpoint_request import ResendCheckpointRequest

# TODO update the JSON string below
json = "{}"
# create an instance of ResendCheckpointRequest from a JSON string
resend_checkpoint_request_instance = ResendCheckpointRequest.from_json(json)
# print the JSON string representation of the object
print(ResendCheckpointRequest.to_json())

# convert the object into a dict
resend_checkpoint_request_dict = resend_checkpoint_request_instance.to_dict()
# create an instance of ResendCheckpointRequest from a dict
resend_checkpoint_request_from_dict = ResendCheckpointRequest.from_dict(resend_checkpoint_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


