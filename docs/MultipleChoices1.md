# MultipleChoices1

A question with multiple choices anwser.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**question** | **str** | The question that must be asked. | 
**qualification_required** | **bool** | Whether the applicant should be disqualified if the answer doesn&#39;t match what is expected. | [optional] [default to False]
**answer_type** | **str** |  | 
**choices** | **List[str]** | A list of choices. | 
**expected_choices** | **List[str]** | A list of ideal choices. | 
**suggested_value** | **str** | A suggested value. | 

## Example

```python
from unipile.models.multiple_choices1 import MultipleChoices1

# TODO update the JSON string below
json = "{}"
# create an instance of MultipleChoices1 from a JSON string
multiple_choices1_instance = MultipleChoices1.from_json(json)
# print the JSON string representation of the object
print(MultipleChoices1.to_json())

# convert the object into a dict
multiple_choices1_dict = multiple_choices1_instance.to_dict()
# create an instance of MultipleChoices1 from a dict
multiple_choices1_from_dict = MultipleChoices1.from_dict(multiple_choices1_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


