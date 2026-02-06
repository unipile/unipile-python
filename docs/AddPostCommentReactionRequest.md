# AddPostCommentReactionRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**reaction** | [**AddPostCommentReactionRequestReaction**](AddPostCommentReactionRequestReaction.md) |  | 
**react_as** | **str** | The ID of the User on whose behalf the reaction should be published (if supported by the provider). | [optional] 

## Example

```python
from unipile.models.add_post_comment_reaction_request import AddPostCommentReactionRequest

# TODO update the JSON string below
json = "{}"
# create an instance of AddPostCommentReactionRequest from a JSON string
add_post_comment_reaction_request_instance = AddPostCommentReactionRequest.from_json(json)
# print the JSON string representation of the object
print(AddPostCommentReactionRequest.to_json())

# convert the object into a dict
add_post_comment_reaction_request_dict = add_post_comment_reaction_request_instance.to_dict()
# create an instance of AddPostCommentReactionRequest from a dict
add_post_comment_reaction_request_from_dict = AddPostCommentReactionRequest.from_dict(add_post_comment_reaction_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


