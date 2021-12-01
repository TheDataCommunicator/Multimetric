# Multimetric Charts...

Are a way to visualise lots of metrics in one chart, so we can compare things more easily.

Suppose you're trying to compare two countries, using health, economic and other types of metrics, so you can see which is higher or lower in each. There's GDP, birth rate, average income per capita and a whole load more metrics you could use. We could create a chart for each metric. But the more charts we add the harder it is to get the overall position. And we can't just lump the metrics together in one chart because they use different scales; GDP is in millions of dollars whereas life expectancy would be in years. You could use two axes but adding axes for all the other metrics would quickly get messy.

Instead we can scale each metric to have the same range, say 0 to 1. Now 0 represents the lowest value in a metric, 1 is the highest and values between the two extremes are scaled proportionally. For example, suppose we had the values 50, 75, 90 and 100. Scaling them to the range 0 to 1 would make 50 equal to 0, 100 equal to 1 and 75 would be 0.5 because it's the midpoint of the range. 90 would become 0.8 because it sits nearer to the top end of the range.

Scaling the source data values this way means we can use one axis, in this case the X axis, to represent lower or higher values. Then, if we separate each metric into groups using the Y axis we can see all the data points in one view using a simple scatter plot. Add the metric labels and you have a neat way to show all the metrics and all the data points. Then if we want to show a particular item from our data, say the country Canada, we can draw a line through its dots across the different metrics. Adding a second country's line gives us another line. And now we have a quick, visual way to show higher or lower for each metric and by how much. And because we can see all the data points we can judge whether values are outliers.

At their heart these are simply parallel metrics charts without the lines, and rotated 90 degrees so we can add labels and extra data in a table next to the chart.
