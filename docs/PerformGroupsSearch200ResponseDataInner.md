# PerformGroupsSearch200ResponseDataInner

A social group with members, posts and, where available, events.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the object: &#x60;Group&#x60;. | 
**id** | **str** | The ID of the social group for the provider. | 
**name** | **str** | The name of the social group. | 
**profile_url** | **str** | Public url to the page of the social group. | [optional] 
**public_picture_url** | **str** | Public url to the picture of the social group. | [optional] 
**membership_status** | **str** | The membership of the account owner in the social group.   - &#x60;member&#x60; the account owner is a member of the social group.   - &#x60;pending&#x60; the account owner asked to join the social group and waits for an approval.   - &#x60;not_member&#x60; the account owner is not a member of the social group. | 
**description** | **str** | The description of the social group. | [optional] 
**members_count** | **float** | The number of members of the social group. | [optional] 
**is_admin** | **bool** | Is the account owner an admin of the social group. | [optional] 

## Example

```python
from unipile.models.perform_groups_search200_response_data_inner import PerformGroupsSearch200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of PerformGroupsSearch200ResponseDataInner from a JSON string
perform_groups_search200_response_data_inner_instance = PerformGroupsSearch200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(PerformGroupsSearch200ResponseDataInner.to_json())

# convert the object into a dict
perform_groups_search200_response_data_inner_dict = perform_groups_search200_response_data_inner_instance.to_dict()
# create an instance of PerformGroupsSearch200ResponseDataInner from a dict
perform_groups_search200_response_data_inner_from_dict = PerformGroupsSearch200ResponseDataInner.from_dict(perform_groups_search200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


