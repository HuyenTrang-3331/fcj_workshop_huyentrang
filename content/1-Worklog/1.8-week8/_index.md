---
title: "Week 8 Worklog"
date: 2026-06-05
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Week 8 Objectives:

* Complete learning content and practice of **Module 07** on data, data analytics, and serverless data processing on AWS.
* Learn the process of building a **data pipeline** on AWS, including ingest data, store data, catalog data, transform data, analyze data, and visualize data.
* Practice creating **S3 Bucket**, Delivery Stream, sample data, Glue Crawler, and checking output data on S3.
* Learn how to analyze data with **Amazon Athena** and visualize data with **Amazon QuickSight**.
* Practice with **Amazon DynamoDB**, including exploring DynamoDB Console, backup, clean up, advanced design patterns, global serverless application, and event-driven architecture.
* Learn how to use tagging, cost allocation, and usage to track costs when working with databases and data.
* Practice using **CloudShell**, AWS Console, SDK, and Cloud9 during data processing.
* Practice data processing with **AWS Glue DataBrew**, **AWS Glue**, **Amazon EMR**, **Athena**, **Kinesis Data Analytics**, **QuickSight**, **Lambda**, and **Amazon Redshift**.
* Practice skills in building dashboards, improving dashboards, and creating interactive dashboards for data analysis.
* Add skills in checking lab results, noting errors, analyzing data flows, and cleaning up resources to avoid unexpected costs.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| :--- | :--- | :--- | :--- | :--- |
| 1    | - Complete Lab35-3.1: Create S3 Bucket<br>- Complete Lab35-3.2: Creating a Delivery Stream<br>- Complete Lab35-3.3: Create Sample Data<br>- Complete Lab35-4.1: Create Glue Crawler<br>- Complete Lab35-4.2: Data Check<br>- Complete Lab35-5.1: Explain code in Vietnamese version<br>- Complete Lab35-5.2: S3 store output<br>- Complete Lab35-5.3: Session connect setup<br>- Complete Lab35-6.1: Analysis with Athena<br>- Complete Lab35-6.2: Visualize with QuickSight<br>- Complete Lab35-7: Clean up resources<br>- Analyze the data flow from ingestion, storage on S3, cataloging with Glue Crawler, querying with Athena, and visualizing with QuickSight | 05/06/2026 | 05/06/2026 | https://000035.awsstudygroup.com/ |
| 2    | - Complete Lab39-1: LHOL - Hands-on Labs for Amazon DynamoDB<br>- Complete Lab39-2: Explore DynamoDB<br>- Complete Lab39-3: Explore DynamoDB Console<br>- Complete Lab39-4: Back up<br>- Complete Lab39-5: Clean up<br>- Complete Lab39-6: LADV - Advanced Design Patterns for Amazon DynamoDB<br>- Complete Lab39-7: LMR - Build and Deploy a Global Serverless Application with Amazon DynamoDB<br>- Complete Lab39-8: LEDA - Build a Serverless Event Driven Architecture with DynamoDB<br>- Note the role of DynamoDB in serverless applications, global applications, and event-driven architecture | 08/06/2026 | 08/06/2026 | https://000039.awsstudygroup.com/ |
| 3    | - Complete Lab40-2.1: Preparing the database<br>- Complete Lab40-2.2: Building a database<br>- Complete Lab40-3.1: Data in the Table<br>- Complete Lab40-3.2: Cost<br>- Complete Lab40-3.3: Tagging and Cost Allocation<br>- Complete Lab40-3.4: Usage<br>- Complete Lab40-3.5: Addition result query<br>- Complete Lab40-4: Clean up resources<br>- Complete Lab60-1: CloudShell 2.2<br>- Complete Lab60-2: Console<br>- Complete Lab60-3: SDK<br>- Analyze how to track costs, usage, and tagging when working with databases on AWS<br>- Compare different ways to interact with AWS via Console, CloudShell, and SDK | 09/06/2026 | 09/06/2026 | https://000040.awsstudygroup.com/<br><br>https://000060.awsstudygroup.com/ |
| 4    | - Complete Lab70-1.1: Creating a Cloud9 Instance<br>- Complete Lab70-1.2: Download Dataset<br>- Complete Lab70-1.3: Upload Dataset to S3<br>- Complete Lab70-2.1: Setting up DataBrew<br>- Complete Lab70-2.2: Data Profiling<br>- Complete Lab70-2.3: Clean & Transform data<br>- Complete Lab72-2: Preparatory steps<br>- Complete Lab72-3: Ingest and Store<br>- Complete Lab72-4: Catalog Data<br>- Note the data preparation process, uploading datasets to S3, profiling, cleaning, transforming, and cataloging data<br>- Analyze the role of Cloud9, S3, DataBrew, and Glue in the data preparation step | 10/06/2026 | 10/06/2026 | https://000070.awsstudygroup.com/<br><br>https://000072.awsstudygroup.com/ |
| 5    | - Complete Lab72-5: Transform Data with AWS Glue interactive sessions<br>- Complete Lab72-6: Transform Data with AWS Glue GUI<br>- Complete Lab72-7: Transform Data with AWS Glue DataBrew<br>- Complete Lab72-8: Transform Data with EMR<br>- Complete Lab72-9: Analysis with Athena<br>- Complete Lab72-10: Analysis with Kinesis Data Analytics<br>- Complete Lab72-11: Visualize in QuickSight<br>- Complete Lab72-12: Serve with Lambda<br>- Complete Lab72-13: Warehouse on Redshift<br>- Complete Lab73-3: Build Dashboard<br>- Complete Lab73-4: Dashboard Improvements<br>- Complete Lab73-5: Create Interactive Dashboard<br>- Analyze the differences between batch processing, streaming analytics, serverless processing, and data warehouse<br>- Complete the dashboard and clean up resources after finishing the lab | 11/06/2026 | 11/06/2026 | https://000072.awsstudygroup.com/<br><br>https://000073.awsstudygroup.com/ |

