# LinkedIn2Recommendations


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**received** | [**List[LinkedIn2RecommendationsReceivedInner]**](LinkedIn2RecommendationsReceivedInner.md) | A collection of the user&#39;s received recommendations. | 
**given** | [**List[LinkedIn2RecommendationsReceivedInner]**](LinkedIn2RecommendationsReceivedInner.md) | A collection of the user&#39;s given recommendations. | 

## Example

```python
from unipile.models.linked_in2_recommendations import LinkedIn2Recommendations

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn2Recommendations from a JSON string
linked_in2_recommendations_instance = LinkedIn2Recommendations.from_json(json)
# print the JSON string representation of the object
print(LinkedIn2Recommendations.to_json())

# convert the object into a dict
linked_in2_recommendations_dict = linked_in2_recommendations_instance.to_dict()
# create an instance of LinkedIn2Recommendations from a dict
linked_in2_recommendations_from_dict = LinkedIn2Recommendations.from_dict(linked_in2_recommendations_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


