# LinkedInInterestsGroupsInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The ID of the group. | [optional] 
**name** | **str** | The name of the group. | 
**url** | **str** | The URL to the group. | [optional] 
**members_count** | **float** | The number of members of the group. | [optional] 
**is_member** | **bool** | Whether the current user is a member of the group. | 
**public_picture_url** | **str** | The public picture URL of the group. | [optional] 

## Example

```python
from unipile.models.linked_in_interests_groups_inner import LinkedInInterestsGroupsInner

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedInInterestsGroupsInner from a JSON string
linked_in_interests_groups_inner_instance = LinkedInInterestsGroupsInner.from_json(json)
# print the JSON string representation of the object
print(LinkedInInterestsGroupsInner.to_json())

# convert the object into a dict
linked_in_interests_groups_inner_dict = linked_in_interests_groups_inner_instance.to_dict()
# create an instance of LinkedInInterestsGroupsInner from a dict
linked_in_interests_groups_inner_from_dict = LinkedInInterestsGroupsInner.from_dict(linked_in_interests_groups_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


