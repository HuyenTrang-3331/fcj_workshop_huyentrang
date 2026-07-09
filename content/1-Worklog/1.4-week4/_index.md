---
title: "Week 4 Worklog"
date: 2026-05-08
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Week 4 Objectives:

* Complete learning content of **Module 03** in the **First Cloud AI Journey** program.
* Learn about the **Compute VM on AWS** service group, focusing on **Amazon EC2** and related components.
* Master key EC2 concepts like **Instance Type**, **AMI**, **Key Pair**, **EBS**, **Instance Store**, **User Data**, **Metadata**, and **EC2 Auto Scaling**.
* Learn additional related services like **Amazon EFS**, **Amazon FSx**, **Amazon Lightsail**, and **AWS Application Migration Service**.
* Analyze the role of compute, storage, backup, and content delivery in a real-world AWS architecture.
* Practice deploying **AWS Backup**, creating backup plans, testing restores, and cleaning up resources.
* Practice creating **S3 Bucket**, **Storage Gateway**, and **File Shares** to understand the hybrid storage model on AWS.
* Practice deploying a static website on **Amazon S3**, configuring public access, CloudFront, bucket versioning, move objects, and multi-region object replication.
* Practice skills for checking lab results, analyzing configuration errors, noting best practices, and cleaning up resources to avoid unexpected costs.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| :--- | :--- | :--- | :--- | :--- |
| 1    | - Study Module 03-01: Compute VM on AWS<br>- Study Module 03-01-01: Amazon EC2 - Instance Type<br>- Study Module 03-01-02: Amazon EC2 - AMI / Backup / Key Pair<br>- Study Module 03-01-03: Amazon EC2 - Elastic Block Store<br>- Study Module 03-01-04: Amazon EC2 - Instance Store<br>- Study Module 03-01-05: Amazon EC2 - User Data<br>- Study Module 03-01-06: Amazon EC2 - Metadata<br>- Study Module 03-01-07: Amazon EC2 - EC2 Auto Scaling<br>- Study Module 03-02: EC2 Auto Scaling, EFS, FSx, Lightsail, and MGN<br>- Analyze the role of EC2 in real-world cloud architecture<br>- Compare EBS and Instance Store based on data durability, performance, and resource lifecycle<br>- Note use cases for EC2, Lightsail, or Auto Scaling | 08/05/2026 | 08/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 2    | - Complete Lab13-01: Deploy AWS Backup to the System - Introduction<br>- Complete Lab13-02.2: Deploy infrastructure<br>- Complete Lab13-03: Create Backup Plan<br>- Complete Lab13-05: Test Restore<br>- Complete Lab13-06: Clean up resources<br>- Analyze the role of backup in production systems<br>- Note the differences between backup and snapshot<br>- Check the restore process to evaluate data recovery capability during incidents<br>- Add a checklist for cleaning up backup resources after lab | 11/05/2026 | 11/05/2026 | https://000013.awsstudygroup.com/ |
| 3    | - Complete Lab24-01.1: Create S3 Bucket<br>- Complete Lab24-01.2: Create EC2 for Storage Gateway<br>- Complete Lab24-02.1: Create Storage Gateway<br>- Complete Lab24-02.2: Create File Shares<br>- Learn about the role of Amazon S3, AWS Storage Gateway, and File Shares<br>- Analyze the hybrid storage model between on-premises environments and AWS<br>- Note use cases for Storage Gateway in enterprises<br>- Check how data is stored, shared, and accessed via file share | 12/05/2026 | 12/05/2026 | https://000024.awsstudygroup.com/ |
| 4    | - Complete Lab57-02.1: Create S3 Bucket<br>- Complete Lab57-02.2: Load data<br>- Complete Lab57-03: Enable static website feature<br>- Complete Lab57-04: Configuring public access block<br>- Complete Lab57-05: Configuring public objects<br>- Complete Lab57-06: Test website<br>- Analyze how S3 works in the static website hosting model<br>- Check the differences between public bucket access and public object access<br>- Note security risks when directly exposing S3 Bucket to the Internet<br>- Check the website after deployment and document access results | 13/05/2026 | 13/05/2026 | https://000057.awsstudygroup.com/ |
| 5    | - Complete Lab57-07.1: Block all public access<br>- Complete Lab57-07.2: Config Amazon CloudFront<br>- Complete Lab57-07.3: Test Amazon CloudFront<br>- Complete Lab57-08: Bucket Versioning<br>- Complete Lab57-09: Move objects<br>- Complete Lab57-10: Replication Object multi Region<br>- Complete Lab57-11: Clean up resources<br>- Analyze the role of CloudFront in speeding up access and protecting origin<br>- Note the benefits of Bucket Versioning and multi-region Object Replication<br>- Complete the architecture diagram for S3 Static Website with CloudFront<br>- Clean up resources to avoid unexpected costs | 14/05/2026 | 14/05/2026 | https://000057.awsstudygroup.com/ |

