# CS8674.FALL2015.NEUSeattle
Copy Of Project Repo for CS8674.FALL2015.Seattle

## Description
Medicare Plan B data for all providers that saw medicare patients in 2012. Includes provider information,
procedures reimbursed by medicare, and aggregated data indicating average medicare payment, average
submitted charge, patient visits, and associated information

## Running
The Source Code is found in the WebPage directory. 
Code related to injestion can be found in Cassandra folder
(injestion code is very crude. It gets the job done, but needs refactoring) 

Project can be run from eclipse on a server or can build a .war and host it
   Recommend using Tomcat 8

Currently directed to my EC2 instance hosting the Cassandra database.

The Solr instance is hosted on another EC2 instance which I do not control, 
so cannot guarentee availablility.

Some code is annotated to indicate author, but most is not. 

Any questions don't hesitate to contact me: timothycowley@gmail.com





