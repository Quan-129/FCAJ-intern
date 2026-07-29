---
title: "Week 11 Report"
date: 2026-08-10
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Objectives for Week 11:

* Master advanced network connectivity models in Multi-account and Hybrid Cloud environments.
* Understand how to optimize performance and transmission latency between disparate infrastructures.

### Tasks to be implemented this week:

| Day | Task                                                                                                                                                                                                                                                          | Start Date | End Date   | Resources                                 |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ---------- | ----------------------------------------- |
| 2   | - Study advanced network connectivity: <br>&emsp; + VPC Peering (Direct network connection between VPCs) <br>&emsp; + AWS Transit Gateway (Hub-and-Spoke model for centralized VPC management) <br>&emsp; + VPC Endpoints (Interface & Gateway)               | 10/08/2026 | 10/08/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Explore Hybrid Cloud models: <br>&emsp; + Site-to-Site VPN (Connection over public Internet) <br>&emsp; + AWS Direct Connect (Dedicated private connection) <br>&emsp; + Comparative analysis vs traditional infrastructure                                 | 11/08/2026 | 11/08/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - **Hands-on Network Lab:** <br>&emsp; + Establish VPC Peering between 2 VPCs in the same Region <br>&emsp; + Configure Routes to allow EC2 instances in different VPCs to communicate using private IPs                                                   | 12/08/2026 | 12/08/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Investigate AWS PrivateLink: <br>&emsp; + Mechanism for secure service sharing between VPCs without public Internet <br>&emsp; + Application of PrivateLink in complex Microservices architectures                                                      | 13/08/2026 | 13/08/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Practical Infrastructure Optimization:** <br>&emsp; + Configure S3 Interface Endpoints to access S3 from private subnets without a NAT Gateway <br>&emsp; + Compare costs between NAT Gateway and VPC Endpoints for high-volume traffic               | 14/08/2026 | 14/08/2026 | <https://cloudjourney.awsstudygroup.com/> |


### Achievements in Week 11:

* Mastered advanced VPC connectivity techniques:
  * Clearly understood how to scale infrastructure from a single VPC to a multi-VPC architecture using Transit Gateway.
  * Gained the ability to use VPC Peering to safely connect data between isolated environments.
  * ...

* Deepened understanding of Hybrid Cloud connectivity:
  * Grasped the various solutions for connecting on-premises data centers with AWS (VPN vs Direct Connect).
  * Learned how to select the optimal solution based on enterprise bandwidth and latency requirements.
  * ...

* Optimized network infrastructure using VPC Endpoints:
  * Leveraged PrivateLink to enable seamless communication between AWS services without traversing the public Internet.
  * Significantly reduced data transfer costs and improved security by replacing NAT Gateways with Gateway/Interface Endpoints for common AWS services (like S3, DynamoDB).
  * ...