# PerformClassicSearchFromUrl200ResponseAnyOf2DataInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**product** | **str** |  | 
**id** | **str** | The ID of the user. | 
**display_name** | **str** | The display name of the User. | 
**public_identifier** | **str** | The public identifier of the User. | [optional] 
**profile_url** | **str** | The profile URL of the User. | [optional] 
**public_picture_url** | **str** | The public picture URL of the User. | [optional] 
**relations_count** | **float** | The number of relations of the User. | [optional] 
**shared_relations_count** | **float** | The number of relations that you share with the User. | [optional] 
**followers_count** | **float** | The number of the followers of the User. | [optional] 
**location** | **str** | The location of the User. | 
**headline** | **str** | The headline of the User. | 
**industry** | **str** | The industry to which the User belongs. | [optional] 
**is_premium** | **bool** | Whether the User has a premium account. | [optional] 
**is_verified** | **bool** | Whether the User has a verified account. | [optional] 
**is_open_profile** | **bool** | Whether the User has an Open Profile. The Open Profile feature allows anyone on LinkedIn to contact a Premium member for free. | [optional] 
**can_send_inmail** | **bool** | Whether it is possible to send an inMail to this User. | [optional] 
**network_distance** | **str** | Network distance to a User.       &#x60;SELF&#x60;: Yourself.       &#x60;FIRST_DEGREE&#x60;: 1st degree connection.       &#x60;SECOND_DEGREE&#x60;: 2nd degree connection (connection of a 1st degree).       &#x60;THIRD_DEGREE&#x60;: 3rd degree connection (connection of a 2nd degree).       &#x60;OUT_OF_NETWORK&#x60;: Unreachable user.&#39; | 
**keywords_match** | **str** | The search terms that produced this result. | [optional] 

## Example

```python
from unipile.models.perform_classic_search_from_url200_response_any_of2_data_inner import PerformClassicSearchFromUrl200ResponseAnyOf2DataInner

# TODO update the JSON string below
json = "{}"
# create an instance of PerformClassicSearchFromUrl200ResponseAnyOf2DataInner from a JSON string
perform_classic_search_from_url200_response_any_of2_data_inner_instance = PerformClassicSearchFromUrl200ResponseAnyOf2DataInner.from_json(json)
# print the JSON string representation of the object
print(PerformClassicSearchFromUrl200ResponseAnyOf2DataInner.to_json())

# convert the object into a dict
perform_classic_search_from_url200_response_any_of2_data_inner_dict = perform_classic_search_from_url200_response_any_of2_data_inner_instance.to_dict()
# create an instance of PerformClassicSearchFromUrl200ResponseAnyOf2DataInner from a dict
perform_classic_search_from_url200_response_any_of2_data_inner_from_dict = PerformClassicSearchFromUrl200ResponseAnyOf2DataInner.from_dict(perform_classic_search_from_url200_response_any_of2_data_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


