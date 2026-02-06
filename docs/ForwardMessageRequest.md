# ForwardMessageRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**chat_id** | **str** | The ID of the Chat to forward the message to. | 
**text** | **str** | Text to be attached to the forwarded message. | [optional] 

## Example

```python
from unipile.models.forward_message_request import ForwardMessageRequest

# TODO update the JSON string below
json = "{}"
# create an instance of ForwardMessageRequest from a JSON string
forward_message_request_instance = ForwardMessageRequest.from_json(json)
# print the JSON string representation of the object
print(ForwardMessageRequest.to_json())

# convert the object into a dict
forward_message_request_dict = forward_message_request_instance.to_dict()
# create an instance of ForwardMessageRequest from a dict
forward_message_request_from_dict = ForwardMessageRequest.from_dict(forward_message_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


