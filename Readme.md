<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128631935/13.1.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E714)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# Data Grid for Windows Forms - How to show tooltips for grid cells even if their content is completely visible

The [ToolTipController](https://docs.devexpress.com/WindowsForms/DevExpress.Utils.ToolTipController) component allows you to manage tooltip behavior for DevExpress Windows Forms controls. 
This example handles the [ToolTipController.GetActiveObjectInfo](https://docs.devexpress.com/WindowsForms/DevExpress.Utils.ToolTipController.GetActiveObjectInfo) event to forcibly display tooltips for grid cells even if cell content is not trimmed. The event handler checks if the `e.Info` event parameter is `null`, and the mouse pointer is over a grid cell. In this case, the code creates a tooltip object for the hovered cell.

<!-- default file list -->
## Files to Look At
* **[Form1.cs](./CS/AlwaysShowCellHints/Form1.cs) (VB: [Form1.vb](./VB/AlwaysShowCellHints/Form1.vb))**
<!-- default file list end -->

## Documentation
- [ToolTipController](https://docs.devexpress.com/WindowsForms/DevExpress.Utils.ToolTipController)
- [ToolTipController.GetActiveObjectInfo](https://docs.devexpress.com/WindowsForms/DevExpress.Utils.ToolTipController.GetActiveObjectInfo)
- [Data Grid Tooltips](https://docs.devexpress.com/WindowsForms/3512/controls-and-libraries/data-grid/data-grid-tooltips)
