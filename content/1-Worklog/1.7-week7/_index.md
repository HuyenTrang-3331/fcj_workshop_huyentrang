---
title: "Week 7 Worklog"
date: 2026-05-29
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Week 7 Objectives:

* Complete learning content of **Module 06** about **Databases on AWS** in the **First Cloud AI Journey** program.
* Review foundational database concepts including relational databases, non-relational databases, schemas, tables, queries, and transactions.
* Learn about key AWS database services like **Amazon RDS**, **Amazon Aurora**, **Amazon Redshift**, and **Amazon ElastiCache**.
* Analyze the role of the database layer in a real-world AWS architecture, including data storage, application connectivity, backup, restore, migration, and performance optimization.
* Practice deploying a system using **Amazon RDS**, including VPC, Security Groups, DB Subnet Group, EC2 Instance, RDS Database Instance, and Application Deployment.
* Practice backing up, restoring, and verifying data recovery capabilities after RDS deployment.
* Practice connecting to EC2 using **RDP Client** and **Fleet Manager** to prepare the migration environment.
* Practice configuring source and target databases for migrating from SQL Server/Oracle to MySQL.
* Practice schema conversion, creating endpoints, creating migration tasks, checking logs, and troubleshooting errors during database migration.
* Practice skills for checking database connectivity, monitoring migration status, analyzing errors, and cleaning up resources to avoid unexpected costs.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| :--- | :--- | :--- | :--- | :--- |
| 1    | - Study Module 06-01: Database Concepts Review<br>- Review foundational database concepts including relational database, non-relational database, schema, table, record, query, and transaction<br>- Study Module 06-02: Amazon RDS & Amazon Aurora<br>- Learn about the role of RDS and Aurora in deploying managed databases on AWS<br>- Study Module 06-03: Redshift - ElastiCache<br>- Learn about data warehouse and caching overview on AWS<br>- Analyze how the database layer connects to the application layer in AWS architecture<br>- Note criteria for choosing database services like performance, cost, scalability, backup, and availability | 29/05/2026 | 29/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 2    | - Complete Lab05-2.1: Create a VPC<br>- Complete Lab05-2.2: Create EC2 Security Group<br>- Complete Lab05-2.3: Create RDS Security Group<br>- Complete Lab05-2.4: Create DB Subnet Group<br>- Complete Lab05-3: Create EC2 Instance<br>- Complete Lab05-4: Create RDS Database Instance<br>- Complete Lab05-5: Application Deployment<br>- Complete Lab05-6: Backup and Restore<br>- Complete Lab05-7: Clean up resources<br>- Analyze connection flow between EC2 Application and RDS Database<br>- Note the role of Security Group and DB Subnet Group in database security | 01/06/2026 | 01/06/2026 | https://000005.awsstudygroup.com/ |
| 3    | - Complete Lab43-01: EC2 Connect RDP Client<br>- Complete Lab43-02: EC2 Connect Fleet Manager<br>- Complete Lab43-03: SQLSrv Src Config<br>- Complete Lab43-04: Oracle connect SrcDB<br>- Complete Lab43-05: Oracle config SrcDB<br>- Complete Lab43-06: Drop Constraint<br>- Complete Lab43-07: MSSQL to Aurora MySQL Target Config<br>- Prepare source and target database environments for migration<br>- Note steps to check connectivity, credentials, network, and database engine before migration | 02/06/2026 | 02/06/2026 | https://000043.awsstudygroup.com/ |
| 4    | - Complete Lab43-08: MSSQL to MySQL Create Project<br>- Complete Lab43-09: MSSQL to MySQL Schema Conversion<br>- Complete Lab43-10: Oracle to MySQL Schema Conversion 1<br>- Complete Lab43-11: Create Migration Task and Endpoint<br>- Complete Lab43-12: Inspect S3<br>- Complete Lab43-13: Create Serverless Migration<br>- Note schema conversion process and creating migration tasks<br>- Analyze the role of endpoints, migration tasks, schema conversion, and S3 in database migration | 03/06/2026 | 03/06/2026 | https://000043.awsstudygroup.com/ |
| 5    | - Complete Lab43-14: Create Event Notification<br>- Complete Lab43-15: Logs<br>- Complete Lab43-16: Troubleshoot Test Scenario Mem Pressure<br>- Complete Lab43-17: Troubleshoot Test Scenario Table Error<br>- Check logs, monitor migration status, and troubleshoot errors during practice<br>- Note common errors like memory pressure, table errors, schema errors, endpoint errors, and access permission errors<br>- Clean up resources after completing lab to avoid unexpected costs | 04/06/2026 | 04/06/2026 | https://000043.awsstudygroup.com/ |

### Week 7 Achievements:

**Overall:**

