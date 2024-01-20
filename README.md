Generate unique identifiers in a warehouse table in Microsoft Fabric
It's a common requirement in data warehouses to assign a unique identifier to each row of a table.
In SQL Server-based environments that's typically done by creating an identity column in a table, however this feature isn't supported in a warehouse in Microsoft Fabric. 
Instead, you'll need to use a workaround technique.

Workaround technique
This code describes a workaround technique that generates unique identifiers in a warehouse table.
