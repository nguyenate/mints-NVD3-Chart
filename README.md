# mints-NVD3-Chart
Test charts for SharedAirDFW using NVD3

## testLineWFocusChart
Has a focus chart to allow the user to change the view of the main line chart.
The background is actually rectangles drawn on top of the chart with hardcoded size. Will make it more difficult to change the size of teh chart and has not had much testing.

## testMultiChart
Draws a much better "background" by creating area graphs for each PM value.
it is much easier to change the size of the graph, but currently unable to add a focus chart with NVD3.

## testMultiChartSmall
Resized Multichart to be much smaller for the bubble pop-up of the sensors. Has other minor changes from testMultiChart.


## Built With
* [NVD3](http://nvd3.org/) - Charts library
