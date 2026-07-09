---
title: "Week 5 Worklog"
date: 2026-05-15
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Week 5 Objectives:

* Complete learning content of **Module 04** about AWS storage services in the **First Cloud AI Journey** program.
* Learn about key AWS storage services like **Amazon S3**, **AWS Storage Gateway**, **Snow Family**, **Disaster Recovery**, **AWS Backup**, and **Amazon FSx**.
* Master important Amazon S3 concepts like **Bucket**, **Object**, **Object Key**, **Access Point**, **Storage Class**, **Static Website Hosting**, **CORS**, **Control Access**, **Performance**, and **Glacier**.
* Analyze the role of storage in AWS architecture, including data storage, backup, recovery, content distribution, and migration support.
* Practice creating S3 Buckets, deploying infrastructure, creating backup plans, setting up notifications, testing restores, and cleaning up resources.
* Practice migrating virtual machines from on-premises environments to AWS via VMware Workstation, exporting/importing virtual machines, and deploying EC2 Instances from AMIs.
* Practice configuring **AWS Storage Gateway**, creating File Shares, and mounting file shares on on-premises machines.
* Practice creating and managing **Amazon FSx file systems**, testing performance, monitoring performance, enabling data deduplication, shadow copies, user quotas, and scaling capacity.
* Practice deploying static websites on Amazon S3, configuring CloudFront, bucket versioning, move objects, multi-region object replication, and cleaning up resources after labs.
* Practice skills for checking lab results, noting errors, analyzing storage costs, and applying best practices when using AWS Storage.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| :--- | :--- | :--- | :--- | :--- |
| 1    | - Study Module 04-01: Storage Services on AWS<br>- Study Module 04-02: Amazon Simple Storage Service S3 - Access Point - Storage Class<br>- Study Module 04-03: S3 Static Website, CORS, Control Access, Object Key, Performance, and Glacier<br>- Study Module 04-04: Snow Family, Storage Gateway, and Backup<br>- Note important concepts about S3, Storage Class, Glacier, Storage Gateway, Snow Family, and AWS Backup<br>- Analyze the role of storage in real-world cloud architecture<br>- Compare storage categories: object storage, file storage, backup storage, and hybrid storage | 15/05/2026 | 15/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 2    | - Complete Lab13-02.1: Create S3 Bucket<br>- Complete Lab13-02.2: Deploy Infrastructure<br>- Complete Lab13-03: Create Backup Plan<br>- Complete Lab13-04: Set up notifications<br>- Complete Lab13-05: Test Restore<br>- Complete Lab13-06: Clean up resources<br>- Analyze the role of backup in protecting system data<br>- Note the differences between backup, restore, and disaster recovery<br>- Check notifications to monitor backup job status<br>- Add a checklist for cleaning up backup resources after lab | 18/05/2026 | 18/05/2026 | https://000013.awsstudygroup.com/ |
| 3    | - Complete Lab14-01: VMware Workstation<br>- Complete Lab14-02.1: Export Virtual Machine from On-premises<br>- Complete Lab14-02.2: Upload virtual machine to AWS<br>- Complete Lab14-02.3: Import virtual machine to AWS<br>- Complete Lab14-02.4: Deploy Instance from AMI<br>- Complete Lab14-03.1: Setting up S3 Bucket ACL<br>- Complete Lab14-03.2: Export virtual machine from Instance<br>- Complete Lab14-05: Resource Cleanup on AWS Cloud<br>- Analyze the process of migrating virtual machines from on-premises to AWS<br>- Note the role of S3 Bucket, ACL, AMI, and EC2 in the migration process | 19/05/2026 | 19/05/2026 | https://000014.awsstudygroup.com/ |
| 4    | - Complete Lab24-2.1: Create Storage Gateway<br>- Complete Lab24-2.2: Create File Shares<br>- Complete Lab24-2.3: Mount File Shares on On-premises Machine<br>- Complete Lab24-3: Clean up resources<br>- Complete Lab25-2.2: Create an SSD Multi-AZ File System<br>- Complete Lab25-2.3: Create an HDD Multi-AZ File System<br>- Complete Lab25-3: Create New File Shares<br>- Complete Lab25-4: Test Performance<br>- Complete Lab25-5: Monitor Performance<br>- Analyze the hybrid storage model between on-premises systems and AWS<br>- Compare SSD Multi-AZ and HDD Multi-AZ based on performance, cost, and use cases | 20/05/2026 | 20/05/2026 | https://000024.awsstudygroup.com/<br><br>https://000025.awsstudygroup.com/ |
| 5    | - Complete Lab25-6: Enable Data Deduplication<br>- Complete Lab25-7: Enable Shadow Copies<br>- Complete Lab25-8: Manage User Sessions and Open Files<br>- Complete Lab25-9: Enable User Storage Quotas<br>- Complete Lab25-11: Scale Throughput Capacity<br>- Complete Lab25-12: Scale Storage Capacity<br>- Complete Lab25-13: Delete Environment<br>- Complete Lab57-2.1: Create S3 Bucket<br>- Complete Lab57-2.2: Load Data<br>- Complete Lab57-3: Enable Static Website Feature<br>- Complete Lab57-4: Configuring Public Access Block<br>- Complete Lab57-5: Configuring Public Objects<br>- Complete Lab57-6: Test Website<br>- Complete Lab57-7.1: Block All Public Access<br>- Complete Lab57-7.2: Config Amazon CloudFront<br>- Complete Lab57-7.3: Test Amazon CloudFront<br>- Complete Lab57-8: Bucket Versioning<br>- Complete Lab57-9: Move Objects<br>- Complete Lab57-10: Replication Object Multi Region<br>- Complete Lab57-11: Clean up resources<br>- Sketch an architecture diagram for S3 Static Website with CloudFront and multi-region replication<br>- Note best practices about public access, versioning, replication, and optimizing storage costs | 21/05/2026 | 21/05/2026 | https://000025.awsstudygroup.com/<br><br>https://000057.awsstudygroup.com/ |

