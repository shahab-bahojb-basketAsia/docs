# PurchaseOrder
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **Contact** | [**Contact**](Contact.md) |  | [optional] [default to null] |
| **LineItems** | [**List**](LineItem.md) | See LineItems | [optional] [default to null] |
| **Date** | **String** | Date purchase order was issued – YYYY-MM-DD. If the Date element is not specified then it will default to the current date based on the timezone setting of the organisation | [optional] [default to null] |
| **DeliveryDate** | **String** | Date the goods are to be delivered – YYYY-MM-DD | [optional] [default to null] |
| **LineAmountTypes** | [**LineAmountTypes**](LineAmountTypes.md) |  | [optional] [default to null] |
| **PurchaseOrderNumber** | **String** | Unique alpha numeric code identifying purchase order (when missing will auto-generate from your Organisation Invoice Settings) | [optional] [default to null] |
| **Reference** | **String** | Additional reference number | [optional] [default to null] |
| **BrandingThemeID** | **UUID** | See BrandingThemes | [optional] [default to null] |
| **CurrencyCode** | [**CurrencyCode**](CurrencyCode.md) |  | [optional] [default to null] |
| **Status** | **String** | See Purchase Order Status Codes | [optional] [default to null] |
| **SentToContact** | **Boolean** | Boolean to set whether the purchase order should be marked as “sent”. This can be set only on purchase orders that have been approved or billed | [optional] [default to null] |
| **DeliveryAddress** | **String** | The address the goods are to be delivered to | [optional] [default to null] |
| **AttentionTo** | **String** | The person that the delivery is going to | [optional] [default to null] |
| **Telephone** | **String** | The phone number for the person accepting the delivery | [optional] [default to null] |
| **DeliveryInstructions** | **String** | A free text feild for instructions (500 characters max) | [optional] [default to null] |
| **ExpectedArrivalDate** | **String** | The date the goods are expected to arrive. | [optional] [default to null] |
| **PurchaseOrderID** | **UUID** | Xero generated unique identifier for purchase order | [optional] [default to null] |
| **CurrencyRate** | **Double** | The currency rate for a multicurrency purchase order. If no rate is specified, the XE.com day rate is used. | [optional] [default to null] |
| **SubTotal** | **Double** | Total of purchase order excluding taxes | [optional] [default to null] |
| **TotalTax** | **Double** | Total tax on purchase order | [optional] [default to null] |
| **Total** | **Double** | Total of Purchase Order tax inclusive (i.e. SubTotal + TotalTax) | [optional] [default to null] |
| **TotalDiscount** | **Double** | Total of discounts applied on the purchase order line items | [optional] [default to null] |
| **HasAttachments** | **Boolean** | boolean to indicate if a purchase order has an attachment | [optional] [default to false] |
| **UpdatedDateUTC** | **String** | Last modified date UTC format | [optional] [default to null] |
| **StatusAttributeString** | **String** | A string to indicate if a invoice status | [optional] [default to null] |
| **ValidationErrors** | [**List**](ValidationError.md) | Displays array of validation error messages from the API | [optional] [default to null] |
| **Warnings** | [**List**](ValidationError.md) | Displays array of warning messages from the API | [optional] [default to null] |
| **Attachments** | [**List**](Attachment.md) | Displays array of attachments from the API | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

