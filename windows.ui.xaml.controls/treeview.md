---
-api-id: T:Windows.UI.Xaml.Controls.TreeView
-api-type: winrt class
---

<!-- Class syntax.
public class TreeView : Control, Control
-->

# Windows.UI.Xaml.Controls.TreeView

## -description

Represents a hierarchical list with expanding and collapsing nodes that contain nested items. 

Equivalent **WinUI 2 API for UWP**: [Microsoft.UI.Xaml.Controls.TreeView](/windows/winui/api/microsoft.ui.xaml.controls.treeview) (for WinUI in the [Windows App SDK](/windows/apps/windows-app-sdk/), see the **[Windows App SDK namespaces](/windows/windows-app-sdk/api/winrt/)**).

## -remarks

If you need to handle pointer events for a [UIElement](../windows.ui.xaml/uielement.md) in a scrollable view (such as a ScrollViewer), you must explicitly disable support for manipulation events on the element in the view by calling [UIElement.CancelDirectmanipulation()](../windows.ui.xaml/uielement_canceldirectmanipulations_1164631120.md). To re-enable manipulation events in the view, call [UIElement.TryStartDirectManipulation()](../windows.ui.xaml/uielement_trystartdirectmanipulation_1983346775.md).

### Control style and template

You can modify the default [Style](../windows.ui.xaml/style.md) and [ControlTemplate](controltemplate.md) to give the control a unique appearance. For information about modifying a control's style and template, see [XAML styles](/windows/apps/design/style/xaml-styles). XAML also includes resources that you can use to modify the colors of a control in different visual states without modifying the control template. Modifying these resources is preferred to setting properties such as [Background](control_background.md) and [Foreground](control_foreground.md). For more info, see the [Light-weight styling](/windows/apps/design/style/xaml-styles#lightweight-styling) section of the [XAML styles](/windows/apps/design/style/xaml-styles) article.

**WinUI Styles (recommended):** Use [Microsoft.UI.Xaml.Controls.TreeView](/windows/winui/api/microsoft.ui.xaml.controls.treeview).

**Non-WinUI styles:** When you use the built-in styles, the default style, template, and resources that define the look of the control are included in the generic.xaml file. For design purposes, generic.xaml is available in the \(Program Files)\Windows Kits\10\DesignTime\CommonConfiguration\Neutral\UAP\ &lt;SDK version&gt;\Generic folder from a Windows SDK installation. Light-weight styling resources are available starting in Windows 10, version 1607 (SDK 14393). Styles and resources from different versions of the SDK might have different values.

### Version history

| Windows version | SDK version | Value added |
| -- | -- | -- |
| 1809 | 17763 | CanDragItems |
| 1809 | 17763 | CanReorderItems |
| 1809 | 17763 | ContainerFromItem |
| 1809 | 17763 | ContainerFromNode |
| 1809 | 17763 | DragItemsCompleted |
| 1809 | 17763 | DragItemsStarting |
| 1809 | 17763 | ItemContainerStyle |
| 1809 | 17763 | ItemContainerStyleSelector |
| 1809 | 17763 | ItemContainerTransitions |
| 1809 | 17763 | ItemFromContainer |
| 1809 | 17763 | ItemsSource |
| 1809 | 17763 | ItemTemplate |
| 1809 | 17763 | ItemTemplateSelector |
| 1809 | 17763 | NodeFromContainer |

## -see-also

## -examples

> [!TIP]
> For more info, design guidance, and code examples, see [Tree view](/windows/apps/design/controls/tree-view).

> [!div class="nextstepaction"]
> [Open the WinUI 2 Gallery app and see the TreeView in action](winui2gallery:/item/TreeView)

> The **WinUI 2 Gallery** app includes interactive examples of most WinUI 2 controls, features, and functionality. Get the app from the [Microsoft Store](https://www.microsoft.com/store/productId/9MSVH128X2ZT) or get the source code on [GitHub](https://github.com/Microsoft/WinUI-Gallery/tree/winui2).
