# ExpenseClaim
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **ExpenseClaimID** | **UUID** | Xero generated unique identifier for an expense claim | [optional] [default to null] |
| **Status** | **String** | Current status of an expense claim – see status types | [optional] [default to null] |
| **Payments** | [**List**](Payment.md) | See Payments | [optional] [default to null] |
| **User** | [**User**](User.md) |  | [optional] [default to null] |
| **Receipts** | [**List**](Receipt.md) |  | [optional] [default to null] |
| **UpdatedDateUTC** | **String** | Last modified date UTC format | [optional] [default to null] |
| **Total** | **Double** | The total of an expense claim being paid | [optional] [default to null] |
| **AmountDue** | **Double** | The amount due to be paid for an expense claim | [optional] [default to null] |
| **AmountPaid** | **Double** | The amount still to pay for an expense claim | [optional] [default to null] |
| **PaymentDueDate** | **String** | The date when the expense claim is due to be paid YYYY-MM-DD | [optional] [default to null] |
| **ReportingDate** | **String** | The date the expense claim will be reported in Xero YYYY-MM-DD | [optional] [default to null] |
| **ReceiptID** | **UUID** | The Xero identifier for the Receipt e.g. e59a2c7f-1306-4078-a0f3-73537afcbba9 | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

