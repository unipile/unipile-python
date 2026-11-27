# UpdateCommunityMemberRequest

The changes to make to the member.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**is_admin** | **bool** | Whether the member administers the community. | 

## Example

```python
from unipile.models.update_community_member_request import UpdateCommunityMemberRequest

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateCommunityMemberRequest from a JSON string
update_community_member_request_instance = UpdateCommunityMemberRequest.from_json(json)
# print the JSON string representation of the object
print(UpdateCommunityMemberRequest.to_json())

# convert the object into a dict
update_community_member_request_dict = update_community_member_request_instance.to_dict()
# create an instance of UpdateCommunityMemberRequest from a dict
update_community_member_request_from_dict = UpdateCommunityMemberRequest.from_dict(update_community_member_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


