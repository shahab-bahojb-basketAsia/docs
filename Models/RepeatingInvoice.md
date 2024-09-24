# RepeatingInvoice
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **Type** | **String** | See Invoice Types | [optional] [default to null] |
| **Contact** | [**Contact**](Contact.md) |  | [optional] [default to null] |
| **Schedule** | [**Schedule**](Schedule.md) |  | [optional] [default to null] |
| **LineItems** | [**List**](LineItem.md) | See LineItems | [optional] [default to null] |
| **LineAmountTypes** | [**LineAmountTypes**](LineAmountTypes.md) |  | [optional] [default to null] |
| **Reference** | **String** | ACCREC only – additional reference number | [optional] [default to null] |
| **BrandingThemeID** | **UUID** | See BrandingThemes | [optional] [default to null] |
| **CurrencyCode** | [**CurrencyCode**](CurrencyCode.md) |  | [optional] [default to null] |
| **Status** | **String** | One of the following - DRAFT or AUTHORISED – See Invoice Status Codes | [optional] [default to null] |
| **SubTotal** | **Double** | Total of invoice excluding taxes | [optional] [default to null] |
| **TotalTax** | **Double** | Total tax on invoice | [optional] [default to null] |
| **Total** | **Double** | Total of Invoice tax inclusive (i.e. SubTotal + TotalTax) | [optional] [default to null] |
| **RepeatingInvoiceID** | **UUID** | Xero generated unique identifier for repeating invoice template | [optional] [default to null] |
| **ID** | **UUID** | Xero generated unique identifier for repeating invoice template | [optional] [default to null] |
| **HasAttachments** | **Boolean** | Boolean to indicate if an invoice has an attachment | [optional] [default to false] |
| **Attachments** | [**List**](Attachment.md) | Displays array of attachments from the API | [optional] [default to null] |
| **ApprovedForSending** | **Boolean** | Boolean to indicate whether the invoice has been approved for sending | [optional] [default to false] |
| **SendCopy** | **Boolean** | Boolean to indicate whether a copy is sent to sender&#39;s email | [optional] [default to false] |
| **MarkAsSent** | **Boolean** | Boolean to indicate whether the invoice in the Xero app displays as \&quot;sent\&quot; | [optional] [default to false] |
| **IncludePDF** | **Boolean** | Boolean to indicate whether to include PDF attachment | [optional] [default to false] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

