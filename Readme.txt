
 
  Project Title: Migrating SQL Server Database to Azure SQL Database

A.  Database Table Details:
	 Number: 3
	 Total File Size: 42MB
	 File format: CSV
	

B.  Business requirments:
    Client (user) needs to move their on-premises database to cloud-hosted database platform for scalability, security, availability, disaster recovery, and performance improvements
	

C.  Solution Steps: 
   	 -create destination (sink) database in Azure SQL Database and also create database contributor access policy for the database user
   	 -connect Microsoft Data Migration Assistant to SQL Server
   	 -Microsoft Data Migration Assistant assesses SQL Server for potential migration issues because of SQL Server upgrades
   	 -resolve issues, if there are any in the migration assessment report
   	 -migrate dababase from SQL Server to Azure SQL Database
   	 -run simple sql queries on the Azure SQL database tables to confirm successful migration


D.  Tech tools: 
   	 -Microsoft Data Migration Assistant
   	 -Microsoft SQL Server
   	 -Azure SQL Database
