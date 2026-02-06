# unipile.LinkedInApi

All URIs are relative to *https://api.unipile.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**browse_sales_account_list**](LinkedInApi.md#browse_sales_account_list) | **POST** /v2/{account_id}/linkedin/sales-navigator/account-lists/{list_id} | Browse an Account List
[**browse_sales_lead_list**](LinkedInApi.md#browse_sales_lead_list) | **POST** /v2/{account_id}/linkedin/sales-navigator/lead-lists/{list_id} | Browse a Lead List
[**close_classic_job_posting**](LinkedInApi.md#close_classic_job_posting) | **POST** /v2/{account_id}/linkedin/jobs/{job_id}/close | Close a Job Posting
[**close_recruiter_job_posting**](LinkedInApi.md#close_recruiter_job_posting) | **POST** /v2/{account_id}/linkedin/recruiter/projects/{project_id}/jobs/{job_id}/close | Close a Job Posting
[**create_classic_job_posting_draft**](LinkedInApi.md#create_classic_job_posting_draft) | **POST** /v2/{account_id}/linkedin/jobs | Create a Job Posting Draft
[**create_recruiter_hiring_project**](LinkedInApi.md#create_recruiter_hiring_project) | **POST** /v2/{account_id}/linkedin/recruiter/projects | Create a New Project
[**create_recruiter_job_posting_draft_in_existing_project**](LinkedInApi.md#create_recruiter_job_posting_draft_in_existing_project) | **POST** /v2/{account_id}/linkedin/recruiter/projects/{project_id}/jobs | Create a Job Posting Draft in an Existing Project
[**create_recruiter_job_posting_draft_in_new_project**](LinkedInApi.md#create_recruiter_job_posting_draft_in_new_project) | **POST** /v2/{account_id}/linkedin/recruiter/jobs | Create a Job Posting Draft in a New Project
[**edit_classic_job_posting**](LinkedInApi.md#edit_classic_job_posting) | **PATCH** /v2/{account_id}/linkedin/jobs/{job_id} | Edit an existing Job Posting
[**edit_recruiter_hiring_project**](LinkedInApi.md#edit_recruiter_hiring_project) | **PATCH** /v2/{account_id}/linkedin/recruiter/projects/{project_id} | Edit a Project
[**edit_recruiter_job_posting**](LinkedInApi.md#edit_recruiter_job_posting) | **PATCH** /v2/{account_id}/linkedin/recruiter/projects/{project_id}/jobs/{job_id} | Edit an Existing Job Posting
[**get_classic_applicant_by_id**](LinkedInApi.md#get_classic_applicant_by_id) | **GET** /v2/{account_id}/linkedin/jobs/{job_id}/applicants/{applicant_id} | Get an Applicant
[**get_classic_applicant_resume**](LinkedInApi.md#get_classic_applicant_resume) | **GET** /v2/{account_id}/linkedin/jobs/{job_id}/applicants/{applicant_id}/resume | Get an Applicant&#39;s Resume
[**get_classic_applicants**](LinkedInApi.md#get_classic_applicants) | **POST** /v2/{account_id}/linkedin/jobs/{job_id}/applicants | List Job Posting Applicants
[**get_classic_company_profile**](LinkedInApi.md#get_classic_company_profile) | **GET** /v2/{account_id}/linkedin/company/{company_id} | Get a Company Profile
[**get_classic_job_posting**](LinkedInApi.md#get_classic_job_posting) | **GET** /v2/{account_id}/linkedin/jobs/{job_id} | Get a Job Posting
[**get_classic_job_posting_budget**](LinkedInApi.md#get_classic_job_posting_budget) | **GET** /v2/{account_id}/linkedin/jobs/{job_id}/budget | Get the Budget for a Job Posting
[**get_classic_search_parameters**](LinkedInApi.md#get_classic_search_parameters) | **GET** /v2/{account_id}/linkedin/search/parameters | List Search Parameters
[**get_inmail_credits**](LinkedInApi.md#get_inmail_credits) | **GET** /v2/{account_id}/linkedin/inmail-credits | Get InMail Credits
[**get_recruiter_applicant_by_id**](LinkedInApi.md#get_recruiter_applicant_by_id) | **POST** /v2/{account_id}/linkedin/recruiter/projects/{project_id}/talent-pool/applicants/{applicant_id} | Get an Applicant
[**get_recruiter_applicant_resume**](LinkedInApi.md#get_recruiter_applicant_resume) | **GET** /v2/{account_id}/linkedin/recruiter/projects/{project_id}/talent-pool/applicants/{applicant_id}/resume | Get an Applicant&#39;s Resume
[**get_recruiter_hiring_project**](LinkedInApi.md#get_recruiter_hiring_project) | **GET** /v2/{account_id}/linkedin/recruiter/projects/{project_id} | Get a Project
[**get_recruiter_hiring_project_list**](LinkedInApi.md#get_recruiter_hiring_project_list) | **GET** /v2/{account_id}/linkedin/recruiter/projects | List Projects
[**get_recruiter_job_posting_budget**](LinkedInApi.md#get_recruiter_job_posting_budget) | **GET** /v2/{account_id}/linkedin/recruiter/projects/{project_id}/jobs/{job_id}/budget | Get the Budget for a Job Posting
[**get_recruiter_job_posting_by_id**](LinkedInApi.md#get_recruiter_job_posting_by_id) | **GET** /v2/{account_id}/linkedin/recruiter/jobs/{job_id} | Get a Job Posting
[**get_recruiter_job_posting_by_project_id**](LinkedInApi.md#get_recruiter_job_posting_by_project_id) | **GET** /v2/{account_id}/linkedin/recruiter/projects/{project_id}/jobs | Get a Job Posting by Project
[**get_recruiter_job_posting_list**](LinkedInApi.md#get_recruiter_job_posting_list) | **GET** /v2/{account_id}/linkedin/recruiter/jobs | List Job Postings
[**get_recruiter_pipeline_candidates**](LinkedInApi.md#get_recruiter_pipeline_candidates) | **POST** /v2/{account_id}/linkedin/recruiter/projects/{project_id}/pipeline | List Pipeline Candidates
[**get_recruiter_search_parameters**](LinkedInApi.md#get_recruiter_search_parameters) | **GET** /v2/{account_id}/linkedin/recruiter/search/parameters | List Search Parameters
[**get_recruiter_talent_pool_applicants**](LinkedInApi.md#get_recruiter_talent_pool_applicants) | **POST** /v2/{account_id}/linkedin/recruiter/projects/{project_id}/talent-pool/applicants | List Job Posting Applicants
[**get_sales_account_lists**](LinkedInApi.md#get_sales_account_lists) | **GET** /v2/{account_id}/linkedin/sales-navigator/account-lists | Get Accounts Lists
[**get_sales_lead_lists**](LinkedInApi.md#get_sales_lead_lists) | **GET** /v2/{account_id}/linkedin/sales-navigator/lead-lists | Get Leads Lists
[**get_sales_search_parameters**](LinkedInApi.md#get_sales_search_parameters) | **GET** /v2/{account_id}/linkedin/sales-navigator/search/parameters | List Search Parameters
[**list_classic_user_job_postings**](LinkedInApi.md#list_classic_user_job_postings) | **GET** /v2/{account_id}/linkedin/jobs | List User Job Postings
[**perform_classic_companies_search**](LinkedInApi.md#perform_classic_companies_search) | **POST** /v2/{account_id}/linkedin/search/companies | Perform Companies Search
[**perform_classic_jobs_search**](LinkedInApi.md#perform_classic_jobs_search) | **POST** /v2/{account_id}/linkedin/search/jobs | Perform Jobs Search
[**perform_classic_people_search**](LinkedInApi.md#perform_classic_people_search) | **POST** /v2/{account_id}/linkedin/search/people | Perform People Search
[**perform_classic_posts_search**](LinkedInApi.md#perform_classic_posts_search) | **POST** /v2/{account_id}/linkedin/search/posts | Perform Posts Search
[**perform_classic_search_from_url**](LinkedInApi.md#perform_classic_search_from_url) | **POST** /v2/{account_id}/linkedin/search | Perform Classic Search from URL
[**perform_recruiter_people_search**](LinkedInApi.md#perform_recruiter_people_search) | **POST** /v2/{account_id}/linkedin/recruiter/search/people | Perform People Search
[**perform_recruiter_people_search_from_talent_pool**](LinkedInApi.md#perform_recruiter_people_search_from_talent_pool) | **POST** /v2/{account_id}/linkedin/recruiter/projects/{project_id}/talent-pool/search | Perform People Search From Talent Pool
[**perform_recruiter_search_from_url**](LinkedInApi.md#perform_recruiter_search_from_url) | **POST** /v2/{account_id}/linkedin/recruiter/search | Perform Recruiter Search from URL
[**perform_sales_companies_search**](LinkedInApi.md#perform_sales_companies_search) | **POST** /v2/{account_id}/linkedin/sales-navigator/search/companies | Perform Companies Search
[**perform_sales_people_search**](LinkedInApi.md#perform_sales_people_search) | **POST** /v2/{account_id}/linkedin/sales-navigator/search/people | Perform People Search
[**perform_sales_search_from_url**](LinkedInApi.md#perform_sales_search_from_url) | **POST** /v2/{account_id}/linkedin/sales-navigator/search | Perform Search from URL
[**proxy_request**](LinkedInApi.md#proxy_request) | **POST** /v2/{account_id}/linkedin/ | Perform a Request to any LinkedIn API Endpoint
[**publish_classic_job_posting**](LinkedInApi.md#publish_classic_job_posting) | **POST** /v2/{account_id}/linkedin/jobs/{job_id}/publish | Publish a Job Posting
[**publish_recruiter_job_posting**](LinkedInApi.md#publish_recruiter_job_posting) | **POST** /v2/{account_id}/linkedin/recruiter/projects/{project_id}/jobs/{job_id}/publish | Publish a Job Posting
[**save_recruiter_candidate_to_pipeline**](LinkedInApi.md#save_recruiter_candidate_to_pipeline) | **POST** /v2/{account_id}/linkedin/recruiter/projects/{project_id}/pipeline/candidate/save | Save a Candidate
[**save_sales_account_to_list**](LinkedInApi.md#save_sales_account_to_list) | **POST** /v2/{account_id}/linkedin/sales-navigator/account-lists/{list_id}/save | Save an Account To a List
[**save_sales_lead_to_list**](LinkedInApi.md#save_sales_lead_to_list) | **POST** /v2/{account_id}/linkedin/sales-navigator/lead-lists/{list_id}/save | Save a Lead To a List
[**submit_classic_company_otp_code**](LinkedInApi.md#submit_classic_company_otp_code) | **POST** /v2/{account_id}/linkedin/company/{company_id}/member/submit-otp | Submit Otp Verification Code
[**submit_recruiter_otp_code**](LinkedInApi.md#submit_recruiter_otp_code) | **POST** /v2/{account_id}/linkedin/recruiter/company/{company_id}/member/submit-otp | Submit Otp Verification Code
[**verify_classic_company_member_identity**](LinkedInApi.md#verify_classic_company_member_identity) | **POST** /v2/{account_id}/linkedin/company/{company_id}/member/verify-email | Verify Company Member Identity
[**verify_recruiter_company_member_identity**](LinkedInApi.md#verify_recruiter_company_member_identity) | **POST** /v2/{account_id}/linkedin/recruiter/company/{company_id}/member/verify-email | Verify Company Member Identity


# **browse_sales_account_list**
> AccountList browse_sales_account_list(list_id, account_id, offset=offset, limit=limit, browse_sales_account_list_request=browse_sales_account_list_request)

Browse an Account List

Returns the accounts that have been saved in the given list.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.account_list import AccountList
from unipile.models.browse_sales_account_list_request import BrowseSalesAccountListRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    list_id = 'list_id_example' # str | The ID of the list to be browsed.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination. (optional)
    limit = 25 # float | The limit of items to be returned. (optional) (default to 25)
    browse_sales_account_list_request = unipile.BrowseSalesAccountListRequest() # BrowseSalesAccountListRequest |  (optional)

    try:
        # Browse an Account List
        api_response = api_instance.browse_sales_account_list(list_id, account_id, offset=offset, limit=limit, browse_sales_account_list_request=browse_sales_account_list_request)
        print("The response of LinkedInApi->browse_sales_account_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->browse_sales_account_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **list_id** | **str**| The ID of the list to be browsed. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 25]
 **browse_sales_account_list_request** | [**BrowseSalesAccountListRequest**](BrowseSalesAccountListRequest.md)|  | [optional] 

### Return type

[**AccountList**](AccountList.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **browse_sales_lead_list**
> LeadList browse_sales_lead_list(list_id, account_id, offset=offset, limit=limit, browse_sales_lead_list_request=browse_sales_lead_list_request)

Browse a Lead List

Returns the leads that have been saved in the given list.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.browse_sales_lead_list_request import BrowseSalesLeadListRequest
from unipile.models.lead_list import LeadList
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    list_id = 'list_id_example' # str | The ID of the list to be browsed.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination. (optional)
    limit = 25 # float | The limit of items to be returned. (optional) (default to 25)
    browse_sales_lead_list_request = unipile.BrowseSalesLeadListRequest() # BrowseSalesLeadListRequest |  (optional)

    try:
        # Browse a Lead List
        api_response = api_instance.browse_sales_lead_list(list_id, account_id, offset=offset, limit=limit, browse_sales_lead_list_request=browse_sales_lead_list_request)
        print("The response of LinkedInApi->browse_sales_lead_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->browse_sales_lead_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **list_id** | **str**| The ID of the list to be browsed. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 25]
 **browse_sales_lead_list_request** | [**BrowseSalesLeadListRequest**](BrowseSalesLeadListRequest.md)|  | [optional] 

### Return type

[**LeadList**](LeadList.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **close_classic_job_posting**
> CloseClassicJobPosting200Response close_classic_job_posting(job_id, account_id)

Close a Job Posting

Closes a job posting so applications cannot be submitted anymore.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.close_classic_job_posting200_response import CloseClassicJobPosting200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    job_id = 'job_id_example' # str | The ID of the Job to close.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Close a Job Posting
        api_response = api_instance.close_classic_job_posting(job_id, account_id)
        print("The response of LinkedInApi->close_classic_job_posting:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->close_classic_job_posting: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **job_id** | **str**| The ID of the Job to close. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**CloseClassicJobPosting200Response**](CloseClassicJobPosting200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **close_recruiter_job_posting**
> CloseClassicJobPosting200Response close_recruiter_job_posting(project_id, job_id, account_id)

Close a Job Posting

Closes a job posting so applications cannot be submitted anymore.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.close_classic_job_posting200_response import CloseClassicJobPosting200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    project_id = 'project_id_example' # str | The ID of the project associated with the the job.
    job_id = 'job_id_example' # str | The ID of the job to close.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Close a Job Posting
        api_response = api_instance.close_recruiter_job_posting(project_id, job_id, account_id)
        print("The response of LinkedInApi->close_recruiter_job_posting:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->close_recruiter_job_posting: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **project_id** | **str**| The ID of the project associated with the the job. | 
 **job_id** | **str**| The ID of the job to close. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**CloseClassicJobPosting200Response**](CloseClassicJobPosting200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **create_classic_job_posting_draft**
> CreateClassicJobPostingDraft201Response create_classic_job_posting_draft(account_id, create_classic_job_posting_draft_request)

Create a Job Posting Draft

Creates a new job posting as draft.
      <br/>
      Use <a href="https://developer.unipile.com/v2.0/reference/post_v2-account-id-linkedin-jobs-job-id-publish">Publish a Job Posting Draft</a> to publish the job once you are ready.
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_classic_job_posting_draft201_response import CreateClassicJobPostingDraft201Response
from unipile.models.create_classic_job_posting_draft_request import CreateClassicJobPostingDraftRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    create_classic_job_posting_draft_request = unipile.CreateClassicJobPostingDraftRequest() # CreateClassicJobPostingDraftRequest | 

    try:
        # Create a Job Posting Draft
        api_response = api_instance.create_classic_job_posting_draft(account_id, create_classic_job_posting_draft_request)
        print("The response of LinkedInApi->create_classic_job_posting_draft:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->create_classic_job_posting_draft: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **create_classic_job_posting_draft_request** | [**CreateClassicJobPostingDraftRequest**](CreateClassicJobPostingDraftRequest.md)|  | 

### Return type

[**CreateClassicJobPostingDraft201Response**](CreateClassicJobPostingDraft201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **create_recruiter_hiring_project**
> CreateRecruiterHiringProject201Response create_recruiter_hiring_project(account_id, create_recruiter_hiring_project_request)

Create a New Project

Creates a new project in the current contract.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_recruiter_hiring_project201_response import CreateRecruiterHiringProject201Response
from unipile.models.create_recruiter_hiring_project_request import CreateRecruiterHiringProjectRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    create_recruiter_hiring_project_request = unipile.CreateRecruiterHiringProjectRequest() # CreateRecruiterHiringProjectRequest | 

    try:
        # Create a New Project
        api_response = api_instance.create_recruiter_hiring_project(account_id, create_recruiter_hiring_project_request)
        print("The response of LinkedInApi->create_recruiter_hiring_project:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->create_recruiter_hiring_project: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **create_recruiter_hiring_project_request** | [**CreateRecruiterHiringProjectRequest**](CreateRecruiterHiringProjectRequest.md)|  | 

### Return type

[**CreateRecruiterHiringProject201Response**](CreateRecruiterHiringProject201Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**201** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **create_recruiter_job_posting_draft_in_existing_project**
> CreateRecruiterJobPostingDraftInExistingProject200Response create_recruiter_job_posting_draft_in_existing_project(project_id, account_id, create_recruiter_job_posting_draft_in_existing_project_request)

Create a Job Posting Draft in an Existing Project

Creates a new job posting as draft in a new project.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_recruiter_job_posting_draft_in_existing_project200_response import CreateRecruiterJobPostingDraftInExistingProject200Response
from unipile.models.create_recruiter_job_posting_draft_in_existing_project_request import CreateRecruiterJobPostingDraftInExistingProjectRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    project_id = 'project_id_example' # str | The ID of the project in which to create the job posting.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    create_recruiter_job_posting_draft_in_existing_project_request = unipile.CreateRecruiterJobPostingDraftInExistingProjectRequest() # CreateRecruiterJobPostingDraftInExistingProjectRequest | 

    try:
        # Create a Job Posting Draft in an Existing Project
        api_response = api_instance.create_recruiter_job_posting_draft_in_existing_project(project_id, account_id, create_recruiter_job_posting_draft_in_existing_project_request)
        print("The response of LinkedInApi->create_recruiter_job_posting_draft_in_existing_project:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->create_recruiter_job_posting_draft_in_existing_project: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **project_id** | **str**| The ID of the project in which to create the job posting. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **create_recruiter_job_posting_draft_in_existing_project_request** | [**CreateRecruiterJobPostingDraftInExistingProjectRequest**](CreateRecruiterJobPostingDraftInExistingProjectRequest.md)|  | 

### Return type

[**CreateRecruiterJobPostingDraftInExistingProject200Response**](CreateRecruiterJobPostingDraftInExistingProject200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **create_recruiter_job_posting_draft_in_new_project**
> CreateRecruiterJobPostingDraftInExistingProject200Response create_recruiter_job_posting_draft_in_new_project(account_id, create_recruiter_job_posting_draft_in_new_project_request)

Create a Job Posting Draft in a New Project

Creates a new job posting as draft in a new project.
      <br/>
      Use <a href="https://developer.unipile.com/v2.0/reference/post_v2-account-id-linkedin-recruiter-projects-project-id-jobs-job-id-publish">Publish a Job Posting Draft</a> to publish the job once you are ready.
      

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_recruiter_job_posting_draft_in_existing_project200_response import CreateRecruiterJobPostingDraftInExistingProject200Response
from unipile.models.create_recruiter_job_posting_draft_in_new_project_request import CreateRecruiterJobPostingDraftInNewProjectRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    create_recruiter_job_posting_draft_in_new_project_request = unipile.CreateRecruiterJobPostingDraftInNewProjectRequest() # CreateRecruiterJobPostingDraftInNewProjectRequest | 

    try:
        # Create a Job Posting Draft in a New Project
        api_response = api_instance.create_recruiter_job_posting_draft_in_new_project(account_id, create_recruiter_job_posting_draft_in_new_project_request)
        print("The response of LinkedInApi->create_recruiter_job_posting_draft_in_new_project:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->create_recruiter_job_posting_draft_in_new_project: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **create_recruiter_job_posting_draft_in_new_project_request** | [**CreateRecruiterJobPostingDraftInNewProjectRequest**](CreateRecruiterJobPostingDraftInNewProjectRequest.md)|  | 

### Return type

[**CreateRecruiterJobPostingDraftInExistingProject200Response**](CreateRecruiterJobPostingDraftInExistingProject200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **edit_classic_job_posting**
> EditClassicJobPosting200Response edit_classic_job_posting(job_id, account_id, edit_classic_job_posting_request=edit_classic_job_posting_request)

Edit an existing Job Posting

Edits a job posting created by the current user.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.edit_classic_job_posting200_response import EditClassicJobPosting200Response
from unipile.models.edit_classic_job_posting_request import EditClassicJobPostingRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    job_id = 'job_id_example' # str | The ID of the Job to be edited.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    edit_classic_job_posting_request = unipile.EditClassicJobPostingRequest() # EditClassicJobPostingRequest |  (optional)

    try:
        # Edit an existing Job Posting
        api_response = api_instance.edit_classic_job_posting(job_id, account_id, edit_classic_job_posting_request=edit_classic_job_posting_request)
        print("The response of LinkedInApi->edit_classic_job_posting:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->edit_classic_job_posting: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **job_id** | **str**| The ID of the Job to be edited. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **edit_classic_job_posting_request** | [**EditClassicJobPostingRequest**](EditClassicJobPostingRequest.md)|  | [optional] 

### Return type

[**EditClassicJobPosting200Response**](EditClassicJobPosting200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **edit_recruiter_hiring_project**
> EditRecruiterHiringProject200Response edit_recruiter_hiring_project(project_id, account_id, edit_recruiter_hiring_project_request=edit_recruiter_hiring_project_request)

Edit a Project

Edits the specified hiring project.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.edit_recruiter_hiring_project200_response import EditRecruiterHiringProject200Response
from unipile.models.edit_recruiter_hiring_project_request import EditRecruiterHiringProjectRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    project_id = 'project_id_example' # str | The ID of the project to be edited.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    edit_recruiter_hiring_project_request = unipile.EditRecruiterHiringProjectRequest() # EditRecruiterHiringProjectRequest |  (optional)

    try:
        # Edit a Project
        api_response = api_instance.edit_recruiter_hiring_project(project_id, account_id, edit_recruiter_hiring_project_request=edit_recruiter_hiring_project_request)
        print("The response of LinkedInApi->edit_recruiter_hiring_project:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->edit_recruiter_hiring_project: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **project_id** | **str**| The ID of the project to be edited. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **edit_recruiter_hiring_project_request** | [**EditRecruiterHiringProjectRequest**](EditRecruiterHiringProjectRequest.md)|  | [optional] 

### Return type

[**EditRecruiterHiringProject200Response**](EditRecruiterHiringProject200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **edit_recruiter_job_posting**
> EditClassicJobPosting200Response edit_recruiter_job_posting(project_id, job_id, account_id, edit_recruiter_job_posting_request=edit_recruiter_job_posting_request)

Edit an Existing Job Posting

Edits an existing job posting from a project.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.edit_classic_job_posting200_response import EditClassicJobPosting200Response
from unipile.models.edit_recruiter_job_posting_request import EditRecruiterJobPostingRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    project_id = 'project_id_example' # str | The ID of the project associated with the the job.
    job_id = 'job_id_example' # str | The ID of the job to be edited.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    edit_recruiter_job_posting_request = unipile.EditRecruiterJobPostingRequest() # EditRecruiterJobPostingRequest |  (optional)

    try:
        # Edit an Existing Job Posting
        api_response = api_instance.edit_recruiter_job_posting(project_id, job_id, account_id, edit_recruiter_job_posting_request=edit_recruiter_job_posting_request)
        print("The response of LinkedInApi->edit_recruiter_job_posting:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->edit_recruiter_job_posting: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **project_id** | **str**| The ID of the project associated with the the job. | 
 **job_id** | **str**| The ID of the job to be edited. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **edit_recruiter_job_posting_request** | [**EditRecruiterJobPostingRequest**](EditRecruiterJobPostingRequest.md)|  | [optional] 

### Return type

[**EditClassicJobPosting200Response**](EditClassicJobPosting200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_classic_applicant_by_id**
> GetClassicApplicantById200Response get_classic_applicant_by_id(job_id, applicant_id, account_id)

Get an Applicant

Retrieves an applicant by ID.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_classic_applicant_by_id200_response import GetClassicApplicantById200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    job_id = 'job_id_example' # str | The ID of the Job the Applicant applied to.
    applicant_id = 'applicant_id_example' # str | The ID of the Applicant.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get an Applicant
        api_response = api_instance.get_classic_applicant_by_id(job_id, applicant_id, account_id)
        print("The response of LinkedInApi->get_classic_applicant_by_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_classic_applicant_by_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **job_id** | **str**| The ID of the Job the Applicant applied to. | 
 **applicant_id** | **str**| The ID of the Applicant. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**GetClassicApplicantById200Response**](GetClassicApplicantById200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_classic_applicant_resume**
> get_classic_applicant_resume(job_id, applicant_id, account_id)

Get an Applicant's Resume

Downloads the resume of a given applicant.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    job_id = 'job_id_example' # str | The ID of the Job the Applicant applied to.
    applicant_id = 'applicant_id_example' # str | The ID of the Applicant for which to get the resume.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get an Applicant's Resume
        api_instance.get_classic_applicant_resume(job_id, applicant_id, account_id)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_classic_applicant_resume: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **job_id** | **str**| The ID of the Job the Applicant applied to. | 
 **applicant_id** | **str**| The ID of the Applicant for which to get the resume. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

void (empty response body)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_classic_applicants**
> GetClassicApplicants200Response get_classic_applicants(job_id, account_id, offset=offset, limit=limit, get_classic_applicants_request=get_classic_applicants_request)

List Job Posting Applicants

Returns a list of the applicants to a job posting.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_classic_applicants200_response import GetClassicApplicants200Response
from unipile.models.get_classic_applicants_request import GetClassicApplicantsRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    job_id = 'job_id_example' # str | The ID of the Job for which to retrieve the applicants.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    get_classic_applicants_request = unipile.GetClassicApplicantsRequest() # GetClassicApplicantsRequest |  (optional)

    try:
        # List Job Posting Applicants
        api_response = api_instance.get_classic_applicants(job_id, account_id, offset=offset, limit=limit, get_classic_applicants_request=get_classic_applicants_request)
        print("The response of LinkedInApi->get_classic_applicants:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_classic_applicants: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **job_id** | **str**| The ID of the Job for which to retrieve the applicants. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **get_classic_applicants_request** | [**GetClassicApplicantsRequest**](GetClassicApplicantsRequest.md)|  | [optional] 

### Return type

[**GetClassicApplicants200Response**](GetClassicApplicants200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_classic_company_profile**
> GetClassicCompanyProfile200Response get_classic_company_profile(company_id, account_id)

Get a Company Profile

Retrieves the specified company profile.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_classic_company_profile200_response import GetClassicCompanyProfile200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    company_id = 'company_id_example' # str | The ID of the company to retrieve the profile of.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get a Company Profile
        api_response = api_instance.get_classic_company_profile(company_id, account_id)
        print("The response of LinkedInApi->get_classic_company_profile:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_classic_company_profile: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **company_id** | **str**| The ID of the company to retrieve the profile of. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**GetClassicCompanyProfile200Response**](GetClassicCompanyProfile200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_classic_job_posting**
> GetClassicJobPosting200Response get_classic_job_posting(job_id, account_id, description_format=description_format, with_sections=with_sections)

Get a Job Posting

Retrieves a job posting by its ID.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_classic_job_posting200_response import GetClassicJobPosting200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    job_id = 'job_id_example' # str | The ID of the Job to be retrieved.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    description_format = raw_text # str | The format of the job description. (optional) (default to raw_text)
    with_sections = ['with_sections_example'] # List[str] | Sections that should be included with the job posting. (optional)

    try:
        # Get a Job Posting
        api_response = api_instance.get_classic_job_posting(job_id, account_id, description_format=description_format, with_sections=with_sections)
        print("The response of LinkedInApi->get_classic_job_posting:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_classic_job_posting: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **job_id** | **str**| The ID of the Job to be retrieved. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **description_format** | **str**| The format of the job description. | [optional] [default to raw_text]
 **with_sections** | [**List[str]**](str.md)| Sections that should be included with the job posting. | [optional] 

### Return type

[**GetClassicJobPosting200Response**](GetClassicJobPosting200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_classic_job_posting_budget**
> GetClassicJobPostingBudget200Response get_classic_job_posting_budget(job_id, account_id)

Get the Budget for a Job Posting

Returns available budget ranges, recommended budgets, and estimated impact.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_classic_job_posting_budget200_response import GetClassicJobPostingBudget200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    job_id = 'job_id_example' # str | The ID of the Job to get the budget of.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get the Budget for a Job Posting
        api_response = api_instance.get_classic_job_posting_budget(job_id, account_id)
        print("The response of LinkedInApi->get_classic_job_posting_budget:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_classic_job_posting_budget: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **job_id** | **str**| The ID of the Job to get the budget of. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**GetClassicJobPostingBudget200Response**](GetClassicJobPostingBudget200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_classic_search_parameters**
> GetClassicSearchParameters200Response get_classic_search_parameters(type, keywords, account_id, offset=offset, limit=limit)

List Search Parameters

Returns a list of parameters to be used in the search route.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_classic_search_parameters200_response import GetClassicSearchParameters200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    type = 'type_example' # str | The type of search parameter.
    keywords = 'keywords_example' # str | A keyword or group of keywords to filter results.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination. (optional)
    limit = 10 # float | The limit of items to be returned. (optional) (default to 10)

    try:
        # List Search Parameters
        api_response = api_instance.get_classic_search_parameters(type, keywords, account_id, offset=offset, limit=limit)
        print("The response of LinkedInApi->get_classic_search_parameters:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_classic_search_parameters: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **type** | **str**| The type of search parameter. | 
 **keywords** | **str**| A keyword or group of keywords to filter results. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 10]

### Return type

[**GetClassicSearchParameters200Response**](GetClassicSearchParameters200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_inmail_credits**
> GetInmailCredits200Response get_inmail_credits(account_id, service=service)

Get InMail Credits

Retrieves InMail credits by service or for all subscribed services.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_inmail_credits200_response import GetInmailCredits200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    service = 'service_example' # str | The targeted LinkedIn service. Leave blank to retrieve all credit statements for subscribed services. (optional)

    try:
        # Get InMail Credits
        api_response = api_instance.get_inmail_credits(account_id, service=service)
        print("The response of LinkedInApi->get_inmail_credits:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_inmail_credits: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **service** | **str**| The targeted LinkedIn service. Leave blank to retrieve all credit statements for subscribed services. | [optional] 

### Return type

[**GetInmailCredits200Response**](GetInmailCredits200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_recruiter_applicant_by_id**
> ApplicantsSearchDataInner get_recruiter_applicant_by_id(project_id, applicant_id, account_id)

Get an Applicant

Retrieves an applicant by ID.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.applicants_search_data_inner import ApplicantsSearchDataInner
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    project_id = 'project_id_example' # str | The ID of the Hiring Project from which to browse the Talent Pool.
    applicant_id = 'applicant_id_example' # str | The Profile ID of the Applicant.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get an Applicant
        api_response = api_instance.get_recruiter_applicant_by_id(project_id, applicant_id, account_id)
        print("The response of LinkedInApi->get_recruiter_applicant_by_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_recruiter_applicant_by_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **project_id** | **str**| The ID of the Hiring Project from which to browse the Talent Pool. | 
 **applicant_id** | **str**| The Profile ID of the Applicant. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**ApplicantsSearchDataInner**](ApplicantsSearchDataInner.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_recruiter_applicant_resume**
> get_recruiter_applicant_resume(project_id, applicant_id, account_id)

Get an Applicant's Resume

Downloads the resume of a given applicant.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    project_id = 'project_id_example' # str | The ID of the Hiring Project from which to browse the Talent Pool.
    applicant_id = 'applicant_id_example' # str | The Profile ID of the Applicant for which the get the resume.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get an Applicant's Resume
        api_instance.get_recruiter_applicant_resume(project_id, applicant_id, account_id)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_recruiter_applicant_resume: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **project_id** | **str**| The ID of the Hiring Project from which to browse the Talent Pool. | 
 **applicant_id** | **str**| The Profile ID of the Applicant for which the get the resume. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

void (empty response body)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_recruiter_hiring_project**
> GetRecruiterHiringProject200Response get_recruiter_hiring_project(project_id, account_id)

Get a Project

Retrieves the specified hiring project.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_recruiter_hiring_project200_response import GetRecruiterHiringProject200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    project_id = 'project_id_example' # str | The ID of the Hiring Project to be retrieved.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get a Project
        api_response = api_instance.get_recruiter_hiring_project(project_id, account_id)
        print("The response of LinkedInApi->get_recruiter_hiring_project:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_recruiter_hiring_project: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **project_id** | **str**| The ID of the Hiring Project to be retrieved. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**GetRecruiterHiringProject200Response**](GetRecruiterHiringProject200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_recruiter_hiring_project_list**
> GetRecruiterHiringProjectList200Response get_recruiter_hiring_project_list(account_id, status=status, keywords=keywords, offset=offset, limit=limit)

List Projects

Returns a list of hiring projects created in the current contract scope.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_recruiter_hiring_project_list200_response import GetRecruiterHiringProjectList200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    status = ['status_example'] # List[str] | A list of statuses that the job posting of the project must match. (optional)
    keywords = 'keywords_example' # str | A keyword or group of keywords to filter projects by name. (optional)
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)

    try:
        # List Projects
        api_response = api_instance.get_recruiter_hiring_project_list(account_id, status=status, keywords=keywords, offset=offset, limit=limit)
        print("The response of LinkedInApi->get_recruiter_hiring_project_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_recruiter_hiring_project_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **status** | [**List[str]**](str.md)| A list of statuses that the job posting of the project must match. | [optional] 
 **keywords** | **str**| A keyword or group of keywords to filter projects by name. | [optional] 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]

### Return type

[**GetRecruiterHiringProjectList200Response**](GetRecruiterHiringProjectList200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_recruiter_job_posting_budget**
> GetRecruiterJobPostingBudget200Response get_recruiter_job_posting_budget(project_id, job_id, account_id)

Get the Budget for a Job Posting

Returns available budget ranges, recommended budgets, and estimated impact.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_recruiter_job_posting_budget200_response import GetRecruiterJobPostingBudget200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    project_id = 'project_id_example' # str | The ID of the project associated with the the job.
    job_id = 'job_id_example' # str | The ID of the job to get the budget of.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get the Budget for a Job Posting
        api_response = api_instance.get_recruiter_job_posting_budget(project_id, job_id, account_id)
        print("The response of LinkedInApi->get_recruiter_job_posting_budget:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_recruiter_job_posting_budget: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **project_id** | **str**| The ID of the project associated with the the job. | 
 **job_id** | **str**| The ID of the job to get the budget of. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**GetRecruiterJobPostingBudget200Response**](GetRecruiterJobPostingBudget200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_recruiter_job_posting_by_id**
> GetRecruiterJobPostingByProjectId200Response get_recruiter_job_posting_by_id(job_id, account_id)

Get a Job Posting

Retrieves a job posting by its ID.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_recruiter_job_posting_by_project_id200_response import GetRecruiterJobPostingByProjectId200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    job_id = 'job_id_example' # str | The ID of the job to be retrieved.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get a Job Posting
        api_response = api_instance.get_recruiter_job_posting_by_id(job_id, account_id)
        print("The response of LinkedInApi->get_recruiter_job_posting_by_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_recruiter_job_posting_by_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **job_id** | **str**| The ID of the job to be retrieved. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**GetRecruiterJobPostingByProjectId200Response**](GetRecruiterJobPostingByProjectId200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_recruiter_job_posting_by_project_id**
> GetRecruiterJobPostingByProjectId200Response get_recruiter_job_posting_by_project_id(project_id, account_id)

Get a Job Posting by Project

Retrieves a job posting by project.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_recruiter_job_posting_by_project_id200_response import GetRecruiterJobPostingByProjectId200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    project_id = 'project_id_example' # str | The ID of the project associated with the the job.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get a Job Posting by Project
        api_response = api_instance.get_recruiter_job_posting_by_project_id(project_id, account_id)
        print("The response of LinkedInApi->get_recruiter_job_posting_by_project_id:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_recruiter_job_posting_by_project_id: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **project_id** | **str**| The ID of the project associated with the the job. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**GetRecruiterJobPostingByProjectId200Response**](GetRecruiterJobPostingByProjectId200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_recruiter_job_posting_list**
> GetRecruiterJobPostingList200Response get_recruiter_job_posting_list(account_id, state=state, sort_by=sort_by, location=location, job_poster=job_poster, contract=contract, workplace_type=workplace_type, offset=offset, limit=limit)

List Job Postings

Returns a list of job postings created by the current user or related job posters.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_recruiter_job_posting_list200_response import GetRecruiterJobPostingList200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    state = ['state_example'] # List[str] | A list of job posting states. (optional)
    sort_by = LAST_ACCESS_TIME # str | The sort method.    Native filter : Sort by    (optional) (default to LAST_ACCESS_TIME)
    location = ['location_example'] # List[str] | A list of parameter IDs. Use <a href=\"https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\">List Search Parameters</a> with `LOCATION` type to find out the possible values.    Native filter : Location    (optional)
    job_poster = ['job_poster_example'] # List[str] | A list of parameter IDs. Use <a href=\"https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\">List Search Parameters</a> with `SEAT` type to find out the possible values.    Native filter : Job poster    (optional)
    contract = ['contract_example'] # List[str] | A list of parameter IDs. Use <a href=\"https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\">List Search Parameters</a> with `CONTRACT` type to find out the possible values.    Native filter : Contract    (optional)
    workplace_type = ['workplace_type_example'] # List[str] |  (optional)
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)

    try:
        # List Job Postings
        api_response = api_instance.get_recruiter_job_posting_list(account_id, state=state, sort_by=sort_by, location=location, job_poster=job_poster, contract=contract, workplace_type=workplace_type, offset=offset, limit=limit)
        print("The response of LinkedInApi->get_recruiter_job_posting_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_recruiter_job_posting_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **state** | [**List[str]**](str.md)| A list of job posting states. | [optional] 
 **sort_by** | **str**| The sort method.    Native filter : Sort by    | [optional] [default to LAST_ACCESS_TIME]
 **location** | [**List[str]**](str.md)| A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;LOCATION&#x60; type to find out the possible values.    Native filter : Location    | [optional] 
 **job_poster** | [**List[str]**](str.md)| A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;SEAT&#x60; type to find out the possible values.    Native filter : Job poster    | [optional] 
 **contract** | [**List[str]**](str.md)| A list of parameter IDs. Use &lt;a href&#x3D;\&quot;https://developer.unipile.com/v2.0/reference/get_v2-account-id-linkedin-recruiter-search-parameters\&quot;&gt;List Search Parameters&lt;/a&gt; with &#x60;CONTRACT&#x60; type to find out the possible values.    Native filter : Contract    | [optional] 
 **workplace_type** | [**List[str]**](str.md)|  | [optional] 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]

### Return type

[**GetRecruiterJobPostingList200Response**](GetRecruiterJobPostingList200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_recruiter_pipeline_candidates**
> PipelineCandidatesSearch get_recruiter_pipeline_candidates(project_id, account_id, offset=offset, limit=limit, get_recruiter_pipeline_candidates_request=get_recruiter_pipeline_candidates_request)

List Pipeline Candidates

Returns a list of candidates from the pipeline of a project.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_recruiter_pipeline_candidates_request import GetRecruiterPipelineCandidatesRequest
from unipile.models.pipeline_candidates_search import PipelineCandidatesSearch
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    project_id = 'project_id_example' # str | The ID of the Hiring Project from which to browse the Pipeline.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    get_recruiter_pipeline_candidates_request = unipile.GetRecruiterPipelineCandidatesRequest() # GetRecruiterPipelineCandidatesRequest |  (optional)

    try:
        # List Pipeline Candidates
        api_response = api_instance.get_recruiter_pipeline_candidates(project_id, account_id, offset=offset, limit=limit, get_recruiter_pipeline_candidates_request=get_recruiter_pipeline_candidates_request)
        print("The response of LinkedInApi->get_recruiter_pipeline_candidates:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_recruiter_pipeline_candidates: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **project_id** | **str**| The ID of the Hiring Project from which to browse the Pipeline. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **get_recruiter_pipeline_candidates_request** | [**GetRecruiterPipelineCandidatesRequest**](GetRecruiterPipelineCandidatesRequest.md)|  | [optional] 

### Return type

[**PipelineCandidatesSearch**](PipelineCandidatesSearch.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_recruiter_search_parameters**
> GetClassicSearchParameters200Response get_recruiter_search_parameters(source, project_id, channel_id, type, account_id, keywords=keywords, stage_id=stage_id, offset=offset, limit=limit)

List Search Parameters

Returns a list of parameters to be used in Recruiter search endpoints.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_classic_search_parameters200_response import GetClassicSearchParameters200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    source = 'source_example' # str | 
    project_id = 'project_id_example' # str | The ID of the Project the Pipeline belongs to.
    channel_id = 'channel_id_example' # str | In Talent Pool context, the ID of the JOB_POSTING Channel to get parameters from.
    type = 'type_example' # str | The type of search parameter.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    keywords = 'keywords_example' # str | A keyword or group of keywords to filter results. (optional)
    stage_id = 'stage_id_example' # str | In Pipeline context, the ID of the Stage to get parameters from. Leave undefined to get results from all stages. (optional)
    offset = 3.4 # float | An offset used for pagination. (optional)
    limit = 10 # float | The limit of items to be returned. (optional) (default to 10)

    try:
        # List Search Parameters
        api_response = api_instance.get_recruiter_search_parameters(source, project_id, channel_id, type, account_id, keywords=keywords, stage_id=stage_id, offset=offset, limit=limit)
        print("The response of LinkedInApi->get_recruiter_search_parameters:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_recruiter_search_parameters: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **source** | **str**|  | 
 **project_id** | **str**| The ID of the Project the Pipeline belongs to. | 
 **channel_id** | **str**| In Talent Pool context, the ID of the JOB_POSTING Channel to get parameters from. | 
 **type** | **str**| The type of search parameter. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **keywords** | **str**| A keyword or group of keywords to filter results. | [optional] 
 **stage_id** | **str**| In Pipeline context, the ID of the Stage to get parameters from. Leave undefined to get results from all stages. | [optional] 
 **offset** | **float**| An offset used for pagination. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 10]

### Return type

[**GetClassicSearchParameters200Response**](GetClassicSearchParameters200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_recruiter_talent_pool_applicants**
> ApplicantsSearch get_recruiter_talent_pool_applicants(project_id, account_id, get_recruiter_talent_pool_applicants_request, offset=offset, limit=limit)

List Job Posting Applicants

Returns a list of applicants from the talent pool of a project.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.applicants_search import ApplicantsSearch
from unipile.models.get_recruiter_talent_pool_applicants_request import GetRecruiterTalentPoolApplicantsRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    project_id = 'project_id_example' # str | The ID of the Hiring Project from which to browse the Talent Pool.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    get_recruiter_talent_pool_applicants_request = unipile.GetRecruiterTalentPoolApplicantsRequest() # GetRecruiterTalentPoolApplicantsRequest | 
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)

    try:
        # List Job Posting Applicants
        api_response = api_instance.get_recruiter_talent_pool_applicants(project_id, account_id, get_recruiter_talent_pool_applicants_request, offset=offset, limit=limit)
        print("The response of LinkedInApi->get_recruiter_talent_pool_applicants:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_recruiter_talent_pool_applicants: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **project_id** | **str**| The ID of the Hiring Project from which to browse the Talent Pool. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **get_recruiter_talent_pool_applicants_request** | [**GetRecruiterTalentPoolApplicantsRequest**](GetRecruiterTalentPoolApplicantsRequest.md)|  | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]

### Return type

[**ApplicantsSearch**](ApplicantsSearch.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_sales_account_lists**
> GetSalesAccountLists200Response get_sales_account_lists(account_id, offset=offset, limit=limit)

Get Accounts Lists

Returns your accounts lists.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_sales_account_lists200_response import GetSalesAccountLists200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination. (optional)
    limit = 25 # float | The limit of items to be returned. (optional) (default to 25)

    try:
        # Get Accounts Lists
        api_response = api_instance.get_sales_account_lists(account_id, offset=offset, limit=limit)
        print("The response of LinkedInApi->get_sales_account_lists:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_sales_account_lists: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 25]

### Return type

[**GetSalesAccountLists200Response**](GetSalesAccountLists200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_sales_lead_lists**
> GetSalesLeadLists200Response get_sales_lead_lists(account_id, offset=offset, limit=limit)

Get Leads Lists

Returns your leads lists.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_sales_lead_lists200_response import GetSalesLeadLists200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination. (optional)
    limit = 25 # float | The limit of items to be returned. (optional) (default to 25)

    try:
        # Get Leads Lists
        api_response = api_instance.get_sales_lead_lists(account_id, offset=offset, limit=limit)
        print("The response of LinkedInApi->get_sales_lead_lists:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_sales_lead_lists: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 25]

### Return type

[**GetSalesLeadLists200Response**](GetSalesLeadLists200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_sales_search_parameters**
> GetClassicSearchParameters200Response get_sales_search_parameters(type, account_id, keywords=keywords, offset=offset, limit=limit)

List Search Parameters

Returns a list of parameters to be used in Sales navigator search endpoints.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_classic_search_parameters200_response import GetClassicSearchParameters200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    type = 'type_example' # str | The type of search parameter.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    keywords = 'keywords_example' # str | A keyword or group of keywords to filter results. (optional)
    offset = 3.4 # float | An offset used for pagination. (optional)
    limit = 10 # float | The limit of items to be returned. (optional) (default to 10)

    try:
        # List Search Parameters
        api_response = api_instance.get_sales_search_parameters(type, account_id, keywords=keywords, offset=offset, limit=limit)
        print("The response of LinkedInApi->get_sales_search_parameters:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->get_sales_search_parameters: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **type** | **str**| The type of search parameter. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **keywords** | **str**| A keyword or group of keywords to filter results. | [optional] 
 **offset** | **float**| An offset used for pagination. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 10]

### Return type

[**GetClassicSearchParameters200Response**](GetClassicSearchParameters200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **list_classic_user_job_postings**
> ListClassicUserJobPostings200Response list_classic_user_job_postings(state, account_id, offset=offset, limit=limit)

List User Job Postings

Returns a list of job postings created by the current user.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.list_classic_user_job_postings200_response import ListClassicUserJobPostings200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    state = 'state_example' # str | A list of Job posting states.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)

    try:
        # List User Job Postings
        api_response = api_instance.list_classic_user_job_postings(state, account_id, offset=offset, limit=limit)
        print("The response of LinkedInApi->list_classic_user_job_postings:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->list_classic_user_job_postings: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **state** | **str**| A list of Job posting states. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]

### Return type

[**ListClassicUserJobPostings200Response**](ListClassicUserJobPostings200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **perform_classic_companies_search**
> PerformClassicSearchFromUrl200ResponseAnyOf3 perform_classic_companies_search(account_id, offset=offset, limit=limit, perform_classic_companies_search_request=perform_classic_companies_search_request)

Perform Companies Search

Returns a list of companies from search results.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.perform_classic_companies_search_request import PerformClassicCompaniesSearchRequest
from unipile.models.perform_classic_search_from_url200_response_any_of3 import PerformClassicSearchFromUrl200ResponseAnyOf3
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    perform_classic_companies_search_request = unipile.PerformClassicCompaniesSearchRequest() # PerformClassicCompaniesSearchRequest |  (optional)

    try:
        # Perform Companies Search
        api_response = api_instance.perform_classic_companies_search(account_id, offset=offset, limit=limit, perform_classic_companies_search_request=perform_classic_companies_search_request)
        print("The response of LinkedInApi->perform_classic_companies_search:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->perform_classic_companies_search: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **perform_classic_companies_search_request** | [**PerformClassicCompaniesSearchRequest**](PerformClassicCompaniesSearchRequest.md)|  | [optional] 

### Return type

[**PerformClassicSearchFromUrl200ResponseAnyOf3**](PerformClassicSearchFromUrl200ResponseAnyOf3.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **perform_classic_jobs_search**
> PerformClassicJobsSearch200Response perform_classic_jobs_search(account_id, offset=offset, limit=limit, perform_classic_jobs_search_request=perform_classic_jobs_search_request)

Perform Jobs Search

Returns a list of job postings from search results.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.perform_classic_jobs_search200_response import PerformClassicJobsSearch200Response
from unipile.models.perform_classic_jobs_search_request import PerformClassicJobsSearchRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    perform_classic_jobs_search_request = unipile.PerformClassicJobsSearchRequest() # PerformClassicJobsSearchRequest |  (optional)

    try:
        # Perform Jobs Search
        api_response = api_instance.perform_classic_jobs_search(account_id, offset=offset, limit=limit, perform_classic_jobs_search_request=perform_classic_jobs_search_request)
        print("The response of LinkedInApi->perform_classic_jobs_search:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->perform_classic_jobs_search: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **perform_classic_jobs_search_request** | [**PerformClassicJobsSearchRequest**](PerformClassicJobsSearchRequest.md)|  | [optional] 

### Return type

[**PerformClassicJobsSearch200Response**](PerformClassicJobsSearch200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **perform_classic_people_search**
> PerformClassicSearchFromUrl200ResponseAnyOf2 perform_classic_people_search(account_id, offset=offset, limit=limit, perform_classic_people_search_request=perform_classic_people_search_request)

Perform People Search

Returns a list of people from search results.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.perform_classic_people_search_request import PerformClassicPeopleSearchRequest
from unipile.models.perform_classic_search_from_url200_response_any_of2 import PerformClassicSearchFromUrl200ResponseAnyOf2
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    perform_classic_people_search_request = unipile.PerformClassicPeopleSearchRequest() # PerformClassicPeopleSearchRequest |  (optional)

    try:
        # Perform People Search
        api_response = api_instance.perform_classic_people_search(account_id, offset=offset, limit=limit, perform_classic_people_search_request=perform_classic_people_search_request)
        print("The response of LinkedInApi->perform_classic_people_search:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->perform_classic_people_search: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **perform_classic_people_search_request** | [**PerformClassicPeopleSearchRequest**](PerformClassicPeopleSearchRequest.md)|  | [optional] 

### Return type

[**PerformClassicSearchFromUrl200ResponseAnyOf2**](PerformClassicSearchFromUrl200ResponseAnyOf2.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **perform_classic_posts_search**
> PerformClassicSearchFromUrl200ResponseAnyOf1 perform_classic_posts_search(account_id, offset=offset, limit=limit, perform_classic_posts_search_request=perform_classic_posts_search_request)

Perform Posts Search

Returns a list of posts from search results.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.perform_classic_posts_search_request import PerformClassicPostsSearchRequest
from unipile.models.perform_classic_search_from_url200_response_any_of1 import PerformClassicSearchFromUrl200ResponseAnyOf1
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    perform_classic_posts_search_request = unipile.PerformClassicPostsSearchRequest() # PerformClassicPostsSearchRequest |  (optional)

    try:
        # Perform Posts Search
        api_response = api_instance.perform_classic_posts_search(account_id, offset=offset, limit=limit, perform_classic_posts_search_request=perform_classic_posts_search_request)
        print("The response of LinkedInApi->perform_classic_posts_search:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->perform_classic_posts_search: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **perform_classic_posts_search_request** | [**PerformClassicPostsSearchRequest**](PerformClassicPostsSearchRequest.md)|  | [optional] 

### Return type

[**PerformClassicSearchFromUrl200ResponseAnyOf1**](PerformClassicSearchFromUrl200ResponseAnyOf1.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **perform_classic_search_from_url**
> PerformClassicSearchFromUrl200Response perform_classic_search_from_url(account_id, perform_classic_search_from_url_request, offset=offset, limit=limit)

Perform Classic Search from URL

Returns a list of results from a LinkedIn Classic search URL.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.perform_classic_search_from_url200_response import PerformClassicSearchFromUrl200Response
from unipile.models.perform_classic_search_from_url_request import PerformClassicSearchFromUrlRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    perform_classic_search_from_url_request = unipile.PerformClassicSearchFromUrlRequest() # PerformClassicSearchFromUrlRequest | 
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)

    try:
        # Perform Classic Search from URL
        api_response = api_instance.perform_classic_search_from_url(account_id, perform_classic_search_from_url_request, offset=offset, limit=limit)
        print("The response of LinkedInApi->perform_classic_search_from_url:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->perform_classic_search_from_url: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **perform_classic_search_from_url_request** | [**PerformClassicSearchFromUrlRequest**](PerformClassicSearchFromUrlRequest.md)|  | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]

### Return type

[**PerformClassicSearchFromUrl200Response**](PerformClassicSearchFromUrl200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **perform_recruiter_people_search**
> PeopleSearch perform_recruiter_people_search(account_id, offset=offset, limit=limit, perform_recruiter_people_search_request=perform_recruiter_people_search_request)

Perform People Search

Returns a list of people from search results.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.people_search import PeopleSearch
from unipile.models.perform_recruiter_people_search_request import PerformRecruiterPeopleSearchRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    perform_recruiter_people_search_request = unipile.PerformRecruiterPeopleSearchRequest() # PerformRecruiterPeopleSearchRequest |  (optional)

    try:
        # Perform People Search
        api_response = api_instance.perform_recruiter_people_search(account_id, offset=offset, limit=limit, perform_recruiter_people_search_request=perform_recruiter_people_search_request)
        print("The response of LinkedInApi->perform_recruiter_people_search:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->perform_recruiter_people_search: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **perform_recruiter_people_search_request** | [**PerformRecruiterPeopleSearchRequest**](PerformRecruiterPeopleSearchRequest.md)|  | [optional] 

### Return type

[**PeopleSearch**](PeopleSearch.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **perform_recruiter_people_search_from_talent_pool**
> PeopleSearch perform_recruiter_people_search_from_talent_pool(project_id, account_id, perform_recruiter_people_search_from_talent_pool_request, offset=offset, limit=limit)

Perform People Search From Talent Pool

Returns a list of people from search results.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.people_search import PeopleSearch
from unipile.models.perform_recruiter_people_search_from_talent_pool_request import PerformRecruiterPeopleSearchFromTalentPoolRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    project_id = 'project_id_example' # str | The ID of the Hiring Project from which to browse the Talent Pool.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    perform_recruiter_people_search_from_talent_pool_request = unipile.PerformRecruiterPeopleSearchFromTalentPoolRequest() # PerformRecruiterPeopleSearchFromTalentPoolRequest | 
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)

    try:
        # Perform People Search From Talent Pool
        api_response = api_instance.perform_recruiter_people_search_from_talent_pool(project_id, account_id, perform_recruiter_people_search_from_talent_pool_request, offset=offset, limit=limit)
        print("The response of LinkedInApi->perform_recruiter_people_search_from_talent_pool:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->perform_recruiter_people_search_from_talent_pool: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **project_id** | **str**| The ID of the Hiring Project from which to browse the Talent Pool. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **perform_recruiter_people_search_from_talent_pool_request** | [**PerformRecruiterPeopleSearchFromTalentPoolRequest**](PerformRecruiterPeopleSearchFromTalentPoolRequest.md)|  | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]

### Return type

[**PeopleSearch**](PeopleSearch.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **perform_recruiter_search_from_url**
> PerformRecruiterSearchFromUrl200Response perform_recruiter_search_from_url(account_id, perform_classic_search_from_url_request, offset=offset, limit=limit)

Perform Recruiter Search from URL

Returns a list of results from a LinkedIn Recruiter search URL.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.perform_classic_search_from_url_request import PerformClassicSearchFromUrlRequest
from unipile.models.perform_recruiter_search_from_url200_response import PerformRecruiterSearchFromUrl200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    perform_classic_search_from_url_request = unipile.PerformClassicSearchFromUrlRequest() # PerformClassicSearchFromUrlRequest | 
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)

    try:
        # Perform Recruiter Search from URL
        api_response = api_instance.perform_recruiter_search_from_url(account_id, perform_classic_search_from_url_request, offset=offset, limit=limit)
        print("The response of LinkedInApi->perform_recruiter_search_from_url:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->perform_recruiter_search_from_url: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **perform_classic_search_from_url_request** | [**PerformClassicSearchFromUrlRequest**](PerformClassicSearchFromUrlRequest.md)|  | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]

### Return type

[**PerformRecruiterSearchFromUrl200Response**](PerformRecruiterSearchFromUrl200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **perform_sales_companies_search**
> CompaniesSearch1 perform_sales_companies_search(account_id, offset=offset, limit=limit, perform_sales_companies_search_request=perform_sales_companies_search_request)

Perform Companies Search

Returns a list of companies from search results.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.companies_search1 import CompaniesSearch1
from unipile.models.perform_sales_companies_search_request import PerformSalesCompaniesSearchRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    perform_sales_companies_search_request = unipile.PerformSalesCompaniesSearchRequest() # PerformSalesCompaniesSearchRequest |  (optional)

    try:
        # Perform Companies Search
        api_response = api_instance.perform_sales_companies_search(account_id, offset=offset, limit=limit, perform_sales_companies_search_request=perform_sales_companies_search_request)
        print("The response of LinkedInApi->perform_sales_companies_search:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->perform_sales_companies_search: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **perform_sales_companies_search_request** | [**PerformSalesCompaniesSearchRequest**](PerformSalesCompaniesSearchRequest.md)|  | [optional] 

### Return type

[**CompaniesSearch1**](CompaniesSearch1.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **perform_sales_people_search**
> PeopleSearch2 perform_sales_people_search(account_id, offset=offset, limit=limit, perform_sales_people_search_request=perform_sales_people_search_request)

Perform People Search

Returns a list of people from search results.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.people_search2 import PeopleSearch2
from unipile.models.perform_sales_people_search_request import PerformSalesPeopleSearchRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)
    perform_sales_people_search_request = unipile.PerformSalesPeopleSearchRequest() # PerformSalesPeopleSearchRequest |  (optional)

    try:
        # Perform People Search
        api_response = api_instance.perform_sales_people_search(account_id, offset=offset, limit=limit, perform_sales_people_search_request=perform_sales_people_search_request)
        print("The response of LinkedInApi->perform_sales_people_search:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->perform_sales_people_search: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]
 **perform_sales_people_search_request** | [**PerformSalesPeopleSearchRequest**](PerformSalesPeopleSearchRequest.md)|  | [optional] 

### Return type

[**PeopleSearch2**](PeopleSearch2.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **perform_sales_search_from_url**
> PerformSalesSearchFromUrl200Response perform_sales_search_from_url(account_id, perform_classic_search_from_url_request, offset=offset, limit=limit)

Perform Search from URL

Returns a list of results from a LinkedIn Sales navigator search URL.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.perform_classic_search_from_url_request import PerformClassicSearchFromUrlRequest
from unipile.models.perform_sales_search_from_url200_response import PerformSalesSearchFromUrl200Response
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    perform_classic_search_from_url_request = unipile.PerformClassicSearchFromUrlRequest() # PerformClassicSearchFromUrlRequest | 
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    limit = 20 # float | The limit of items to be returned. (optional) (default to 20)

    try:
        # Perform Search from URL
        api_response = api_instance.perform_sales_search_from_url(account_id, perform_classic_search_from_url_request, offset=offset, limit=limit)
        print("The response of LinkedInApi->perform_sales_search_from_url:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->perform_sales_search_from_url: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **perform_classic_search_from_url_request** | [**PerformClassicSearchFromUrlRequest**](PerformClassicSearchFromUrlRequest.md)|  | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. | [optional] [default to 20]

### Return type

[**PerformSalesSearchFromUrl200Response**](PerformSalesSearchFromUrl200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **proxy_request**
> ProxyRequest200Response proxy_request(account_id, proxy_request_request)

Perform a Request to any LinkedIn API Endpoint

Allows advanced users to implement any LinkedIn feature that is not yet supported by our platform.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.proxy_request200_response import ProxyRequest200Response
from unipile.models.proxy_request_request import ProxyRequestRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    proxy_request_request = unipile.ProxyRequestRequest() # ProxyRequestRequest | 

    try:
        # Perform a Request to any LinkedIn API Endpoint
        api_response = api_instance.proxy_request(account_id, proxy_request_request)
        print("The response of LinkedInApi->proxy_request:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->proxy_request: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **proxy_request_request** | [**ProxyRequestRequest**](ProxyRequestRequest.md)|  | 

### Return type

[**ProxyRequest200Response**](ProxyRequest200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **publish_classic_job_posting**
> PublishClassicJobPosting200Response publish_classic_job_posting(job_id, account_id, publish_classic_job_posting_request=publish_classic_job_posting_request)

Publish a Job Posting

Publishes a job posting with specific budget options.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.publish_classic_job_posting200_response import PublishClassicJobPosting200Response
from unipile.models.publish_classic_job_posting_request import PublishClassicJobPostingRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    job_id = 'job_id_example' # str | The ID of the Job to publish.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    publish_classic_job_posting_request = unipile.PublishClassicJobPostingRequest() # PublishClassicJobPostingRequest |  (optional)

    try:
        # Publish a Job Posting
        api_response = api_instance.publish_classic_job_posting(job_id, account_id, publish_classic_job_posting_request=publish_classic_job_posting_request)
        print("The response of LinkedInApi->publish_classic_job_posting:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->publish_classic_job_posting: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **job_id** | **str**| The ID of the Job to publish. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **publish_classic_job_posting_request** | [**PublishClassicJobPostingRequest**](PublishClassicJobPostingRequest.md)|  | [optional] 

### Return type

[**PublishClassicJobPosting200Response**](PublishClassicJobPosting200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **publish_recruiter_job_posting**
> PublishClassicJobPosting200Response publish_recruiter_job_posting(project_id, job_id, account_id, publish_recruiter_job_posting_request=publish_recruiter_job_posting_request)

Publish a Job Posting

Publishes a job posting with specific budget options.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.publish_classic_job_posting200_response import PublishClassicJobPosting200Response
from unipile.models.publish_recruiter_job_posting_request import PublishRecruiterJobPostingRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    project_id = 'project_id_example' # str | The ID of the project associated with the the job.
    job_id = 'job_id_example' # str | The ID of the job to publish.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    publish_recruiter_job_posting_request = unipile.PublishRecruiterJobPostingRequest() # PublishRecruiterJobPostingRequest |  (optional)

    try:
        # Publish a Job Posting
        api_response = api_instance.publish_recruiter_job_posting(project_id, job_id, account_id, publish_recruiter_job_posting_request=publish_recruiter_job_posting_request)
        print("The response of LinkedInApi->publish_recruiter_job_posting:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->publish_recruiter_job_posting: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **project_id** | **str**| The ID of the project associated with the the job. | 
 **job_id** | **str**| The ID of the job to publish. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **publish_recruiter_job_posting_request** | [**PublishRecruiterJobPostingRequest**](PublishRecruiterJobPostingRequest.md)|  | [optional] 

### Return type

[**PublishClassicJobPosting200Response**](PublishClassicJobPosting200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **save_recruiter_candidate_to_pipeline**
> SaveRecruiterCandidateToPipeline200Response save_recruiter_candidate_to_pipeline(project_id, account_id, save_recruiter_candidate_to_pipeline_request)

Save a Candidate

Saves a candidate to the pipeline of a project

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.save_recruiter_candidate_to_pipeline200_response import SaveRecruiterCandidateToPipeline200Response
from unipile.models.save_recruiter_candidate_to_pipeline_request import SaveRecruiterCandidateToPipelineRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    project_id = 'project_id_example' # str | The ID of the Hiring Project where the candidate should be saved to.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    save_recruiter_candidate_to_pipeline_request = unipile.SaveRecruiterCandidateToPipelineRequest() # SaveRecruiterCandidateToPipelineRequest | 

    try:
        # Save a Candidate
        api_response = api_instance.save_recruiter_candidate_to_pipeline(project_id, account_id, save_recruiter_candidate_to_pipeline_request)
        print("The response of LinkedInApi->save_recruiter_candidate_to_pipeline:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->save_recruiter_candidate_to_pipeline: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **project_id** | **str**| The ID of the Hiring Project where the candidate should be saved to. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **save_recruiter_candidate_to_pipeline_request** | [**SaveRecruiterCandidateToPipelineRequest**](SaveRecruiterCandidateToPipelineRequest.md)|  | 

### Return type

[**SaveRecruiterCandidateToPipeline200Response**](SaveRecruiterCandidateToPipeline200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **save_sales_account_to_list**
> SaveSalesAccountToList200Response save_sales_account_to_list(list_id, account_id, save_sales_account_to_list_request)

Save an Account To a List

Add an account to an existing list

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.save_sales_account_to_list200_response import SaveSalesAccountToList200Response
from unipile.models.save_sales_account_to_list_request import SaveSalesAccountToListRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    list_id = 'list_id_example' # str | The ID of the List to save the Account to.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    save_sales_account_to_list_request = unipile.SaveSalesAccountToListRequest() # SaveSalesAccountToListRequest | 

    try:
        # Save an Account To a List
        api_response = api_instance.save_sales_account_to_list(list_id, account_id, save_sales_account_to_list_request)
        print("The response of LinkedInApi->save_sales_account_to_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->save_sales_account_to_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **list_id** | **str**| The ID of the List to save the Account to. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **save_sales_account_to_list_request** | [**SaveSalesAccountToListRequest**](SaveSalesAccountToListRequest.md)|  | 

### Return type

[**SaveSalesAccountToList200Response**](SaveSalesAccountToList200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **save_sales_lead_to_list**
> SaveSalesLeadToList200Response save_sales_lead_to_list(list_id, account_id, save_sales_lead_to_list_request)

Save a Lead To a List

Add a lead to an existing list

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.save_sales_lead_to_list200_response import SaveSalesLeadToList200Response
from unipile.models.save_sales_lead_to_list_request import SaveSalesLeadToListRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    list_id = 'list_id_example' # str | The ID of the List to save the Lead to.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    save_sales_lead_to_list_request = unipile.SaveSalesLeadToListRequest() # SaveSalesLeadToListRequest | 

    try:
        # Save a Lead To a List
        api_response = api_instance.save_sales_lead_to_list(list_id, account_id, save_sales_lead_to_list_request)
        print("The response of LinkedInApi->save_sales_lead_to_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->save_sales_lead_to_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **list_id** | **str**| The ID of the List to save the Lead to. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **save_sales_lead_to_list_request** | [**SaveSalesLeadToListRequest**](SaveSalesLeadToListRequest.md)|  | 

### Return type

[**SaveSalesLeadToList200Response**](SaveSalesLeadToList200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **submit_classic_company_otp_code**
> SubmitClassicCompanyOtpCode200Response submit_classic_company_otp_code(company_id, account_id, submit_classic_company_otp_code_request)

Submit Otp Verification Code

Completes the process of member identity verification.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.submit_classic_company_otp_code200_response import SubmitClassicCompanyOtpCode200Response
from unipile.models.submit_classic_company_otp_code_request import SubmitClassicCompanyOtpCodeRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    company_id = 'company_id_example' # str | The ID of the company for which the user's identity must be verified.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    submit_classic_company_otp_code_request = unipile.SubmitClassicCompanyOtpCodeRequest() # SubmitClassicCompanyOtpCodeRequest | 

    try:
        # Submit Otp Verification Code
        api_response = api_instance.submit_classic_company_otp_code(company_id, account_id, submit_classic_company_otp_code_request)
        print("The response of LinkedInApi->submit_classic_company_otp_code:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->submit_classic_company_otp_code: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **company_id** | **str**| The ID of the company for which the user&#39;s identity must be verified. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **submit_classic_company_otp_code_request** | [**SubmitClassicCompanyOtpCodeRequest**](SubmitClassicCompanyOtpCodeRequest.md)|  | 

### Return type

[**SubmitClassicCompanyOtpCode200Response**](SubmitClassicCompanyOtpCode200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **submit_recruiter_otp_code**
> SubmitClassicCompanyOtpCode200Response submit_recruiter_otp_code(company_id, account_id, submit_classic_company_otp_code_request)

Submit Otp Verification Code

Completes the process of member identity verification.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.submit_classic_company_otp_code200_response import SubmitClassicCompanyOtpCode200Response
from unipile.models.submit_classic_company_otp_code_request import SubmitClassicCompanyOtpCodeRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    company_id = 'company_id_example' # str | The ID of the company for which the user's identity must be verified.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    submit_classic_company_otp_code_request = unipile.SubmitClassicCompanyOtpCodeRequest() # SubmitClassicCompanyOtpCodeRequest | 

    try:
        # Submit Otp Verification Code
        api_response = api_instance.submit_recruiter_otp_code(company_id, account_id, submit_classic_company_otp_code_request)
        print("The response of LinkedInApi->submit_recruiter_otp_code:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->submit_recruiter_otp_code: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **company_id** | **str**| The ID of the company for which the user&#39;s identity must be verified. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **submit_classic_company_otp_code_request** | [**SubmitClassicCompanyOtpCodeRequest**](SubmitClassicCompanyOtpCodeRequest.md)|  | 

### Return type

[**SubmitClassicCompanyOtpCode200Response**](SubmitClassicCompanyOtpCode200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **verify_classic_company_member_identity**
> VerifyClassicCompanyMemberIdentity200Response verify_classic_company_member_identity(company_id, account_id, verify_classic_company_member_identity_request)

Verify Company Member Identity

Verifies member identity by submitting an email address.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.verify_classic_company_member_identity200_response import VerifyClassicCompanyMemberIdentity200Response
from unipile.models.verify_classic_company_member_identity_request import VerifyClassicCompanyMemberIdentityRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    company_id = 'company_id_example' # str | The ID of the company for which the user's identity must be verified.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    verify_classic_company_member_identity_request = unipile.VerifyClassicCompanyMemberIdentityRequest() # VerifyClassicCompanyMemberIdentityRequest | 

    try:
        # Verify Company Member Identity
        api_response = api_instance.verify_classic_company_member_identity(company_id, account_id, verify_classic_company_member_identity_request)
        print("The response of LinkedInApi->verify_classic_company_member_identity:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->verify_classic_company_member_identity: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **company_id** | **str**| The ID of the company for which the user&#39;s identity must be verified. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **verify_classic_company_member_identity_request** | [**VerifyClassicCompanyMemberIdentityRequest**](VerifyClassicCompanyMemberIdentityRequest.md)|  | 

### Return type

[**VerifyClassicCompanyMemberIdentity200Response**](VerifyClassicCompanyMemberIdentity200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **verify_recruiter_company_member_identity**
> VerifyClassicCompanyMemberIdentity200Response verify_recruiter_company_member_identity(company_id, account_id, verify_classic_company_member_identity_request)

Verify Company Member Identity

Verifies member identity by submitting an email address.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.verify_classic_company_member_identity200_response import VerifyClassicCompanyMemberIdentity200Response
from unipile.models.verify_classic_company_member_identity_request import VerifyClassicCompanyMemberIdentityRequest
from unipile.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to https://api.unipile.com
# See configuration.py for a list of all supported configuration parameters.
configuration = unipile.Configuration(
    host = "https://api.unipile.com"
)

# The client must configure the authentication and authorization parameters
# in accordance with the API server security policy.
# Examples for each auth method are provided below, use the example that
# satisfies your auth use case.

# Configure API key authorization: apiKey
configuration.api_key['apiKey'] = os.environ["API_KEY"]

# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['apiKey'] = 'Bearer'

# Enter a context with an instance of the API client
with unipile.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = unipile.LinkedInApi(api_client)
    company_id = 'company_id_example' # str | The ID of the company for which the user's identity must be verified.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    verify_classic_company_member_identity_request = unipile.VerifyClassicCompanyMemberIdentityRequest() # VerifyClassicCompanyMemberIdentityRequest | 

    try:
        # Verify Company Member Identity
        api_response = api_instance.verify_recruiter_company_member_identity(company_id, account_id, verify_classic_company_member_identity_request)
        print("The response of LinkedInApi->verify_recruiter_company_member_identity:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling LinkedInApi->verify_recruiter_company_member_identity: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **company_id** | **str**| The ID of the company for which the user&#39;s identity must be verified. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **verify_classic_company_member_identity_request** | [**VerifyClassicCompanyMemberIdentityRequest**](VerifyClassicCompanyMemberIdentityRequest.md)|  | 

### Return type

[**VerifyClassicCompanyMemberIdentity200Response**](VerifyClassicCompanyMemberIdentity200Response.md)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

