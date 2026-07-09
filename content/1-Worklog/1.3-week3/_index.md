---
title: "Week 3 Worklog"
date: 2026-05-01
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Week 3 Objectives:

* Complete learning content of **Module 02** on **Amazon Virtual Private Cloud** in the **First Cloud AI Journey** program.
* Understand the role of Amazon VPC in building private, isolated network environments with access control on AWS.
* Master core AWS Networking components like **VPC**, **Subnet**, **Route Table**, **Internet Gateway**, **NAT Gateway**, **Security Group**, **Network ACLs**, and **EC2 Instance Connect Endpoint**.
* Practice building AWS network models from basic to advanced, including Custom VPC, public/private subnets, NAT Gateway, Hybrid DNS, VPC Peering, and Transit Gateway.
* Understand how to control network traffic using Security Groups and Network ACLs following the principle of least privilege.
* Learn how to design AWS network architecture diagrams that are secure, scalable, and suitable for different deployment needs.
* Practice skills for testing connectivity, troubleshooting network issues, reading route tables, and cleaning up resources after completing labs.

### Tasks to be carried out this week:

| Day | Task | Start Date | Completion Date | Reference Material |
| :--- | :--- | :--- | :--- | :--- |
| 1    | - Study Module 02-01: AWS Virtual Private Cloud<br>- Learn Amazon VPC concept and the role of VPC in AWS architecture<br>- Study Module 02-02: VPC Security and Multi-VPC Features<br>- Learn security mechanisms in VPC and multi-VPC connection models<br>- Study Module 02-03: VPN, Direct Connect, Load Balancer, and Extra Resources<br>- Note important concepts related to networking, network security, and load balancing<br>- Analyze differences between traditional networks and cloud networks<br>- Sketch an overview diagram of the AWS network layer | 01/05/2026 | 01/05/2026 | https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i |
| 2    | - Complete Lab03-01: Start with Amazon VPC and AWS VPN Site-to-Site Introduction<br>- Complete Lab03-01.1: Subnets<br>- Complete Lab03-01.2: Route Table<br>- Complete Lab03-01.3: Internet Gateway IGW<br>- Complete Lab03-01.4: NAT Gateway<br>- Complete Lab03-02.1: Security Group<br>- Complete Lab03-02.2: Network ACLs<br>- Complete Lab03-02.3: VPC Resource Map<br>- Note the role of each component in the VPC model<br>- Compare Security Group and Network ACLs based on scope, state, and rule application | 04/05/2026 | 04/05/2026 | https://000003.awsstudygroup.com/ |
| 3    | - Complete Lab03-03.1: Create VPC<br>- Complete Lab03-03.2: Create Subnet<br>- Complete Lab03-03.3: Create an Internet Gateway<br>- Complete Lab03-03.4: Create Route Table for Outbound Internet Routing via Internet Gateway<br>- Complete Lab03-03.5: Create Security Groups<br>- Complete Lab03-04.1: Create EC2 Instances in Subnets<br>- Complete Lab03-04.2: Test Connection<br>- Complete Lab03-04.3: Create NAT Gateway<br>- Complete Lab03-04.5: EC2 Instance Connect Endpoint<br>- Test connectivity between EC2 instances in public and private subnets<br>- Note common errors when configuring routing, security groups, or NAT Gateway<br>- Add cost considerations when using NAT Gateway and EC2 resources | 05/05/2026 | 05/05/2026 | https://000003.awsstudygroup.com/ |
| 4    | - Complete Lab10-01: Set up Hybrid DNS with Route 53 Resolver Introduction<br>- Complete Lab10-02.1: Generate Key Pair<br>- Complete Lab10-02.2: Initialize CloudFormation Template<br>- Complete Lab10-02.3: Configure Security Group<br>- Complete Lab10-03: Connect to RDGW<br>- Complete Lab10-05: Set up DNS<br>- Complete Lab10-05.1: Create Route 53 Outbound Endpoint<br>- Complete Lab10-05.2: Create Route 53 Resolver Rules<br>- Complete Lab10-05.3: Create Route 53 Inbound Endpoints<br>- Complete Lab10-05.4: Test Results<br>- Complete Lab10-06: Clean up Resources<br>- Learn the role of Route 53 Resolver in Hybrid DNS models<br>- Note how DNS supports connectivity between AWS and on-premises environments | 06/05/2026 | 06/05/2026 | https://000010.awsstudygroup.com/ |
| 5    | - Complete Lab19-01: Set up VPC Peering Introduction<br>- Complete Lab19-02.1: Initialize CloudFormation Templates<br>- Complete Lab19-02.2: Create Security Group<br>- Complete Lab19-02.3: Create EC2 Instance<br>- Complete Lab19-03: Update Network ACLs<br>- Complete Lab19-04: Create a Peering Connection<br>- Complete Lab19-05: Configure Route Tables<br>- Complete Lab19-06: Enable Cross-Peer DNS<br>- Complete Lab19-07: Clean up Resources<br>- Complete Lab20-01: Set up AWS Transit Gateway Introduction<br>- Complete Lab20-02: Preparation Steps<br>- Complete Lab20-03: Create Transit Gateway<br>- Complete Lab20-04: Create Transit Gateway Attachments<br>- Complete Lab20-05: Create Transit Gateway Route Tables<br>- Complete Lab20-06: Add Transit Gateway Routes to VPC Route Tables<br>- Complete Lab20-07: Clean up Resources<br>- Compare VPC Peering and Transit Gateway based on scalability, routing, and use cases<br>- Complete a comprehensive AWS network architecture diagram for Week 3<br>- Clean up resources to avoid unexpected costs | 07/05/2026 | 07/05/2026 | https://000019.awsstudygroup.com/<br><br>https://000020.awsstudygroup.com/ |

