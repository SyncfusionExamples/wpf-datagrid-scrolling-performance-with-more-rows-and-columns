# WPF DataGrid - Scrolling performance with more number of rows and columns

By default, datagrid loads textblock as cell content and re-uses the same during scroll operations. Compare to loading textblock drawing the text will enhance the performance. You can change the rendering mode of datagrid to drawing by setting UseDrawing as Default to improve loading and also scrolling performance. To learn more about changing the rendering more read [improving loading and scrolling performance using light weight templates](https://help.syncfusion.com/wpf/sfdatagrid/performance#improving-loading-and-scrolling-performance-using-lightweighttemplate).


## Reference
[WPF DataGrid Performance](https://help.syncfusion.com/wpf/sfdatagrid/performance)

[WPF DataGrid](https://www.syncfusion.com/products/wpf-ui-controls/datagrid)

## More examples


[WPF DataGrid - Working with large numbers of records](https://github.com/SyncfusionExamples/working-with-large-numbers-of-records-in-wpf-datagrid)

[WPF DataGrid Performance - Asynchronous scrolling example](https://github.com/SyncfusionExamples/wpf-datagrid-asynchronous-scrolling)
