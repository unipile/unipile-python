# UpdatePostRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**text** | **str** | Textual content of the post. User mentions can be added by inserting an @ followed by the ID or public identifier of the user (example: @JohnDoe). | [optional] 
**can_comment** | **str** | The comment control level for the new post (if supported by the provider).           - &#x60;anyone&#x60; is visible to anyone.           - &#x60;relations_only&#x60; is visible only to the user&#39;s relations.           - &#x60;no_one&#x60; is visible to no one. | [optional] [default to 'anyone']

## Example

```python
from unipile.models.update_post_request import UpdatePostRequest

# TODO update the JSON string below
json = "{}"
# create an instance of UpdatePostRequest from a JSON string
update_post_request_instance = UpdatePostRequest.from_json(json)
# print the JSON string representation of the object
print(UpdatePostRequest.to_json())

# convert the object into a dict
update_post_request_dict = update_post_request_instance.to_dict()
# create an instance of UpdatePostRequest from a dict
update_post_request_from_dict = UpdatePostRequest.from_dict(update_post_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


