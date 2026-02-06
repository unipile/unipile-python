# PublishInPromotedModeBudget

The daily OR total budget.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**daily** | [**DailyDaily**](DailyDaily.md) |  | 
**total** | [**DailyDaily**](DailyDaily.md) |  | 

## Example

```python
from unipile.models.publish_in_promoted_mode_budget import PublishInPromotedModeBudget

# TODO update the JSON string below
json = "{}"
# create an instance of PublishInPromotedModeBudget from a JSON string
publish_in_promoted_mode_budget_instance = PublishInPromotedModeBudget.from_json(json)
# print the JSON string representation of the object
print(PublishInPromotedModeBudget.to_json())

# convert the object into a dict
publish_in_promoted_mode_budget_dict = publish_in_promoted_mode_budget_instance.to_dict()
# create an instance of PublishInPromotedModeBudget from a dict
publish_in_promoted_mode_budget_from_dict = PublishInPromotedModeBudget.from_dict(publish_in_promoted_mode_budget_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


