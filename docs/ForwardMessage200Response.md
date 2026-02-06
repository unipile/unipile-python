# ForwardMessage200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**message_id** | **str** | The ID of the message created in the destination chat. | 
**chat_id** | **str** | The ID of the Chat where the message was forwarded to. | 

## Example

```python
from unipile.models.forward_message200_response import ForwardMessage200Response

# TODO update the JSON string below
json = "{}"
# create an instance of ForwardMessage200Response from a JSON string
forward_message200_response_instance = ForwardMessage200Response.from_json(json)
# print the JSON string representation of the object
print(ForwardMessage200Response.to_json())

# convert the object into a dict
forward_message200_response_dict = forward_message200_response_instance.to_dict()
# create an instance of ForwardMessage200Response from a dict
forward_message200_response_from_dict = ForwardMessage200Response.from_dict(forward_message200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


