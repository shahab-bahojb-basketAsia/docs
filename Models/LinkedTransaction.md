# LinkedTransaction
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **SourceTransactionID** | **UUID** | Filter by the SourceTransactionID. Get all the linked transactions created from a particular ACCPAY invoice | [optional] [default to null] |
| **SourceLineItemID** | **UUID** | The line item identifier from the source transaction. | [optional] [default to null] |
| **ContactID** | **UUID** | Filter by the combination of ContactID and Status. Get all the linked transactions that have been assigned to a particular customer and have a particular status e.g. GET /LinkedTransactions?ContactID&#x3D;4bb34b03-3378-4bb2-a0ed-6345abf3224e&amp;Status&#x3D;APPROVED. | [optional] [default to null] |
| **TargetTransactionID** | **UUID** | Filter by the TargetTransactionID. Get all the linked transactions  allocated to a particular ACCREC invoice | [optional] [default to null] |
| **TargetLineItemID** | **UUID** | The line item identifier from the target transaction. It is possible  to link multiple billable expenses to the same TargetLineItemID. | [optional] [default to null] |
| **LinkedTransactionID** | **UUID** | The Xero identifier for an Linked Transaction e.g./LinkedTransactions/297c2dc5-cc47-4afd-8ec8-74990b8761e9 | [optional] [default to null] |
| **Status** | **String** | Filter by the combination of ContactID and Status. Get all the linked transactions that have been assigned to a particular customer and have a particular status e.g. GET /LinkedTransactions?ContactID&#x3D;4bb34b03-3378-4bb2-a0ed-6345abf3224e&amp;Status&#x3D;APPROVED. | [optional] [default to null] |
| **Type** | **String** | This will always be BILLABLEEXPENSE. More types may be added in future. | [optional] [default to null] |
| **UpdatedDateUTC** | **String** | The last modified date in UTC format | [optional] [default to null] |
| **SourceTransactionTypeCode** | **String** | The Type of the source tranasction. This will be ACCPAY if the linked transaction was created from an invoice and SPEND if it was created from a bank transaction. | [optional] [default to null] |
| **ValidationErrors** | [**List**](ValidationError.md) | Displays array of validation error messages from the API | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

