# ChallengeSelection

The user must pick which alternative verification method to use to receive their code.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **str** |  | 
**challenges** | [**List[ChallengeSelectionChallengesInner]**](ChallengeSelectionChallengesInner.md) | A list of alternative verification methods to choose from. | 

## Example

```python
from unipile.models.challenge_selection import ChallengeSelection

# TODO update the JSON string below
json = "{}"
# create an instance of ChallengeSelection from a JSON string
challenge_selection_instance = ChallengeSelection.from_json(json)
# print the JSON string representation of the object
print(ChallengeSelection.to_json())

# convert the object into a dict
challenge_selection_dict = challenge_selection_instance.to_dict()
# create an instance of ChallengeSelection from a dict
challenge_selection_from_dict = ChallengeSelection.from_dict(challenge_selection_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


