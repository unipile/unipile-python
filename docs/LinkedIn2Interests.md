# LinkedIn2Interests

The user's interests.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**top_voices** | [**List[LinkedIn2InterestsTopVoicesInner]**](LinkedIn2InterestsTopVoicesInner.md) | A collection of Top voice User profiles. | [optional] 
**companies** | [**List[LinkedIn2InterestsCompaniesInner]**](LinkedIn2InterestsCompaniesInner.md) | A collection of Companies. | [optional] 
**schools** | [**List[LinkedIn2InterestsSchoolsInner]**](LinkedIn2InterestsSchoolsInner.md) | A collection of Schools. | [optional] 
**newsletters** | [**List[LinkedIn2InterestsNewslettersInner]**](LinkedIn2InterestsNewslettersInner.md) | A collection of Newsletters. | [optional] 
**groups** | [**List[LinkedIn2InterestsGroupsInner]**](LinkedIn2InterestsGroupsInner.md) | A collection of Groups. | [optional] 

## Example

```python
from unipile.models.linked_in2_interests import LinkedIn2Interests

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedIn2Interests from a JSON string
linked_in2_interests_instance = LinkedIn2Interests.from_json(json)
# print the JSON string representation of the object
print(LinkedIn2Interests.to_json())

# convert the object into a dict
linked_in2_interests_dict = linked_in2_interests_instance.to_dict()
# create an instance of LinkedIn2Interests from a dict
linked_in2_interests_from_dict = LinkedIn2Interests.from_dict(linked_in2_interests_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


