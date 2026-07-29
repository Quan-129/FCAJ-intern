---
title: "Week 8 Report"
date: 2026-07-20
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Objectives for Week 8:

* Master data encryption methodologies, cryptographic key management, and centralized credential storage.
* Build a defense layer against common web exploits and manage servers without opening public network ports.

### Tasks to be implemented this week:

| Day | Task                                                                                                                                                                                                                                                          | Start Date | End Date   | Resources                                 |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ---------- | ----------------------------------------- |
| 2   | - Study encryption with AWS KMS (Key Management Service): <br>&emsp; + Data encryption at rest and in transit <br>&emsp; + Differentiate between Customer Managed Keys (CMK) and AWS Managed Keys                                                             | 20/07/2026 | 20/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Explore AWS Secrets Manager & SSM Parameter Store: <br>&emsp; + Compare features and pricing of both services <br>&emsp; + Automated Credential Rotation mechanism integrated with Amazon RDS                                                               | 21/07/2026 | 21/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - **Hands-on Secrets Management Lab:** <br>&emsp; + Encrypt an S3 bucket using a custom KMS key <br>&emsp; + Store database credentials securely in Secrets Manager <br>&emsp; + Write code for EC2/Lambda to fetch secrets via API instead of hardcoding     | 22/07/2026 | 22/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Investigate Edge Security with AWS WAF & Shield: <br>&emsp; + Anti-DDoS mechanisms of AWS Shield (Standard vs Advanced) <br>&emsp; + Configure AWS WAF on ALB/CloudFront to mitigate OWASP Top 10 vulnerabilities (SQLi, XSS)                               | 23/07/2026 | 23/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Study AWS Systems Manager (SSM): <br>&emsp; + Operational mechanics of the SSM Agent <br>&emsp; + **Hands-on:** Use SSM Session Manager to terminal into an EC2 instance in a Private Subnet without a Bastion Host or opening port 22 (SSH)              | 24/07/2026 | 24/07/2026 | <https://cloudjourney.awsstudygroup.com/> |


### Achievements in Week 8:

* Elevated data security standards for the architecture:
  * Understood how to utilize AWS KMS to create and manage the lifecycle of encryption keys.
  * Grasped the fundamental rule of never hardcoding passwords or tokens directly into the source code.
  * Proficiently used Parameter Store and Secrets Manager to securely store and retrieve sensitive configuration data.
  * ...

* Successfully deployed robust Application Protection shields:
  * Knew how to set up Web Application Firewall (AWS WAF) rules to block malicious requests, safeguarding the Load Balancer or CloudFront distribution.
  * Understood how AWS Shield automatically protects the infrastructure from Distributed Denial of Service (DDoS) attacks.
  * ...

* Optimized secure system operations (SecOps):
  * Completely eliminated the security risks associated with exposing SSH ports (port 22) to the public Internet.
  * securely logged into servers via the web/CLI using SSM Session Manager, while simultaneously logging all executed commands for auditing purposes.
  * ...