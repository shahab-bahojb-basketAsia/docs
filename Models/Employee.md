# Employee
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **EmployeeID** | **UUID** | The Xero identifier for an employee e.g. 297c2dc5-cc47-4afd-8ec8-74990b8761e9 | [optional] [default to null] |
| **Status** | **String** | Current status of an employee – see contact status types | [optional] [default to null] |
| **FirstName** | **String** | First name of an employee (max length &#x3D; 255) | [optional] [default to null] |
| **LastName** | **String** | Last name of an employee (max length &#x3D; 255) | [optional] [default to null] |
| **ExternalLink** | [**ExternalLink**](ExternalLink.md) |  | [optional] [default to null] |
| **UpdatedDateUTC** | **String** |  | [optional] [default to null] |
| **StatusAttributeString** | **String** | A string to indicate if a invoice status | [optional] [default to null] |
| **ValidationErrors** | [**List**](ValidationError.md) | Displays array of validation error messages from the API | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

