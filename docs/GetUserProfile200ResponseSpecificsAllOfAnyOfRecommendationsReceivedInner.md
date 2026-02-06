# GetUserProfile200ResponseSpecificsAllOfAnyOfRecommendationsReceivedInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**caption** | **str** | Recommendation details, including date and actors relationship. | [optional] 
**created_on** | **str** | Creation date of the recommendation. | [optional] 
**text** | **str** | Content of the recommendation. | 
**user** | [**GetUserProfile200ResponseSpecificsAllOfAnyOfRecommendationsReceivedInnerUser**](GetUserProfile200ResponseSpecificsAllOfAnyOfRecommendationsReceivedInnerUser.md) |  | 

## Example

```python
from unipile.models.get_user_profile200_response_specifics_all_of_any_of_recommendations_received_inner import GetUserProfile200ResponseSpecificsAllOfAnyOfRecommendationsReceivedInner

# TODO update the JSON string below
json = "{}"
# create an instance of GetUserProfile200ResponseSpecificsAllOfAnyOfRecommendationsReceivedInner from a JSON string
get_user_profile200_response_specifics_all_of_any_of_recommendations_received_inner_instance = GetUserProfile200ResponseSpecificsAllOfAnyOfRecommendationsReceivedInner.from_json(json)
# print the JSON string representation of the object
print(GetUserProfile200ResponseSpecificsAllOfAnyOfRecommendationsReceivedInner.to_json())

# convert the object into a dict
get_user_profile200_response_specifics_all_of_any_of_recommendations_received_inner_dict = get_user_profile200_response_specifics_all_of_any_of_recommendations_received_inner_instance.to_dict()
# create an instance of GetUserProfile200ResponseSpecificsAllOfAnyOfRecommendationsReceivedInner from a dict
get_user_profile200_response_specifics_all_of_any_of_recommendations_received_inner_from_dict = GetUserProfile200ResponseSpecificsAllOfAnyOfRecommendationsReceivedInner.from_dict(get_user_profile200_response_specifics_all_of_any_of_recommendations_received_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


