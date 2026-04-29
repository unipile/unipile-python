# ProfileView


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**last_updated_at** | **str** | The time at which the activity was updated. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**last_updated_by** | [**LinkedInProjectsInnerContributorsInner**](LinkedInProjectsInnerContributorsInner.md) |  | 
**event** | **str** | The type of event. | 

## Example

```python
from unipile.models.profile_view import ProfileView

# TODO update the JSON string below
json = "{}"
# create an instance of ProfileView from a JSON string
profile_view_instance = ProfileView.from_json(json)
# print the JSON string representation of the object
print(ProfileView.to_json())

# convert the object into a dict
profile_view_dict = profile_view_instance.to_dict()
# create an instance of ProfileView from a dict
profile_view_from_dict = ProfileView.from_dict(profile_view_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


