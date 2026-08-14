# GetPostsList200ResponseDataInnerQuotedPostSpecifics

Object containing provider-specific post data.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**job_posting** | [**GetPostsList200ResponseDataInnerQuotedPostSpecificsJobPosting**](GetPostsList200ResponseDataInnerQuotedPostSpecificsJobPosting.md) |  | [optional] 
**article** | [**GetPostsList200ResponseDataInnerQuotedPostSpecificsArticle**](GetPostsList200ResponseDataInnerQuotedPostSpecificsArticle.md) |  | [optional] 

## Example

```python
from unipile.models.get_posts_list200_response_data_inner_quoted_post_specifics import GetPostsList200ResponseDataInnerQuotedPostSpecifics

# TODO update the JSON string below
json = "{}"
# create an instance of GetPostsList200ResponseDataInnerQuotedPostSpecifics from a JSON string
get_posts_list200_response_data_inner_quoted_post_specifics_instance = GetPostsList200ResponseDataInnerQuotedPostSpecifics.from_json(json)
# print the JSON string representation of the object
print(GetPostsList200ResponseDataInnerQuotedPostSpecifics.to_json())

# convert the object into a dict
get_posts_list200_response_data_inner_quoted_post_specifics_dict = get_posts_list200_response_data_inner_quoted_post_specifics_instance.to_dict()
# create an instance of GetPostsList200ResponseDataInnerQuotedPostSpecifics from a dict
get_posts_list200_response_data_inner_quoted_post_specifics_from_dict = GetPostsList200ResponseDataInnerQuotedPostSpecifics.from_dict(get_posts_list200_response_data_inner_quoted_post_specifics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


