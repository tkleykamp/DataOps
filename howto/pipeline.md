## Understanding the Data Pipeline:
The term "Data Pipeline" may mean different things to different people. As it applies to DataOps or government, the "data pipeline" should be viewed as a series of connected actions and processes associated with data from the point of capture through storage, operational, and ultimately analytical uses. Generally, the output of one action or process is the input of another action or process.

### Data Sources
+ Do all of the data reside in a single location?
  + Are they all tables in a database?
+ Are there data that reside outside of your "control"
### Data Collection:
+ Who is collecting data and/or entering data; under what circumstances. 
  + Are data collected in the field? Is a form filled out and then entered later? During an interview?
+ What controls exist at the point of entry? 
  + Which fields are domain controlled (i.e. Drop downs, check boxes, true/false)
  + Which fields are required?
  + Which fields enforce rules, formatting, or validate entry (addresses, dates, etc)
  + Are any fields “re-purposed” or used for a purpose which may not be included in documentation? 
### Data Storage
+ After data are entered, where are they stored? 
  + A large relational database (SQL Server, Oracle, DB2, Postgres (probably not)? 
  + A local database such as MS Access, spreadsheets? 
  + Is the system vendor managed?   
+ Is data stored entirely in the operation database, or is there a data warehouse or reporting database? (i.e. a version of the data not used for operation purposes)
+ Are there any exisiting processes or tools to clean or standardize data
### Reporting and Extraction
+ How are data currently extracted from a database
+ What "reports" are currently in use
+ What tools exist to extract "raw" data.
  + Are there tools or prcesses to transform, standardize or "clean" data?
### Analysis and Reports
+ Are the data currently used for reports or analysis?
  + Who is the audeince or recipient?
+ For what purpose are they created?
+ What are the tools or processes used to generate reports or analysis
  + How frequest are they?
  + Have they resulted in any insight or influence in decision making?
