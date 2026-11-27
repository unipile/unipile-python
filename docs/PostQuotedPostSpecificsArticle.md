# PostQuotedPostSpecificsArticle

An article that can be included as an insert in the post.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The text content of the message, when available. | 
**title** | **str** | Title of the article. | 
**author** | **str** | Author of the article. | [optional] 
**url** | **str** | Public url to the article. | [optional] 
**published_at** | **str** | The publication date of the article. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**excerpt** | **str** | A short excerpt of the article content. | [optional] 
**picture_url** | **str** | Public url to the cover picture of the article. | [optional] 

## Example

```python
from unipile.models.post_quoted_post_specifics_article import PostQuotedPostSpecificsArticle

# TODO update the JSON string below
json = "{}"
# create an instance of PostQuotedPostSpecificsArticle from a JSON string
post_quoted_post_specifics_article_instance = PostQuotedPostSpecificsArticle.from_json(json)
# print the JSON string representation of the object
print(PostQuotedPostSpecificsArticle.to_json())

# convert the object into a dict
post_quoted_post_specifics_article_dict = post_quoted_post_specifics_article_instance.to_dict()
# create an instance of PostQuotedPostSpecificsArticle from a dict
post_quoted_post_specifics_article_from_dict = PostQuotedPostSpecificsArticle.from_dict(post_quoted_post_specifics_article_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


