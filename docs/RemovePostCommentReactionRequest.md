# RemovePostCommentReactionRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**reaction** | [**RemovePostCommentReactionRequestReaction**](RemovePostCommentReactionRequestReaction.md) |  | 
**react_as** | **str** | The ID of the User on whose behalf the reaction was published and should be removed (if supported by the provider). | [optional] 

## Example

```python
from unipile.models.remove_post_comment_reaction_request import RemovePostCommentReactionRequest

# TODO update the JSON string below
json = "{}"
# create an instance of RemovePostCommentReactionRequest from a JSON string
remove_post_comment_reaction_request_instance = RemovePostCommentReactionRequest.from_json(json)
# print the JSON string representation of the object
print(RemovePostCommentReactionRequest.to_json())

# convert the object into a dict
remove_post_comment_reaction_request_dict = remove_post_comment_reaction_request_instance.to_dict()
# create an instance of RemovePostCommentReactionRequest from a dict
remove_post_comment_reaction_request_from_dict = RemovePostCommentReactionRequest.from_dict(remove_post_comment_reaction_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


