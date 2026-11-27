# UpdateCommunityRequest

The changes to make to the community. Fields left out are kept.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The new name of the community. | [optional] 
**description** | **str** | The new description of the community. An empty string removes it. | [optional] 
**join_approval** | **bool** | Whether an admin must approve the people who ask to join the community. | [optional] 

## Example

```python
from unipile.models.update_community_request import UpdateCommunityRequest

# TODO update the JSON string below
json = "{}"
# create an instance of UpdateCommunityRequest from a JSON string
update_community_request_instance = UpdateCommunityRequest.from_json(json)
# print the JSON string representation of the object
print(UpdateCommunityRequest.to_json())

# convert the object into a dict
update_community_request_dict = update_community_request_instance.to_dict()
# create an instance of UpdateCommunityRequest from a dict
update_community_request_from_dict = UpdateCommunityRequest.from_dict(update_community_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


