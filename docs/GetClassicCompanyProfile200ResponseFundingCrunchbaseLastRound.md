# GetClassicCompanyProfile200ResponseFundingCrunchbaseLastRound

The last funding round.

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**announced_on** | **str** | The date on which the round was announced. Uses ISO 8601 en_US datetime (MM/DD/YYYY). | 
**url** | **str** | The URL to the funding round on Crunchbase. | 
**funding_type** | **str** | The type of funding. | 
**investors_count** | **float** | The number of investors for the current round. | 
**lead_investors** | [**List[GetClassicCompanyProfile200ResponseFundingCrunchbaseLastRoundLeadInvestorsInner]**](GetClassicCompanyProfile200ResponseFundingCrunchbaseLastRoundLeadInvestorsInner.md) | A list of most important investors. | 
**money_raised** | [**GetClassicCompanyProfile200ResponseFundingCrunchbaseLastRoundMoneyRaised**](GetClassicCompanyProfile200ResponseFundingCrunchbaseLastRoundMoneyRaised.md) |  | [optional] 

## Example

```python
from unipile.models.get_classic_company_profile200_response_funding_crunchbase_last_round import GetClassicCompanyProfile200ResponseFundingCrunchbaseLastRound

# TODO update the JSON string below
json = "{}"
# create an instance of GetClassicCompanyProfile200ResponseFundingCrunchbaseLastRound from a JSON string
get_classic_company_profile200_response_funding_crunchbase_last_round_instance = GetClassicCompanyProfile200ResponseFundingCrunchbaseLastRound.from_json(json)
# print the JSON string representation of the object
print(GetClassicCompanyProfile200ResponseFundingCrunchbaseLastRound.to_json())

# convert the object into a dict
get_classic_company_profile200_response_funding_crunchbase_last_round_dict = get_classic_company_profile200_response_funding_crunchbase_last_round_instance.to_dict()
# create an instance of GetClassicCompanyProfile200ResponseFundingCrunchbaseLastRound from a dict
get_classic_company_profile200_response_funding_crunchbase_last_round_from_dict = GetClassicCompanyProfile200ResponseFundingCrunchbaseLastRound.from_dict(get_classic_company_profile200_response_funding_crunchbase_last_round_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


