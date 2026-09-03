# LinkedInClassicSharedContent

A specific content to be shared in the current message.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | The type of content. | 
**id** | **str** | The ID of the content to be shared. | 

## Example

```python
from unipile.models.linked_in_classic_shared_content import LinkedInClassicSharedContent

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedInClassicSharedContent from a JSON string
linked_in_classic_shared_content_instance = LinkedInClassicSharedContent.from_json(json)
# print the JSON string representation of the object
print(LinkedInClassicSharedContent.to_json())

# convert the object into a dict
linked_in_classic_shared_content_dict = linked_in_classic_shared_content_instance.to_dict()
# create an instance of LinkedInClassicSharedContent from a dict
linked_in_classic_shared_content_from_dict = LinkedInClassicSharedContent.from_dict(linked_in_classic_shared_content_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


