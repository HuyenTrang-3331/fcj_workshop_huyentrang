---
title: "Week 10 Worklog"
date: 2026-06-19
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Week 10 Objectives:

* Review and reinforce AWS services that support building cloud applications on AWS.
* Reinforce knowledge about **web application** architecture on AWS.
* Learn the workflow between **User**, **Route 53**, **CloudFront**, **AWS WAF**, **Application Load Balancer**, **EC2**, **S3**, and **RDS**.
* Review key network components like **VPC**, **Subnet**, **Route Table**, **Internet Gateway**, **NAT Gateway**, and **Security Group**.
* Practice skills in analyzing, reviewing, and correcting AWS architecture diagrams according to real-world deployment logic.
* Learn security options for internal systems like **VPN**, **IP Allowlist**, **HTTPS**, **Authentication**, **API Key**, and **HMAC**.
* Analyze how to balance security, cost, complexity, and suitability for project scale.
* Prepare weekly report notes, synthesize architecture knowledge, and complete AWS architecture review content.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| :--- | :--- | :--- | :--- | :--- |
| 1    | - Review web application architecture on AWS<br>- Learn the access flow User → Route 53 → CloudFront/WAF → ALB → EC2<br>- Note the role of each component in the architecture<br>- Analyze differences between frontend, backend, and static content access flows<br>- Determine appropriate positions for CloudFront, WAF, ALB, EC2, S3, and RDS in diagrams | 19/06/2026 | 19/06/2026 | https://aws.amazon.com/architecture/ |
| 2    | - Review VPC, Public Subnet, Private Subnet, Route Table, Internet Gateway, and NAT Gateway<br>- Distinguish resources in Region, VPC, Subnet, and global resources<br>- Note how to place services correctly in architecture diagrams<br>- Analyze the role of public and private subnets in system security<br>- Note common errors when misplacing services in AWS architecture | 22/06/2026 | 22/06/2026 | https://docs.aws.amazon.com/vpc/ |
| 3    | - Learn the roles of ALB, CloudFront, WAF, and S3 in web systems<br>- Distinguish between CloudFront to S3 flow and CloudFront/WAF to ALB flow<br>- Note common errors when drawing AWS architecture diagrams<br>- Analyze how CloudFront supports static content delivery and reduces origin load<br>- Note how WAF is attached to CloudFront or ALB instead of being drawn as an independent network node | 23/06/2026 | 23/06/2026 | https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/ |
| 4    | - Learn security options for internal dashboards<br>- Compare WAF, VPN, IP Allowlist, HTTPS, Authentication, API Key, and HMAC<br>- Note how to choose appropriate security options based on cost and project needs<br>- Analyze cases where alternative security layers are needed when not using WAF<br>- Evaluate security options suitable for internal dashboards or small-scale systems | 24/06/2026 | 24/06/2026 | https://docs.aws.amazon.com/waf/ |
| 5    | - Synthesize Week 10 AWS architecture knowledge<br>- Review and correct architecture diagrams for logical accuracy<br>- Complete Week 10 report notes<br>- Clean up unused lab resources or materials<br>- Prepare AWS architecture review checklist including access flow, service positions, subnets, security groups, database, and cost optimization | 25/06/2026 | 25/06/2026 | https://aws.amazon.com/blogs/architecture/ |

### Week 10 Achievements:

**Overall:**

In Week 10, I focused on reviewing and reinforcing knowledge about web application architecture on AWS. This week's content helped me better understand how services like Route 53, CloudFront, WAF, ALB, EC2, S3, and RDS work together to form a complete web application system.

In addition to theoretical review, I practiced skills in reviewing AWS architecture diagrams, identifying design errors, correcting access flows, and analyzing suitable security options for internal dashboards. Through this, I gained the ability to evaluate architecture based on factors like security, cost, ease of deployment, and scalability.

**Learned Theory:**

* Better understood the basic access flow of a web application on AWS:

  * User.
  * Route 53.
  * CloudFront.
  * AWS WAF.
  * Application Load Balancer.
  * EC2 Backend.
  * RDS Database.
* Understood that **CloudFront** can be used to deliver static content from Amazon S3 or forward requests to backends via ALB.
* Understood that **AWS WAF** should not be drawn as an independent intermediate network node, but is usually attached to CloudFront or Application Load Balancer.
* Mastered the role of **Application Load Balancer** in distributing traffic to EC2 backends.
* Understood the role of **Amazon S3** in storing static content or hosting static websites.
* Understood the role of **Amazon RDS** in storing application data.
* Reviewed key network components in AWS:

  * VPC.
  * Public Subnet.
  * Private Subnet.
  * Route Table.
  * Internet Gateway.
  * NAT Gateway.
  * Security Group.
* Distinguished resources in VPC, outside VPC, and global resources.
* Understood that **Internet Gateway** is used for Internet access of resources in public subnets.
* Understood that **NAT Gateway** is mainly used for outbound traffic from private subnets to the Internet.
* Understood the role of **Security Group** in controlling traffic to/from resources like EC2, ALB, or RDS.
* Mastered common errors when drawing AWS architecture diagrams:

  * Drawing IAM as a main data processing flow.
  * Placing WAF in the wrong position.
  * Confusing Internet Gateway and Application Load Balancer.
  * Missing Security Group or Route Table.
  * Not clearly showing public and private subnets.
  * Placing database in a position where it can be accessed directly from the Internet.
* Understood internal dashboard security options:

  * VPN.
  * IP Allowlist.
  * HTTPS.
  * Authentication.
  * API Key.
  * HMAC.
* Knew that alternative security layers are still needed when not using WAF.
* Noted some best practices:

  * Don't expose backend or database directly to the Internet.
  * Place ALB in public subnets and backends/database in private subnets.
  * Use HTTPS for user access flows.
  * Combine Authentication with API Key or HMAC to protect internal APIs.
  * Use IP Allowlist or VPN for internal dashboards.
  * Track costs when using NAT Gateway, ALB, CloudFront, WAF, and RDS.

**Practices and Synthesis:**

* Reviewed AWS web application architecture and the role of each service in the system.
* Analyzed main access flow:

  * User → Route 53 → CloudFront/WAF → ALB → EC2 → RDS.
* Analyzed static content delivery flow:

  * User → Route 53 → CloudFront → S3.
* Practiced thinking about reviewing AWS architecture diagrams based on criteria:

  * Does the access flow make logical sense?
  * Are services placed in correct positions?
  * Are public and private subnets clear?
  * Is the database protected in a private subnet?
  * Are Security Group and Route Table reasonably represented?
  * Are there appropriate security layers for frontend, backend, and internal dashboards?
* Synthesized architecture diagram review checklist:

  * Check system entry points.
  * Check CloudFront, WAF, and ALB positions.
  * Check public/private subnets.
  * Check flow from backend to database.
  * Check security layers.
  * Check potentially high-cost services.
* Analyzed internal dashboard security options:

  * If strong security and internal access are needed: use VPN.
  * If small project and fixed access users: use IP Allowlist.
  * If there are internal APIs: combine HTTPS, Authentication, API Key, or HMAC.
  * If exposed to the Internet and at risk of web attacks: consider WAF.
* Noted cost optimization points:

  * Don't leave EC2, RDS, ALB, or NAT Gateway running when not in use.
  * Control CloudWatch Logs to avoid storing too many logs.
  * Only use WAF or NAT Gateway when truly necessary.
  * Clean up lab resources after completion.
