# SolveCheckpointRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**code** | **str** | The code to solve the checkpoint. Check the AuthenticationCheckpoint response you have already obtained to see what type of code is expected. | 
**credential** | **str** | The secret that goes with the chosen option, when the checkpoint asks for one. On ENCRYPTED_HISTORY, &#x60;code&#x60; names the option and this carries the PIN or the recovery code; it is left out when the option needs no secret. | [optional] 
**intent_id** | **str** | The ID of the intent for which a checkpoint must be solved. | 

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


