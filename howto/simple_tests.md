## Simple tests to validate and discover data quality issues
Conducting some simple summary analysis should help to indentify many common data quality problems. Ideally, it should be a simple exercise to generate quality summary level analysis from data. If it's difficult to generate summary data, more robust data analysis will only be more difficult. The following may not necessarily deliver much insight, however they will likely help in identifying many common data quality issues that need to be resolved in order to implement more robust analysis.

### Generate Counts:
Basic counts of data rarely provide insight, but counts often correlate to population numbers. For instance, the number of cases by zip code in a database should correlate, on some level, to the population. In essence, jurisdictions with higher populations are likely to have a similarly high number of cases. If your counts don’t meet expectations, investigate the issue…non standard data entry, capitalization issues, etc
 
### Create a time series or timeline chart:
Dates are a common data quality issue that can inhibit one's ability to analyze and understand data. Generating a time series or timeline with your data will indeitify outliers that ultimately may skew your results. In general, dates should adhere to the same timeframe in which the data are collected. dates that are incirrectly formatted or have data entry errors should be readily apparent when creating a time series chart.

## Look for outliers:
First, generate some summary statistics such as mean (average) and median (happens the most). Looks for records that may disproportionately skew those results by using a [scatterplot](https://en.wikipedia.org/wiki/Scatter_plot) to vsiualize the data. Often times dates or quanities may be entered or collected in error and will be displayed as either exceptionally high or low.
