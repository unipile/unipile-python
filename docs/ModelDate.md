# ModelDate

A date.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** | Indicates a date-only value (for all-day events). | 
**var_date** | **date** | The date. Must use a supported date format. See [supported date formats](https://developer.unipile.com/v2.0/reference/api-usage#dates). | 
**timezone** | **str** | The IANA timezone in which the date is expressed (e.g. &#x60;Europe/Paris&#x60;). | [optional] 

## Example

```python
from unipile.models.model_date import ModelDate

# TODO update the JSON string below
json = "{}"
# create an instance of ModelDate from a JSON string
model_date_instance = ModelDate.from_json(json)
# print the JSON string representation of the object
print(ModelDate.to_json())

# convert the object into a dict
model_date_dict = model_date_instance.to_dict()
# create an instance of ModelDate from a dict
model_date_from_dict = ModelDate.from_dict(model_date_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


