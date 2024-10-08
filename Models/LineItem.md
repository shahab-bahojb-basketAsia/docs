# LineItem
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **LineItemID** | **UUID** | LineItem unique ID | [optional] [default to null] |
| **Description** | **String** | Description needs to be at least 1 char long. A line item with just a description (i.e no unit amount or quantity) can be created by specifying just a &lt;Description&gt; element that contains at least 1 character | [optional] [default to null] |
| **Quantity** | **Double** | LineItem Quantity | [optional] [default to null] |
| **UnitAmount** | **Double** | LineItem Unit Amount | [optional] [default to null] |
| **ItemCode** | **String** | See Items | [optional] [default to null] |
| **AccountCode** | **String** | See Accounts | [optional] [default to null] |
| **AccountID** | **UUID** | The associated account ID related to this line item | [optional] [default to null] |
| **TaxType** | **String** | The tax type from TaxRates | [optional] [default to null] |
| **TaxAmount** | **Double** | The tax amount is auto calculated as a percentage of the line amount (see below) based on the tax rate. This value can be overriden if the calculated &lt;TaxAmount&gt; is not correct. | [optional] [default to null] |
| **Item** | [**LineItemItem**](LineItemItem.md) |  | [optional] [default to null] |
| **LineAmount** | **Double** | If you wish to omit either the Quantity or UnitAmount you can provide a LineAmount and Xero will calculate the missing amount for you. The line amount reflects the discounted price if either a DiscountRate or DiscountAmount has been used i.e. LineAmount &#x3D; Quantity * Unit Amount * ((100 - DiscountRate)/100) or LineAmount &#x3D; (Quantity * UnitAmount) - DiscountAmount | [optional] [default to null] |
| **Tracking** | [**List**](LineItemTracking.md) | Optional Tracking Category – see Tracking.  Any LineItem can have a  maximum of 2 &lt;TrackingCategory&gt; elements. | [optional] [default to null] |
| **DiscountRate** | **Double** | Percentage discount being applied to a line item (only supported on  ACCREC invoices – ACC PAY invoices and credit notes in Xero do not support discounts | [optional] [default to null] |
| **DiscountAmount** | **Double** | Discount amount being applied to a line item. Only supported on ACCREC invoices and quotes. ACCPAY invoices and credit notes in Xero do not support discounts. | [optional] [default to null] |
| **RepeatingInvoiceID** | **UUID** | The Xero identifier for a Repeating Invoice | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

