# MultipleChoices

A question with multiple choices anwser.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**question** | **str** | The question that must be asked. | 
**qualification_required** | **bool** | Whether the applicant should be disqualified if the answer doesn&#39;t match what is expected. | [optional] [default to False]
**answer_type** | **str** |  | 
**choices** | **List[Optional[str]]** | A list of choices. | 
**expected_choices** | **List[Optional[str]]** | A list of ideal choices. | 
**suggested_value** | **str** | A suggested value. | 

## Example

```python
from unipile.models.multiple_choices import MultipleChoices

# TODO update the JSON string below
json = "{}"
# create an instance of MultipleChoices from a JSON string
multiple_choices_instance = MultipleChoices.from_json(json)
# print the JSON string representation of the object
print(MultipleChoices.to_json())

# convert the object into a dict
multiple_choices_dict = multiple_choices_instance.to_dict()
# create an instance of MultipleChoices from a dict
multiple_choices_from_dict = MultipleChoices.from_dict(multiple_choices_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


