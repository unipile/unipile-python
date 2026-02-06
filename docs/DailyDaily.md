# DailyDaily


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**currency** | **str** | A 3 capital letters ISO 4217 currency code. | 
**amount** | **float** | The amount of money to be spent on the job posting. | 

## Example

```python
from unipile.models.daily_daily import DailyDaily

# TODO update the JSON string below
json = "{}"
# create an instance of DailyDaily from a JSON string
daily_daily_instance = DailyDaily.from_json(json)
# print the JSON string representation of the object
print(DailyDaily.to_json())

# convert the object into a dict
daily_daily_dict = daily_daily_instance.to_dict()
# create an instance of DailyDaily from a dict
daily_daily_from_dict = DailyDaily.from_dict(daily_daily_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


