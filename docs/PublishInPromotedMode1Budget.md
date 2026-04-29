# PublishInPromotedMode1Budget

Leave this field blank if you don't have a choice of budget when posting a job on LinkedIn.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**currency** | **str** | A 3 capital letters ISO 4217 currency code. | 
**amount** | **float** | The amount of money to be spent on the job posting. | 
**scope** | **str** | The time scope of the budget. | 

## Example

```python
from unipile.models.publish_in_promoted_mode1_budget import PublishInPromotedMode1Budget

# TODO update the JSON string below
json = "{}"
# create an instance of PublishInPromotedMode1Budget from a JSON string
publish_in_promoted_mode1_budget_instance = PublishInPromotedMode1Budget.from_json(json)
# print the JSON string representation of the object
print(PublishInPromotedMode1Budget.to_json())

# convert the object into a dict
publish_in_promoted_mode1_budget_dict = publish_in_promoted_mode1_budget_instance.to_dict()
# create an instance of PublishInPromotedMode1Budget from a dict
publish_in_promoted_mode1_budget_from_dict = PublishInPromotedMode1Budget.from_dict(publish_in_promoted_mode1_budget_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


