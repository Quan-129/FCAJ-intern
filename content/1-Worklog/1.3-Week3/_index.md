---
title: "Week 3 Report"
date: 2026-06-15
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Objectives for Week 3:

* Understand the architecture and be able to set up an independent virtual network infrastructure (Amazon VPC).
* Grasp and practically deploy database services on AWS (Amazon RDS and DynamoDB).

### Tasks to be implemented this week:

| Day | Task                                                                                                                                                                                                                                                        | Start Date | End Date   | Resources                                 |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ---------- | ----------------------------------------- |
| 2   | - Study Amazon VPC virtual network infrastructure: <br>&emsp; + Analyze components: Subnets, Route Tables <br>&emsp; + Role of Internet Gateway (IGW) and NAT Gateway <br>&emsp; + Differentiate between Security Groups and NACL                           | 15/06/2026 | 15/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - **Hands-on VPC:** <br>&emsp; + Create a Custom VPC <br>&emsp; + Set up Public Subnet and Private Subnet <br>&emsp; + Configure Route Tables for secure EC2 Internet access                                                                                | 16/06/2026 | 16/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Explore Relational Database Service (Amazon RDS): <br>&emsp; + Supported engines (MySQL, PostgreSQL,...) <br>&emsp; + Multi-AZ standby architecture <br>&emsp; + Read Replicas mechanism                                                                  | 17/06/2026 | 17/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - **Practical RDS implementation:** <br>&emsp; + Launch a Database Instance (MySQL/PostgreSQL) <br>&emsp; + Configure Security Group to allow connections from EC2 <br>&emsp; + Use a client to access and manipulate sample data                           | 18/06/2026 | 18/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Study Amazon DynamoDB non-relational database service: <br>&emsp; + NoSQL concepts, Tables, Items, and Attributes <br>&emsp; + Importance of Partition Key and Sort Key <br>&emsp; + **Hands-on:** Create tables and query data                           | 19/06/2026 | 19/06/2026 | <https://cloudjourney.awsstudygroup.com/> |


### Achievements in Week 3:

* Mastered network architecture and data flow communication within AWS through VPC:
  * Successfully segregated the internal network environment using Public and Private Subnets.
  * Accurately configured Internet Gateways and Route Tables.
  * Understood and correctly applied network security layers (Security Groups and Network ACLs).
  * ...

* Understood the structure and smoothly operated the Amazon RDS database service:
  * Successfully launched a standard Database Instance.
  * Understood the Multi-AZ mechanism to ensure High Availability (HA).
  * Successfully connected an application on an EC2 virtual server to an internal RDS.
  * ...

* Initially familiarized with the NoSQL database management system through Amazon DynamoDB:
  * Understood how to organize unstructured data.
  * Created tables and performed basic data operations from the AWS Console.
  * ...

* Confidently set up a basic 2-tier architecture environment (Web Server on EC2 in a Public Subnet, Database in a Private Subnet).
* ...