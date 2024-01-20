# laughing-funicular
[C#] (Microsoft AZ-204 certification) Exercise: Connect an app to Azure Cache for Redis by using .NET Core

# Notes
[https://learn.microsoft.com/en-us/training/modules/develop-for-azure-cache-for-redis/5-console-app-azure-cache-redis)](https://learn.microsoft.com/en-us/training/modules/develop-for-azure-cache-for-redis/5-console-app-azure-cache-redis)

# Commands
* az login
* az group create --name az204-redis-rg --location uksouth;
* az redis create --location uksouth --resource-group az204-redis-rg --name laughingfunicular --sku Basic --vm-size c0;
