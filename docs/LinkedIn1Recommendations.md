# LinkedIn1Recommendations


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**received** | [**List[LinkedIn1RecommendationsReceivedInner]**](LinkedIn1RecommendationsReceivedInner.md) | A collection of the user&#39;s received recommendations. | 
**given** | [**List[LinkedIn1RecommendationsReceivedInner]**](LinkedIn1RecommendationsReceivedInner.md) | A collection of the user&#39;s given recommendations. | 

## Example

```python
from unipile.models.linked_in1_recommendations import LinkedIn1Recommendations

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn1Recommendations from a JSON string
linked_in1_recommendations_instance = LinkedIn1Recommendations.from_json(json)
# print the JSON string representation of the object
print(LinkedIn1Recommendations.to_json())

# convert the object into a dict
linked_in1_recommendations_dict = linked_in1_recommendations_instance.to_dict()
# create an instance of LinkedIn1Recommendations from a dict
linked_in1_recommendations_from_dict = LinkedIn1Recommendations.from_dict(linked_in1_recommendations_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


