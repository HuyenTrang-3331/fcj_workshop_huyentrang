---
title: "Week 6 Worklog"
date: 2026-05-22
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Week 6 Objectives:

* Complete learning content of **Module 05** about security and identity management on AWS in the **First Cloud AI Journey** program.
* Understand the **Shared Responsibility Model** and differentiate security responsibilities between AWS and users.
* Learn about security and identity management services like **IAM**, **Amazon Cognito**, **AWS Organizations**, **AWS Identity Center**, **AWS KMS**, and **AWS Security Hub**.
* Practice enabling **AWS Security Hub**, checking security scores, and cleaning up resources after lab.
* Practice using **tags** to manage AWS resources, create Resource Groups, and work with tags via AWS CLI.
* Practice creating **IAM User**, **IAM Policy**, **IAM Role**, **Switch Role**, and checking access based on conditions like tags, region, IP, and time.
* Practice creating restriction policies, IAM limited users, and checking IAM User permissions following the **least privilege** principle.
* Practice encrypting data with **AWS KMS**, logging with **CloudTrail**, querying logs with **Athena**, and checking shared encrypted data on S3.
* Learn about risks of using long-term access keys and compare with safer permission methods using IAM Roles for EC2.
* Practice skills for analyzing access permissions, checking policies, noting configuration errors, and applying AWS security best practices.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| :--- | :--- | :--- | :--- | :--- |
| 1    | - Study Module 05-01: Shared Responsibility Model<br>- Study Module 05-02: Amazon Identity and Access Management<br>- Study Module 05-03: Amazon Cognito<br>- Study Module 05-04: AWS Organization<br>- Study Module 05-05: AWS Identity Center<br>- Study Module 05-06: Amazon Key Management Service<br>- Study Module 05-07: AWS Security Hub<br>- Study Module 05-08: Hands-on and Additional Research<br>- Note important concepts about security, IAM, identity management, encryption, account organization, and security monitoring<br>- Analyze the role of security layer in a real-world AWS architecture | 22/05/2026 | 22/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 2    | - Complete Lab18-02: Enable Security Hub<br>- Complete Lab18-03: Score for each set of criteria<br>- Complete Lab18-04: Clean up resources<br>- Complete Lab22-2.1: Create VPC<br>- Complete Lab22-2.2: Create Security Group<br>- Complete Lab22-2.3: Create EC2 Instance<br>- Complete Lab22-2.4: Incoming Webhooks Slack<br>- Complete Lab22-3: Create Tag for Instance<br>- Complete Lab22-4: Create Role for Lambda<br>- Complete Lab22-5.1: Function stop instance<br>- Complete Lab22-5.2: Function start instance<br>- Complete Lab22-6: Check Result<br>- Complete Lab22-7: Clean up resources<br>- Analyze how Security Hub supports AWS account security assessment<br>- Note how to use tags, Lambda, and Slack webhook to automate EC2 management | 25/05/2026 | 25/05/2026 | https://000018.awsstudygroup.com/<br><br>https://000022.awsstudygroup.com/ |
| 3    | - Complete Lab27-2.1.1: Create EC2 Instance with tag<br>- Complete Lab27-2.1.2: Managing Tags in AWS Resources<br>- Complete Lab27-2.1.3: Filter resources by tag<br>- Complete Lab27-2.2: Using tags with CLI<br>- Complete Lab27-3: Create a Resource Group<br>- Complete Lab27-4: Clean up resources<br>- Complete Lab28-2.1: Create IAM User<br>- Complete Lab28-3: Create IAM Policy<br>- Complete Lab28-4: Create IAM Role<br>- Complete Lab28-5.1: Switch Roles<br>- Analyze the role of tags in resource management, permissions, and operations optimization<br>- Note how IAM Policy and IAM Role control access in AWS | 26/05/2026 | 26/05/2026 | https://000027.awsstudygroup.com/<br><br>https://000028.awsstudygroup.com/ |
| 4    | - Complete Lab28-5.2.1: Initiating access to EC2 console in AWS Region - Tokyo<br>- Complete Lab28-5.2.2: Initiating access to EC2 console in AWS Region - North Virginia<br>- Complete Lab28-5.2.3: Proceed to create EC2 instance when there are no qualified Tags<br>- Complete Lab28-5.2.4: Edit Resource Tag on EC2 Instance<br>- Complete Lab28-5.2.5: Policy Check<br>- Complete Lab28-6: Clean up resources<br>- Complete Lab30-3: Create Restriction Policy<br>- Complete Lab30-4: Create IAM Limited User<br>- Complete Lab30-5: Test IAM User Limits<br>- Complete Lab30-6: Clean up resources<br>- Check access permissions based on region, resource tag, and policy conditions<br>- Note how to apply least privilege to limit IAM User permissions | 27/05/2026 | 27/05/2026 | https://000028.awsstudygroup.com/<br><br>https://000030.awsstudygroup.com/ |
| 5    | - Complete Lab33-2.1: Create Policy and Role<br>- Complete Lab33-2.2: Create Group and User<br>- Complete Lab33-3: Create Key Management Service<br>- Complete Lab33-4.1: Create Bucket<br>- Complete Lab33-4.2: Upload data to S3<br>- Complete Lab33-5.1: Create CloudTrail<br>- Complete Lab33-5.2: Logging to CloudTrail<br>- Complete Lab33-5.3: Create Amazon Athena<br>- Complete Lab33-5.4: Retrieve data with Athena<br>- Complete Lab33-6: Test and share encrypted data on S3<br>- Complete Lab33-7: Resource cleanup<br>- Complete Lab44-2: Create IAM Group<br>- Complete Lab44-3.1: Create IAM Users<br>- Complete Lab44-3.2: Check permissions<br>- Complete Lab44-4.1: Create Admin IAM Role<br>- Complete Lab44-4.2: Configure Switch Role<br>- Complete Lab44-4.3.1: Limit switch role by IP<br>- Complete Lab44-4.3.2: Limit switch role by Time<br>- Complete Lab44-5: Clean up resources<br>- Complete Lab48-1.1: Create EC2 Instance<br>- Complete Lab48-1.2: Create S3 Bucket<br>- Complete Lab48-2.1: Generate IAM User and Access Key<br>- Complete Lab48-2.2: Use Access Key<br>- Complete Lab48-3.1: Create IAM Role<br>- Complete Lab48-3.2: Using IAM Role<br>- Complete Lab48-4: Clean up resources<br>- Analyze the role of KMS, CloudTrail, and Athena in encryption, auditing, and log querying<br>- Compare risks between long-term access keys and IAM Roles for EC2<br>- Clean up resources to avoid unexpected costs | 28/05/2026 | 28/05/2026 | https://000033.awsstudygroup.com/<br><br>https://000044.awsstudygroup.com/<br><br>https://000048.awsstudygroup.com/ |