### Week 4 Achievements:

**Overall:**

In Week 4, I completed the learning content of **Module 03** about the **Compute VM on AWS** service group. This week's content helped me better understand how AWS provides virtual server resources through Amazon EC2, while expanding my knowledge to related components like storage, backup, Auto Scaling, Storage Gateway, S3, and CloudFront.

In addition to studying the module and completing labs, I also added architecture analysis, compared services, checked configuration errors, noted best practices, and evaluated costs when using resources. Through this, I gained a more practical perspective on how to deploy an AWS system with effective storage, backup, recovery, and content distribution capabilities.

**Learned Theory:**

* Understand the role of **Amazon EC2** in providing flexible virtual servers for deploying applications and workloads on AWS.
* Master key EC2 components:

  * Instance Type.
  * AMI.
  * Key Pair.
  * EBS.
  * Instance Store.
  * User Data.
  * Metadata.
  * EC2 Auto Scaling.
* Understand how to choose **Instance Type** based on CPU, RAM, network performance, and storage performance requirements.
* Distinguish between **EBS** and **Instance Store**:

  * EBS is suitable for long-term data storage that can persist independently from EC2 lifecycle.
  * Instance Store is suitable for temporary data, cache, or high-performance workloads that don't require long-term storage.
* Understand the role of **User Data** in automatically running scripts when EC2 Instance is launched.
* Understand the role of **Metadata** in providing configuration information for EC2 Instance.
* Master the role of **EC2 Auto Scaling** in automatically scaling the number of instances based on system load.
* Learn about additional related services:

  * **Amazon EFS**: shared file storage for multiple instances.
  * **Amazon FSx**: managed file systems for specialized workloads.
  * **Amazon Lightsail**: service that simplifies server deployment, suitable for small websites or applications.
  * **AWS Application Migration Service**: supports migrating workloads from current environments to AWS.
* Understand the role of **AWS Backup** in centralized backup and recovery management.
* Understand the role of **Amazon S3** in object storage, static website deployment, and data management.
* Understand the role of **AWS Storage Gateway** in connecting existing storage environments to AWS.
* Understand the role of **Amazon CloudFront** in content distribution, reducing latency, speeding up access, and protecting origin.
* Master object management-related concepts:

  * Bucket Versioning.
  * Move objects.
  * Multi-region Object Replication.
  * Public access block.
  * Static website hosting.
* Note some best practices:

  * Don't public S3 Bucket unless absolutely necessary.
  * Use CloudFront to distribute content instead of directly accessing the bucket.
  * Need to check restore capability after configuring backup.
  * Need to clean up EC2, backup plans, buckets, CloudFront distributions, and related resources after lab.
  * Need to monitor costs when using NAT Gateway, EC2, Storage Gateway, CloudFront, and multi-region replication.

**Practiced with Labs:**

* Completed the **Deploy AWS Backup to the System** lab:

  * Deploy infrastructure.
  * Create Backup Plan.
  * Test Restore.
  * Clean up resources.
* Practiced deploying **AWS Backup**, creating backup plans, and testing data restore capability.
* Note the backup/restore process to understand how to protect data in real-world systems.
* Completed the **Storage Gateway** lab:

  * Create S3 Bucket.
  * Create EC2 for Storage Gateway.
  * Create Storage Gateway.
  * Create File Shares.
* Practiced creating **S3 Bucket**, **Storage Gateway**, and **File Shares** to understand the hybrid storage model on AWS.
* Check how data is shared and accessed via file share.
* Completed the **S3 Static Website** deployment lab:

  * Create S3 bucket.
  * Load data.
  * Enable static website hosting.
  * Configure public access.
  * Configure public objects.
  * Test website.
* Practiced deploying a static website on Amazon S3 and checking Internet access results.
* Practiced configuring **CloudFront** to distribute website content from S3.
* Check the differences between accessing the website directly from S3 and accessing via CloudFront.
* Practiced S3 object management operations:

  * Bucket Versioning.
  * Move objects.
  * Multi-region Object Replication.
* Sketched an architecture diagram for a static website including:

  * User/Client.
  * CloudFront.
  * S3 Bucket.
  * Public access / Block public access.
  * Object versioning.
  * Multi-region replication.
* Note errors or things to check after configuration:

  * Bucket policy.
  * Public access block.
  * Object permission.
  * CloudFront distribution status.
  * S3 website endpoint.
  * Replication rule.
* Cleaned up resources after completing the lab to avoid unnecessary costs.
