# AzureChallenge: Spring Boot Application

This is a simple full stack Azure example, which connects to a SQL Server database running in Azure, with the example data set. The Spring Boot application connects to that database using Spring Data's repository helpers and a Vaadin UI lets end users view and modify the data.

Deploying to Azure App Service:

 * Create SQL Server in azure, load the "Sample" data set which is used by this example
 * Download Microsoft JDBC Driver for SQL Server (ex. 4.2) and install it to your local maven directory
 * Change the connection string parameters (your server, user and password are different)
 * Build the project (ex. using 'mvn clean package' command)
 * (Optional, for local running/development) In Azure web console, open Firewall for your database and use "Add client IP" to allow connections from your current IP address
 * Deploying web app to the Azure App Service 
 
