# PostQuotedPostSpecificsMentionsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**url** | **str** | Public URL targeted by the mention. | 
**start** | **float** | Start index of the mention in the post text. | 
**length** | **float** | Length of the mention in the post text. | 

## Example

```python
from unipile.models.post_quoted_post_specifics_mentions_inner import PostQuotedPostSpecificsMentionsInner

# TODO update the JSON string below
json = "{}"
# create an instance of PostQuotedPostSpecificsMentionsInner from a JSON string
post_quoted_post_specifics_mentions_inner_instance = PostQuotedPostSpecificsMentionsInner.from_json(json)
# print the JSON string representation of the object
print(PostQuotedPostSpecificsMentionsInner.to_json())

# convert the object into a dict
post_quoted_post_specifics_mentions_inner_dict = post_quoted_post_specifics_mentions_inner_instance.to_dict()
# create an instance of PostQuotedPostSpecificsMentionsInner from a dict
post_quoted_post_specifics_mentions_inner_from_dict = PostQuotedPostSpecificsMentionsInner.from_dict(post_quoted_post_specifics_mentions_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


