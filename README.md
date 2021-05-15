# distributeddataanalytics
This repository holds the information of an Audit Balance Control built in Azure Data Factory using datafactory pipelines along with the integration of Logic Apps.
The data warehousing tool used for building the framework is Azure Synapse Analytics.

# Overview

This framework uses four tables to log the information of the pipelines running in Azure Data Factory
-Audit incremental master
-Parent Audit table
-Child Audit table
-Audit source dataset table


The records are loaded into these tables using the following sets of stored procedures
-Start Child Audit
-Success Child Audit
-Failure Child Audit
-Start Parent Audit
-Success Parent Audit
-Failure Parent Audit
