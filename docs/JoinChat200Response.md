# JoinChat200Response

The result of the request to join the chat.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the object: &#x60;ChatJoined&#x60;. | 
**membership_status** | **str** | Whether the account joined the chat (&#x60;member&#x60;) or is waiting for an admin to approve the request (&#x60;pending&#x60;). | 
**chat_id** | **str** | The Messaging API ID of the chat, when membership is confirmed. | [optional] 

## Example

```python
from unipile.models.join_chat200_response import JoinChat200Response

# TODO update the JSON string below
json = "{}"
# create an instance of JoinChat200Response from a JSON string
join_chat200_response_instance = JoinChat200Response.from_json(json)
# print the JSON string representation of the object
print(JoinChat200Response.to_json())

# convert the object into a dict
join_chat200_response_dict = join_chat200_response_instance.to_dict()
# create an instance of JoinChat200Response from a dict
join_chat200_response_from_dict = JoinChat200Response.from_dict(join_chat200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


