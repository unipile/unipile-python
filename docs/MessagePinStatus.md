# MessagePinStatus


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**message_id** | **str** | ID of the message that was pinned or unpinned. | [optional] 
**is_pin** | **bool** | Indicates whether the message is pinned (true) or unpinned (false). | 
**duration** | **float** | Duration for which the message remains pinned, if applicable. | [optional] 

## Example

```python
from unipile.models.message_pin_status import MessagePinStatus

# TODO update the JSON string below
json = "{}"
# create an instance of MessagePinStatus from a JSON string
message_pin_status_instance = MessagePinStatus.from_json(json)
# print the JSON string representation of the object
print(MessagePinStatus.to_json())

# convert the object into a dict
message_pin_status_dict = message_pin_status_instance.to_dict()
# create an instance of MessagePinStatus from a dict
message_pin_status_from_dict = MessagePinStatus.from_dict(message_pin_status_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


