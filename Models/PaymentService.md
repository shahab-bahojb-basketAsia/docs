# PaymentService
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **PaymentServiceID** | **UUID** | Xero identifier | [optional] [default to null] |
| **PaymentServiceName** | **String** | Name of payment service | [optional] [default to null] |
| **PaymentServiceUrl** | **String** | The custom payment URL | [optional] [default to null] |
| **PayNowText** | **String** | The text displayed on the Pay Now button in Xero Online Invoicing. If this is not set it will default to Pay by credit card | [optional] [default to null] |
| **PaymentServiceType** | **String** | This will always be CUSTOM for payment services created via the API. | [optional] [default to null] |
| **ValidationErrors** | [**List**](ValidationError.md) | Displays array of validation error messages from the API | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

