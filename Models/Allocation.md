# Allocation
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **AllocationID** | **UUID** | Xero generated unique identifier | [optional] [default to null] |
| **Invoice** | [**Invoice**](Invoice.md) |  | [default to null] |
| **Overpayment** | [**Overpayment**](Overpayment.md) |  | [optional] [default to null] |
| **Prepayment** | [**Prepayment**](Prepayment.md) |  | [optional] [default to null] |
| **CreditNote** | [**CreditNote**](CreditNote.md) |  | [optional] [default to null] |
| **Amount** | **Double** | the amount being applied to the invoice | [default to null] |
| **Date** | **String** | the date the allocation is applied YYYY-MM-DD. | [default to null] |
| **IsDeleted** | **Boolean** | A flag that returns true when the allocation is succesfully deleted | [optional] [default to null] |
| **StatusAttributeString** | **String** | A string to indicate if a invoice status | [optional] [default to null] |
| **ValidationErrors** | [**List**](ValidationError.md) | Displays array of validation error messages from the API | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

