# GetUserCommentsList200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[GetUserCommentsList200ResponseDataInner]**](GetUserCommentsList200ResponseDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the endpoint. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.get_user_comments_list200_response import GetUserCommentsList200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetUserCommentsList200Response from a JSON string
get_user_comments_list200_response_instance = GetUserCommentsList200Response.from_json(json)
# print the JSON string representation of the object
print(GetUserCommentsList200Response.to_json())

# convert the object into a dict
get_user_comments_list200_response_dict = get_user_comments_list200_response_instance.to_dict()
# create an instance of GetUserCommentsList200Response from a dict
get_user_comments_list200_response_from_dict = GetUserCommentsList200Response.from_dict(get_user_comments_list200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


