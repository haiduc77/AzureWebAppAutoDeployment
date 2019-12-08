# Azure ARM template example for deployment of a website connected to a database
Automate the creation of the necessary infrastructure and deployment of ​a dynamic website on Microsoft Azure connected to a database.

The solution was to use ARM templates configured to install a web application connected to a SQL server database. The website is provided as a zip file ..\WebAppToDeploy\webapplication.zip
The template install automatically the website, the SQL server, provision website with SQL connection string and adds some auto scale settings based on CPU percentage. Also some alerts using the Azure Applications Insights.

To install the template click the "Deploy to Azure" button and login with your Azure account:

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fhaiduc77%2FAzureWebAppAutoDeployment%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="https://raw.githubusercontent.com/haiduc77/AzureWebAppAutoDeployment/master/Resources/deploytoazure.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fhaiduc77%2FAzureWebAppAutoDeployment%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="https://raw.githubusercontent.com/haiduc77/AzureWebAppAutoDeployment/master/Resources/visualizebutton.png"/>
</a>

