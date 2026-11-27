# GetGroupMembersList200ResponseDataInner

A member of a social group or community.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the object. | 
**user** | [**GetGroupMembersList200ResponseDataInnerUser**](GetGroupMembersList200ResponseDataInnerUser.md) |  | 
**is_self** | **bool** | Whether the member is the owner of the account making the request. | 
**is_admin** | **bool** | Whether the member administers the group or community. | 

## Example

```python
from unipile.models.get_group_members_list200_response_data_inner import GetGroupMembersList200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetGroupMembersList200ResponseDataInner from a JSON string
get_group_members_list200_response_data_inner_instance = GetGroupMembersList200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(GetGroupMembersList200ResponseDataInner.to_json())

# convert the object into a dict
get_group_members_list200_response_data_inner_dict = get_group_members_list200_response_data_inner_instance.to_dict()
# create an instance of GetGroupMembersList200ResponseDataInner from a dict
get_group_members_list200_response_data_inner_from_dict = GetGroupMembersList200ResponseDataInner.from_dict(get_group_members_list200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


