## Simple tests to validate and discover data quality issues
Conducting some simple summary analysis should help to indentify many common data quality problems. Ideally, it should be a simple exercise to generate quality summary level analysis from data. If it's difficult to generate summary data, more robust data analysis will only be more difficult. The following may not necessarily deliver much insight, however they will likely help in identifying many common data quality issues that need to be resolved in order to implement more robust analysis.

### Generate Counts:
Basic counts of data rarely provide insight, but counts often correlate to population numbers. For instance, the number of cases by zip code in a database should correlate, on some level, to the population. In essence, jurisdictions with higher populations are likely to have a similarly high number of cases. If your counts don’t meet expectations, investigate the issue…non standard data entry, capitalization issues, etc
 
### Create a time series or timeline chart:
Dates are a common data quality issue that can inhibit one's ability to analyze and understand data. Generating a time series or timeline with your data will indentify outliers that ultimately may skew your results. In general, dates should adhere to the same timeframe in which the data are collected. Dates that are incorrectly formatted or have data entry errors should be readily apparent when creating a time series chart.

### Look for outliers:
First, generate some summary statistics such as mean (average) and median (happens the most). Looks for records that may disproportionately skew those results by using a [scatterplot](https://en.wikipedia.org/wiki/Scatter_plot) to vsiualize the data. Often, dates or quanities may be entered or collected in error and will be displayed as either exceptionally high or low.

## Document data quality issues
Make a list list of any data quality issues that have been discovered during this process. Review the source of those errors. For instance were the data entered incorrectly, were their no controls to enforce standard data entry (i.e all caps, no caps, some caps, date formats, address incosistenc, etc.). Were the errors or issues related to a database report? Common soureces of data quality issues are as follows:
1. Entry quality: Did the information enter the system correctly at the origin?

2. Process quality: Was the integrity of the information maintained during processing through the system?
 
3. Identification quality: Are two similar objects identified correctly to be the same or different? 

4. Integration quality: Is all the known information about an object integrated to the point of providing an accurate representation of the object? 

5. Usage quality: Is the information used and interpreted correctly at the point of access? 

6. Aging quality: Has enough time passed that the validity of the information can no longer be trusted? 

7. Organizational quality: Can the same information be reconciled between two systems based on the way the organization constructs and views the data? 
[source](https://www.melissadata.com/enews/articles/0611/2.htm) 

**Flag or mark the possible areas on your data process flow chart where these erros might be occuring for further invesitgation later**
