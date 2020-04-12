---
type: Array<any>
---
---
##### shortDescription
An array of items displayed by the widget.

---
You can use the [dataSource](/api-reference/10%20UI%20Widgets/DataExpressionMixin/1%20Configuration/dataSource.md '{basewidgetpath}/Configuration/#dataSource') option instead. Unlike the **items** option, the **dataSource** option can take on the [DataSource](/api-reference/30%20Data%20Layer/DataSource '/Documentation/ApiReference/Data_Layer/DataSource/') configuration object as well as a simple array.

[note]If you need to modify the data source specified using the **items** option at runtime, do it only with the help of the **items** option. Updating data items using the [dataSource](/api-reference/10%20UI%20Widgets/DataExpressionMixin/1%20Configuration/dataSource.md '{basewidgetpath}/Configuration/#dataSource') option may cause unexpected results.