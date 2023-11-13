# Bulk-Copy-Multiple-Tables-with-Lookup-and-ForEach

This projects implement bulk copying of multiple tables from Azure SQL database to Azure blob storage. It makes use of azure data factory's Lookup activity, ForEach activity and the Copy activity.

The pipeline in Azure Data Factory uses a Lookup activity to fetch tables from Azure SQL Database. A ForEach loop iterates over the tables, and the Copy Data activity transfers data from each table to Azure Blob Storage. Error handling, triggers, and security measures enhance the pipeline's reliability and efficiency.

### Create the required resources for the project.
![Create the required resources for the project](https://github.com/Nkamanyi/Bulk-Copy-Multiple-Tables-with-Lookup-and-ForEach/blob/main/Create%20the%20required%20resources%20for%20the%20project.png)

### Create a sample database with three tables.
![Create a sample database with three tables](https://github.com/Nkamanyi/Bulk-Copy-Multiple-Tables-with-Lookup-and-ForEach/blob/main/Create%20a%20sample%20database%20with%20three%20tables.png)

### Create a data container for the incoming data.
![Create a data container for the incoming data](https://github.com/Nkamanyi/Bulk-Copy-Multiple-Tables-with-Lookup-and-ForEach/blob/main/Create%20a%20data%20container%20for%20the%20incoming%20data.png)

### Create the linked service to Azure blob storage.
![Create the linked service to Azure blob storage](https://github.com/Nkamanyi/Bulk-Copy-Multiple-Tables-with-Lookup-and-ForEach/blob/main/Create%20the%20linked%20service%20to%20Azure%20blob%20storage.png)

### Create the linked service to Azure sql database. 
![Create the linked service to Azure sql database](https://github.com/Nkamanyi/Bulk-Copy-Multiple-Tables-with-Lookup-and-ForEach/blob/main/Create%20the%20linked%20service%20to%20Azure%20sql%20database.png)

### Create a lookup activity that looks up for the desireed tables.
![Create a lookup activity that looks up for the desireed tables](https://github.com/Nkamanyi/Bulk-Copy-Multiple-Tables-with-Lookup-and-ForEach/blob/main/Create%20a%20lookup%20activity%20that%20looks%20up%20for%20the%20desireed%20tables.png)

### Lookup output.
![Lookup output](https://github.com/Nkamanyi/Bulk-Copy-Multiple-Tables-with-Lookup-and-ForEach/blob/main/Lookup%20output.png)

### Create and configure the ForEach activity.
![Create and configure the ForEach activity](https://github.com/Nkamanyi/Bulk-Copy-Multiple-Tables-with-Lookup-and-ForEach/blob/main/Create%20and%20configure%20the%20ForEach%20activity.png)

### Create the source dataset to be used for the lookup.
![Create the source dataset to be used for the lookup](https://github.com/Nkamanyi/Bulk-Copy-Multiple-Tables-with-Lookup-and-ForEach/blob/main/Create%20the%20source%20dataset%20to%20be%20used%20for%20the%20lookup.png)

### Parameterized the data source.
![Parameterized the data source](https://github.com/Nkamanyi/Bulk-Copy-Multiple-Tables-with-Lookup-and-ForEach/blob/main/Parameterized%20the%20data%20source.png)

### Parameterized the destination data.
![Parameterized the destination data](https://github.com/Nkamanyi/Bulk-Copy-Multiple-Tables-with-Lookup-and-ForEach/blob/main/Parameterized%20the%20destination%20data.png)

### Monitor the data pipeline.
![Monitor the data pipeline](https://github.com/Nkamanyi/Bulk-Copy-Multiple-Tables-with-Lookup-and-ForEach/blob/main/Monitor%20the%20data%20pipeline.png)

### monitor data pipeline.
![monitor data pipeline ](https://github.com/Nkamanyi/Bulk-Copy-Multiple-Tables-with-Lookup-and-ForEach/blob/main/monitor%20data%20pipeline%202.png)
