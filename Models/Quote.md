# Quote
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **QuoteID** | **UUID** | QuoteID GUID is automatically generated and is returned after create or GET. | [optional] [default to null] |
| **QuoteNumber** | **String** | Unique alpha numeric code identifying a quote (Max Length &#x3D; 255) | [optional] [default to null] |
| **Reference** | **String** | Additional reference number | [optional] [default to null] |
| **Terms** | **String** | Terms of the quote | [optional] [default to null] |
| **Contact** | [**Contact**](Contact.md) |  | [optional] [default to null] |
| **LineItems** | [**List**](LineItem.md) | See LineItems | [optional] [default to null] |
| **Date** | **String** | Date quote was issued – YYYY-MM-DD. If the Date element is not specified it will default to the current date based on the timezone setting of the organisation | [optional] [default to null] |
| **DateString** | **String** | Date the quote was issued (YYYY-MM-DD) | [optional] [default to null] |
| **ExpiryDate** | **String** | Date the quote expires – YYYY-MM-DD. | [optional] [default to null] |
| **ExpiryDateString** | **String** | Date the quote expires – YYYY-MM-DD. | [optional] [default to null] |
| **Status** | [**QuoteStatusCodes**](QuoteStatusCodes.md) |  | [optional] [default to null] |
| **CurrencyCode** | [**CurrencyCode**](CurrencyCode.md) |  | [optional] [default to null] |
| **CurrencyRate** | **Double** | The currency rate for a multicurrency quote | [optional] [default to null] |
| **SubTotal** | **Double** | Total of quote excluding taxes. | [optional] [default to null] |
| **TotalTax** | **Double** | Total tax on quote | [optional] [default to null] |
| **Total** | **Double** | Total of Quote tax inclusive (i.e. SubTotal + TotalTax). This will be ignored if it doesn’t equal the sum of the LineAmounts | [optional] [default to null] |
| **TotalDiscount** | **Double** | Total of discounts applied on the quote line items | [optional] [default to null] |
| **Title** | **String** | Title text for the quote | [optional] [default to null] |
| **Summary** | **String** | Summary text for the quote | [optional] [default to null] |
| **BrandingThemeID** | **UUID** | See BrandingThemes | [optional] [default to null] |
| **UpdatedDateUTC** | **String** | Last modified date UTC format | [optional] [default to null] |
| **LineAmountTypes** | [**QuoteLineAmountTypes**](QuoteLineAmountTypes.md) |  | [optional] [default to null] |
| **StatusAttributeString** | **String** | A string to indicate if a invoice status | [optional] [default to null] |
| **ValidationErrors** | [**List**](ValidationError.md) | Displays array of validation error messages from the API | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

