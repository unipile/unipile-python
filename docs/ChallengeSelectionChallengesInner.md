# ChallengeSelectionChallengesInner


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | Identifier of the method (EMAIL, SMS or WHATSAPP). Send it back as the &#x60;challenge&#x60; field of Request Checkpoint to switch to this method. | 
**label** | **str** | Human-readable name of the method (e.g. \&quot;WhatsApp\&quot;, \&quot;Text message\&quot;, \&quot;Email\&quot;). | 
**description** | **str** | Extra detail about the method, e.g. the masked destination the code will be sent to. | [optional] 

## Example

```python
from unipile.models.challenge_selection_challenges_inner import ChallengeSelectionChallengesInner

# TODO update the JSON string below
json = "{}"
# create an instance of ChallengeSelectionChallengesInner from a JSON string
challenge_selection_challenges_inner_instance = ChallengeSelectionChallengesInner.from_json(json)
# print the JSON string representation of the object
print(ChallengeSelectionChallengesInner.to_json())

# convert the object into a dict
challenge_selection_challenges_inner_dict = challenge_selection_challenges_inner_instance.to_dict()
# create an instance of ChallengeSelectionChallengesInner from a dict
challenge_selection_challenges_inner_from_dict = ChallengeSelectionChallengesInner.from_dict(challenge_selection_challenges_inner_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