### Week 6 Achievements:

**Overall:**

In Week 6, I completed the learning content of **Module 05** about security and identity management on AWS. This week's content helped me better understand how AWS organizes security across multiple layers, from identity management, permissions, data encryption, logging, security monitoring to conditional access control.

In addition to studying the module and completing labs, I also added policy analysis, access permission checks, access key vs IAM Role comparisons, security assessments using Security Hub, and noted best practices like least privilege, tag-based access control, data encryption, and audit logs.

**Learned Theory:**

* Understand the **Shared Responsibility Model**:

  * AWS is responsible for security of the cloud.
  * Users are responsible for security in the cloud.
* Master the role of **IAM** in managing:

  * IAM User.
  * IAM Group.
  * IAM Role.
  * IAM Policy.
  * Permission.
  * Access Key.
  * Switch Role.
* Understand the role of **Amazon Cognito** in authenticating and authorizing application users.
* Understand the role of **AWS Organizations** and **AWS Identity Center** in managing multiple AWS accounts and centralized login.
* Understand the role of **AWS KMS** in creating, managing, and using encryption keys to protect data.
* Understand the role of **AWS Security Hub** in aggregating, assessing, and monitoring AWS account security status.
* Master how to use **tags** to categorize resources, filter resources, create Resource Groups, and support access control.
* Understand how IAM Policy can control permissions based on conditions like:

  * Region.
  * Resource tag.
  * IP address.
  * Time.
* Understand the role of **CloudTrail** in logging API activities and supporting auditing.
* Understand how **Athena** can be used to query logs stored on S3.
* Recognize risks of using **long-term access keys** and benefits of **IAM Roles** in providing temporary, safer permissions for workloads.
* Note some best practices:

  * Apply the least privilege principle.
  * Don't use Root User for daily tasks.
  * Limit use of long-term access keys.
  * Prioritize IAM Roles for EC2 and Lambda.
  * Enable MFA for important accounts.
  * Encrypt sensitive data with KMS.
  * Monitor account activity with CloudTrail and Security Hub.
  * Clean up users, roles, policies, access keys, and resources after lab.

**Practiced with Labs:**

* Completed **AWS Security Hub** lab:

  * Enable Security Hub.
  * Check security scores by criteria sets.
  * Clean up resources.
* Practiced creating VPC, Security Group, EC2 Instance, tagging instance, and automating EC2 start/stop with Lambda.
* Practiced integrating **Slack Webhook** to receive notifications for automation.
* Completed **tag management** lab:

  * Create EC2 Instance with tags.
  * Manage tags on AWS Resources.
  * Filter resources by tags.
  * Use tags with AWS CLI.
  * Create Resource Group.
* Completed **IAM User, IAM Policy, IAM Role, and Switch Role** labs:

  * Create IAM User.
  * Create IAM Policy.
  * Create IAM Role.
  * Practice Switch Role.
  * Check permissions by region and resource tag.
* Completed **restriction policy and IAM limited user** labs:

  * Create restriction policy.
  * Create IAM Limited User.
  * Test IAM User permission limits.
* Completed **AWS KMS, S3, CloudTrail, and Athena** labs:

  * Create policy, role, group, and user.
  * Create KMS Key.
  * Create S3 Bucket and upload data.
  * Create CloudTrail and log activities.
  * Create Athena and query logs.
  * Test and share encrypted data on S3.
* Completed **conditional Switch Role** lab:

  * Create IAM Group and IAM Users.
  * Create Admin IAM Role.
  * Configure Switch Role.
  * Limit switch role by IP.
  * Limit switch role by time.
* Completed **Access Key and IAM Role for EC2** lab:

  * Create EC2 Instance.
  * Create S3 Bucket.
  * Create IAM User and Access Key.
  * Use Access Key.
  * Create IAM Role.
  * Attach IAM Role to EC2.
* Note errors or things to check:

  * Policy condition.
  * Resource tag.
  * Region restriction.
  * Access key permission.
  * Role trust policy.
  * KMS key permission.
  * CloudTrail log location.
  * Athena query result.
* Cleaned up users, groups, roles, policies, access keys, EC2, S3, Lambda, Security Hub, and related resources after completing labs.
