# EndorseClassicMemberSkillRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**skill_id** | **str** | The endorsement ID for the selected skill.&lt;br/&gt;Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/getuserprofile\&quot;&gt;Get a User Profile&lt;/a&gt; with &#x60;linkedin_skills&#x60; in param &#x60;with_sections&#x60; to retrieve the skills you can endorse for the given member. | 

## Example

```python
from unipile.models.endorse_classic_member_skill_request import EndorseClassicMemberSkillRequest

# TODO update the JSON string below
json = "{}"
# create an instance of EndorseClassicMemberSkillRequest from a JSON string
endorse_classic_member_skill_request_instance = EndorseClassicMemberSkillRequest.from_json(json)
# print the JSON string representation of the object
print(EndorseClassicMemberSkillRequest.to_json())

# convert the object into a dict
endorse_classic_member_skill_request_dict = endorse_classic_member_skill_request_instance.to_dict()
# create an instance of EndorseClassicMemberSkillRequest from a dict
endorse_classic_member_skill_request_from_dict = EndorseClassicMemberSkillRequest.from_dict(endorse_classic_member_skill_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


