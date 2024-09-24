# Contact
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **ContactID** | **UUID** | Xero identifier | [optional] [default to null] |
| **MergedToContactID** | **UUID** | ID for the destination of a merged contact. Only returned when using paging or when fetching a contact by ContactId or ContactNumber. | [optional] [default to null] |
| **ContactNumber** | **String** | This can be updated via the API only i.e. This field is read only on the Xero contact screen, used to identify contacts in external systems (max length &#x3D; 50). If the Contact Number is used, this is displayed as Contact Code in the Contacts UI in Xero. | [optional] [default to null] |
| **AccountNumber** | **String** | A user defined account number. This can be updated via the API and the Xero UI (max length &#x3D; 50) | [optional] [default to null] |
| **ContactStatus** | **String** | Current status of a contact – see contact status types | [optional] [default to null] |
| **Name** | **String** | Full name of contact/organisation (max length &#x3D; 255) | [optional] [default to null] |
| **FirstName** | **String** | First name of contact person (max length &#x3D; 255) | [optional] [default to null] |
| **LastName** | **String** | Last name of contact person (max length &#x3D; 255) | [optional] [default to null] |
| **CompanyNumber** | **String** | Company registration number (max length &#x3D; 50) | [optional] [default to null] |
| **EmailAddress** | **String** | Email address of contact person (umlauts not supported) (max length  &#x3D; 255) | [optional] [default to null] |
| **ContactPersons** | [**List**](ContactPerson.md) | See contact persons | [optional] [default to null] |
| **BankAccountDetails** | **String** | Bank account number of contact | [optional] [default to null] |
| **TaxNumber** | **String** | Tax number of contact – this is also known as the ABN (Australia), GST Number (New Zealand), VAT Number (UK) or Tax ID Number (US and global) in the Xero UI depending on which regionalized version of Xero you are using (max length &#x3D; 50) | [optional] [default to null] |
| **AccountsReceivableTaxType** | **String** | The tax type from TaxRates | [optional] [default to null] |
| **AccountsPayableTaxType** | **String** | The tax type from TaxRates | [optional] [default to null] |
| **Addresses** | [**List**](Address.md) | Store certain address types for a contact – see address types | [optional] [default to null] |
| **Phones** | [**List**](Phone.md) | Store certain phone types for a contact – see phone types | [optional] [default to null] |
| **IsSupplier** | **Boolean** | true or false – Boolean that describes if a contact that has any AP  invoices entered against them. Cannot be set via PUT or POST – it is automatically set when an accounts payable invoice is generated against this contact. | [optional] [default to null] |
| **IsCustomer** | **Boolean** | true or false – Boolean that describes if a contact has any AR invoices entered against them. Cannot be set via PUT or POST – it is automatically set when an accounts receivable invoice is generated against this contact. | [optional] [default to null] |
| **SalesDefaultLineAmountType** | **String** | The default sales line amount type for a contact. Only available when summaryOnly parameter or paging is used, or when fetch by ContactId or ContactNumber. | [optional] [default to null] |
| **PurchasesDefaultLineAmountType** | **String** | The default purchases line amount type for a contact Only available when summaryOnly parameter or paging is used, or when fetch by ContactId or ContactNumber. | [optional] [default to null] |
| **DefaultCurrency** | [**CurrencyCode**](CurrencyCode.md) |  | [optional] [default to null] |
| **XeroNetworkKey** | **String** | Store XeroNetworkKey for contacts. | [optional] [default to null] |
| **SalesDefaultAccountCode** | **String** | The default sales account code for contacts | [optional] [default to null] |
| **PurchasesDefaultAccountCode** | **String** | The default purchases account code for contacts | [optional] [default to null] |
| **SalesTrackingCategories** | [**List**](SalesTrackingCategory.md) | The default sales tracking categories for contacts | [optional] [default to null] |
| **PurchasesTrackingCategories** | [**List**](SalesTrackingCategory.md) | The default purchases tracking categories for contacts | [optional] [default to null] |
| **TrackingCategoryName** | **String** | The name of the Tracking Category assigned to the contact under SalesTrackingCategories and PurchasesTrackingCategories | [optional] [default to null] |
| **TrackingCategoryOption** | **String** | The name of the Tracking Option assigned to the contact under SalesTrackingCategories and PurchasesTrackingCategories | [optional] [default to null] |
| **PaymentTerms** | [**PaymentTerm**](PaymentTerm.md) |  | [optional] [default to null] |
| **UpdatedDateUTC** | **String** | UTC timestamp of last update to contact | [optional] [default to null] |
| **ContactGroups** | [**List**](ContactGroup.md) | Displays which contact groups a contact is included in | [optional] [default to null] |
| **Website** | **String** | Website address for contact (read only) | [optional] [default to null] |
| **BrandingTheme** | [**BrandingTheme**](BrandingTheme.md) |  | [optional] [default to null] |
| **BatchPayments** | [**BatchPaymentDetails**](BatchPaymentDetails.md) |  | [optional] [default to null] |
| **Discount** | **Double** | The default discount rate for the contact (read only) | [optional] [default to null] |
| **Balances** | [**Balances**](Balances.md) |  | [optional] [default to null] |
| **Attachments** | [**List**](Attachment.md) | Displays array of attachments from the API | [optional] [default to null] |
| **HasAttachments** | **Boolean** | A boolean to indicate if a contact has an attachment | [optional] [default to false] |
| **ValidationErrors** | [**List**](ValidationError.md) | Displays validation errors returned from the API | [optional] [default to null] |
| **HasValidationErrors** | **Boolean** | A boolean to indicate if a contact has an validation errors | [optional] [default to false] |
| **StatusAttributeString** | **String** | Status of object | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

