# mints-NVD3-Chart
Test charts for SharedAirDFW using NVD3.

## testLineWFocusChart
Has a focus chart to allow the user to change the view of the main line chart.
The background is actually rectangles drawn on top of the chart with hardcoded size. This will make it more difficult to change the size of teh chart and has not had much testing.

## testMultiChart
Draws a much better "background" by creating area graphs for each PM value.
It is much easier to change the size of the graph, but currently unable to add a focus chart with NVD3.

## testMultiChartSmall
Resized Multichart to be much smaller for the bubble pop-up of the sensors. Has other minor changes from testMultiChart.

## To Do
* May want to show the gaps in the data instead of connecting to next point.
* Initialize with latest 24hr data instead of the data from [2020-03-18 00:00:00 to 2020-03-19 00:00:00](http://mintsdata.utdallas.edu:3000/data/001e06323a06/2020-03-18T00:00:00.00Z/2020-03-19T00:00:00.00Z).
* Add a loading screen when getting data from teh api and formatting it.

## Built With
* [NVD3](http://nvd3.org/) - Charts library
