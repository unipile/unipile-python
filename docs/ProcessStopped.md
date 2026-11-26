# ProcessStopped

A terminal outcome for the current authentication attempt. No checkpoint resolution is expected: stop polling and do not call Solve Checkpoint, Request Checkpoint or Resend Checkpoint for this attempt. Use message, description and link to inform the account owner. To retry authentication, start a new authentication attempt rather than continuing the existing intent.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | The current authentication attempt has stopped and cannot be continued or resolved. | 
**message** | **str** | The reason why the authentication attempt cannot continue. | 
**description** | **str** | Additional context or instructions for the account owner, supplementing the main message. | [optional] 
**link** | [**ProcessStoppedLink**](ProcessStoppedLink.md) |  | [optional] 

## Example

```python
from unipile.models.process_stopped import ProcessStopped

# TODO update the JSON string below
json = "{}"
# create an instance of ProcessStopped from a JSON string
process_stopped_instance = ProcessStopped.from_json(json)
# print the JSON string representation of the object
print(ProcessStopped.to_json())

# convert the object into a dict
process_stopped_dict = process_stopped_instance.to_dict()
# create an instance of ProcessStopped from a dict
process_stopped_from_dict = ProcessStopped.from_dict(process_stopped_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


