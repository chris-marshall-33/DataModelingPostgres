# DataModelingPostgres
Project submission for Udacity Data Engineering Nano Degree<br/>
<b>
<br/><br/>
Discuss the purpose of this database in the context of the startup, Sparkify, and their analytical goals. </b>
<br/><br/>
The purpose of this database is to allow a cleaner method to look into Sparkify's data to gain insights on what songs users are currently listening to. Having a ton of data stored in logs (JSON files) is definately not the best or most efficient way to keep data that will be used for analytical purposes. So it is only natural to collect the data in a centralized and standardized method to allow for analytics and insights.
<br/><br/>
<b>
State and justify your database schema design and ETL pipeline.</b>
<br/>
The star schema that I chose allows for all dim tables to point to the fact table to limit space and allow for easier and more explicit queries to be run.
<br/><br/>
The ETL pipeline currently runs by gathering/extracting the JSON data, filtering and transforming to the proper information, and loading the prepped information into the previously created tables. This is a straigthforward method of gathering the data needed to meet the business goals.
<br/><br/>
