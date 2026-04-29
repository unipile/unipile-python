# Unhandled


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**last_updated_at** | **str** | The time at which the activity was updated. Uses ISO 8601 UTC datetime (YYYY-MM-DDTHH:MM:SS.sssZ). | 
**last_updated_by** | [**LinkedInProjectsInnerContributorsInner**](LinkedInProjectsInnerContributorsInner.md) |  | 
**event** | **str** | The type of event. | 

## Example

```python
from unipile.models.unhandled import Unhandled

# TODO update the JSON string below
json = "{}"
# create an instance of Unhandled from a JSON string
unhandled_instance = Unhandled.from_json(json)
# print the JSON string representation of the object
print(Unhandled.to_json())

# convert the object into a dict
unhandled_dict = unhandled_instance.to_dict()
# create an instance of Unhandled from a dict
unhandled_from_dict = Unhandled.from_dict(unhandled_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


