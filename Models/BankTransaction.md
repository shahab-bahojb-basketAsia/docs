# BankTransaction
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **Type** | **String** | See Bank Transaction Types | [default to null] |
| **Contact** | [**Contact**](Contact.md) |  | [optional] [default to null] |
| **LineItems** | [**List**](LineItem.md) | See LineItems | [default to null] |
| **BankAccount** | [**Account**](Account.md) |  | [default to null] |
| **IsReconciled** | **Boolean** | Boolean to show if transaction is reconciled | [optional] [default to null] |
| **Date** | **String** | Date of transaction – YYYY-MM-DD | [optional] [default to null] |
| **Reference** | **String** | Reference for the transaction. Only supported for SPEND and RECEIVE transactions. | [optional] [default to null] |
| **CurrencyCode** | [**CurrencyCode**](CurrencyCode.md) |  | [optional] [default to null] |
| **CurrencyRate** | **Double** | Exchange rate to base currency when money is spent or received. e.g.0.7500 Only used for bank transactions in non base currency. If this isn’t specified for non base currency accounts then either the user-defined rate (preference) or the XE.com day rate will be used. Setting currency is only supported on overpayments. | [optional] [default to null] |
| **Url** | **String** | URL link to a source document – shown as “Go to App Name” | [optional] [default to null] |
| **Status** | **String** | See Bank Transaction Status Codes | [optional] [default to null] |
| **LineAmountTypes** | [**LineAmountTypes**](LineAmountTypes.md) |  | [optional] [default to null] |
| **SubTotal** | **Double** | Total of bank transaction excluding taxes | [optional] [default to null] |
| **TotalTax** | **Double** | Total tax on bank transaction | [optional] [default to null] |
| **Total** | **Double** | Total of bank transaction tax inclusive | [optional] [default to null] |
| **BankTransactionID** | **UUID** | Xero generated unique identifier for bank transaction | [optional] [default to null] |
| **PrepaymentID** | **UUID** | Xero generated unique identifier for a Prepayment. This will be returned on BankTransactions with a Type of SPEND-PREPAYMENT or RECEIVE-PREPAYMENT | [optional] [default to null] |
| **OverpaymentID** | **UUID** | Xero generated unique identifier for an Overpayment. This will be returned on BankTransactions with a Type of SPEND-OVERPAYMENT or RECEIVE-OVERPAYMENT | [optional] [default to null] |
| **UpdatedDateUTC** | **String** | Last modified date UTC format | [optional] [default to null] |
| **HasAttachments** | **Boolean** | Boolean to indicate if a bank transaction has an attachment | [optional] [default to false] |
| **StatusAttributeString** | **String** | A string to indicate if a invoice status | [optional] [default to null] |
| **ValidationErrors** | [**List**](ValidationError.md) | Displays array of validation error messages from the API | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

