# UpdatePostCommentRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **str** | Updated textual content of the comment. User mentions can be added by inserting an @ followed by the &#x60;id&#x60; or &#x60;public_identifier&#x60; of the user (example: @JohnDoe). | 

## Example

```python
from unipile.models.update_post_comment_request import UpdatePostCommentRequest

# TODO update the JSON string below
json = "{}"
# create an instance of UpdatePostCommentRequest from a JSON string
update_post_comment_request_instance = UpdatePostCommentRequest.from_json(json)
# print the JSON string representation of the object
print(UpdatePostCommentRequest.to_json())

# convert the object into a dict
update_post_comment_request_dict = update_post_comment_request_instance.to_dict()
# create an instance of UpdatePostCommentRequest from a dict
update_post_comment_request_from_dict = UpdatePostCommentRequest.from_dict(update_post_comment_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


