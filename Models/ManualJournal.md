# ManualJournal
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **Narration** | **String** | Description of journal being posted | [default to null] |
| **JournalLines** | [**List**](ManualJournalLine.md) | See JournalLines | [optional] [default to null] |
| **Date** | **String** | Date journal was posted – YYYY-MM-DD | [optional] [default to null] |
| **LineAmountTypes** | [**LineAmountTypes**](LineAmountTypes.md) |  | [optional] [default to null] |
| **Status** | **String** | See Manual Journal Status Codes | [optional] [default to null] |
| **Url** | **String** | Url link to a source document – shown as “Go to [appName]” in the Xero app | [optional] [default to null] |
| **ShowOnCashBasisReports** | **Boolean** | Boolean – default is true if not specified | [optional] [default to null] |
| **HasAttachments** | **Boolean** | Boolean to indicate if a manual journal has an attachment | [optional] [default to false] |
| **UpdatedDateUTC** | **String** | Last modified date UTC format | [optional] [default to null] |
| **ManualJournalID** | **UUID** | The Xero identifier for a Manual Journal | [optional] [default to null] |
| **StatusAttributeString** | **String** | A string to indicate if a invoice status | [optional] [default to null] |
| **Warnings** | [**List**](ValidationError.md) | Displays array of warning messages from the API | [optional] [default to null] |
| **ValidationErrors** | [**List**](ValidationError.md) | Displays array of validation error messages from the API | [optional] [default to null] |
| **Attachments** | [**List**](Attachment.md) | Displays array of attachments from the API | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

