# unipile.CalendarApi

All URIs are relative to *https://api.unipile.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**cancel_calendar_event**](CalendarApi.md#cancel_calendar_event) | **POST** /v2/{account_id}/calendars/{calendar_id}/events/{event_id}/cancel | Cancel a calendar event
[**create_calendar**](CalendarApi.md#create_calendar) | **POST** /v2/{account_id}/calendars | Create a Calendar
[**create_calendar_event**](CalendarApi.md#create_calendar_event) | **POST** /v2/{account_id}/calendars/{calendar_id}/events | Create a calendar event
[**delete_calendar**](CalendarApi.md#delete_calendar) | **DELETE** /v2/{account_id}/calendars/{calendar_id} | Delete a Calendar
[**delete_calendar_event**](CalendarApi.md#delete_calendar_event) | **DELETE** /v2/{account_id}/calendars/{calendar_id}/events/{event_id} | Delete a Calendar event
[**get_calendar**](CalendarApi.md#get_calendar) | **GET** /v2/{account_id}/calendars/{calendar_id} | Get a Calendar
[**get_calendar_event**](CalendarApi.md#get_calendar_event) | **GET** /v2/{account_id}/calendars/{calendar_id}/events/{event_id} | Get a calendar event
[**get_calendar_event_list**](CalendarApi.md#get_calendar_event_list) | **GET** /v2/{account_id}/calendars/{calendar_id}/events | List all calendar events
[**get_calendars_list**](CalendarApi.md#get_calendars_list) | **GET** /v2/{account_id}/calendars | List all Calendars
[**restore_calendar_event**](CalendarApi.md#restore_calendar_event) | **POST** /v2/{account_id}/calendars/{calendar_id}/events/{event_id}/restore | Restore a cancelled calendar event
[**set_calendar_event_rsvp**](CalendarApi.md#set_calendar_event_rsvp) | **POST** /v2/{account_id}/calendars/{calendar_id}/events/{event_id}/rsvp | Respond to a calendar event
[**update_calendar**](CalendarApi.md#update_calendar) | **PATCH** /v2/{account_id}/calendars/{calendar_id} | Update a Calendar
[**update_calendar_event**](CalendarApi.md#update_calendar_event) | **PATCH** /v2/{account_id}/calendars/{calendar_id}/events/{event_id} | Update a calendar event


# **cancel_calendar_event**
> cancel_calendar_event(calendar_id, event_id, account_id, cancel_calendar_event_request=cancel_calendar_event_request)

Cancel a calendar event

Cancels the specified event and notifies its attendees. Only the organizer of the event can cancel it, use the delete event method to remove an event from the calendar of the connected account.
        - For Google, the event is deleted and stays readable as a cancelled event.
        - For Outlook, the event is moved to the Deleted Items folder and is no longer readable by the organizer.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.cancel_calendar_event_request import CancelCalendarEventRequest
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
    api_instance = unipile.CalendarApi(api_client)
    calendar_id = 'calendar_id_example' # str | Identifier of the parent calendar.
    event_id = 'event_id_example' # str | ID of the event to cancel.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    cancel_calendar_event_request = unipile.CancelCalendarEventRequest() # CancelCalendarEventRequest |  (optional)

    try:
        # Cancel a calendar event
        api_instance.cancel_calendar_event(calendar_id, event_id, account_id, cancel_calendar_event_request=cancel_calendar_event_request)
    except Exception as e:
        print("Exception when calling CalendarApi->cancel_calendar_event: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **calendar_id** | **str**| Identifier of the parent calendar. | 
 **event_id** | **str**| ID of the event to cancel. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **cancel_calendar_event_request** | [**CancelCalendarEventRequest**](CancelCalendarEventRequest.md)|  | [optional] 

### Return type

void (empty response body)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **create_calendar**
> GetCalendarsList200ResponseDataInner create_calendar(account_id, create_calendar_request)

Create a Calendar

Create a new calendar.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_calendar_request import CreateCalendarRequest
from unipile.models.get_calendars_list200_response_data_inner import GetCalendarsList200ResponseDataInner
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
    api_instance = unipile.CalendarApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    create_calendar_request = unipile.CreateCalendarRequest() # CreateCalendarRequest | 

    try:
        # Create a Calendar
        api_response = api_instance.create_calendar(account_id, create_calendar_request)
        print("The response of CalendarApi->create_calendar:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarApi->create_calendar: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **create_calendar_request** | [**CreateCalendarRequest**](CreateCalendarRequest.md)|  | 

### Return type

[**GetCalendarsList200ResponseDataInner**](GetCalendarsList200ResponseDataInner.md)

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

# **create_calendar_event**
> CreateCalendarEvent201Response create_calendar_event(calendar_id, account_id, create_calendar_event_request)

Create a calendar event

Create a brand new calendar event.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_calendar_event201_response import CreateCalendarEvent201Response
from unipile.models.create_calendar_event_request import CreateCalendarEventRequest
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
    api_instance = unipile.CalendarApi(api_client)
    calendar_id = 'calendar_id_example' # str | Identifier of the parent calendar.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    create_calendar_event_request = unipile.CreateCalendarEventRequest() # CreateCalendarEventRequest | 

    try:
        # Create a calendar event
        api_response = api_instance.create_calendar_event(calendar_id, account_id, create_calendar_event_request)
        print("The response of CalendarApi->create_calendar_event:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarApi->create_calendar_event: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **calendar_id** | **str**| Identifier of the parent calendar. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **create_calendar_event_request** | [**CreateCalendarEventRequest**](CreateCalendarEventRequest.md)|  | 

### Return type

[**CreateCalendarEvent201Response**](CreateCalendarEvent201Response.md)

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

# **delete_calendar**
> delete_calendar(calendar_id, account_id)

Delete a Calendar

Delete the specified calendar.

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
    api_instance = unipile.CalendarApi(api_client)
    calendar_id = 'calendar_id_example' # str | ID of the calendar to delete.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Delete a Calendar
        api_instance.delete_calendar(calendar_id, account_id)
    except Exception as e:
        print("Exception when calling CalendarApi->delete_calendar: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **calendar_id** | **str**| ID of the calendar to delete. | 
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
**204** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **delete_calendar_event**
> delete_calendar_event(calendar_id, event_id, account_id)

Delete a Calendar event

Delete the specified calendar event.

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
    api_instance = unipile.CalendarApi(api_client)
    calendar_id = 'calendar_id_example' # str | Identifier of the parent calendar.
    event_id = 'event_id_example' # str | ID of the event to delete.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Delete a Calendar event
        api_instance.delete_calendar_event(calendar_id, event_id, account_id)
    except Exception as e:
        print("Exception when calling CalendarApi->delete_calendar_event: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **calendar_id** | **str**| Identifier of the parent calendar. | 
 **event_id** | **str**| ID of the event to delete. | 
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
**204** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **get_calendar**
> GetCalendarsList200ResponseDataInner get_calendar(calendar_id, account_id)

Get a Calendar

Retrieves the specified Calendar.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_calendars_list200_response_data_inner import GetCalendarsList200ResponseDataInner
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
    api_instance = unipile.CalendarApi(api_client)
    calendar_id = 'calendar_id_example' # str | Identifier of the calendar to retrieve 
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get a Calendar
        api_response = api_instance.get_calendar(calendar_id, account_id)
        print("The response of CalendarApi->get_calendar:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarApi->get_calendar: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **calendar_id** | **str**| Identifier of the calendar to retrieve  | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**GetCalendarsList200ResponseDataInner**](GetCalendarsList200ResponseDataInner.md)

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

# **get_calendar_event**
> CreateCalendarEvent201Response get_calendar_event(calendar_id, event_id, account_id)

Get a calendar event

Retrieves a calendar event object.
        - For Outlook, the attendee list of an invitation the connected account received is the one the organizer sent, and their responses are not refreshed on it. Only the response of the connected account is kept up to date. Read the event from the calendar of its organizer to get the responses of the other attendees.
        - For Outlook, an account invited through one of its aliases is not identifiable in the attendee list: Microsoft does not support an alias taking part in a calendar, so the invitation keeps the alias address while the account answers with its primary one.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_calendar_event201_response import CreateCalendarEvent201Response
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
    api_instance = unipile.CalendarApi(api_client)
    calendar_id = 'calendar_id_example' # str | Identifier of the parent calendar.
    event_id = 'event_id_example' # str | Identifier of the event to retrieve 
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Get a calendar event
        api_response = api_instance.get_calendar_event(calendar_id, event_id, account_id)
        print("The response of CalendarApi->get_calendar_event:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarApi->get_calendar_event: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **calendar_id** | **str**| Identifier of the parent calendar. | 
 **event_id** | **str**| Identifier of the event to retrieve  | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 

### Return type

[**CreateCalendarEvent201Response**](CreateCalendarEvent201Response.md)

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

# **get_calendar_event_list**
> GetCalendarEventList200Response get_calendar_event_list(calendar_id, account_id, is_cancelled=is_cancelled, title=title, description=description, ical_uid=ical_uid, location=location, start=start, end=end, busy=busy, updated_before=updated_before, updated_after=updated_after, attendees=attendees, event_type=event_type, expand_recurring=expand_recurring, offset=offset, cursor=cursor, limit=limit)

List all calendar events

Returns a list of calendar events.
        - For Outlook, the attendee list of an invitation the connected account received is the one the organizer sent, and their responses are not refreshed on it. Only the response of the connected account is kept up to date.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_calendar_event_list200_response import GetCalendarEventList200Response
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
    api_instance = unipile.CalendarApi(api_client)
    calendar_id = 'calendar_id_example' # str | Identifier of the calendar.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    is_cancelled = True # bool | Whether you want to retrieve the cancelled events. (optional) (default to True)
    title = 'title_example' # str | Filter for events matching the specified title. (optional)
    description = 'description_example' # str | Filter for events matching the specified description. (optional)
    ical_uid = 'ical_uid_example' # str | Filter for events matching the specified iCal UID. (optional)
    location = 'location_example' # str | Filter for events matching the specified location. (optional)
    start = 'start_example' # str | Filter events starting after this date. (optional)
    end = 'end_example' # str | Filter events ending before this date. (optional)
    busy = True # bool | Filter for events with the status `busy` (optional)
    updated_before = 'updated_before_example' # str | Filter events updated before this date. (optional)
    updated_after = 'updated_after_example' # str | Filter events updated after this date. (optional)
    attendees = 'attendees_example' # str | Filter events with attendees contained in this list. This parameter accepts a comma-delimited list of email addresses. (optional)
    event_type = 'event_type_example' # str | Filter events by event type. This parameter accepts a comma-delimited list of event type. (optional)
    expand_recurring = True # bool | Filter events by type (single or occurence). (optional)
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)
    limit = 20 # float | The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. (optional) (default to 20)

    try:
        # List all calendar events
        api_response = api_instance.get_calendar_event_list(calendar_id, account_id, is_cancelled=is_cancelled, title=title, description=description, ical_uid=ical_uid, location=location, start=start, end=end, busy=busy, updated_before=updated_before, updated_after=updated_after, attendees=attendees, event_type=event_type, expand_recurring=expand_recurring, offset=offset, cursor=cursor, limit=limit)
        print("The response of CalendarApi->get_calendar_event_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarApi->get_calendar_event_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **calendar_id** | **str**| Identifier of the calendar. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **is_cancelled** | **bool**| Whether you want to retrieve the cancelled events. | [optional] [default to True]
 **title** | **str**| Filter for events matching the specified title. | [optional] 
 **description** | **str**| Filter for events matching the specified description. | [optional] 
 **ical_uid** | **str**| Filter for events matching the specified iCal UID. | [optional] 
 **location** | **str**| Filter for events matching the specified location. | [optional] 
 **start** | **str**| Filter events starting after this date. | [optional] 
 **end** | **str**| Filter events ending before this date. | [optional] 
 **busy** | **bool**| Filter for events with the status &#x60;busy&#x60; | [optional] 
 **updated_before** | **str**| Filter events updated before this date. | [optional] 
 **updated_after** | **str**| Filter events updated after this date. | [optional] 
 **attendees** | **str**| Filter events with attendees contained in this list. This parameter accepts a comma-delimited list of email addresses. | [optional] 
 **event_type** | **str**| Filter events by event type. This parameter accepts a comma-delimited list of event type. | [optional] 
 **expand_recurring** | **bool**| Filter events by type (single or occurence). | [optional] 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. | [optional] [default to 20]

### Return type

[**GetCalendarEventList200Response**](GetCalendarEventList200Response.md)

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

# **get_calendars_list**
> GetCalendarsList200Response get_calendars_list(account_id, offset=offset, cursor=cursor, limit=limit)

List all Calendars

Returns a list of calendars.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_calendars_list200_response import GetCalendarsList200Response
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
    api_instance = unipile.CalendarApi(api_client)
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    offset = 3.4 # float | An offset used for pagination, if supported by the provider, else use `cursor`. (optional)
    cursor = 'cursor_example' # str | A cursor used for pagination. If supported by the provider, use `next_cursor` given by the previous page of the list, else use `offset`. (optional)
    limit = 20 # float | The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. (optional) (default to 20)

    try:
        # List all Calendars
        api_response = api_instance.get_calendars_list(account_id, offset=offset, cursor=cursor, limit=limit)
        print("The response of CalendarApi->get_calendars_list:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarApi->get_calendars_list: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **offset** | **float**| An offset used for pagination, if supported by the provider, else use &#x60;cursor&#x60;. | [optional] 
 **cursor** | **str**| A cursor used for pagination. If supported by the provider, use &#x60;next_cursor&#x60; given by the previous page of the list, else use &#x60;offset&#x60;. | [optional] 
 **limit** | **float**| The limit of items to be returned. The maximum allowed value depends on the provider. This is a ceiling, not a guarantee: some providers can return fewer items than requested for a given page. | [optional] [default to 20]

### Return type

[**GetCalendarsList200Response**](GetCalendarsList200Response.md)

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

# **restore_calendar_event**
> restore_calendar_event(calendar_id, event_id, account_id)

Restore a cancelled calendar event

Restores an event previously cancelled by the connected account. Only the organizer of the event can restore it.
        - Only available for Google Calendar, and only while Google still holds the data of the cancelled event.
        - Outlook exposes no way to restore a cancelled event and always answers a `provider/method_not_allowed` error.

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
    api_instance = unipile.CalendarApi(api_client)
    calendar_id = 'calendar_id_example' # str | Identifier of the parent calendar.
    event_id = 'event_id_example' # str | ID of the event to restore.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.

    try:
        # Restore a cancelled calendar event
        api_instance.restore_calendar_event(calendar_id, event_id, account_id)
    except Exception as e:
        print("Exception when calling CalendarApi->restore_calendar_event: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **calendar_id** | **str**| Identifier of the parent calendar. | 
 **event_id** | **str**| ID of the event to restore. | 
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
**204** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **set_calendar_event_rsvp**
> set_calendar_event_rsvp(calendar_id, event_id, account_id, set_calendar_event_rsvp_request)

Respond to a calendar event

Sets the response of the connected account to an event it is invited to. Only the response of the connected account is affected, the other attendees are left untouched.
        - For Outlook, declining an invitation also removes the event from the calendar of the connected account, and the organizer of an event cannot respond to it.
        - For Google, the organizer can respond when they are also an attendee of the event.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.set_calendar_event_rsvp_request import SetCalendarEventRsvpRequest
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
    api_instance = unipile.CalendarApi(api_client)
    calendar_id = 'calendar_id_example' # str | Identifier of the parent calendar.
    event_id = 'event_id_example' # str | ID of the event to respond to.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    set_calendar_event_rsvp_request = unipile.SetCalendarEventRsvpRequest() # SetCalendarEventRsvpRequest | 

    try:
        # Respond to a calendar event
        api_instance.set_calendar_event_rsvp(calendar_id, event_id, account_id, set_calendar_event_rsvp_request)
    except Exception as e:
        print("Exception when calling CalendarApi->set_calendar_event_rsvp: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **calendar_id** | **str**| Identifier of the parent calendar. | 
 **event_id** | **str**| ID of the event to respond to. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **set_calendar_event_rsvp_request** | [**SetCalendarEventRsvpRequest**](SetCalendarEventRsvpRequest.md)|  | 

### Return type

void (empty response body)

### Authorization

[apiKey](../README.md#apiKey)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**204** | Default Response |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **update_calendar**
> GetCalendarsList200ResponseDataInner update_calendar(calendar_id, account_id, update_calendar_request=update_calendar_request)

Update a Calendar

Updates the specified calendar by setting the values of the parameters passed. Any parameters not provided will be left unchanged.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.get_calendars_list200_response_data_inner import GetCalendarsList200ResponseDataInner
from unipile.models.update_calendar_request import UpdateCalendarRequest
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
    api_instance = unipile.CalendarApi(api_client)
    calendar_id = 'calendar_id_example' # str | ID of the Calendar to update.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    update_calendar_request = unipile.UpdateCalendarRequest() # UpdateCalendarRequest |  (optional)

    try:
        # Update a Calendar
        api_response = api_instance.update_calendar(calendar_id, account_id, update_calendar_request=update_calendar_request)
        print("The response of CalendarApi->update_calendar:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarApi->update_calendar: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **calendar_id** | **str**| ID of the Calendar to update. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **update_calendar_request** | [**UpdateCalendarRequest**](UpdateCalendarRequest.md)|  | [optional] 

### Return type

[**GetCalendarsList200ResponseDataInner**](GetCalendarsList200ResponseDataInner.md)

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

# **update_calendar_event**
> CreateCalendarEvent201Response update_calendar_event(calendar_id, event_id, account_id, update_calendar_event_request=update_calendar_event_request)

Update a calendar event

Updates the specified calendar by setting the values of the parameters passed. Any parameters not provided will be left unchanged.

### Example

* Api Key Authentication (apiKey):

```python
import unipile
from unipile.models.create_calendar_event201_response import CreateCalendarEvent201Response
from unipile.models.update_calendar_event_request import UpdateCalendarEventRequest
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
    api_instance = unipile.CalendarApi(api_client)
    calendar_id = 'calendar_id_example' # str | Identifier of the parent calendar.
    event_id = 'event_id_example' # str | ID of the event to update.
    account_id = 'account_id_example' # str | ID of the Account (acc_xxx) to call the method on behalf of.
    update_calendar_event_request = unipile.UpdateCalendarEventRequest() # UpdateCalendarEventRequest |  (optional)

    try:
        # Update a calendar event
        api_response = api_instance.update_calendar_event(calendar_id, event_id, account_id, update_calendar_event_request=update_calendar_event_request)
        print("The response of CalendarApi->update_calendar_event:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling CalendarApi->update_calendar_event: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **calendar_id** | **str**| Identifier of the parent calendar. | 
 **event_id** | **str**| ID of the event to update. | 
 **account_id** | **str**| ID of the Account (acc_xxx) to call the method on behalf of. | 
 **update_calendar_event_request** | [**UpdateCalendarEventRequest**](UpdateCalendarEventRequest.md)|  | [optional] 

### Return type

[**CreateCalendarEvent201Response**](CreateCalendarEvent201Response.md)

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

