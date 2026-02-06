# LinkedInClassicApplicant

Options available when the recipient is a candidate for one of your job postings.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**id** | **str** | The applicant ID of the recipient. | 
**messaging_token** | **str** | The messaging token to be retrieved using the &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-jobs-job-id-applicants-applicant-id\&quot;&gt;Get an Applicant&lt;/a&gt; endpoint. | 

## Example

```python
from unipile.models.linked_in_classic_applicant import LinkedInClassicApplicant

# TODO update the JSON string below
json = "{}"
# create an instance of LinkedInClassicApplicant from a JSON string
linked_in_classic_applicant_instance = LinkedInClassicApplicant.from_json(json)
# print the JSON string representation of the object
print(LinkedInClassicApplicant.to_json())

# convert the object into a dict
linked_in_classic_applicant_dict = linked_in_classic_applicant_instance.to_dict()
# create an instance of LinkedInClassicApplicant from a dict
linked_in_classic_applicant_from_dict = LinkedInClassicApplicant.from_dict(linked_in_classic_applicant_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


