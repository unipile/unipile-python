# DaysBased


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**days** | **float** | Days from now to send the message. | 
**timezone** | **str** | The time zone from which the message is scheduled (e.g. &#39;Europe/Paris&#39;, &#39;America/Phoenix&#39;...). | [optional] [default to 'Your browser time zone.']

## Example

```python
from unipile.models.days_based import DaysBased

# TODO update the JSON string below
json = "{}"
# create an instance of DaysBased from a JSON string
days_based_instance = DaysBased.from_json(json)
# print the JSON string representation of the object
print(DaysBased.to_json())

# convert the object into a dict
days_based_dict = days_based_instance.to_dict()
# create an instance of DaysBased from a dict
days_based_from_dict = DaysBased.from_dict(days_based_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


