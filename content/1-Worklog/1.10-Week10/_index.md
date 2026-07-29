---
title: "Week 10 Report"
date: 2026-08-03
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Objectives for Week 10:

* Understand and apply the 6 pillars of the AWS Well-Architected Framework to system design.
* Master cost management tools (FinOps) and establish Disaster Recovery (DR) strategies.

### Tasks to be implemented this week:

| Day | Task                                                                                                                                                                                                                                                          | Start Date | End Date   | Resources                                 |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ---------- | ----------------------------------------- |
| 2   | - Study AWS Well-Architected Framework: <br>&emsp; + Understand the 6 pillars: Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization, and Sustainability <br>&emsp; + How to use the AWS Well-Architected Tool               | 03/08/2026 | 03/08/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Explore Cloud Cost Optimization (FinOps): <br>&emsp; + Analyze data with AWS Cost Explorer and AWS Budgets <br>&emsp; + Compare On-Demand, Reserved Instances, Savings Plans, and Spot Instances                                                            | 04/08/2026 | 04/08/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Investigate Disaster Recovery (DR) Strategies: <br>&emsp; + Concepts of RTO (Recovery Time Objective) and RPO (Recovery Point Objective) <br>&emsp; + 4 DR strategies: Backup & Restore, Pilot Light, Warm Standby, Multi-Site Active/Active                | 05/08/2026 | 05/08/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - **Hands-on AWS Backup Lab:** <br>&emsp; + Configure an automated Backup Plan for EC2 and RDS resources <br>&emsp; + Set up storage lifecycles to automatically transition backups to cold storage for cost savings                                          | 06/08/2026 | 06/08/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Practical System Auditing:** <br>&emsp; + Use AWS Trusted Advisor to scan the current AWS account <br>&emsp; + Implement remediation steps based on flagged security risks and cost-leaking resources                                                     | 07/08/2026 | 07/08/2026 | <https://cloudjourney.awsstudygroup.com/> |


### Achievements in Week 10:

* Formulated a standardized Cloud system design mindset (Well-Architected):
  * Memorized the 6 core design pillars of AWS.
  * Gained the ability to self-evaluate application architectures and identify high-risk issues using the Well-Architected Tool.
  * ...

* Governed and optimized Cloud finances (FinOps):
  * Interpreted cost reports and established automated budget alerts via AWS Budgets.
  * Grasped strategies for selecting appropriate Pricing Models for specific workloads (e.g., using Spot instances for batch processing, Savings Plans for steady state workloads).
  * ...

* Ensured Business Continuity:
  * Successfully set up centralized, automated backup plans using AWS Backup instead of configuring individual services manually.
  * Differentiated and selected appropriate DR strategies aligned with budget constraints and RTO/RPO requirements.
  * Thoroughly remediated account misconfigurations based on actionable recommendations from AWS Trusted Advisor.
  * ...