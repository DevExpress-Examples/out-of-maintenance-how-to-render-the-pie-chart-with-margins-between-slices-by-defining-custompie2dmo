<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/WpfApplication73/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/WpfApplication73/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/WpfApplication73/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/WpfApplication73/MainWindow.xaml.vb))
<!-- default file list end -->
# How to render the Pie Chart with margins between slices by defining CustomPie2DModel 


<p>This example demonstrates how to define <a href="https://documentation.devexpress.com/WPF/clsDevExpressXpfChartsCustomPie2DModeltopic.aspx">CustomPie2DModel</a> that displays pie slices with additional margins. The default Pie Models render a chart in the following way: the model templates contains a simple ellipse and the Model object has the <a href="https://msdn.microsoft.com/en-us/library/system.windows.uielement.clip(v=vs.110).aspx">Clip Property</a> applied. This clip allows displaying only a slice of the ellipse in the chart control. <br>The custom model template demonstrated here uses a custom rendering approach. Each slice is represented by a <a href="https://msdn.microsoft.com/en-us/library/system.windows.shapes.path(v=vs.110).aspx">Path </a> object. The path's <a href="https://msdn.microsoft.com/en-us/library/system.windows.shapes.path.data(v=vs.110).aspx">Data</a> property is bound to the Clip property of the parent model. </p>
<p>Note that it is also possible to display the point slices with margins using the <a href="https://documentation.devexpress.com/WPF/clsDevExpressXpfChartsPieSeriestopic.aspx">PieSeries.</a><a href="https://documentation.devexpress.com/WPF/DevExpressXpfChartsPieSeries_ExplodedDistancetopic.aspx">ExplodedDistance</a> property. </p>
<p><img src="https://raw.githubusercontent.com/DevExpress-Examples/how-to-render-the-pie-chart-with-margins-between-slices-by-defining-custompie2dmodel-t472229/16.2.3+/media/66d3f842-dbd4-11e6-80bf-00155d62480c.png"></p>

<br/>


