# Journal
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **JournalID** | **UUID** | Xero identifier | [optional] [default to null] |
| **JournalDate** | **String** | Date the journal was posted | [optional] [default to null] |
| **JournalNumber** | **Integer** | Xero generated journal number | [optional] [default to null] |
| **CreatedDateUTC** | **String** | Created date UTC format | [optional] [default to null] |
| **Reference** | **String** | reference field for additional indetifying information | [optional] [default to null] |
| **SourceID** | **UUID** | The identifier for the source transaction (e.g. InvoiceID) | [optional] [default to null] |
| **SourceType** | **String** | The journal source type. The type of transaction that created the journal | [optional] [default to null] |
| **JournalLines** | [**List**](JournalLine.md) | See JournalLines | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

