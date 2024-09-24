# Organisation
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **OrganisationID** | **UUID** | Unique Xero identifier | [optional] [default to null] |
| **APIKey** | **String** | Display a unique key used for Xero-to-Xero transactions | [optional] [default to null] |
| **Name** | **String** | Display name of organisation shown in Xero | [optional] [default to null] |
| **LegalName** | **String** | Organisation name shown on Reports | [optional] [default to null] |
| **PaysTax** | **Boolean** | Boolean to describe if organisation is registered with a local tax authority i.e. true, false | [optional] [default to null] |
| **Version** | **String** | See Version Types | [optional] [default to null] |
| **OrganisationType** | **String** | Organisation Type | [optional] [default to null] |
| **BaseCurrency** | [**CurrencyCode**](CurrencyCode.md) |  | [optional] [default to null] |
| **CountryCode** | [**CountryCode**](CountryCode.md) |  | [optional] [default to null] |
| **IsDemoCompany** | **Boolean** | Boolean to describe if organisation is a demo company. | [optional] [default to null] |
| **OrganisationStatus** | **String** | Will be set to ACTIVE if you can connect to organisation via the Xero API | [optional] [default to null] |
| **RegistrationNumber** | **String** | Shows for New Zealand, Australian and UK organisations | [optional] [default to null] |
| **EmployerIdentificationNumber** | **String** | Shown if set. US Only. | [optional] [default to null] |
| **TaxNumber** | **String** | Shown if set. Displays in the Xero UI as Tax File Number (AU), GST Number (NZ), VAT Number (UK) and Tax ID Number (US &amp; Global). | [optional] [default to null] |
| **FinancialYearEndDay** | **Integer** | Calendar day e.g. 0-31 | [optional] [default to null] |
| **FinancialYearEndMonth** | **Integer** | Calendar Month e.g. 1-12 | [optional] [default to null] |
| **SalesTaxBasis** | **String** | The accounting basis used for tax returns. See Sales Tax Basis | [optional] [default to null] |
| **SalesTaxPeriod** | **String** | The frequency with which tax returns are processed. See Sales Tax Period | [optional] [default to null] |
| **DefaultSalesTax** | **String** | The default for LineAmountTypes on sales transactions | [optional] [default to null] |
| **DefaultPurchasesTax** | **String** | The default for LineAmountTypes on purchase transactions | [optional] [default to null] |
| **PeriodLockDate** | **String** | Shown if set. See lock dates | [optional] [default to null] |
| **EndOfYearLockDate** | **String** | Shown if set. See lock dates | [optional] [default to null] |
| **CreatedDateUTC** | **String** | Timestamp when the organisation was created in Xero | [optional] [default to null] |
| **Timezone** | [**TimeZone**](TimeZone.md) |  | [optional] [default to null] |
| **OrganisationEntityType** | **String** | Organisation Entity Type | [optional] [default to null] |
| **ShortCode** | **String** | A unique identifier for the organisation. Potential uses. | [optional] [default to null] |
| **Class** | **String** | Organisation Classes describe which plan the Xero organisation is on (e.g. DEMO, TRIAL, PREMIUM) | [optional] [default to null] |
| **Edition** | **String** | BUSINESS or PARTNER. Partner edition organisations are sold exclusively through accounting partners and have restricted functionality (e.g. no access to invoicing) | [optional] [default to null] |
| **LineOfBusiness** | **String** | Description of business type as defined in Organisation settings | [optional] [default to null] |
| **Addresses** | [**List**](AddressForOrganisation.md) | Address details for organisation – see Addresses | [optional] [default to null] |
| **Phones** | [**List**](Phone.md) | Phones details for organisation – see Phones | [optional] [default to null] |
| **ExternalLinks** | [**List**](ExternalLink.md) | Organisation profile links for popular services such as Facebook,Twitter, GooglePlus and LinkedIn. You can also add link to your website here. Shown if Organisation settings  is updated in Xero. See ExternalLinks below | [optional] [default to null] |
| **PaymentTerms** | [**PaymentTerm**](PaymentTerm.md) |  | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

