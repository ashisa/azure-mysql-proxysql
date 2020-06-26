# Load balance read replicas using ProxySQL in Azure Database for MySQL


<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fashisa%2Fazure-mysql-proxysql%2Fmaster%2Ftemplate.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png" />
</a>

This ARM template deploys ProxySQL as a Load Balancer for an existing Azure Database for MySQL.

ProxySQL, a high-performance MySQL proxy, enables users to distribute different queries to multiple servers to distribute the load more efficiently. ProxySQL has several benefits, including intelligent load balancing across different databases and the ability to determine if a database instance is running so that read traffic can be redirected accordingly.

To get the detailed explanation of the setup, please refer to [Load balance read replicas using ProxySQL in Azure Database for MySQL](https://techcommunity.microsoft.com/t5/Azure-Database-for-MySQL/Load-balance-read-replicas-using-ProxySQL-in-Azure-Database-for/ba-p/880042)
