# Invoice
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **Type** | **String** | See Invoice Types | [optional] [default to null] |
| **Contact** | [**Contact**](Contact.md) |  | [optional] [default to null] |
| **LineItems** | [**List**](LineItem.md) | See LineItems | [optional] [default to null] |
| **Date** | **String** | Date invoice was issued – YYYY-MM-DD. If the Date element is not specified it will default to the current date based on the timezone setting of the organisation | [optional] [default to null] |
| **DueDate** | **String** | Date invoice is due – YYYY-MM-DD | [optional] [default to null] |
| **LineAmountTypes** | [**LineAmountTypes**](LineAmountTypes.md) |  | [optional] [default to null] |
| **InvoiceNumber** | **String** | ACCREC – Unique alpha numeric code identifying invoice (when missing will auto-generate from your Organisation Invoice Settings) (max length &#x3D; 255) | [optional] [default to null] |
| **Reference** | **String** | ACCREC only – additional reference number | [optional] [default to null] |
| **BrandingThemeID** | **UUID** | See BrandingThemes | [optional] [default to null] |
| **Url** | **String** | URL link to a source document – shown as “Go to [appName]” in the Xero app | [optional] [default to null] |
| **CurrencyCode** | [**CurrencyCode**](CurrencyCode.md) |  | [optional] [default to null] |
| **CurrencyRate** | **Double** | The currency rate for a multicurrency invoice. If no rate is specified, the XE.com day rate is used. (max length &#x3D; [18].[6]) | [optional] [default to null] |
| **Status** | **String** | See Invoice Status Codes | [optional] [default to null] |
| **SentToContact** | **Boolean** | Boolean to set whether the invoice in the Xero app should be marked as “sent”. This can be set only on invoices that have been approved | [optional] [default to null] |
| **ExpectedPaymentDate** | **String** | Shown on sales invoices (Accounts Receivable) when this has been set | [optional] [default to null] |
| **PlannedPaymentDate** | **String** | Shown on bills (Accounts Payable) when this has been set | [optional] [default to null] |
| **CISDeduction** | **Double** | CIS deduction for UK contractors | [optional] [default to null] |
| **CISRate** | **Double** | CIS Deduction rate for the organisation | [optional] [default to null] |
| **SubTotal** | **Double** | Total of invoice excluding taxes | [optional] [default to null] |
| **TotalTax** | **Double** | Total tax on invoice | [optional] [default to null] |
| **Total** | **Double** | Total of Invoice tax inclusive (i.e. SubTotal + TotalTax). This will be ignored if it doesn’t equal the sum of the LineAmounts | [optional] [default to null] |
| **TotalDiscount** | **Double** | Total of discounts applied on the invoice line items | [optional] [default to null] |
| **InvoiceID** | **UUID** | Xero generated unique identifier for invoice | [optional] [default to null] |
| **RepeatingInvoiceID** | **UUID** | Xero generated unique identifier for repeating invoices | [optional] [default to null] |
| **HasAttachments** | **Boolean** | boolean to indicate if an invoice has an attachment | [optional] [default to false] |
| **IsDiscounted** | **Boolean** | boolean to indicate if an invoice has a discount | [optional] [default to null] |
| **Payments** | [**List**](Payment.md) | See Payments | [optional] [default to null] |
| **Prepayments** | [**List**](Prepayment.md) | See Prepayments | [optional] [default to null] |
| **Overpayments** | [**List**](Overpayment.md) | See Overpayments | [optional] [default to null] |
| **AmountDue** | **Double** | Amount remaining to be paid on invoice | [optional] [default to null] |
| **AmountPaid** | **Double** | Sum of payments received for invoice | [optional] [default to null] |
| **FullyPaidOnDate** | **String** | The date the invoice was fully paid. Only returned on fully paid invoices | [optional] [default to null] |
| **AmountCredited** | **Double** | Sum of all credit notes, over-payments and pre-payments applied to invoice | [optional] [default to null] |
| **UpdatedDateUTC** | **String** | Last modified date UTC format | [optional] [default to null] |
| **CreditNotes** | [**List**](CreditNote.md) | Details of credit notes that have been applied to an invoice | [optional] [default to null] |
| **Attachments** | [**List**](Attachment.md) | Displays array of attachments from the API | [optional] [default to null] |
| **HasErrors** | **Boolean** | A boolean to indicate if a invoice has an validation errors | [optional] [default to false] |
| **StatusAttributeString** | **String** | A string to indicate if a invoice status | [optional] [default to null] |
| **ValidationErrors** | [**List**](ValidationError.md) | Displays array of validation error messages from the API | [optional] [default to null] |
| **Warnings** | [**List**](ValidationError.md) | Displays array of warning messages from the API | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

