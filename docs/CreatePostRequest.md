# CreatePostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **str** | Textual content of the post. User mentions can be added by inserting an @ followed by the ID or public identifier of the user (example: @JohnDoe). | 
**attachments** | [**List[SendEmailRequestAttachmentsInner]**](SendEmailRequestAttachmentsInner.md) | The list of files to appear in the post. | [optional] 
**can_read** | **str** | The visibility level for the new post (if supported by the provider).           - &#x60;anyone&#x60; is visible to anyone.           - &#x60;relations_only&#x60; is visible only to the user&#39;s relations. | [optional] [default to 'anyone']
**can_comment** | **str** | The comment control level for the new post (if supported by the provider).           - &#x60;anyone&#x60; anyone can comment.           - &#x60;relations_only&#x60; only to the user&#39;s relations can comment.           - &#x60;no_one&#x60; no one can comment. | [optional] [default to 'anyone']
**quoted_post_id** | **str** | The ID of a Post to be quoted. For a simple repost without commentary, leave &#x60;text&#x60; as an empty string. | [optional] 
**post_as** | **str** | The ID of the User on whose behalf the post should be published (if supported by the provider). | [optional] 
**specifics** | [**CreatePostRequestSpecifics**](CreatePostRequestSpecifics.md) |  | 

## Example

```python
from unipile.models.create_post_request import CreatePostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CreatePostRequest from a JSON string
create_post_request_instance = CreatePostRequest.from_json(json)
# print the JSON string representation of the object
print(CreatePostRequest.to_json())

# convert the object into a dict
create_post_request_dict = create_post_request_instance.to_dict()
# create an instance of CreatePostRequest from a dict
create_post_request_from_dict = CreatePostRequest.from_dict(create_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


