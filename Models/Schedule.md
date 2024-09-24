# Schedule
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **Period** | **Integer** | Integer used with the unit e.g. 1 (every 1 week), 2 (every 2 months) | [optional] [default to null] |
| **Unit** | **String** | One of the following - WEEKLY or MONTHLY | [optional] [default to null] |
| **DueDate** | **Integer** | Integer used with due date type e.g 20 (of following month), 31 (of current month) | [optional] [default to null] |
| **DueDateType** | **String** | the payment terms | [optional] [default to null] |
| **StartDate** | **String** | Date the first invoice of the current version of the repeating schedule was generated (changes when repeating invoice is edited) | [optional] [default to null] |
| **NextScheduledDate** | **String** | The calendar date of the next invoice in the schedule to be generated | [optional] [default to null] |
| **EndDate** | **String** | Invoice end date – only returned if the template has an end date set | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

