# BatchPayment
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **Account** | [**Account**](Account.md) |  | [optional] [default to null] |
| **Reference** | **String** | (NZ Only) Optional references for the batch payment transaction. It will also show with the batch payment transaction in the bank reconciliation Find &amp; Match screen. Depending on your individual bank, the detail may also show on the bank statement you import into Xero. | [optional] [default to null] |
| **Particulars** | **String** | (NZ Only) Optional references for the batch payment transaction. It will also show with the batch payment transaction in the bank reconciliation Find &amp; Match screen. Depending on your individual bank, the detail may also show on the bank statement you import into Xero. | [optional] [default to null] |
| **Code** | **String** | (NZ Only) Optional references for the batch payment transaction. It will also show with the batch payment transaction in the bank reconciliation Find &amp; Match screen. Depending on your individual bank, the detail may also show on the bank statement you import into Xero. | [optional] [default to null] |
| **Details** | **String** | (Non-NZ Only) These details are sent to the org’s bank as a reference for the batch payment transaction. They will also show with the batch payment transaction in the bank reconciliation Find &amp; Match screen. Depending on your individual bank, the detail may also show on the bank statement imported into Xero. Maximum field length &#x3D; 18 | [optional] [default to null] |
| **Narrative** | **String** | (UK Only) Only shows on the statement line in Xero. Max length &#x3D;18 | [optional] [default to null] |
| **BatchPaymentID** | **UUID** | The Xero generated unique identifier for the bank transaction (read-only) | [optional] [default to null] |
| **DateString** | **String** | Date the payment is being made (YYYY-MM-DD) e.g. 2009-09-06 | [optional] [default to null] |
| **Date** | **String** | Date the payment is being made (YYYY-MM-DD) e.g. 2009-09-06 | [optional] [default to null] |
| **Amount** | **Double** | The amount of the payment. Must be less than or equal to the outstanding amount owing on the invoice e.g. 200.00 | [optional] [default to null] |
| **Payments** | [**List**](Payment.md) | An array of payments | [optional] [default to null] |
| **Type** | **String** | PAYBATCH for bill payments or RECBATCH for sales invoice payments (read-only) | [optional] [default to null] |
| **Status** | **String** | AUTHORISED or DELETED (read-only). New batch payments will have a status of AUTHORISED. It is not possible to delete batch payments via the API. | [optional] [default to null] |
| **TotalAmount** | **Double** | The total of the payments that make up the batch (read-only) | [optional] [default to null] |
| **UpdatedDateUTC** | **String** | UTC timestamp of last update to the payment | [optional] [default to null] |
| **IsReconciled** | **Boolean** | Booelan that tells you if the batch payment has been reconciled (read-only) | [optional] [default to null] |
| **ValidationErrors** | [**List**](ValidationError.md) | Displays array of validation error messages from the API | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

