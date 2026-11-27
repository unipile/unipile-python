# CreateCommunityRequest

The community to create.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**name** | **str** | The name of the community. | 
**description** | **str** | The description of the community. | [optional] 

## Example

```python
from unipile.models.create_community_request import CreateCommunityRequest

# TODO update the JSON string below
json = "{}"
# create an instance of CreateCommunityRequest from a JSON string
create_community_request_instance = CreateCommunityRequest.from_json(json)
# print the JSON string representation of the object
print(CreateCommunityRequest.to_json())

# convert the object into a dict
create_community_request_dict = create_community_request_instance.to_dict()
# create an instance of CreateCommunityRequest from a dict
create_community_request_from_dict = CreateCommunityRequest.from_dict(create_community_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


