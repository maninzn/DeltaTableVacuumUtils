# DeltaTableVacuumUtils
In production Datalake solutions, we would have multiple Delta tables created. 

Running vacuum on all those manually would be a tedious process. 

This utility would traverse all the folders from a given sub root path and runs vacuum on all the underlying folders


Note:

This works directly on Databricks, but in case you have to make it a part of your code base, add the spark changes as required.