In Week 7, I completed the learning content of **Module 06** about **Databases on AWS**. This week's content helped me better understand the role of databases in cloud architecture, from deploying relational databases using Amazon RDS, using managed databases, configuring application connections, to backup, restore, and data migration.

In addition to studying the module and completing labs, I also added database layer architecture analysis, checked security for EC2-to-RDS connections, monitored migration status, read logs, troubleshot errors, and evaluated factors to consider when deploying databases on AWS like performance, cost, security, and data recovery capabilities.

**Learned Theory:**

* Reviewed foundational database concepts:

  * Database.
  * Table.
  * Record.
  * Schema.
  * Query.
  * Transaction.
  * Relational Database.
  * Non-relational Database.
* Understand the role of **Amazon RDS** in deploying and managing relational databases on AWS.
* Understand the role of **Amazon Aurora** in providing high-performance, highly scalable, and highly available databases.
* Understand the role of **Amazon Redshift** in building data warehouses for large-scale data analysis.
* Understand the role of **Amazon ElastiCache** in speeding up applications through caching and reducing direct query load on databases.
* Master key components for deploying RDS:

  * VPC.
  * EC2 Security Group.
  * RDS Security Group.
  * DB Subnet Group.
  * EC2 Instance.
  * RDS Database Instance.
  * Database endpoint.
* Understand the role of **Security Group** in controlling connections from application servers to databases.
* Understand why databases should be placed in private subnets to restrict direct Internet access.
* Master the role of **backup and restore** in protecting data and ensuring recovery capabilities in case of incidents.
* Understand the process of migrating databases from SQL Server/Oracle to MySQL:

  * Prepare source database.
  * Prepare target database.
  * Convert schema.
  * Create endpoints.
  * Create migration task.
  * Monitor logs and troubleshoot errors.
* Understand the role of **schema conversion** when moving data between different database management systems.
* Understand the role of **Amazon S3** in storing intermediate data or artifacts related to the migration process.
* Note some best practices for deploying databases on AWS:

  * Don't expose databases directly to the Internet.
  * Only open database ports for necessary access sources.
  * Use clear Security Groups for EC2 and RDS.
  * Always verify backup/restore instead of just creating backups.
  * Monitor logs during migration to detect errors early.
  * Clean up RDS, EC2, endpoints, migration tasks, and related resources after lab to avoid unexpected costs.

**Practiced with Labs:**

* Completed **Amazon RDS** deployment lab:

  * Create a VPC.
  * Create EC2 Security Group.
  * Create RDS Security Group.
  * Create DB Subnet Group.
  * Create EC2 Instance.
  * Create RDS Database Instance.
  * Application Deployment.
  * Backup and Restore.
  * Clean up resources.
* Practiced creating network infrastructure, Security Groups, and DB Subnet Groups to prepare the environment for RDS.
* Practiced creating EC2 Instances as connection environments or deploying database-accessing applications.
* Practiced creating RDS Database Instances and verifying application-to-database connectivity.
* Practiced backing up and restoring databases to verify data recovery capabilities.
* Completed migration environment preparation labs:

  * EC2 Connect RDP Client.
  * EC2 Connect Fleet Manager.
  * SQL Server source configuration.
  * Oracle source database connection.
  * Oracle source database configuration.
  * Drop Constraint.
  * MSSQL to Aurora MySQL target configuration.
* Practiced connecting to EC2 using RDP Client and Fleet Manager.
* Practiced configuring source and target databases for migration.
* Completed schema conversion and migration labs:

  * MSSQL to MySQL Create Project.
  * MSSQL to MySQL Schema Conversion.
  * Oracle to MySQL Schema Conversion.
  * Create Migration Task and Endpoint.
  * Inspect S3.
  * Create Serverless Migration.
* Practiced creating migration projects, converting schemas, creating endpoints and migration tasks.
* Practiced checking S3 to observe data or migration-related artifacts.
* Completed migration monitoring and troubleshooting labs:

  * Create Event Notification.
  * Logs.
  * Troubleshoot Memory Pressure.
  * Troubleshoot Table Error.
* Practiced checking logs, monitoring migration status, and troubleshooting basic errors during migration.
* Note things to check when encountering migration errors:

  * Source database connectivity.
  * Target database connectivity.
  * Credential.
  * Security Group.
  * Endpoint.
  * Schema conversion.
  * Migration task status.
  * Error logs.
* Sketched a database layer diagram including:

  * Application/EC2.
  * RDS Database.
  * DB Subnet Group.
  * Security Group.
  * Source Database.
  * Target Database.
  * Migration Task.
  * S3.
  * Logs/Event Notification.
* Cleaned up resources like EC2, RDS, Security Group, DB Subnet Group, migration task, endpoint, S3 artifacts, and related resources after completing the lab.
