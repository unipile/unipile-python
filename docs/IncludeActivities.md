# IncludeActivities


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**timespan** | **str** | The time period from which to filter results.    Native filter : Within date range    | [optional] [default to 'ANYTIME']
**include** | **List[str]** |  | 

## Example

```python
from unipile.models.include_activities import IncludeActivities

# TODO update the JSON string below
json = "{}"
# create an instance of IncludeActivities from a JSON string
include_activities_instance = IncludeActivities.from_json(json)
# print the JSON string representation of the object
print(IncludeActivities.to_json())

# convert the object into a dict
include_activities_dict = include_activities_instance.to_dict()
# create an instance of IncludeActivities from a dict
include_activities_from_dict = IncludeActivities.from_dict(include_activities_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


