# PerformCommunitiesSearch200ResponseDataInner

A community whose members have access to linked group chats.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the object: &#x60;Community&#x60;. | 
**id** | **str** | The ID of the community for the provider. | 
**name** | **str** | The name of the community. | 
**membership_status** | **str** | The membership of the account owner in the community.   - &#x60;member&#x60; the account owner is a member of the community.   - &#x60;pending&#x60; the account owner asked to join the community and waits for an approval.   - &#x60;not_member&#x60; the account owner is not a member of the community. | 
**description** | **str** | The description of the community. | [optional] 
**members_count** | **float** | The number of members of the community. | [optional] 
**is_admin** | **bool** | Is the account owner an admin of the community. | [optional] 
**chat_ids** | **List[str]** | The IDs of the known Messaging API chats in the community, including its announcement chat when available. Access depends on the permissions of the account owner. | [optional] 

## Example

```python
from unipile.models.perform_communities_search200_response_data_inner import PerformCommunitiesSearch200ResponseDataInner

# TODO update the JSON string below
json = "{}"
# create an instance of PerformCommunitiesSearch200ResponseDataInner from a JSON string
perform_communities_search200_response_data_inner_instance = PerformCommunitiesSearch200ResponseDataInner.from_json(json)
# print the JSON string representation of the object
print(PerformCommunitiesSearch200ResponseDataInner.to_json())

# convert the object into a dict
perform_communities_search200_response_data_inner_dict = perform_communities_search200_response_data_inner_instance.to_dict()
# create an instance of PerformCommunitiesSearch200ResponseDataInner from a dict
perform_communities_search200_response_data_inner_from_dict = PerformCommunitiesSearch200ResponseDataInner.from_dict(perform_communities_search200_response_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


