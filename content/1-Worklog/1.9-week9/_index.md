---
title: "Week 9 Worklog"
date: 2026-06-12
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Week 9 Objectives:

* Review and reinforce the content learned in the **First Cloud AI Journey** program.
* Systematize knowledge about core AWS service groups like Compute, Storage, Networking, Database, Security, and Management Tools.
* Learn more about AWS security, especially **IAM**, **MFA**, **Policy**, **Role**, and the **Least Privilege** principle.
* Learn how to manage costs on AWS via **AWS Budgets**, **Cost Explorer**, Free Tier, and resource cleanup processes after labs.
* Practice skills in analyzing AWS architecture diagrams and identifying the role of each service in the system.
* Note common errors when configuring IAM, permissions, Billing access, and resource management.
* Prepare report content, study notes, and sharing materials related to AWS IAM, account security, and cost optimization.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| :--- | :--- | :--- | :--- | :--- |
| 1    | - Review foundational knowledge about AWS Cloud<br>- Systematize core service groups like Compute, Storage, Networking, Database, Security, and Management Tools<br>- Note the role of each service group in cloud architecture<br>- Analyze how AWS services coordinate in a real system<br>- Summarize key knowledge from previous weeks | 12/06/2026 | 12/06/2026 | https://cloudjourney.awsstudygroup.com/vi/ |
| 2    | - Review AWS IAM<br>- Re-learn User, Group, Role, Policy, and Permission<br>- Learn the Least Privilege principle in granting permissions<br>- Note common errors when configuring IAM permissions<br>- Analyze the differences between IAM User and IAM Role<br>- Note best practices when granting permissions to users and services | 15/06/2026 | 15/06/2026 | https://docs.aws.amazon.com/iam/ |
| 3    | - Learn MFA, IAM Identity Center, and secure access management<br>- Review how to grant Billing access to IAM Users<br>- Learn the role of IAM in AWS account security<br>- Note how to protect the Root User, enable MFA, and limit the use of long-term access keys<br>- Analyze the role of single sign-on in environments with multiple AWS Accounts | 16/06/2026 | 16/06/2026 | https://docs.aws.amazon.com/IAM/latest/UserGuide/ |
| 4    | - Learn cost optimization on AWS<br>- Review AWS Budgets, Cost Explorer, and Free Tier<br>- Note common cost-driving factors like NAT Gateway, EC2, RDS, CloudWatch Logs, and Load Balancer<br>- Practice checking and cleaning up unused resources<br>- Create a cost check checklist after completing labs<br>- Analyze how tagging helps track costs by project or environment | 17/06/2026 | 17/06/2026 | https://aws.amazon.com/aws-cost-management/ |
| 5    | - Summarize Week 9 study content<br>- Write notes/sharing materials about IAM and cost optimization<br>- Prepare weekly report content<br>- Complete the week's achievements section<br>- Review key knowledge about security, cost, and AWS architecture<br>- Prepare content for presentations or sharing within the study group | 18/06/2026 | 18/06/2026 | https://aws.amazon.com/blogs/security/ |

### Week 9 Achievements:

**Overall:**

In Week 9, I focused on reviewing and systematizing the knowledge learned in the **First Cloud AI Journey** program. This week's content helped me reinforce the role of core AWS service groups, while better understanding how services work together in a real-world cloud architecture.

In addition to review, I also deepened my knowledge of **IAM**, account security, access management, cost optimization, and resource cleanup after labs. Through this, I formed habits of checking access permissions, tracking costs, and evaluating resources before deploying or ending a practice exercise.

**Learned Theory:**

* Systematized core AWS service groups:

  * Compute.
  * Storage.
  * Networking.
  * Database.
  * Security.
  * Management Tools.
* Better understood the role of each service group in AWS architecture.
* Mastered the role of **IAM** in managing identities and permissions on AWS.
* Reviewed core IAM components:

  * User.
  * Group.
  * Role.
  * Policy.
  * Permission.
* Understood the **Least Privilege** principle and why only the minimum necessary permissions should be granted to users or services.
* Distinguished between **IAM User** and **IAM Role**:

  * IAM User is suitable for users or accounts that need direct login.
  * IAM Role is suitable for granting temporary permissions to services or workloads.
* Understood the importance of **MFA** in protecting AWS accounts.
* Understood the role of **IAM Identity Center** in managing single sign-on.
* Knew how to grant **Billing** access to IAM Users.
* Mastered common cost-driving factors on AWS:

  * EC2 Instance running continuously.
  * RDS Database Instance not stopped or deleted.
  * NAT Gateway incurring hourly and data processing costs.
  * CloudWatch Logs storing too many logs.
  * Load Balancer not used but not deleted.
  * S3 storage, versioning, or replication not properly controlled.
* Understood the role of **AWS Budgets** and **Cost Explorer** in tracking, alerting, and analyzing costs.
* Noted some best practices:

  * Enable MFA for Root User and important IAM Users.
  * Don't use Root User for daily tasks.
  * Limit use of long-term access keys.
  * Prioritize using IAM Roles for EC2, Lambda, and workloads.
  * Tag resources for easy management and cost tracking.
  * Check resources after each lab to avoid unnecessary costs.

**Practices and Synthesis:**

* Reviewed foundational knowledge about AWS Cloud and core service groups.
* Summarized the role of each service group in a basic AWS architecture.
* Reviewed key IAM content:

  * User.
  * Group.
  * Role.
  * Policy.
  * Permission.
  * MFA.
  * Billing access.
* Analyzed common IAM configuration errors:

  * Granting overly broad permissions.
  * Assigning policies to the wrong entities.
  * Not enabling MFA.
  * Using long-term access keys.
  * Not understanding trust policies when using roles.
* Practiced thinking about checking access permissions based on the least privilege principle.
* Reviewed cost tracking using AWS Budgets, Cost Explorer, and Free Tier.
* Created a post-lab resource check checklist:

  * EC2 Instance.
  * RDS Database.
  * NAT Gateway.
  * Load Balancer.
  * CloudWatch Logs.
  * S3 Bucket.
  * Unused IAM User, Role, Policy.
* Noted services that can incur high costs if not properly controlled, like NAT Gateway, RDS, CloudWatch Logs, and Load Balancer.
* Prepared sharing content about **IAM**, account security, and cost optimization on AWS.
* Practiced skills in analyzing AWS architecture diagrams, identifying each service's role, and recognizing areas for improvement in security or cost.
