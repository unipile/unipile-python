# ExcludeActivities


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**timespan** | **str** | The time period from which to filter results.    Native filter : Within date range    | [optional] [default to 'ANYTIME']
**exclude** | **List[str]** |  | 

## Example

```python
from unipile.models.exclude_activities import ExcludeActivities

# TODO update the JSON string below
json = "{}"
# create an instance of ExcludeActivities from a JSON string
exclude_activities_instance = ExcludeActivities.from_json(json)
# print the JSON string representation of the object
print(ExcludeActivities.to_json())

# convert the object into a dict
exclude_activities_dict = exclude_activities_instance.to_dict()
# create an instance of ExcludeActivities from a dict
exclude_activities_from_dict = ExcludeActivities.from_dict(exclude_activities_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


