## Document
Document object represents an update to a document to show the document as submitted / completed from EPay Advantage to another system. This will always need to be sent as an array or list.

| Attribute | Data Type | Definition | Max Length |
| :----------- | :--------- | :--------- | :--------- |
| ErrorMessage | String | Error message to be displayed onto the document to show the document as not submitted | nvarchar(25) |
| ID | String | Document number or uniqueidentifier  | nvarchar(50) |
| IsSubmitted | Boolean | Indicates if the document will show as submitted | bit |
