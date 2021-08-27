<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128570625/11.2.7%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E3798)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [MainWindow.xaml](./CS/WpfApplication1/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/WpfApplication1/MainWindow.xaml))
<!-- default file list end -->
# How to integrate a State Indicator with the Circular Gauge control  


<p>The following sample shows how a State Indicator control can be integrated with the Circular Gauge control. This integration forces the State Indicator control to automatically change its state every time when a Value Indicator enters into a new range on a Circular Gauge.</p>


<h3>Description</h3>

<p>For this, it is necessary to bind a State Indicator control to any value indicator of the Circular Gauge control (e.g., to a needle element) using the <a href="http://help.devexpress.com/#WPF/DevExpressXpfGaugesAnalogGaugeControl_ValueIndicatortopic"><u>AnalogGaugeControl.ValueIndicator</u></a> attached property.  </p><p>You also need to add range elements to the scale of the Circular Gauge and specify<strong> </strong>states of the State Indicator control that correspond to these elements.</p>

<br/>


