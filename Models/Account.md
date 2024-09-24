# Account
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **Code** | **String** | Customer defined alpha numeric account code e.g 200 or SALES (max length &#x3D; 10) | [optional] [default to null] |
| **Name** | **String** | Name of account (max length &#x3D; 150) | [optional] [default to null] |
| **AccountID** | **UUID** | The Xero identifier for an account – specified as a string following  the endpoint name   e.g. /297c2dc5-cc47-4afd-8ec8-74990b8761e9 | [optional] [default to null] |
| **Type** | [**AccountType**](AccountType.md) |  | [optional] [default to null] |
| **BankAccountNumber** | **String** | For bank accounts only (Account Type BANK) | [optional] [default to null] |
| **Status** | **String** | Accounts with a status of ACTIVE can be updated to ARCHIVED. See Account Status Codes | [optional] [default to null] |
| **Description** | **String** | Description of the Account. Valid for all types of accounts except bank accounts (max length &#x3D; 4000) | [optional] [default to null] |
| **BankAccountType** | **String** | For bank accounts only. See Bank Account types | [optional] [default to null] |
| **CurrencyCode** | [**CurrencyCode**](CurrencyCode.md) |  | [optional] [default to null] |
| **TaxType** | **String** | The tax type from taxRates | [optional] [default to null] |
| **EnablePaymentsToAccount** | **Boolean** | Boolean – describes whether account can have payments applied to it | [optional] [default to null] |
| **ShowInExpenseClaims** | **Boolean** | Boolean – describes whether account code is available for use with expense claims | [optional] [default to null] |
| **Class** | **String** | See Account Class Types | [optional] [default to null] |
| **SystemAccount** | **String** | If this is a system account then this element is returned. See System Account types. Note that non-system accounts may have this element set as either “” or null. | [optional] [default to null] |
| **ReportingCode** | **String** | Shown if set | [optional] [default to null] |
| **ReportingCodeName** | **String** | Shown if set | [optional] [default to null] |
| **HasAttachments** | **Boolean** | boolean to indicate if an account has an attachment (read only) | [optional] [default to false] |
| **UpdatedDateUTC** | **String** | Last modified date UTC format | [optional] [default to null] |
| **AddToWatchlist** | **Boolean** | Boolean – describes whether the account is shown in the watchlist widget on the dashboard | [optional] [default to null] |
| **ValidationErrors** | [**List**](ValidationError.md) | Displays array of validation error messages from the API | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

