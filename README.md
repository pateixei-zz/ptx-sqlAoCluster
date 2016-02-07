# ptx-sqlAoCluster
This template deploys a SQL Server 2014 AlwaysOn Cluster in a new VNET and Active Directory Domain.
You will be prompted for the following parameters:

+ **ResourcesPrefix:** a prefix (only letters & numbers, lowercase between [a-z,0-9]) to be uniquely identify the resources to be created
+ **AdDomainName:** the name to be used in the new Active Directory Domain
+ **AdminUsername:** local & domain administrator username 
+ **AdminPassword:** admin password
+ **SqlServiceAccount:** username to be used in the SQL AlwaysOn cluster deployment
+ **SqlServicePassword:** SQL user password

[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/)