# Business Intelligence
- Business Intelligence is also known as DSS – Decision support system which refers to the technologies, application and practices for the collection, integration and analysis of the business related information or data. 
- The purpose of business intelligence is to provide better business decision making.

## OLAP
- Online Analytical Processing
- OLAP introduced a groundbreaking way for business users (typically analysts) to easily perform multidimensional analysis of large volumes of business data.
- The magic behind OLAP derives from its ability to pre-calculate and pre-aggregate data. 

## ROLAP
- Relational Online Analytical Processing
- ROLAP stores data in columns and rows (also known as relational tables) and retrieves the information on demand through user submitted queries. 
- A ROLAP database can be accessed through complex SQL queries to calculate information. 
- ROLAP can handle large data volumes, but the larger the data, the slower the processing times. 

## MOLAP
- Multidimensional Online Analytical Processing
- MOLAP uses a multidimensional cube that accesses stored data through various combinations. 
- Data is pre-computed, pre-summarized, and stored (a difference from ROLAP, where queries are served on-demand).
- Its speedy data retrieval makes it the best for “slicing and dicing” operations.

## HOLAP
- Hybrid Online Analytical Processing
- HOLAP storage mode connects attributes of both MOLAP and ROLAP. 
- Since HOLAP involves storing part of your data in a ROLAP store and another part in a MOLAP store, developers get the benefits of both. 
- With this use of the two OLAPs, the data is stored in both multidimensional databases and relational databases.

## DSS
- A decision support system (DSS) is a computerized system that gathers and analyzes data, synthesizing it to produce comprehensive information reports.
- A decision support system (DSS) is a computerized program used to support determinations, judgments, and courses of action in an organization or a business. 
- A DSS sifts through and analyzes massive amounts of data, compiling comprehensive information that can be used to solve problems and in decision-making, timely problem-solving, and improved efficiency in dealing with issues or operations, planning, and even management.

# Operational Database
- An Operational Database or OLTP (On-Line Transaction Processing) is a database management system where data is stored and processed in real-time. 
- They also provide a real-time analytics opportunity which is highly sought after and can manage both SQL and NoSQL based database.

### Functions
- Indexing and Cataloguing
- Replication
- File Storage, Structure
- Query Processing
- Transactions Support

# Data mart
- A Datamart is a specialized version of Datawarehousing and it contains a snapshot of operational data that helps the business people to decide with the analysis of past trends and experiences. 
- A data mart helps to emphasizes on easy access to relevant information.

# Multidimensional Databases
- Multidimensional databases are used mostly for OLAP (online analytical processing) and data warehousing. 
- They can be used to show multiple dimensions of data to users .
- A multidimensional database is created from multiple relational databases. 
- While relational databases allow users to access data in the form of queries, the multidimensional databases allow users to ask analytical questions related to business or market trends.
- The multidimensional databases uses MOLAP (multidimensional online analytical processing) to access its data. 
- They allow the users to quickly get answers to their requests by generating and analysing the data rather quickly.
- The data in multidimensional databases is stored in a data cube format. This means that data can be seen and understood from many dimensions and perspectives. 

### Advantage
- Increased performance
- Easy maintenance
- Better data presentation

### Disadvantage
- Complexity

# Client/Server computing model
- The Client-server model is a distributed application structure that partitions task or workload between the providers of a resource or service, called servers, and service requesters called clients.
- A server manages most processes and stores all data. 
- A client requests specified data or processes.
