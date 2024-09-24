# CreditNote
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **Type** | **String** | See Credit Note Types | [optional] [default to null] |
| **Contact** | [**Contact**](Contact.md) |  | [optional] [default to null] |
| **Date** | **String** | The date the credit note is issued YYYY-MM-DD. If the Date element is not specified then it will default to the current date based on the timezone setting of the organisation | [optional] [default to null] |
| **DueDate** | **String** | Date invoice is due – YYYY-MM-DD | [optional] [default to null] |
| **Status** | **String** | See Credit Note Status Codes | [optional] [default to null] |
| **LineAmountTypes** | [**LineAmountTypes**](LineAmountTypes.md) |  | [optional] [default to null] |
| **LineItems** | [**List**](LineItem.md) | See Invoice Line Items | [optional] [default to null] |
| **SubTotal** | **Double** | The subtotal of the credit note excluding taxes | [optional] [default to null] |
| **TotalTax** | **Double** | The total tax on the credit note | [optional] [default to null] |
| **Total** | **Double** | The total of the Credit Note(subtotal + total tax) | [optional] [default to null] |
| **CISDeduction** | **Double** | CIS deduction for UK contractors | [optional] [default to null] |
| **CISRate** | **Double** | CIS Deduction rate for the organisation | [optional] [default to null] |
| **UpdatedDateUTC** | **String** | UTC timestamp of last update to the credit note | [optional] [default to null] |
| **CurrencyCode** | [**CurrencyCode**](CurrencyCode.md) |  | [optional] [default to null] |
| **FullyPaidOnDate** | **String** | Date when credit note was fully paid(UTC format) | [optional] [default to null] |
| **CreditNoteID** | **UUID** | Xero generated unique identifier | [optional] [default to null] |
| **CreditNoteNumber** | **String** | ACCRECCREDIT – Unique alpha numeric code identifying credit note (when missing will auto-generate from your Organisation Invoice Settings) | [optional] [default to null] |
| **Reference** | **String** | ACCRECCREDIT only – additional reference number | [optional] [default to null] |
| **SentToContact** | **Boolean** | Boolean to set whether the credit note in the Xero app should be marked as “sent”. This can be set only on credit notes that have been approved | [optional] [default to null] |
| **CurrencyRate** | **Double** | The currency rate for a multicurrency invoice. If no rate is specified, the XE.com day rate is used | [optional] [default to null] |
| **RemainingCredit** | **Double** | The remaining credit balance on the Credit Note | [optional] [default to null] |
| **Allocations** | [**List**](Allocation.md) | See Allocations | [optional] [default to null] |
| **AppliedAmount** | **Double** | The amount of applied to an invoice | [optional] [default to null] |
| **Payments** | [**List**](Payment.md) | See Payments | [optional] [default to null] |
| **BrandingThemeID** | **UUID** | See BrandingThemes | [optional] [default to null] |
| **StatusAttributeString** | **String** | A string to indicate if a invoice status | [optional] [default to null] |
| **HasAttachments** | **Boolean** | boolean to indicate if a credit note has an attachment | [optional] [default to false] |
| **HasErrors** | **Boolean** | A boolean to indicate if a credit note has an validation errors | [optional] [default to false] |
| **ValidationErrors** | [**List**](ValidationError.md) | Displays array of validation error messages from the API | [optional] [default to null] |
| **Warnings** | [**List**](ValidationError.md) | Displays array of warning messages from the API | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

