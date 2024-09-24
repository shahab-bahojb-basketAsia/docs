# Overpayment
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **Type** | **String** | See Overpayment Types | [optional] [default to null] |
| **Contact** | [**Contact**](Contact.md) |  | [optional] [default to null] |
| **Date** | **String** | The date the overpayment is created YYYY-MM-DD | [optional] [default to null] |
| **Status** | **String** | See Overpayment Status Codes | [optional] [default to null] |
| **LineAmountTypes** | [**LineAmountTypes**](LineAmountTypes.md) |  | [optional] [default to null] |
| **LineItems** | [**List**](LineItem.md) | See Overpayment Line Items | [optional] [default to null] |
| **SubTotal** | **Double** | The subtotal of the overpayment excluding taxes | [optional] [default to null] |
| **TotalTax** | **Double** | The total tax on the overpayment | [optional] [default to null] |
| **Total** | **Double** | The total of the overpayment (subtotal + total tax) | [optional] [default to null] |
| **UpdatedDateUTC** | **String** | UTC timestamp of last update to the overpayment | [optional] [default to null] |
| **CurrencyCode** | [**CurrencyCode**](CurrencyCode.md) |  | [optional] [default to null] |
| **OverpaymentID** | **UUID** | Xero generated unique identifier | [optional] [default to null] |
| **CurrencyRate** | **Double** | The currency rate for a multicurrency overpayment. If no rate is specified, the XE.com day rate is used | [optional] [default to null] |
| **RemainingCredit** | **Double** | The remaining credit balance on the overpayment | [optional] [default to null] |
| **Allocations** | [**List**](Allocation.md) | See Allocations | [optional] [default to null] |
| **AppliedAmount** | **Double** | The amount of applied to an invoice | [optional] [default to null] |
| **Payments** | [**List**](Payment.md) | See Payments | [optional] [default to null] |
| **HasAttachments** | **Boolean** | boolean to indicate if a overpayment has an attachment | [optional] [default to false] |
| **Attachments** | [**List**](Attachment.md) | See Attachments | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

