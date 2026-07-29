---
title: "Week 4 Report"
date: 2026-06-22
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

### Objectives for Week 4:

* Understand and configure Elastic Load Balancing and Auto Scaling systems.
* Grasp the Domain Name System service (Route 53) and Content Delivery Network (CloudFront) to optimize delivery performance.

### Tasks to be implemented this week:

| Day | Task                                                                                                                                                                                                                                                          | Start Date | End Date   | Resources                                 |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ---------- | ----------------------------------------- |
| 2   | - Study Elastic Load Balancing (ELB) services: <br>&emsp; + Differentiate between Application Load Balancer (ALB) and Network Load Balancer (NLB) <br>&emsp; + Concepts of Listeners and Target Groups                                                        | 22/06/2026 | 22/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Explore Auto Scaling Groups (ASG): <br>&emsp; + How to configure Launch Templates <br>&emsp; + Scaling Policies: Target tracking, Step scaling <br>&emsp; + Health Checks mechanism                                                                         | 23/06/2026 | 23/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - **Hands-on High Availability Lab:** <br>&emsp; + Create a Launch Template with Nginx/Apache <br>&emsp; + Set up ASG integrated with an Application Load Balancer (ALB) <br>&emsp; + Test fault tolerance by terminating an instance                         | 24/06/2026 | 24/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Investigate Amazon Route 53 DNS service: <br>&emsp; + Manage Hosted Zones and DNS Records (A, CNAME, Alias) <br>&emsp; + Routing Policies: Simple, Weighted, Failover                                                                                       | 25/06/2026 | 25/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Study Amazon CloudFront (CDN): <br>&emsp; + Caching mechanisms and Edge Locations <br>&emsp; + **Hands-on:** Configure CloudFront to securely distribute static content from an S3 Bucket using Origin Access Control (OAC)                                 | 26/06/2026 | 26/06/2026 | <https://cloudjourney.awsstudygroup.com/> |


### Achievements in Week 4:

* Clearly understood the concepts and features of automated scaling and fault-tolerant systems:
  * Grasped the differences between Load Balancer types (ALB, NLB).
  * Knew how to use Target Groups and Listeners to route traffic.
  * Understood the operating mechanism of Launch Templates and Scaling Policies.
  * ...

* Successfully deployed a basic High Availability architecture:
  * Successfully integrated an Auto Scaling Group with an Application Load Balancer.
  * The system automatically launched or terminated EC2 instances based on Health Check configurations.
  * ...

* Managed domain names and optimized content delivery speed:
  * Understood how to configure DNS Records in Route 53.
  * Differentiated between Alias Records and CNAME Records on AWS.
  * Successfully integrated CloudFront with an S3 Bucket to act as a CDN for static web hosting, reducing latency.
  * ...

* Flexibly combined advanced networking services to build a secure, fast, and resilient web architecture.
* ...