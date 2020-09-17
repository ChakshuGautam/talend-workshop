# talend-workshop


### 1. Problem Statement
To be able to transfer data from a one format to another. Examples for the formats include
- CSV
- PostgresQL
- Excel
- MySQL
- MongoDB
- Big Data (Hadoop, Cassandra) etc

*_What is ETL?_*

[Extract, Transform and Load](https://en.wikipedia.org/wiki/Extract,_transform,_load)

We will be focussing on all these today. We will try to 
1. Extract data out of CSV and load it PSQL
2. Extract data out of PSQL, transform and load it to Excel
3. Get a bunch of files (CSVs) and load them to PSQL.

Then to automate it so that it runs on it's own wihtout human intervention. [Will be done in the next session]

### 2. What is talend?

A tool that helps us do all of the above.

New Concept
- Components and Connectors: All the operations in Talend are performed by connectors and components. Input output connected through connectors.

### 3. Setting up the environment.

#### 1. Adding PSQL connection
```json
{
  "postgres_host": "64.225.85.167",
  "postgres_port": 5432,
  "postgres_database": "postgres",
  "postgres_username": "postgres",
  "postgres_password": "nfcSXQ8k211P3hXfHLOgdJerrk69MVXUxlFD8zOuIPzv7vyoOwb6eXbNRnlqJzOM"
}
```

#### 2. Adding CSV

[CSV1](https://cdn.samagra.io/workshop/obd2.csv?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=admin%2F20200917%2F%2Fs3%2Faws4_request&X-Amz-Date=20200917T050323Z&X-Amz-Expires=432000&X-Amz-SignedHeaders=host&X-Amz-Signature=ea5a04850b9feea150968d735c878424842f850510853c32091a1d130bb68bf5)

[CSV2](https://cdn.samagra.io/workshop/obd2.csv?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=admin%2F20200917%2F%2Fs3%2Faws4_request&X-Amz-Date=20200917T050353Z&X-Amz-Expires=432000&X-Amz-SignedHeaders=host&X-Amz-Signature=3227f4ecc21a7823cb79e3266477dab8ac3cbd5f7888a708ae247430f5b9c154)

- Creating a folder and saving both files into the system.

### 4. Extract data out of CSV and load it PSQL

Steps
- Add the delimited file
- Connect it to the database

New Concepts
- Schema

### 5. Extract data out of PSQL, transform and load it to Excel

New Concepts
- Map

Steps
- Adding events-2 to the table
- Setting up map
- Adding excel output component


### 6. Get a bunch of files (CSVs) and load them to PSQL.

New Concepts
- FileIterator

