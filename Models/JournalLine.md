# JournalLine
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **JournalLineID** | **UUID** | Xero identifier for Journal | [optional] [default to null] |
| **AccountID** | **UUID** | See Accounts | [optional] [default to null] |
| **AccountCode** | **String** | See Accounts | [optional] [default to null] |
| **AccountType** | [**AccountType**](AccountType.md) |  | [optional] [default to null] |
| **AccountName** | **String** | See AccountCodes | [optional] [default to null] |
| **Description** | **String** | The description from the source transaction line item. Only returned if populated. | [optional] [default to null] |
| **NetAmount** | **Double** | Net amount of journal line. This will be a positive value for a debit and negative for a credit | [optional] [default to null] |
| **GrossAmount** | **Double** | Gross amount of journal line (NetAmount + TaxAmount). | [optional] [default to null] |
| **TaxAmount** | **Double** | Total tax on a journal line | [optional] [default to null] |
| **TaxType** | **String** | The tax type from taxRates | [optional] [default to null] |
| **TaxName** | **String** | see TaxRates | [optional] [default to null] |
| **TrackingCategories** | [**List**](TrackingCategory.md) | Optional Tracking Category – see Tracking. Any JournalLine can have a maximum of 2 &lt;TrackingCategory&gt; elements. | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