### Week 3 Achievements:

**Overall:**

In Week 3, I completed the learning content of **Module 02** on **Amazon Virtual Private Cloud**. This week's content helped me better understand the role of VPC in building a private network environment on AWS, where resources can be segmented, access-controlled, and connected according to system requirements.

In addition to studying the module and completing labs, I also added network architecture analysis, compared different connectivity models, troubleshooted network configuration issues, and noted considerations about security, routing, and costs. Through this, I gained a more practical perspective on designing the network layer in a cloud system, rather than just following step-by-step lab instructions to create resources.

**Learned Theory:**

* Understand the role of **Amazon VPC** in creating private, isolated network environments with access control on AWS.
* Master key components of AWS network architecture:

  * **VPC**: private network space for deploying AWS resources.
  * **Subnet**: divides VPC into smaller network segments to organize resources.
  * **Route Table**: directs network traffic between subnets, gateways, and other connections.
  * **Internet Gateway**: allows resources in public subnets to access the Internet.
  * **NAT Gateway**: allows resources in private subnets to access the Internet outbound without a public IP.
  * **Security Group**: controls traffic at the instance or network interface level.
  * **Network ACLs**: controls traffic at the subnet level.
  * **EC2 Instance Connect Endpoint**: supports connecting to EC2 without opening direct public access.
  * **VPC Resource Map**: provides visual observation of network components in VPC.
* Distinguish between **Security Group** and **Network ACLs**:

  * Security Group operates at the instance or elastic network interface level.
  * Network ACLs operate at the subnet level.
  * Security Group is **stateful**.
  * Network ACLs are **stateless**.
  * Security Group is often used to control direct access to resources.
  * Network ACLs are suitable for creating an additional control layer at the subnet level.
* Understand the role of **Route Table** in determining traffic paths.
* Understand **public subnet** and **private subnet** models:

  * Public subnets typically contain resources that need Internet access like bastion hosts, load balancers, or public EC2 instances.
  * Private subnets typically contain backend servers, databases, or resources that shouldn't be directly exposed to the Internet.
