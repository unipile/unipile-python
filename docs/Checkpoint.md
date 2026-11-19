# Checkpoint

Authentication requires another step or has stopped and cannot continue.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**checkpoint** | [**CheckpointCheckpoint**](CheckpointCheckpoint.md) |  | 
**intent_id** | **str** | The ID of the authentication intent. Use it for the next step required by the checkpoint. For PROCESS_STOPPED, it only identifies the stopped attempt and must not be used to resume or resolve it. | 

## Example

```python
from unipile.models.checkpoint import Checkpoint

# TODO update the JSON string below
json = "{}"
# create an instance of Checkpoint from a JSON string
checkpoint_instance = Checkpoint.from_json(json)
# print the JSON string representation of the object
print(Checkpoint.to_json())

# convert the object into a dict
checkpoint_dict = checkpoint_instance.to_dict()
# create an instance of Checkpoint from a dict
checkpoint_from_dict = Checkpoint.from_dict(checkpoint_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


