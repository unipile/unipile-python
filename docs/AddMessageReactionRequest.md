# AddMessageReactionRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**reaction** | **str** | The emoji unicode. | 

## Example

```python
from unipile.models.add_message_reaction_request import AddMessageReactionRequest

# TODO update the JSON string below
json = "{}"
# create an instance of AddMessageReactionRequest from a JSON string
add_message_reaction_request_instance = AddMessageReactionRequest.from_json(json)
# print the JSON string representation of the object
print(AddMessageReactionRequest.to_json())

# convert the object into a dict
add_message_reaction_request_dict = add_message_reaction_request_instance.to_dict()
# create an instance of AddMessageReactionRequest from a dict
add_message_reaction_request_from_dict = AddMessageReactionRequest.from_dict(add_message_reaction_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


