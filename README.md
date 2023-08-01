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

High Availability is a method of protecting computer systems from failure, in which standby equipment automatically takes over when the main system fails.
```False```

Which two are true about Oracle Transparent Application Continuity (TAC)?
```It transparently tracks and records session information in case there is a failure```
```It uses Application Continuity and Oracle Real Application Clusters```

Active Data Guard is the Oracle solution for disaster recovery. It eliminates single point of failure by providing one or more synchronized physical replicas of the production database.
```False```

### Test: Skill Check: Resiliency

1. Which two are true about Oracle Real Application Clusters (RAC)?
- [x] utilizes two or more instances of an Oracle Database concurrently (*) 
- [ ] requires manual failover 
- [ ] Is ideal for database consolidation 
- [x] zero downtime rolling maintenance (*)

2. Which are the three security zones of control?
- [ ] Manage 
- [ ] Solve 
- [x] Prevent (*) 
- [x] Assess (*) 
- [x] Detect (*)

3. Which of the following has expanded flexibility with shared or dedicated Exadata infrastructure?
- [x] Oracle Autonomous Database (*) 
- [ ] Oracle Database Cloud Service 
- [ ] Oracle Exadata Cloud Service

4. Which two are true about Oracle Transparent Application Continuity (TAC)?
- [x] It uses Application Continuity and Oracle Real Application Clusters. (*) 
- [x] It transparently tracks and records session information in case there is a failure. (*) 
- [ ] The application sees errors during outages. 
- [ ] It's built outside of the database.

## 7 : Developing on Oracle Database

Which of the following is a sophisticated, powerful tool for profiling, cleaning, and preparing your data?
```Enterprise Data Quality (EDQ)```

Which of the following is an Enterprise-class data integration tool with extract-load-transform (ELT) architecture?
```Oracle Data Integrator (ODI)```

Liquibase is an open-source database-independent library for tracking, managing, and applying database schema changes.
```True```

Terraform is a tool for building, changing, and versioning infrastructure safely and efficiently.
```True```

### Test: Skill Check: Developing in Oracle Database

1. Which ADB tool can you use to upload or access data from local files or remote databases?
- [ ] Data Insights 
- [ ] Catalog 
- [ ] Data Transforms 
- [x] Data Load (*) 

2. Which is NOT an ORDS feature?
- [ ] Mongo style REST API for Oracle Database (SODA) 
- [x] Impact analysis (*) 
- [ ] SQL Developer Web 
- [ ] Web listener for your Oracle PL/SQL programs or APEX

3. Which is NOT true about low code?
- [x] rich functionality with more code (*) 
- [ ] builds apps faster 
- [ ] scalable 
- [ ] accessible

4. Which ADB tool can you use to discover anomalies, outliers, and hidden patterns in your data?
- [x] Data Insights (*) 
- [ ] Catalog 
- [ ] Data Transforms 
- [ ] Data Load 

## 8 : Data Lake, Data Warehouse & Machine Learning

What are the five key elements of the Oracle Lakehouse?
```
Data Lake
Data Catalog
Managed Open-Source Services
Data Warehouse
Data Integration
```

Which of the following is the source of truth for object storage metadata and can regularly harvest the information from the data sources?
```Data Catalog```

The demand side is the need for data sets, models, and libraries.
```False```

What is a Data Mesh?

```A data solution for enterprise-scale domains and/or event-driven data-centric cloud projects```

### Test: Skill Check: Data Lake, Data Warehouse & ML

1. Which of the following helps avoid manual or exhaustive search techniques?
- [ ] Adaptive Sampling 
- [ ] Feature Prediction Impact 
- [x] Auto Model Tuning (*) 
- [ ] Auto Algorithm Selection 
- [ ] Auto Feature Selection

2. Which two are true about Data Catalog?
- [x] It discovers data using a powerful search. (*) 
- [ ] Data Catalog does not integrate with Autonomous Database. 
- [ ] Management is required. 
- [x] It harvests object storage to derive schemas. (*)

3. What is Data Mesh?
- [x] It is a single tool or single cloud service that you can buy. 
- [ ] It is a data solution for enterprise-scale domains and/or event-driven data-centric cloud projects. (*) 
- [ ] It is a finite project that can be run by an LoB Departmental IT org in isolation. 
- [ ] It is an alternative point-solution for data warehouse or data lakes.

4. Which three are a part of the five key Lakehouse elements?
- [x] Data Catalog (*) 
- [x]  Managed open-source services (*) 
- [ ] Data load 
- [x] Data Integration (*) 
- [ ] Data analysis

5. What protects against external and internal threats?
- [ ] Data Productivity 
- [ ] Data Liquidity 
- [x] Data Security (*) 
- [ ] Data Governance 

## 9 : Upgrades & Migrations

When selecting a migration method for moving your database to the cloud, take into consideration the database version, the database size, and high availability.
```True```

Which migration type uses RMAN and DataGurad tools?

```Physical Migration```

DMS is free for all common use cases, and what is included in the pricing is the service itself —all the environment that the service runs on and the infrastructure that the service runs on.
```True```

Oracle Database 19c is the final release supporting non-CDB architecture.
```True```

What is the only recommended method to update your database?
```AutoUpgrade```

### Skill Check: Upgrade and Migration

1. What is the most important reason for upgrading and patching a database?
- [ ] Upgrading and patching the database is not important. 
- [ ] Fix bugs 
- [x] Security (*)

2. In which release is the non-CDB architecture supported?
- [ ] Oracle Database 18c 
- [ ] Oracle Database 21c 
- [ ] Oracle Database 20c 
- [x] Oracle Database 19c (*)

3. Which migration type uses Data Pump and GoldenGate tools?
- [x] Logical Migration (*) 
- [ ] Direct Connection 
- [ ] Indirect Connection 
- [ ] Physical Migration

4. Which is the recommended method to upgrade databases?
- [ ] Data Pump Export/Import 
- [x] AutoUpgrade (*) 
- [ ] Manual upgrade 
- [ ] Upgrading the database is not recommended 
- [ ] Restructure the database 




