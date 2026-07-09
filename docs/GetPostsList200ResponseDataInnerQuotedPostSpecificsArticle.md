# GetPostsList200ResponseDataInnerQuotedPostSpecificsArticle

An article that can be included as an insert in the post.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Unique identifier of the job posting. | 
**title** | **str** | Title of the article. | 
**author** | **str** | Author of the article. | [optional] 
**url** | **str** | Public url to the article. | [optional] 
**published_at** | **str** | The publication date of the article. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | [optional] 
**excerpt** | **str** | A short excerpt of the article content. | [optional] 
**picture_url** | **str** | Public url to the cover picture of the article. | [optional] 

## Example

```python
from unipile.models.get_posts_list200_response_data_inner_quoted_post_specifics_article import GetPostsList200ResponseDataInnerQuotedPostSpecificsArticle

# TODO update the JSON string below
json = "{}"
# create an instance of GetPostsList200ResponseDataInnerQuotedPostSpecificsArticle from a JSON string
get_posts_list200_response_data_inner_quoted_post_specifics_article_instance = GetPostsList200ResponseDataInnerQuotedPostSpecificsArticle.from_json(json)
# print the JSON string representation of the object
print(GetPostsList200ResponseDataInnerQuotedPostSpecificsArticle.to_json())

# convert the object into a dict
get_posts_list200_response_data_inner_quoted_post_specifics_article_dict = get_posts_list200_response_data_inner_quoted_post_specifics_article_instance.to_dict()
# create an instance of GetPostsList200ResponseDataInnerQuotedPostSpecificsArticle from a dict
get_posts_list200_response_data_inner_quoted_post_specifics_article_from_dict = GetPostsList200ResponseDataInnerQuotedPostSpecificsArticle.from_dict(get_posts_list200_response_data_inner_quoted_post_specifics_article_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


