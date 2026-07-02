# LinkedInInterests

The user's interests.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**top_voices** | [**List[LinkedInInterestsTopVoicesInner]**](LinkedInInterestsTopVoicesInner.md) | A collection of Top voice User profiles. | [optional] 
**companies** | [**List[LinkedInInterestsCompaniesInner]**](LinkedInInterestsCompaniesInner.md) | A collection of Companies. | [optional] 
**schools** | [**List[LinkedInInterestsSchoolsInner]**](LinkedInInterestsSchoolsInner.md) | A collection of Schools. | [optional] 
**newsletters** | [**List[LinkedInInterestsNewslettersInner]**](LinkedInInterestsNewslettersInner.md) | A collection of Newsletters. | [optional] 
**groups** | [**List[LinkedInInterestsGroupsInner]**](LinkedInInterestsGroupsInner.md) | A collection of Groups. | [optional] 

## Example

```python
from unipile.models.linked_in_interests import LinkedInInterests

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedInInterests from a JSON string
linked_in_interests_instance = LinkedInInterests.from_json(json)
# print the JSON string representation of the object
print(LinkedInInterests.to_json())

# convert the object into a dict
linked_in_interests_dict = linked_in_interests_instance.to_dict()
# create an instance of LinkedInInterests from a dict
linked_in_interests_from_dict = LinkedInInterests.from_dict(linked_in_interests_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


