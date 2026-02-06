# AddPostCommentRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **str** | Textual content of the comment. User mentions can be added by inserting an @ followed by the &#x60;id&#x60; or &#x60;public_identifier&#x60; of the user (example: @JohnDoe). | 
**comment_as** | **str** | The ID of the User on whose behalf the comment should be published (if supported by the provider). | [optional] 

## Example

```python
from unipile.models.add_post_comment_request import AddPostCommentRequest

# TODO update the JSON string below
json = "{}"
# create an instance of AddPostCommentRequest from a JSON string
add_post_comment_request_instance = AddPostCommentRequest.from_json(json)
# print the JSON string representation of the object
print(AddPostCommentRequest.to_json())

# convert the object into a dict
add_post_comment_request_dict = add_post_comment_request_instance.to_dict()
# create an instance of AddPostCommentRequest from a dict
add_post_comment_request_from_dict = AddPostCommentRequest.from_dict(add_post_comment_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


