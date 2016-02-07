# ptx-sqlAoCluster
This template deploys a SQL Server 2014 AlwaysOn Cluster in a new VNET and Active Directory Domain.
You should inform the following properties: 

a) ResourcesPrefix: a prefix (only letters & numbers, lowercase between [a-z,0-9]) to be uniquely identify the resources to be created
b) AdDomainName: the name to be used in the new Active Directory Domain
c) AdminUsername: local & domain administrator username 
d) AdminPassword: admin password
e) SqlServiceAccount: username to be used in the SQL AlwaysOn cluster deployment
f) SqlServicePassword: SQL user password

[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/)