# CreateGroupPostRequest

The post to publish in the social group.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **str** | Textual content of the post. User mentions can be added by inserting an @ followed by the ID or public identifier of the user (example: @JohnDoe). | 
**attachments** | [**List[UpdateChatRequestPicture]**](UpdateChatRequestPicture.md) | The list of files to appear in the post. | [optional] 

## Example

```python
from unipile.models.create_group_post_request import CreateGroupPostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CreateGroupPostRequest from a JSON string
create_group_post_request_instance = CreateGroupPostRequest.from_json(json)
# print the JSON string representation of the object
print(CreateGroupPostRequest.to_json())

# convert the object into a dict
create_group_post_request_dict = create_group_post_request_instance.to_dict()
# create an instance of CreateGroupPostRequest from a dict
create_group_post_request_from_dict = CreateGroupPostRequest.from_dict(create_group_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


