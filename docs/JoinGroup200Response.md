# JoinGroup200Response

The result of the request to join the social group.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** | The type of the object: &#x60;GroupJoined&#x60;. | 
**membership_status** | **str** | The membership of the account owner once the request is sent.   - &#x60;member&#x60; the account owner joined the social group.   - &#x60;pending&#x60; the social group approves its members: the request waits for an approval. | 
**group_id** | **str** | The ID of the joined social group, when available. Use it as &#x60;group_id&#x60; with other Groups operations. | [optional] 

## Example

```python
from unipile.models.join_group200_response import JoinGroup200Response

# TODO update the JSON string below
json = "{}"
# create an instance of JoinGroup200Response from a JSON string
join_group200_response_instance = JoinGroup200Response.from_json(json)
# print the JSON string representation of the object
print(JoinGroup200Response.to_json())

# convert the object into a dict
join_group200_response_dict = join_group200_response_instance.to_dict()
# create an instance of JoinGroup200Response from a dict
join_group200_response_from_dict = JoinGroup200Response.from_dict(join_group200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


