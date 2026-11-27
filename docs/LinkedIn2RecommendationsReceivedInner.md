# LinkedIn2RecommendationsReceivedInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**caption** | **str** | Recommendation details, including date and actors relationship. | [optional] 
**created_on** | **str** | Creation date of the recommendation. | [optional] 
**text** | **str** | Content of the recommendation. | 
**user** | [**User**](User.md) |  | 

## Example

```python
from unipile.models.linked_in2_recommendations_received_inner import LinkedIn2RecommendationsReceivedInner

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn2RecommendationsReceivedInner from a JSON string
linked_in2_recommendations_received_inner_instance = LinkedIn2RecommendationsReceivedInner.from_json(json)
# print the JSON string representation of the object
print(LinkedIn2RecommendationsReceivedInner.to_json())

# convert the object into a dict
linked_in2_recommendations_received_inner_dict = linked_in2_recommendations_received_inner_instance.to_dict()
# create an instance of LinkedIn2RecommendationsReceivedInner from a dict
linked_in2_recommendations_received_inner_from_dict = LinkedIn2RecommendationsReceivedInner.from_dict(linked_in2_recommendations_received_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


