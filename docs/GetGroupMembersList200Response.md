# GetGroupMembersList200Response

The members of the group or community.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**data** | [**List[GetGroupMembersList200ResponseDataInner]**](GetGroupMembersList200ResponseDataInner.md) |  | 
**total_count** | **float** | Total number of results if supported by the provider. | [optional] 
**next_cursor** | **str** | Cursor to get the next page of results if supported. Else use &#x60;offset&#x60;. | [optional] 

## Example

```python
from unipile.models.get_group_members_list200_response import GetGroupMembersList200Response

# TODO update the JSON string below
json = "{}"
# create an instance of GetGroupMembersList200Response from a JSON string
get_group_members_list200_response_instance = GetGroupMembersList200Response.from_json(json)
# print the JSON string representation of the object
print(GetGroupMembersList200Response.to_json())

# convert the object into a dict
get_group_members_list200_response_dict = get_group_members_list200_response_instance.to_dict()
# create an instance of GetGroupMembersList200Response from a dict
get_group_members_list200_response_from_dict = GetGroupMembersList200Response.from_dict(get_group_members_list200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


