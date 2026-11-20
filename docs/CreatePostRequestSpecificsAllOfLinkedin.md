# CreatePostRequestSpecificsAllOfLinkedin

Specific options to apply if the provider of the targeted account is LinkedIn.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**document_title** | **str** | Display title of the document published with the post. Defaults to the attachment&#39;s file name when omitted. Only applies when a single document is attached. | [optional] 

## Example

```python
from unipile.models.create_post_request_specifics_all_of_linkedin import CreatePostRequestSpecificsAllOfLinkedin

# TODO update the JSON string below
json = "{}"
# create an instance of CreatePostRequestSpecificsAllOfLinkedin from a JSON string
create_post_request_specifics_all_of_linkedin_instance = CreatePostRequestSpecificsAllOfLinkedin.from_json(json)
# print the JSON string representation of the object
print(CreatePostRequestSpecificsAllOfLinkedin.to_json())

# convert the object into a dict
create_post_request_specifics_all_of_linkedin_dict = create_post_request_specifics_all_of_linkedin_instance.to_dict()
# create an instance of CreatePostRequestSpecificsAllOfLinkedin from a dict
create_post_request_specifics_all_of_linkedin_from_dict = CreatePostRequestSpecificsAllOfLinkedin.from_dict(create_post_request_specifics_all_of_linkedin_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


