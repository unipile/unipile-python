# GetClassicCompanyProfile200ResponseFundingCrunchbase

Details about Crunchbase funding.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**rounds_url** | **str** | The URL to the funding rounds on Crunchbase. | 
**rounds_count** | **float** | The number of funding rounds. | 
**company_url** | **str** | The URL of the Company on Crunchbase. | 
**last_round** | [**GetClassicCompanyProfile200ResponseFundingCrunchbaseLastRound**](GetClassicCompanyProfile200ResponseFundingCrunchbaseLastRound.md) |  | 

## Example

```python
from unipile.models.get_classic_company_profile200_response_funding_crunchbase import GetClassicCompanyProfile200ResponseFundingCrunchbase

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicCompanyProfile200ResponseFundingCrunchbase from a JSON string
get_classic_company_profile200_response_funding_crunchbase_instance = GetClassicCompanyProfile200ResponseFundingCrunchbase.from_json(json)
# print the JSON string representation of the object
print(GetClassicCompanyProfile200ResponseFundingCrunchbase.to_json())

# convert the object into a dict
get_classic_company_profile200_response_funding_crunchbase_dict = get_classic_company_profile200_response_funding_crunchbase_instance.to_dict()
# create an instance of GetClassicCompanyProfile200ResponseFundingCrunchbase from a dict
get_classic_company_profile200_response_funding_crunchbase_from_dict = GetClassicCompanyProfile200ResponseFundingCrunchbase.from_dict(get_classic_company_profile200_response_funding_crunchbase_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


