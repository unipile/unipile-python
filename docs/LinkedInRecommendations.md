# LinkedInRecommendations


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**received** | [**List[LinkedInRecommendationsReceivedInner]**](LinkedInRecommendationsReceivedInner.md) |  | 
**given** | [**List[LinkedInRecommendationsReceivedInner]**](LinkedInRecommendationsReceivedInner.md) |  | 

## Example

```python
from unipile.models.linked_in_recommendations import LinkedInRecommendations

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedInRecommendations from a JSON string
linked_in_recommendations_instance = LinkedInRecommendations.from_json(json)
# print the JSON string representation of the object
print(LinkedInRecommendations.to_json())

# convert the object into a dict
linked_in_recommendations_dict = linked_in_recommendations_instance.to_dict()
# create an instance of LinkedInRecommendations from a dict
linked_in_recommendations_from_dict = LinkedInRecommendations.from_dict(linked_in_recommendations_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


