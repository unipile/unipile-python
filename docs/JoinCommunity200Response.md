# JoinCommunity200Response

The result of the request to join the community.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the object: &#x60;CommunityJoined&#x60;. | 
**membership_status** | **str** | The membership of the account owner once the request is sent.   - &#x60;member&#x60; the account owner joined the community.   - &#x60;pending&#x60; the community approves its members: the request waits for an approval. | 
**community_id** | **str** | The ID of the community when membership is confirmed. Use it as &#x60;community_id&#x60; in Communities operations. | [optional] 

## Example

```python
from unipile.models.join_community200_response import JoinCommunity200Response

# TODO update the JSON string below
json = "{}"
# create an instance of JoinCommunity200Response from a JSON string
join_community200_response_instance = JoinCommunity200Response.from_json(json)
# print the JSON string representation of the object
print(JoinCommunity200Response.to_json())

# convert the object into a dict
join_community200_response_dict = join_community200_response_instance.to_dict()
# create an instance of JoinCommunity200Response from a dict
join_community200_response_from_dict = JoinCommunity200Response.from_dict(join_community200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


