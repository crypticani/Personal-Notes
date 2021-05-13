## What is Dimension Table?

Dimension table is a table which contain attributes of measurements stored in fact tables. This table consists of hierarchies, categories and logic that can be used to traverse in nodes.

## What is Fact Table?

Fact table contains the measurement of business processes, and it contains foreign keys for the dimension tables.
Example – If the business process is manufacturing of bricks
Average number of bricks produced by one person/machine – measure of the business process

## What are the stages of Datawarehousing?

There are four stages of Datawarehousing:

    Offline Operational Database
    Offline Data Warehouse
    Real Time Datawarehouse
    Integrated Datawarehouse

 
## What is OLTP?

OLTP is abbreviated as On-Line Transaction Processing, and it is an application that modifies the data whenever it received and has large number of simultaneous users.

## What is ODS?

ODS is abbreviated as Operational Data Store and it is a repository of real time operational data rather than long term trend data.

## What is the difference between View and Materialized View?

- A view is nothing but a virtual table which takes the output of the query and it can be used in place of tables.
- A materialized view is nothing but an indirect access to the table data by storing the results of a query in a separate schema.

## What is ETL?

- ETL is abbreviated as Extract, Transform and Load. 
- ETL is a software which is used to reads the data from the specified data source and extracts a desired subset of data. 
- Next, it transform the data using rules and lookup tables and convert it to a desired state.
- Then, load function is used to load the resulting data to the target database.

## What is VLDB?

- VLDB is abbreviated as Very Large Database and its size is set to be more than one terabyte database. 
- These are decision support systems which is used to server large number of users.

## What is real-time datawarehousing?

- Real-time datawarehousing captures the business data whenever it occurs. 
- When there is business activity gets completed, that data will be available in the flow and become available for use instantly.

## What are Aggregate tables?

- Aggregate tables are the tables which contain the existing warehouse data which has been grouped to certain level of dimensions. 
- It is easy to retrieve data from the aggregated tables than the original table which has more number of records.
- This table reduces the load in the database server and increases the performance of the query.

## What is factless fact tables?

A factless fact tables are the fact table which doesn’t contain numeric fact column in the fact table.

## What is Datamart?

- A Datamart is a specialized version of Datawarehousing and it contains a snapshot of operational data that helps the business people to decide with the analysis of past trends and experiences. 
- A data mart helps to emphasizes on easy access to relevant information.

## What is Active Datawarehousing?

An active datawarehouse is a datawarehouse that enables decision makers within a company or organization to manage customer relationships effectively and efficiently.

## What is ER Diagram?

- ER diagram is abbreviated as Entity-Relationship diagram which illustrates the interrelationships between the entities in the database. 
- This diagram shows the structure of each tables and the links between the tables.

## What are the key columns in Fact and dimension tables?

- Foreign keys of dimension tables are primary keys of entity tables. 
- Foreign keys of fact tables are the primary keys of the dimension tables.

## What is SCD?

SCD is defined as slowly changing dimensions, and it applies to the cases where record changes over time.

## What are the types of SCD?

There are three types of SCD and they are as follows:

- **SCD 1** – The new record replaces the original record

- **SCD 2** – A new record is added to the existing customer dimension table

- **SCD 3** – A original data is modified to include new data

## What is BUS Schema?

BUS schema consists of suite of confirmed dimension and standardized definition if there is a fact tables.

## What is Star Schema?

Star schema is nothing but a type of organizing the tables in such a way that result can be retrieved from the database quickly in the data warehouse environment.

## What is Snowflake Schema?

Snowflake schema which has primary dimension table to which one or more dimensions can be joined. The primary dimension table is the only table that can be joined with the fact table.

## What is called data cleaning?

- Name itself implies that it is a self explanatory term. 
- Cleaning of Orphan records, Data breaching business rules, Inconsistent data and missing information in a database.

## What is Metadata?

- Metadata is defined as data about the data. 
- The metadata contains information like number of columns used, fix width and limited width, ordering of fields and data types of the fields.

## What are loops in Datawarehousing?

- In datawarehousing, loops are existing between the tables. 
- If there is a loop between the tables, then the query generation will take more time and it creates ambiguity. 
- It is advised to avoid loop between the tables.

## What is surrogate key?

- Surrogate key is nothing but a substitute for the natural primary key. 
- It is set to be a unique identifier for each row that can be used for the primary key to a table.

## What are the steps to build the datawarehouse?

Following are the steps to be followed to build the datawaerhouse:

    Gathering business requirements
    Identifying the necessary sources
    Identifying the facts
    Defining the dimensions
    Defining the attributes
    Redefine the dimensions and attributes if required
    Organize the Attribute hierarchy
    Define Relationships
    Assign unique Identifiers

## What are the different types of datawarehosuing?

Following are the different types of Datawarehousing:

    Enterprise Datawarehousing
    Operational Data Store
    Data Mart

## What needs to be done while starting the database?

Following need to be done to start the database:

    Start an Instance
    Mount the database
    Open the database

## What needs to be done when the database is shutdown?

Following needs to be done when the database is shutdown:

    Close the database
    Dismount the database
    Shutdown the Instance

## What are the tools available for ETL?

Following are the ETL tools available:

- Informatica
- Data Stage
- Oracle
- Warehouse Builder
- Ab Initio
- Data Junction

## What is the difference between metadata and data dictionary?

- Metadata is defined as data about the data. 
- Data dictionary contain the information about the project information, graphs, abinito commands and server information.
