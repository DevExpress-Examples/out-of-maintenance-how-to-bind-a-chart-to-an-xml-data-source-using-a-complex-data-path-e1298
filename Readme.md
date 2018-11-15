<!-- default file list -->
*Files to look at*:

* [Window1.xaml](./CS/Window1.xaml) (VB: [Window1.xaml](./VB/Window1.xaml))
<!-- default file list end -->
# How to bind a chart to an XML data source using a complex data path


<p>The following example demonstrates how to bind a chart to using a complex data path with dots.</p><p>To accomplish this task, it is necessary to add an <strong>XmlDataProvider</strong> object to a collection of the window's static resources, then assign this resource to a series' <strong>DataSource</strong> property, and then set the <strong>ArgumentDataMember</strong> and <strong>ValueDataMember</strong> properties to the complex names of XML elements (containing a path to a specific XML node) that should provide data for arguments and value.</p><p>Note that this approach to data binding is done completely in XAML, and no code-behind file is required.</p>

<br/>


