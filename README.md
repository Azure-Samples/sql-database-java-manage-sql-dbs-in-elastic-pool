---
page_type: sample
languages:
- java
products:
- azure
- azure-sql-database
description: "Azure SQL sample for managing SQL Database."
urlFragment: sql-database-java-manage-sql-dbs-in-elastic-pool
---

# Manage Azure SQL Database In Elastic Pool (Java)

Azure SQL sample for managing SQL Database.

- Create a SQL Server with elastic pool and 2 databases
- Create another database and add it to elastic pool through database update
- Create one more database and add it to elastic pool through elastic pool update.
- List and print databases in the elastic pool
- Remove a database from elastic pool.
- List and print elastic pool activities
- List and print elastic pool database activities
- Add another elastic pool in existing SQL Server.
- Delete database, elastic pools and SQL Server
 

## Running this sample

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

```bash
git clone https://github.com/Azure-Samples/sql-database-java-manage-sql-dbs-in-elastic-pool.git
cd sql-database-java-manage-sql-dbs-in-elastic-pool
mvn clean compile exec:java
```

## More information

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
