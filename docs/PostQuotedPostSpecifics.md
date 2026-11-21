# PostQuotedPostSpecifics

Object containing provider-specific post data.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**mentions** | [**List[PostQuotedPostSpecificsMentionsInner]**](PostQuotedPostSpecificsMentionsInner.md) |  | [optional] 
**job_posting** | [**PostQuotedPostSpecificsJobPosting**](PostQuotedPostSpecificsJobPosting.md) |  | [optional] 
**article** | [**PostQuotedPostSpecificsArticle**](PostQuotedPostSpecificsArticle.md) |  | [optional] 

## Example

```python
from unipile.models.post_quoted_post_specifics import PostQuotedPostSpecifics

# TODO update the JSON string below
json = "{}"
# create an instance of PostQuotedPostSpecifics from a JSON string
post_quoted_post_specifics_instance = PostQuotedPostSpecifics.from_json(json)
# print the JSON string representation of the object
print(PostQuotedPostSpecifics.to_json())

# convert the object into a dict
post_quoted_post_specifics_dict = post_quoted_post_specifics_instance.to_dict()
# create an instance of PostQuotedPostSpecifics from a dict
post_quoted_post_specifics_from_dict = PostQuotedPostSpecifics.from_dict(post_quoted_post_specifics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


