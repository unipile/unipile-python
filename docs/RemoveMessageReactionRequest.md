# RemoveMessageReactionRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**reaction** | **str** | The emoji unicode to be removed. | 

## Example

```python
from unipile.models.remove_message_reaction_request import RemoveMessageReactionRequest

# TODO update the JSON string below
json = "{}"
# create an instance of RemoveMessageReactionRequest from a JSON string
remove_message_reaction_request_instance = RemoveMessageReactionRequest.from_json(json)
# print the JSON string representation of the object
print(RemoveMessageReactionRequest.to_json())

# convert the object into a dict
remove_message_reaction_request_dict = remove_message_reaction_request_instance.to_dict()
# create an instance of RemoveMessageReactionRequest from a dict
remove_message_reaction_request_from_dict = RemoveMessageReactionRequest.from_dict(remove_message_reaction_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


