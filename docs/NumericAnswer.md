# NumericAnswer

A question with numeric anwser.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**question** | **str** | The question that must be asked. | 
**qualification_required** | **bool** | Whether the applicant should be disqualified if the answer doesn&#39;t match what is expected. | [optional] [default to False]
**answer_type** | **str** |  | 
**min_expectation** | **float** | A minimum expectation. | [optional] 
**max_expectation** | **float** | A maximum expectation. | [optional] 
**suggested_value** | **float** | A suggested value. | 

## Example

```python
from unipile.models.numeric_answer import NumericAnswer

# TODO update the JSON string below
json = "{}"
# create an instance of NumericAnswer from a JSON string
numeric_answer_instance = NumericAnswer.from_json(json)
# print the JSON string representation of the object
print(NumericAnswer.to_json())

# convert the object into a dict
numeric_answer_dict = numeric_answer_instance.to_dict()
# create an instance of NumericAnswer from a dict
numeric_answer_from_dict = NumericAnswer.from_dict(numeric_answer_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


