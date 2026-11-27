# GetCommunityJoinRequestsList200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[GetCommunityJoinRequestsList200ResponseDataInner]**](GetCommunityJoinRequestsList200ResponseDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the provider. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.get_community_join_requests_list200_response import GetCommunityJoinRequestsList200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetCommunityJoinRequestsList200Response from a JSON string
get_community_join_requests_list200_response_instance = GetCommunityJoinRequestsList200Response.from_json(json)
# print the JSON string representation of the object
print(GetCommunityJoinRequestsList200Response.to_json())

# convert the object into a dict
get_community_join_requests_list200_response_dict = get_community_join_requests_list200_response_instance.to_dict()
# create an instance of GetCommunityJoinRequestsList200Response from a dict
get_community_join_requests_list200_response_from_dict = GetCommunityJoinRequestsList200Response.from_dict(get_community_join_requests_list200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


