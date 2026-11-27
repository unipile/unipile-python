# CancelCommunityJoinRequest200Response

The request was refused.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the object: &#x60;CommunityJoinRequestCanceled&#x60;. | 

## Example

```python
from unipile.models.cancel_community_join_request200_response import CancelCommunityJoinRequest200Response

# TODO update the JSON string below
json = "{}"
# create an instance of CancelCommunityJoinRequest200Response from a JSON string
cancel_community_join_request200_response_instance = CancelCommunityJoinRequest200Response.from_json(json)
# print the JSON string representation of the object
print(CancelCommunityJoinRequest200Response.to_json())

# convert the object into a dict
cancel_community_join_request200_response_dict = cancel_community_join_request200_response_instance.to_dict()
# create an instance of CancelCommunityJoinRequest200Response from a dict
cancel_community_join_request200_response_from_dict = CancelCommunityJoinRequest200Response.from_dict(cancel_community_join_request200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


