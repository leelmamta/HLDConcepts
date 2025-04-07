### CQRS (Command Query Request Segregation) 
**Microservice Design Patterns** to independently scale **read** and **write** workloads of an application & have well **optimized data schema**.
[CQRS](CQRS.png)
- Command: modifies the data and does not return anything (WRITE)
- Query: does not modify but returns data (READ)

Here we have
 Query Service - Handles all the READ requirements
Command Services - handles all other requirements which modifies the data
[CQRSServices](CQRS-02.png)