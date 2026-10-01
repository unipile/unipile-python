# LinkedIn1RecommendationsReceivedInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**caption** | **str** | Recommendation details, including date and actors relationship. | [optional] 
**created_on** | **str** | Creation date of the recommendation. | [optional] 
**text** | **str** | Content of the recommendation. | 
**user** | [**LinkedIn1RecommendationsReceivedInnerUser**](LinkedIn1RecommendationsReceivedInnerUser.md) |  | 

## Example

```python
from unipile.models.linked_in1_recommendations_received_inner import LinkedIn1RecommendationsReceivedInner

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn1RecommendationsReceivedInner from a JSON string
linked_in1_recommendations_received_inner_instance = LinkedIn1RecommendationsReceivedInner.from_json(json)
# print the JSON string representation of the object
print(LinkedIn1RecommendationsReceivedInner.to_json())

# convert the object into a dict
linked_in1_recommendations_received_inner_dict = linked_in1_recommendations_received_inner_instance.to_dict()
# create an instance of LinkedIn1RecommendationsReceivedInner from a dict
linked_in1_recommendations_received_inner_from_dict = LinkedIn1RecommendationsReceivedInner.from_dict(linked_in1_recommendations_received_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


