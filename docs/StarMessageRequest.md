# StarMessageRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**star_status** | **bool** | If supported, set to &#x60;true&#x60; to mark the message as starred (favorite), or &#x60;false&#x60; to unmark it.         The message can be one of the account&#39;s own or one received from another participant.         This state is private to the account and is not visible to the other participants of the chat. | 

## Example

```python
from unipile.models.star_message_request import StarMessageRequest

# TODO update the JSON string below
json = "{}"
# create an instance of StarMessageRequest from a JSON string
star_message_request_instance = StarMessageRequest.from_json(json)
# print the JSON string representation of the object
print(StarMessageRequest.to_json())

# convert the object into a dict
star_message_request_dict = star_message_request_instance.to_dict()
# create an instance of StarMessageRequest from a dict
star_message_request_from_dict = StarMessageRequest.from_dict(star_message_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


