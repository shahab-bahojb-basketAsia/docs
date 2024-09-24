# Payment
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **Invoice** | [**Invoice**](Invoice.md) |  | [optional] [default to null] |
| **CreditNote** | [**CreditNote**](CreditNote.md) |  | [optional] [default to null] |
| **Prepayment** | [**Prepayment**](Prepayment.md) |  | [optional] [default to null] |
| **Overpayment** | [**Overpayment**](Overpayment.md) |  | [optional] [default to null] |
| **InvoiceNumber** | **String** | Number of invoice or credit note you are applying payment to e.g.INV-4003 | [optional] [default to null] |
| **CreditNoteNumber** | **String** | Number of invoice or credit note you are applying payment to e.g. INV-4003 | [optional] [default to null] |
| **BatchPayment** | [**BatchPayment**](BatchPayment.md) |  | [optional] [default to null] |
| **Account** | [**Account**](Account.md) |  | [optional] [default to null] |
| **Code** | **String** | Code of account you are using to make the payment e.g. 001 (note- not all accounts have a code value) | [optional] [default to null] |
| **Date** | **String** | Date the payment is being made (YYYY-MM-DD) e.g. 2009-09-06 | [optional] [default to null] |
| **CurrencyRate** | **Double** | Exchange rate when payment is received. Only used for non base currency invoices and credit notes e.g. 0.7500 | [optional] [default to null] |
| **Amount** | **Double** | The amount of the payment. Must be less than or equal to the outstanding amount owing on the invoice e.g. 200.00 | [optional] [default to null] |
| **BankAmount** | **Double** | The amount of the payment in the currency of the bank account. | [optional] [default to null] |
| **Reference** | **String** | An optional description for the payment e.g. Direct Debit | [optional] [default to null] |
| **IsReconciled** | **Boolean** | An optional parameter for the payment. A boolean indicating whether you would like the payment to be created as reconciled when using PUT, or whether a payment has been reconciled when using GET | [optional] [default to null] |
| **Status** | **String** | The status of the payment. | [optional] [default to null] |
| **PaymentType** | **String** | See Payment Types. | [optional] [default to null] |
| **UpdatedDateUTC** | **String** | UTC timestamp of last update to the payment | [optional] [default to null] |
| **PaymentID** | **UUID** | The Xero identifier for an Payment e.g. 297c2dc5-cc47-4afd-8ec8-74990b8761e9 | [optional] [default to null] |
| **BatchPaymentID** | **UUID** | Present if the payment was created as part of a batch. | [optional] [default to null] |
| **BankAccountNumber** | **String** | The suppliers bank account number the payment is being made to | [optional] [default to null] |
| **Particulars** | **String** | The suppliers bank account number the payment is being made to | [optional] [default to null] |
| **Details** | **String** | The information to appear on the supplier&#39;s bank account | [optional] [default to null] |
| **HasAccount** | **Boolean** | A boolean to indicate if a contact has an validation errors | [optional] [default to false] |
| **HasValidationErrors** | **Boolean** | A boolean to indicate if a contact has an validation errors | [optional] [default to false] |
| **StatusAttributeString** | **String** | A string to indicate if a invoice status | [optional] [default to null] |
| **ValidationErrors** | [**List**](ValidationError.md) | Displays array of validation error messages from the API | [optional] [default to null] |
| **Warnings** | [**List**](ValidationError.md) | Displays array of warning messages from the API | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

