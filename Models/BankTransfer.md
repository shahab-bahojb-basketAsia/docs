# BankTransfer
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **FromBankAccount** | [**Account**](Account.md) |  | [default to null] |
| **ToBankAccount** | [**Account**](Account.md) |  | [default to null] |
| **Amount** | **Double** | amount of the transaction | [default to null] |
| **Date** | **String** | The date of the Transfer YYYY-MM-DD | [optional] [default to null] |
| **BankTransferID** | **UUID** | The identifier of the Bank Transfer | [optional] [default to null] |
| **CurrencyRate** | **Double** | The currency rate | [optional] [default to null] |
| **FromBankTransactionID** | **UUID** | The Bank Transaction ID for the source account | [optional] [default to null] |
| **ToBankTransactionID** | **UUID** | The Bank Transaction ID for the destination account | [optional] [default to null] |
| **FromIsReconciled** | **Boolean** | The Bank Transaction boolean to show if it is reconciled for the source account | [optional] [default to false] |
| **ToIsReconciled** | **Boolean** | The Bank Transaction boolean to show if it is reconciled for the destination account | [optional] [default to false] |
| **Reference** | **String** | Reference for the transactions. | [optional] [default to null] |
| **HasAttachments** | **Boolean** | Boolean to indicate if a Bank Transfer has an attachment | [optional] [default to false] |
| **CreatedDateUTC** | **String** | UTC timestamp of creation date of bank transfer | [optional] [default to null] |
| **ValidationErrors** | [**List**](ValidationError.md) | Displays array of validation error messages from the API | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

