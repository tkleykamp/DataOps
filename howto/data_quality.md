## Identifying and Addressing Data Quality Issues

Presumably by conducting some simple data anlysis and visualization, some issues related to quality have been presented. These could include things like duplicate records, non-standard dates or times, inconsistent data entry (all caps, some caps, no caps), or any one of the items on [this list](https://github.com/Quartz/bad-data-guide). **Adressing these issues, in the most efficient manner possible, may be the most critical component to implmenting a successful anaytics program.**

**[Common sources of poor data quality](https://www.melissadata.com/enews/articles/0611/2.htm)

### Start at the point of entry
Correcting data quality issues at the point data is entered or captured is ideal. This requires less donwstream effort to prepare data for analysis, and less maintenance of any software, tools, or code which may be used to correct for these issues.

**Talk to a person who physically enters the data**
* Observe them entering data,
* Ask them if they understand what is supposed to be entered and how,
* Are they transposing data from a paper form? Is it legigble?
* Are they speaking to someone over the phone?

**Can data quality issues be resolved at the point of entry?**
* Can rules be enforced at the point of entry? For instance can the software easily be modified to include a data picker? Can addresses be validated? Can the sofwtare be modified to inlcude "pick-lists" or dropdowns with standard values?
* Does the person enterning data understand how it's going to be used? Can their process be easily modified to ensure accurate entry?

### After data have been captured
* Do you have tools to clean the data?
* Are you using an ETL (Extract, Transform, & Load) process?
  + Does a mechanism exist to cleanse the data?
* Can you automate these peroceses
