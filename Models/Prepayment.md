# Prepayment
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **Type** | **String** | See Prepayment Types | [optional] [default to null] |
| **Contact** | [**Contact**](Contact.md) |  | [optional] [default to null] |
| **Date** | **String** | The date the prepayment is created YYYY-MM-DD | [optional] [default to null] |
| **Status** | **String** | See Prepayment Status Codes | [optional] [default to null] |
| **LineAmountTypes** | [**LineAmountTypes**](LineAmountTypes.md) |  | [optional] [default to null] |
| **LineItems** | [**List**](LineItem.md) | See Prepayment Line Items | [optional] [default to null] |
| **SubTotal** | **Double** | The subtotal of the prepayment excluding taxes | [optional] [default to null] |
| **TotalTax** | **Double** | The total tax on the prepayment | [optional] [default to null] |
| **Total** | **Double** | The total of the prepayment(subtotal + total tax) | [optional] [default to null] |
| **Reference** | **String** | Returns Invoice number field. Reference field isn&#39;t available. | [optional] [default to null] |
| **UpdatedDateUTC** | **String** | UTC timestamp of last update to the prepayment | [optional] [default to null] |
| **CurrencyCode** | [**CurrencyCode**](CurrencyCode.md) |  | [optional] [default to null] |
| **PrepaymentID** | **UUID** | Xero generated unique identifier | [optional] [default to null] |
| **CurrencyRate** | **Double** | The currency rate for a multicurrency prepayment. If no rate is specified, the XE.com day rate is used | [optional] [default to null] |
| **RemainingCredit** | **Double** | The remaining credit balance on the prepayment | [optional] [default to null] |
| **Allocations** | [**List**](Allocation.md) | See Allocations | [optional] [default to null] |
| **Payments** | [**List**](Payment.md) | See Payments | [optional] [default to null] |
| **AppliedAmount** | **Double** | The amount of applied to an invoice | [optional] [default to null] |
| **HasAttachments** | **Boolean** | boolean to indicate if a prepayment has an attachment | [optional] [default to false] |
| **Attachments** | [**List**](Attachment.md) | See Attachments | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

