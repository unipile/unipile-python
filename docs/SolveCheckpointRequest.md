# SolveCheckpointRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**code** | **str** | The code to solve the checkpoint. Check the AuthenticationCheckpoint response you have already obtained to see what type of code is expected. | 
**intent_id** | **str** | The ID of the intent to solve. | 

## Example

```python
from unipile.models.solve_checkpoint_request import SolveCheckpointRequest

# TODO update the JSON string below
json = "{}"
# create an instance of SolveCheckpointRequest from a JSON string
solve_checkpoint_request_instance = SolveCheckpointRequest.from_json(json)
# print the JSON string representation of the object
print(SolveCheckpointRequest.to_json())

# convert the object into a dict
solve_checkpoint_request_dict = solve_checkpoint_request_instance.to_dict()
# create an instance of SolveCheckpointRequest from a dict
solve_checkpoint_request_from_dict = SolveCheckpointRequest.from_dict(solve_checkpoint_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


