# PostSpecifics

Object containing provider-specific post data.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**mentions** | [**List[PostQuotedPostSpecificsMentionsInner]**](PostQuotedPostSpecificsMentionsInner.md) |  | [optional] 
**job_posting** | [**PostSpecificsJobPosting**](PostSpecificsJobPosting.md) |  | [optional] 
**article** | [**PostSpecificsArticle**](PostSpecificsArticle.md) |  | [optional] 

## Example

```python
from unipile.models.post_specifics import PostSpecifics

# TODO update the JSON string below
json = "{}"
# create an instance of PostSpecifics from a JSON string
post_specifics_instance = PostSpecifics.from_json(json)
# print the JSON string representation of the object
print(PostSpecifics.to_json())

# convert the object into a dict
post_specifics_dict = post_specifics_instance.to_dict()
# create an instance of PostSpecifics from a dict
post_specifics_from_dict = PostSpecifics.from_dict(post_specifics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


