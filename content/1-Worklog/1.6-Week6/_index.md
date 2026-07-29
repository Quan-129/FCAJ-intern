---
title: "Week 6 Report"
date: 2026-07-06
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Objectives for Week 6:

* Understand and deploy Containerized Applications using the AWS ecosystem (ECR, ECS, and Fargate).
* Grasp the mindset of Infrastructure as Code (IaC) automation through AWS CloudFormation.

### Tasks to be implemented this week:

| Day | Task                                                                                                                                                                                                                                                          | Start Date | End Date   | Resources                                 |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ---------- | ----------------------------------------- |
| 2   | - Study Containers and Amazon ECR: <br>&emsp; + Foundational knowledge of Docker and Containers <br>&emsp; + Introduction to Amazon Elastic Container Registry (ECR) <br>&emsp; + Managing the lifecycle of Container Images                                  | 06/07/2026 | 06/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Explore Amazon ECS & AWS Fargate: <br>&emsp; + Differences between EC2 launch type and Fargate (Serverless compute for containers) <br>&emsp; + Core concepts: Clusters, Task Definitions, and Services                                                     | 07/07/2026 | 07/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - **Hands-on Container Lab:** <br>&emsp; + Build a Docker image for a basic web application <br>&emsp; + Authenticate and Push the image to the ECR repository <br>&emsp; + Deploy the application on ECS using Fargate                                       | 08/07/2026 | 08/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Understand IaC and AWS CloudFormation: <br>&emsp; + Infrastructure as Code concepts <br>&emsp; + Anatomy of a CloudFormation Template (YAML/JSON) <br>&emsp; + Understanding template sections: Resources, Parameters, Outputs                              | 09/07/2026 | 09/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Practical Infrastructure Automation (IaC):** <br>&emsp; + Write a YAML template to provision an EC2 Instance and Security Group <br>&emsp; + Deploy and Update the Stack via Console/CLI <br>&emsp; + Delete the Stack to clean up resources            | 10/07/2026 | 10/07/2026 | <https://cloudjourney.awsstudygroup.com/> |


### Achievements in Week 6:

* Mastered the process of packaging and deploying applications using Containers on AWS:
  * Understood how to build Docker images and store them securely on Amazon ECR.
  * Successfully configured Task Definitions to specify resources (CPU, RAM) for containers.
  * Deployed a Service on ECS using Fargate, entirely eliminating the need to manage server operating systems.
  * ...

* Shifted infrastructure deployment mindset from manual provisioning (ClickOps) to automation (IaC):
  * Understood how to declare infrastructure as code (CloudFormation Templates).
  * Grasped the process of creating, updating, and deleting entire environments (Stacks) through a single, unified operation.
  * ...

* Optimized the resource cleanup process by deleting CloudFormation Stacks, helping to strictly control learning costs.
* ...