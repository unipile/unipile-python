# VerifyClassicCompanyMemberIdentity200Response


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**object** | **str** |  | 
**challenge_id** | **str** | The challenge ID to pass to the Submit OTP endpoint along with the code. | 

## Example

```python
from unipile.models.verify_classic_company_member_identity200_response import VerifyClassicCompanyMemberIdentity200Response

# TODO update the JSON string below
json = "{}"
# create an instance of VerifyClassicCompanyMemberIdentity200Response from a JSON string
verify_classic_company_member_identity200_response_instance = VerifyClassicCompanyMemberIdentity200Response.from_json(json)
# print the JSON string representation of the object
print(VerifyClassicCompanyMemberIdentity200Response.to_json())

# convert the object into a dict
verify_classic_company_member_identity200_response_dict = verify_classic_company_member_identity200_response_instance.to_dict()
# create an instance of VerifyClassicCompanyMemberIdentity200Response from a dict
verify_classic_company_member_identity200_response_from_dict = VerifyClassicCompanyMemberIdentity200Response.from_dict(verify_classic_company_member_identity200_response_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


