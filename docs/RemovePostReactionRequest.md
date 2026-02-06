# RemovePostReactionRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**reaction** | [**RemovePostReactionRequestReaction**](RemovePostReactionRequestReaction.md) |  | 

## Example

```python
from unipile.models.remove_post_reaction_request import RemovePostReactionRequest

# TODO update the JSON string below
json = "{}"
# create an instance of RemovePostReactionRequest from a JSON string
remove_post_reaction_request_instance = RemovePostReactionRequest.from_json(json)
# print the JSON string representation of the object
print(RemovePostReactionRequest.to_json())

# convert the object into a dict
remove_post_reaction_request_dict = remove_post_reaction_request_instance.to_dict()
# create an instance of RemovePostReactionRequest from a dict
remove_post_reaction_request_from_dict = RemovePostReactionRequest.from_dict(remove_post_reaction_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