### Week 5 Achievements:

**Overall:**

In Week 5, I completed the learning content of **Module 04** about AWS storage services. This week's content helped me better understand how AWS supports storage, backup, recovery, migration, hybrid storage, and content distribution through services like Amazon S3, AWS Backup, Storage Gateway, Amazon FSx, and CloudFront.

In addition to studying theory and completing labs, I also added storage architecture analysis, service comparisons, restore checks, file system performance evaluations, and noted security, cost, and resource cleanup considerations after labs.

**Learned Theory:**

* Understand the role of AWS storage services in storing, protecting, backing up, and distributing data.
* Master key services:

  * Amazon S3.
  * AWS Backup.
  * AWS Storage Gateway.
  * Amazon FSx.
  * Snow Family.
  * Disaster Recovery on AWS.
* Understand important Amazon S3 concepts:

  * Bucket.
  * Object.
  * Object Key.
  * Access Point.
  * Storage Class.
  * Static Website Hosting.
  * CORS.
  * Glacier.
* Understand how to choose the right S3 Storage Class to optimize costs based on data access frequency.
* Understand the role of **AWS Backup** in centralized backup and restore management.
* Understand the process of migrating virtual machines from on-premises to AWS via S3, AMI, and EC2.
* Understand the role of **Storage Gateway** in the hybrid storage model.
* Understand the role of **Amazon FSx** in providing managed file systems on AWS.
* Understand the role of **CloudFront** in distributing content from S3, speeding up access, and protecting the origin.
* Note some best practices:

  * Don't public buckets unless necessary.
  * Use CloudFront instead of directly accessing S3.
  * Enable versioning for important data.
  * Check restore after configuring backup.
  * Monitor costs when using replication, FSx, Storage Gateway, and backup.

**Practiced with Labs:**

* Completed the **AWS Backup** lab:

  * Create S3 Bucket.
  * Deploy infrastructure.
  * Create Backup Plan.
  * Set up notifications.
  * Test Restore.
  * Clean up resources.
* Practiced migrating virtual machines from on-premises environments to AWS:

  * Export virtual machine.
  * Upload VM to AWS.
  * Import VM as AMI.
  * Deploy EC2 Instance from AMI.
  * Clean up resources after lab.
* Completed the **AWS Storage Gateway** lab:

  * Create Storage Gateway.
  * Create File Shares.
  * Mount file shares on on-premises machine.
* Completed the **Amazon FSx** lab:

  * Create SSD/HDD Multi-AZ file system.
  * Test and monitor performance.
  * Enable data deduplication, shadow copies, and user quotas.
  * Scale throughput/storage capacity.
* Completed the **S3 Static Website and CloudFront** lab:

  * Create S3 Bucket.
  * Upload data.
  * Enable static website hosting.
  * Configure public access.
  * Configure CloudFront.
  * Enable bucket versioning.
  * Move objects.
  * Configure multi-region object replication.
* Sketched an architecture diagram for the storage layer including S3, CloudFront, AWS Backup, Storage Gateway, FSx, and on-premises environment.
* Cleaned up resources after completing the lab to avoid unnecessary costs.