* Master extended connectivity models in AWS:

  * **VPN Site-to-Site**: connects on-premises networks to AWS via VPN.
  * **AWS Direct Connect**: dedicated private connection from external systems to AWS with higher stability.
  * **VPC Peering**: direct connection between two VPCs for resources to communicate via private IPs.
  * **Transit Gateway**: hub-and-spoke model that makes connecting multiple VPCs and different networks easier to manage.
  * **Hybrid DNS**: supports domain name resolution between AWS and on-premises environments.
* Understand the role of **Route 53 Resolver** in Hybrid DNS models.
* Compare **VPC Peering** and **Transit Gateway**:

  * VPC Peering is suitable when the number of VPCs is small and the connectivity model is simple.
  * Transit Gateway is suitable when there are many VPCs, many connections, and a scalable hub-and-spoke network model is needed.
* Master some best practices when designing the network layer:

  * Don't expose unnecessary resources publicly.
  * Only open required ports in Security Groups.
  * Clearly separate public and private subnets.
  * Check route tables when experiencing connectivity issues.
  * Clean up NAT Gateway, EC2, and other network resources after practice to avoid unexpected costs.

**Practiced with Labs:**

* Completed foundational Amazon VPC labs:

  * **Lab03-01:** Start with Amazon VPC and AWS VPN Site-to-Site Introduction.
  * **Lab03-01.1:** Subnets.
  * **Lab03-01.2:** Route Table.
  * **Lab03-01.3:** Internet Gateway.
  * **Lab03-01.4:** NAT Gateway.
  * **Lab03-02.1:** Security Group.
  * **Lab03-02.2:** Network ACLs.
  * **Lab03-02.3:** VPC Resource Map.
* Practiced creating and configuring basic AWS network components:

  * Create VPC.
  * Create Subnet.
  * Create an Internet Gateway.
  * Create Route Table for Outbound Internet Routing via Internet Gateway.
  * Create Security Groups.
  * Create EC2 Instances in Subnets.
  * Test Connection.
  * Create NAT Gateway.
  * EC2 Instance Connect Endpoint.
* Practiced testing connectivity between resources:

  * Test connectivity from public subnet to Internet.
  * Test connectivity from private subnet through NAT Gateway.
  * Test connectivity to EC2 Instance.
  * Check route tables when traffic doesn't follow the correct path.
  * Check Security Group and Network ACLs when connectivity is blocked.
* Practiced configuring **Hybrid DNS with Route 53 Resolver**:

  * Generate Key Pair.
  * Initialize CloudFormation Template.
  * Configure Security Group.
  * Connect to RDGW.
  * Set up DNS.
  * Create Route 53 Outbound Endpoint.
  * Create Route 53 Resolver Rules.
  * Create Route 53 Inbound Endpoints.
  * Test Results.
  * Clean up Resources.
* Practiced configuring **VPC Peering**:

  * Initialize CloudFormation Templates.
  * Create Security Group.
  * Create EC2 Instance.
  * Update Network ACLs.
  * Create a Peering Connection.
  * Configure Route Tables.
  * Enable Cross-Peer DNS.
  * Clean up Resources.
* Practiced configuring **AWS Transit Gateway**:

  * Preparation Steps.
  * Create Transit Gateway.
  * Create Transit Gateway Attachments.
  * Create Transit Gateway Route Tables.
  * Add Transit Gateway Routes to VPC Route Tables.
  * Clean up Resources.
* Added analysis and operational skills after completing labs:

  * Read lab requirements before configuring.
  * Follow each step on AWS Console.
  * Note the role of each created resource.
  * Observe results after each configuration step.
  * Document errors if any.
  * Compare VPC Peering and Transit Gateway models.
  * Sketch network architecture diagrams after completing labs.
  * Clean up resources like EC2, NAT Gateway, Route 53 Resolver Endpoint, VPC Peering, Transit Gateway, and related resources to avoid unexpected costs.
