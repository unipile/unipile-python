# GetCommunityJoinRequestsList200ResponseDataInner

A request to join a community, waiting for an admin to accept or refuse it.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the object: &#x60;CommunityJoinRequest&#x60;. | 
**id** | **str** | The ID of the request, to accept or refuse it. | 
**user** | [**GetCommunityJoinRequestsList200ResponseDataInnerUser**](GetCommunityJoinRequestsList200ResponseDataInnerUser.md) |  | 
**requested_at** | **datetime** | The date of the request. | [optional] 

## Example

```python
from unipile.models.get_community_join_requests_list200_response_data_inner import GetCommunityJoinRequestsList200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetCommunityJoinRequestsList200ResponseDataInner from a JSON string
get_community_join_requests_list200_response_data_inner_instance = GetCommunityJoinRequestsList200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetCommunityJoinRequestsList200ResponseDataInner.to_json())

# convert the object into a dict
get_community_join_requests_list200_response_data_inner_dict = get_community_join_requests_list200_response_data_inner_instance.to_dict()
# create an instance of GetCommunityJoinRequestsList200ResponseDataInner from a dict
get_community_join_requests_list200_response_data_inner_from_dict = GetCommunityJoinRequestsList200ResponseDataInner.from_dict(get_community_join_requests_list200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


