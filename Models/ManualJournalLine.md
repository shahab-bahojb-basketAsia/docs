# ManualJournalLine
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **LineAmount** | **Double** | total for line. Debits are positive, credits are negative value | [optional] [default to null] |
| **AccountCode** | **String** | See Accounts | [optional] [default to null] |
| **AccountID** | **UUID** | See Accounts | [optional] [default to null] |
| **Description** | **String** | Description for journal line | [optional] [default to null] |
| **TaxType** | **String** | The tax type from TaxRates | [optional] [default to null] |
| **Tracking** | [**List**](TrackingCategory.md) | Optional Tracking Category – see Tracking. Any JournalLine can have a maximum of 2 &lt;TrackingCategory&gt; elements. | [optional] [default to null] |
| **TaxAmount** | **Double** | The calculated tax amount based on the TaxType and LineAmount | [optional] [default to null] |
| **IsBlank** | **Boolean** | is the line blank | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

