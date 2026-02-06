# VerifyClassicCompanyMemberIdentityRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**email** | **str** | The email address to submit for verification. | 

## Example

```python
from unipile.models.verify_classic_company_member_identity_request import VerifyClassicCompanyMemberIdentityRequest

# TODO update the JSON string below
json = "{}"
# create an instance of VerifyClassicCompanyMemberIdentityRequest from a JSON string
verify_classic_company_member_identity_request_instance = VerifyClassicCompanyMemberIdentityRequest.from_json(json)
# print the JSON string representation of the object
print(VerifyClassicCompanyMemberIdentityRequest.to_json())

# convert the object into a dict
verify_classic_company_member_identity_request_dict = verify_classic_company_member_identity_request_instance.to_dict()
# create an instance of VerifyClassicCompanyMemberIdentityRequest from a dict
verify_classic_company_member_identity_request_from_dict = VerifyClassicCompanyMemberIdentityRequest.from_dict(verify_classic_company_member_identity_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


