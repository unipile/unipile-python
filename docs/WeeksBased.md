# WeeksBased


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**weeks** | **float** | Weeks from now to send the message. | 
**timezone** | **str** | The time zone from which the message is scheduled (e.g. &#39;Europe/Paris&#39;, &#39;America/Phoenix&#39;...). | [optional] [default to 'Your browser time zone.']

## Example

```python
from unipile.models.weeks_based import WeeksBased

# TODO update the JSON string below
json = "{}"
# create an instance of WeeksBased from a JSON string
weeks_based_instance = WeeksBased.from_json(json)
# print the JSON string representation of the object
print(WeeksBased.to_json())

# convert the object into a dict
weeks_based_dict = weeks_based_instance.to_dict()
# create an instance of WeeksBased from a dict
weeks_based_from_dict = WeeksBased.from_dict(weeks_based_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


