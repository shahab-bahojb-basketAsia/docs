# Receipt
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **Date** | **String** | Date of receipt – YYYY-MM-DD | [optional] [default to null] |
| **Contact** | [**Contact**](Contact.md) |  | [optional] [default to null] |
| **LineItems** | [**List**](LineItem.md) |  | [optional] [default to null] |
| **User** | [**User**](User.md) |  | [optional] [default to null] |
| **Reference** | **String** | Additional reference number | [optional] [default to null] |
| **LineAmountTypes** | [**LineAmountTypes**](LineAmountTypes.md) |  | [optional] [default to null] |
| **SubTotal** | **Double** | Total of receipt excluding taxes | [optional] [default to null] |
| **TotalTax** | **Double** | Total tax on receipt | [optional] [default to null] |
| **Total** | **Double** | Total of receipt tax inclusive (i.e. SubTotal + TotalTax) | [optional] [default to null] |
| **ReceiptID** | **UUID** | Xero generated unique identifier for receipt | [optional] [default to null] |
| **Status** | **String** | Current status of receipt – see status types | [optional] [default to null] |
| **ReceiptNumber** | **String** | Xero generated sequence number for receipt in current claim for a given user | [optional] [default to null] |
| **UpdatedDateUTC** | **String** | Last modified date UTC format | [optional] [default to null] |
| **HasAttachments** | **Boolean** | boolean to indicate if a receipt has an attachment | [optional] [default to false] |
| **Url** | **String** | URL link to a source document – shown as “Go to [appName]” in the Xero app | [optional] [default to null] |
| **ValidationErrors** | [**List**](ValidationError.md) | Displays array of validation error messages from the API | [optional] [default to null] |
| **Warnings** | [**List**](ValidationError.md) | Displays array of warning messages from the API | [optional] [default to null] |
| **Attachments** | [**List**](Attachment.md) | Displays array of attachments from the API | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

