## Invoice Line Item
Invoice line item object represents a line item to be associated to an invoice. This will always need to be sent as an array or list. This object may be included as a child attribute of other JSON objects (such as [Invoice](Invoice.md)).

| Attribute | Data Type | Definition | Max Length |
| :----------- | :--------- | :--------- | :--------- |
| Description | String | Description of the item | nvarchar(101) |
| ExtendedPrice | Decimal | Extended price in the functional currency | decimal(19,2) |
| InvoiceNumber | String | Invoice number | nvarchar(30) |
| InvoiceType | Int | Invoice type | int |
| ItemCode | String | Item code | nvarchar(50) |
| Markdown | Decimal | Markdown amount in the functional currency | decimal(19,5) |
| MarkdownPercentage | Decimal | Markdown percentage | decimal(19,5) |
| NonInventory | Boolean | Indicates if the item is a valid predefined item | bit |
| OriginatingExtendedPrice | Decimal | Extended price in the invoice currency | decimal(19,2) |
| OriginatingMarkdown | Decimal | Markdown amount in the invoice currency | decimal(19,5) |
| OriginatingTaxAmount | Decimal | Tax amount in the invoice currency | decimal(19,2) |
| OriginatingUnitPrice | Decimal | Unit price in the invoice currency | decimal(19,5) |
| PriceLevel | String | Price level | varchar(50) |
| Quantity | Decimal | Number of quantity | decimal(19,2) |
| ReqShipDate\* | String | Timestamp indicating when this item is required to ship. Format must be "YYYY-MM-DD" or "YYYY-MM-DD HH:mm:ss" | datetime |
| SalesPersonID | String | SalesPerson number | nvarchar(25) |
| Sequence | Int | Line item number identifier | int |
| ShipToAddress | [Object](Address.md) | Address object |
| ShippingMethod | String | Shipping method name | varchar(100) |
| SiteID | String | Ship from site / warehouse | nvarchar(25) |
| TaxAmount | Decimal | Tax amount in the functional currency | decimal(19,2) |
| Taxable | Boolean | Indicates if the item is taxable | bit |
| UnitOfMeasure | String | Unit of measure | nvarchar(25) |
| UnitPrice | Decimal | Unit price in the functional currency | decimal(19,2) |
\*Required
