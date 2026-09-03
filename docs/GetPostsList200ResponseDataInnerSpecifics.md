# GetPostsList200ResponseDataInnerSpecifics

Object containing provider-specific post data.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**mentions** | [**List[GetPostsList200ResponseDataInnerQuotedPostSpecificsMentionsInner]**](GetPostsList200ResponseDataInnerQuotedPostSpecificsMentionsInner.md) |  | [optional] 
**job_posting** | [**GetPostsList200ResponseDataInnerSpecificsJobPosting**](GetPostsList200ResponseDataInnerSpecificsJobPosting.md) |  | [optional] 
**article** | [**GetPostsList200ResponseDataInnerSpecificsArticle**](GetPostsList200ResponseDataInnerSpecificsArticle.md) |  | [optional] 

## Example

```python
from unipile.models.get_posts_list200_response_data_inner_specifics import GetPostsList200ResponseDataInnerSpecifics

# TODO update the JSON string below
json = "{}"
# create an instance of GetPostsList200ResponseDataInnerSpecifics from a JSON string
get_posts_list200_response_data_inner_specifics_instance = GetPostsList200ResponseDataInnerSpecifics.from_json(json)
# print the JSON string representation of the object
print(GetPostsList200ResponseDataInnerSpecifics.to_json())

# convert the object into a dict
get_posts_list200_response_data_inner_specifics_dict = get_posts_list200_response_data_inner_specifics_instance.to_dict()
# create an instance of GetPostsList200ResponseDataInnerSpecifics from a dict
get_posts_list200_response_data_inner_specifics_from_dict = GetPostsList200ResponseDataInnerSpecifics.from_dict(get_posts_list200_response_data_inner_specifics_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


