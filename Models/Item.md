# Item
## Properties

| Name | Type | Description | Notes |
|------------ | ------------- | ------------- | -------------|
| **Code** | **String** | User defined item code (max length &#x3D; 30) | [default to null] |
| **InventoryAssetAccountCode** | **String** | The inventory asset account for the item. The account must be of type INVENTORY. The  COGSAccountCode in PurchaseDetails is also required to create a tracked item | [optional] [default to null] |
| **Name** | **String** | The name of the item (max length &#x3D; 50) | [optional] [default to null] |
| **IsSold** | **Boolean** | Boolean value, defaults to true. When IsSold is true the item will be available on sales transactions in the Xero UI. If IsSold is updated to false then Description and SalesDetails values will be nulled. | [optional] [default to null] |
| **IsPurchased** | **Boolean** | Boolean value, defaults to true. When IsPurchased is true the item is available for purchase transactions in the Xero UI. If IsPurchased is updated to false then PurchaseDescription and PurchaseDetails values will be nulled. | [optional] [default to null] |
| **Description** | **String** | The sales description of the item (max length &#x3D; 4000) | [optional] [default to null] |
| **PurchaseDescription** | **String** | The purchase description of the item (max length &#x3D; 4000) | [optional] [default to null] |
| **PurchaseDetails** | [**Purchase**](Purchase.md) |  | [optional] [default to null] |
| **SalesDetails** | [**Purchase**](Purchase.md) |  | [optional] [default to null] |
| **IsTrackedAsInventory** | **Boolean** | True for items that are tracked as inventory. An item will be tracked as inventory if the InventoryAssetAccountCode and COGSAccountCode are set. | [optional] [default to null] |
| **TotalCostPool** | **Double** | The value of the item on hand. Calculated using average cost accounting. | [optional] [default to null] |
| **QuantityOnHand** | **Double** | The quantity of the item on hand | [optional] [default to null] |
| **UpdatedDateUTC** | **String** | Last modified date in UTC format | [optional] [default to null] |
| **ItemID** | **UUID** | The Xero identifier for an Item | [optional] [default to null] |
| **StatusAttributeString** | **String** | Status of object | [optional] [default to null] |
| **ValidationErrors** | [**List**](ValidationError.md) | Displays array of validation error messages from the API | [optional] [default to null] |

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

