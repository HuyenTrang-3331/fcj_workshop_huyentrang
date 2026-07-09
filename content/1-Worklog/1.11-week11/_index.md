---
title: "Week 11 Worklog"
date: 2026-06-12
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Week 11 Objectives:

- Learn about AWS services for monitoring, logging, security, and risk detection during system operations.
- Review the roles of **Amazon CloudWatch**, **AWS CloudTrail**, **AWS Config**, **Amazon GuardDuty**, and **AWS Security Hub**.
- Understand how to monitor system activity through **metrics**, **logs**, **alarms**, and **dashboards**.
- Learn how to detect abnormal behavior, security risks, and configuration issues in an AWS environment.
- Practice skills in checking logs, evaluating alerts, classifying severity levels, and proposing incident handling directions.
- Analyze the role of monitoring, logging, and security in a real-world AWS architecture.
- Synthesize knowledge for weekly reports and prepare content for the final stage of the learning program.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| :--- | :--- | :--- | :--- | :--- |
| 1    | - Learn about Amazon CloudWatch<br>- Note the roles of Metrics, Logs, Alarms, and Dashboard<br>- Learn how CloudWatch supports monitoring AWS resources<br>- Analyze how CloudWatch is used to monitor EC2, RDS, Lambda, and operational services in the system<br>- Note situations where alarms should be created for early incident warnings | 26/06/2026 | 26/06/2026 | https://docs.aws.amazon.com/cloudwatch/ |
| 2    | - Learn about AWS CloudTrail<br>- Note CloudTrail's role in tracking API calls and user activity<br>- Distinguish between CloudWatch Logs and CloudTrail Logs<br>- Analyze how CloudTrail supports auditing, checking administrative actions, and tracing events in an AWS account<br>- Note situations where CloudTrail should be checked when detecting unusual changes | 29/06/2026 | 29/06/2026 | https://docs.aws.amazon.com/cloudtrail/ |
| 3    | - Learn about Amazon GuardDuty and AWS Security Hub<br>- Note how these services support detecting security risks<br>- Learn about finding, severity, and remediation concepts<br>- Analyze how GuardDuty detects abnormal behavior based on logs and threat intelligence<br>- Note how Security Hub aggregates findings from many different security services | 30/06/2026 | 30/06/2026 | https://docs.aws.amazon.com/guardduty/ |
| 4    | - Learn about AWS Config and checking resource compliance<br>- Note the roles of rules, resource inventory, and configuration history<br>- Connect to real-world cloud system administration<br>- Analyze how AWS Config supports tracking configuration changes and detecting non-compliant resources<br>- Note some examples of common compliance rules in AWS administration | 01/07/2026 | 01/07/2026 | https://docs.aws.amazon.com/config/ |
| 5    | - Synthesize monitoring and security knowledge on AWS<br>- Note basic log checking, alerting, and error handling processes<br>- Complete Week 11 report content<br>- Build a system check checklist based on logs, metrics, alarms, findings, and compliance<br>- Prepare presentation content about monitoring, logging, and security in AWS | 02/07/2026 | 02/07/2026 | https://aws.amazon.com/security/ |

### Week 11 Achievements:

**Overall:**

In Week 11, I focused on learning about AWS services supporting **monitoring**, **logging**, **security**, and **risk detection**. This week's content helped me better understand how to track system status, record user activity, detect abnormal behavior, and check the compliance status of AWS resources.

In addition to theoretical review, I also added analysis of real-world operational processes, including how to check logs, evaluate alerts, classify finding severity levels, and propose initial handling directions when there are performance or security incidents.

**Learned Theory:**

- Understand the role of **monitoring** and **logging** in operating AWS systems.
- Master the role of **Amazon CloudWatch** in monitoring resources and applications.
- Understand key CloudWatch components:

  - Metrics.
  - Logs.
  - Alarms.
  - Dashboards.
- Know how CloudWatch supports monitoring the status of EC2, RDS, Lambda, and other AWS services.
- Understand the role of **AWS CloudTrail** in recording API calls, user activity, and administrative actions on an AWS account.
- Distinguish between **CloudWatch** and **CloudTrail**:

  - CloudWatch is used to monitor performance, application logs, and system alerts.
  - CloudTrail is used to record user actions, API calls, and account administrative activity.
- Understand the role of **Amazon GuardDuty** in detecting abnormal behavior, suspicious access, or security risks.
- Understand the role of **AWS Security Hub** in aggregating, evaluating, and managing findings from multiple security services.
- Master basic concepts:

  - Finding.
  - Severity.
  - Remediation.
  - Threat Detection.
  - Compliance.
- Understand the role of **AWS Config** in tracking resource configurations, checking compliance, and storing configuration change history.
- Note some best practices:

  - Set up alarms for important resources.
  - Check CloudTrail when there are unusual changes in the account.
  - Monitor findings from GuardDuty and Security Hub.
  - Use AWS Config to check if resources comply with policies.
  - Classify alerts by severity level before handling.
  - Combine monitoring, logging, and security to operate the system more securely.

**Practices and Synthesis:**

- Synthesized the roles of monitoring and security services on AWS:

  - Amazon CloudWatch.
  - AWS CloudTrail.
  - AWS Config.
  - Amazon GuardDuty.
  - AWS Security Hub.
- Practiced thinking about checking systems based on:

  - Metric.
  - Log.
  - Alarm.
  - Finding.
  - Severity.
  - Compliance rule.
- Analyzed basic incident checking processes:

  - Identify affected services.
  - Check CloudWatch metrics and alarms.
  - View logs related to applications or resources.
  - Check CloudTrail to identify configuration change actions.
  - Check findings from GuardDuty or Security Hub if security risks are suspected.
  - Propose appropriate handling or remediation directions.
- Noted real-world situations to pay attention to:

  - EC2 CPU increasing unusually high.
  - RDS having unstable connections or performance.
  - Lambda errors when running.
  - IAM User or Role having unusual activity.
  - AWS resources misconfigured or not complying with policy.
- Built a monitoring and security check checklist:

  - Are CloudWatch Alarms configured?
  - Are logs stored and easily retrievable?
  - Is CloudTrail recording full account activity?
  - Has GuardDuty/Security Hub detected any critical findings?
  - Has AWS Config detected any non-compliant resources?
  - Are there handling or remediation directions for important alerts?
- Practiced skills in reading logs, evaluating alerts, and proposing initial handling directions when incidents occur.
- Completed study notes about CloudWatch, CloudTrail, GuardDuty, Security Hub, and AWS Config.
