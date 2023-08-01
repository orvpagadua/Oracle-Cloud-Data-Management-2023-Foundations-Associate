# Oracle-Cloud-Data-Management-2023-Foundations-Associate
Questions I encountered while taking the course

## 1 : Data Management Introduction

#### Test: Skill Check: Data Management Introduction

1. Which two statements are true about the Autonomous Database?
- [ ] Running of complex applications, such as Siebel, is not available. 
- [x] It has self-service tools for analytics and data access. 
- [x] Auto-scaling is based on workloads. 
- [ ] Indexes are added manually only after recommendations.

2. Which two self-service tools are available with the Autonomous Database?
- [ ] Business Objects 
- [x] Low-Code App Dev, APEX 
- [x] Oracle Machine Learning 
- [ ] Encryption only in Object Storage

3. Which two statements are true about a converged Database?
- [x] It supports graph and spatial workloads. 
- [ ] It requires a dedicated hardware. 
- [ ] It does not support analytical workloads. 
- [x] It supports both structured and unstructured data types.

4. Which two interconnect solutions are available to connect Oracle Cloud to other cloud providers?
- [x] Cloud Router (*) 
- [ ] Virtual Private Cloud 
- [ ] Virtual Cloud Network 
- [x] FastConnect (*)


## 2 : Autonomous Database (ADB)

Dedicated infrastructure provides a Private Database Cloud, enabling IT to achieve the highest degree of security and governance while providing a completely self-service database experience for its users.
TRUE

Oracle Autonomous Transaction Processing (ATP) is designed to run all enterprise applications, from simple web apps to mission-critical enterprise applications, including mixed workloads and real-time analytics, with no compromise on app performance.
TRUE

### Skill Check: Autonomous Database (ADB)

1. Which three are required for provisioning an Oracle Autonomous Database instance?
   
- [x] workload type 
- [ ] backup location FRA size 
- [ ] number of tablespaces 
- [x] database name 
- [x] number of CPUs

2. Which two actions can be performed from the OCI Console for an Oracle Autonomous Database?
   
- [ ] Increase network bandwidth. 
- [x] Scale up or scale down the CPU.
- [x] Increase the storage allocated for the database.
- [ ] Scale up or scale down memory.

3. Which three capabilities of Oracle Autonomous Database can accelerate innovation?
   
- [x] built-in AI and ML, which help find patterns that can identify undiscovered anomalies 
- [ ] scaling of CPUs with very little down time 
- [x] instant scaling of storage 
- [x] provisioning a data warehouse in seconds

4. Which two statements are true about Autonomous Transaction Processing?
- [x] Data is stored in row format.
- [ ] Data is stored in columnar format. 
- [x] Missing indexes are detected and created.
- [ ] Complex SQL queries are optimized.

5. Which statement is true about Autonomous Transaction Processing?
- [ ] It is used for analytic workloads. 
- [ ] Data is stored in columnar format. 
- [ ] It is used with data marts and machine learning. 
- [x] It is used for OLTP and mixed workloads.
      
## 3 : Exadata & Database Cloud Service (DBCS)

With Exadata Cloud Service, customers benefit from cloud economics and only pay for what they use.
True

In terms of service operation, Oracle manages everything running in the database VM and customers manage the Exadata infrastructure.
False

Which package includes Active Data Guard, Oracle RAC, and Database In-Memory?
Enterprise Edition
Enterprise Edition High Performance
---Standard Edition 2
Enterprise Edition Extreme Performance

### Exadata and DBCS

1. Which is NOT the responsibility of a customer in a simple cloud management model?
- [ ] Control access to customer VMs. 
- [ ] Manage everything inside the database. 
- [x] Manage database servers and VM hosts. 
- [ ] Subscribe to database servers. 

2. Which are two advantages of Oracle Databases on Virtual Machines?
- [ ] provide dedicated resources 
- [ ] run only OLTP database workloads 
- [x] lower cost with pay-per-use 
- [x] provisioned with block storage

3. Which two statements are true about the default configuration for automatic database backups?
- [x] Archive redo log files are backed up every 30 minutes. (*) 
- [ ] The retention period is set at 14 days. 
- [x] Backups are executed in the primary site. (*) 
- [ ] Backups occur weekly

4. Which two are management interfaces for Exadata Cloud Service?
- [ ] SQL Worksheet 
- [x] Oracle Cloud Rest APIs 
- [ ] OCI Console 
- [x] Oracle Cloud Web-Based UI

5. Which update is Oracle’s responsibility for the maintenance of Exadata Cloud Service?
- [ ] Database Updates 
- [ ] Exadata OS Updates 
- [x] Infrastructure Updates 
- [ ] Grid Infrastructure

## 4 : MySQL & NoSQL

### Test: Skill Check: MySQL and NoSQL

1. Which component is not included in a MySQL Database Service DB System?
- [ ] Virtual Network Interface 
- [x] FastConnect 
- [ ] Compute Instance 
- [ ] Block Storage

2. Which command for the MySQL Data Service will resume OCPU billing?
- [x] Restart
- [ ] Stop 
- [ ] Start 
- [ ] Backup 

3. Which are two responsibilities of a developer or user when managing NoSQL Database Cloud Service?
- [ ] installation of software and updates 
- [ ] replication across multiple availability domains 
- [x] setting roles and privileges 
- [x] application development  

4. Which two statements describe HeatWave Clusters?
- [x] It has an in-memory engine for fast execution of analytic queries. 
- [ ] Restarting will only make the existing data available again. 
- [x] It is exclusively available in OCI.
- [ ] Stopping Heatwave Clusters continues billing because of the data. 

5. Where is the data stored in MySQL Database?
- [ ] Storage Management 
- [x] Block Volumes 
- [ ] Object Storage 
- [ ] File systems 

## 5 : Converged Database

### Test: Skill Check: Converged Database

1. Which two are true about Spatial Studio?
- [ ] Spatial Studio can be included at an additional cost with Oracle Autonomous Database. 
- [ ] It is not a self-service application. 
- [x] Users can convert address data to coordinates so that they can plot locations on a map. (*) 
- [x] You can create interactive maps and perform spatial analysis on business data quickly and easily. (*)

2. Which two statements are true about an Autonomous JSON database?
- [ ] A DBA is required. 
- [x] It has instant auto-scaling. (*) 
- [ ] Applications cannot be built without SQL. 
- [x] The Autonomous JSON database is accessed via document APIs. (*)

3. Which three options can developers use to access spatial features?
- [ ] Location 
- [x] PL/SQL (*) 
- [x] Python (*) 
- [ ] JEE 
- [x] Node.js (*)

4. Which two are true about Graph Analytics?
- [x] Oracle provides an Open-Source Graph Language (PGQL). (*) 
- [ ] There are no in-memory parallel analytic graph functions. 
- [ ] Graph Analytics is not free with all Oracle Database editions. 
- [x] Graph Analytics can be used to discover influencers, dependencies, communities, and ranking. (*)

## 6 : Resiliency
## 7 : Developing on Oracle Database
## 8 : Data Lake, Data Warehouse & Machine Learning
## 9 : Upgrades & Migrations
