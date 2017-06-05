# polymeetup
Developed a meetup portal that will provide a common platform for Knowledge Sharing, Tech forum and Research articles. 
The project mainly focuses on the database aspects of it. Used MSSQL as the database. 
Dealt with Stored Procedures, Triggers, Dynamic SQL, XML transactions, Cursors and etc.. ,   
For the Front End part used jsp pages for the user input and retrieval of information from DB through JDBC Connection.

#Introduction

DB Name : Final_Project 
(SQL File is in polymeetup_DB project)

In db.properties change url, username, password

dbDriver=com.microsoft.sqlserver.jdbc.SQLServerDriver
connectionUrl=jdbc:sqlserver://localhost:1433;databaseName=Final_Project;
userName=sa
password=********

After changing deploy it on the Server (Tomcat) 

Hit URL: http://localhost:8080/polymeetup/ 

Welcome page will appear !

Portal has option to create user / login  / create meetup / RSVP meetup / Report Generation 