### Week 8 Achievements:

**Overall:**

In Week 8, I completed the learning content and practice of **Module 07** on data, data analytics, and serverless data processing on AWS. This week's content helped me better understand how to build a data pipeline on AWS, from data ingestion, storage, cataloging, cleaning, transformation, analysis to data visualization.

In addition to completing the labs, I also added data architecture analysis, compared data processing services, checked costs, tagging, usage, dashboards, and cleaned up resources. Through this, I gained a more practical perspective on designing the data analytics layer in a cloud system.

**Learned Theory:**

* Understand the basic process of a data pipeline on AWS:

  * Ingest data.
  * Store data.
  * Catalog data.
  * Transform data.
  * Analyze data.
  * Visualize data.
  * Clean up resources.
* Understand the role of **Amazon S3** in storing input data, intermediate data, and output data.
* Understand the role of **Delivery Stream** in collecting and transferring data to storage or analysis destinations.
* Understand the role of **AWS Glue Crawler** in scanning data, detecting schemas, and creating metadata in the Data Catalog.
* Understand how to use **Amazon Athena** to query data directly on S3.
* Understand how to use **Amazon QuickSight** to visualize data and build dashboards.
* Master the role of **Amazon DynamoDB** in providing a managed NoSQL database with high scalability and suitability for serverless applications.
* Learn advanced DynamoDB patterns such as advanced design patterns, global serverless applications, and event-driven architecture.
* Understand the role of **tagging** and **cost allocation** in tracking AWS resource costs.
* Understand how to use different tools to interact with AWS:

  * AWS Console.
  * CloudShell.
  * SDK.
  * Cloud9.
* Understand the role of **AWS Glue DataBrew** in data profiling, cleaning, and transformation.
* Understand the role of **AWS Glue** in the data ETL process.
* Understand the role of **Amazon EMR** in processing big data with distributed frameworks.
* Understand the role of **Kinesis Data Analytics** in streaming data analytics.
* Understand the role of **AWS Lambda** in serverless data processing.
* Understand the role of **Amazon Redshift** in building data warehouses for large-scale data analysis.
* Note some best practices:

  * Organize data on S3 for easy cataloging and querying.
  * Check schemas after running Glue Crawler.
  * Track cost and usage when processing data.
  * Use tags to categorize resources and support cost allocation.
  * Clean up S3, Glue jobs, DynamoDB tables, QuickSight datasets, Cloud9, and related resources after labs.

**Practiced with Labs:**

* Completed labs on **S3, Delivery Stream, Glue Crawler, Athena, and QuickSight**:

  * Create S3 Bucket.
  * Create Delivery Stream.
  * Create sample data.
  * Create Glue Crawler.
  * Check data.
  * Store output on S3.
  * Analyze data with Athena.
  * Visualize data with QuickSight.
  * Clean up resources.
* Completed labs on **Amazon DynamoDB**:

  * Explore DynamoDB Console.
  * Check tables, items, keys, and basic configurations.
  * Practice backup.
  * Learn advanced design patterns.
  * Learn global serverless applications.
  * Learn event-driven architecture with DynamoDB.
* Completed labs on **database, cost, tagging, and usage**:

  * Prepare database.
  * Build database.
  * Check data in table.
  * Check cost.
  * Configure tagging and cost allocation.
  * Check usage.
  * Perform additional queries.
* Practiced using **CloudShell**, **AWS Console**, and **SDK** to interact with AWS services.
* Completed labs on **Cloud9, dataset, S3, and AWS Glue DataBrew**:

  * Create Cloud9 Instance.
  * Download dataset.
  * Upload dataset to S3.
  * Set up DataBrew.
  * Profile data.
  * Clean and transform data.
* Completed labs on **AWS Glue, EMR, Athena, Kinesis Data Analytics, Lambda, and Redshift**:

  * Ingest and Store.
  * Catalog Data.
  * Transform Data with Glue interactive sessions.
  * Transform Data with Glue GUI.
  * Transform Data with Glue DataBrew.
  * Transform Data with EMR.
  * Analysis with Athena.
  * Analysis with Kinesis Data Analytics.
  * Visualize in QuickSight.
  * Serve with Lambda.
  * Warehouse on Redshift.
* Completed labs on **dashboards**:

  * Build Dashboard.
  * Dashboard Improvements.
  * Create Interactive Dashboard.
* Sketched a data analytics flow on AWS including:

  * Data Source.
  * S3.
  * Delivery Stream.
  * Glue Crawler / Data Catalog.
  * Glue / DataBrew / EMR.
  * Athena / Kinesis Data Analytics.
  * QuickSight Dashboard.
  * Lambda.
  * Redshift.
* Note things to check when processing data:

  * S3 path.
  * Schema after crawler runs.
  * Data access permissions.
  * Job status.
  * Query result.
  * Dashboard dataset.
  * Cost and usage.
* Cleaned up resources like S3 Bucket, Glue Crawler, DynamoDB table, Cloud9 instance, QuickSight dataset/dashboard, Lambda, Redshift, and related resources after completing the lab.
