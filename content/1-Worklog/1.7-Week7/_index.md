---
title: "Week 7 Report"
date: 2026-07-13
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Objectives for Week 7:

* Build and operate an automated Continuous Integration and Continuous Deployment (CI/CD) pipeline using AWS Developer Tools.
* Master the mechanisms of performance monitoring, centralized logging, and system-wide security auditing.

### Tasks to be implemented this week:

| Day | Task                                                                                                                                                                                                                                                          | Start Date | End Date   | Resources                                 |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ---------- | ----------------------------------------- |
| 2   | - Study CI/CD concepts and AWS CodeBuild: <br>&emsp; + Differences between Continuous Integration, Delivery, and Deployment <br>&emsp; + Configuring the buildspec.yml file <br>&emsp; + Automating source code compilation and testing                       | 13/07/2026 | 13/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Explore AWS CodeDeploy & CodePipeline: <br>&emsp; + Deployment strategies (In-place, Blue/Green deployments) <br>&emsp; + Configuring the appspec.yml file <br>&emsp; + Designing an automated Pipeline workflow from Source to Deployment                  | 14/07/2026 | 14/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - **Hands-on CI/CD Lab:** <br>&emsp; + Connect a GitHub repository to AWS <br>&emsp; + Build a CodePipeline to automatically build and deploy a web application to EC2 upon a new commit                                                                      | 15/07/2026 | 15/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Investigate Amazon CloudWatch monitoring system: <br>&emsp; + Differentiate between Metrics, Alarms, and Events (EventBridge) <br>&emsp; + Collect and analyze centralized logs with CloudWatch Logs <br>&emsp; + Create monitoring Dashboards            | 16/07/2026 | 16/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Study security auditing with AWS CloudTrail: <br>&emsp; + Concepts of API Call Tracking and Event History <br>&emsp; + **Hands-on:** Create a CloudWatch Alarm to trigger when EC2 CPU exceeds 80% and query CloudTrail logs                              | 17/07/2026 | 17/07/2026 | <https://cloudjourney.awsstudygroup.com/> |


### Achievements in Week 7:

* Mastered modern software development and deployment processes (DevOps):
  * Understood and wrote standard configuration files (`buildspec.yml`, `appspec.yml`) to route the application packaging and installation process.
  * Successfully set up a complete CI/CD Pipeline, minimizing manual operations and human errors when releasing new features.
  * Clearly understood the pros and cons of different deployment strategies (Blue/Green vs In-place).
  * ...

* Established an "all-seeing eye" monitoring system for all Cloud resources:
  * Successfully pushed logs from EC2 instances to CloudWatch Logs for centralized management.
  * Automated responses to system anomalies through CloudWatch Alarms (e.g., overload alerts).
  * ...

* Enhanced security and compliance capabilities:
  * Utilized CloudTrail to track all actions (API calls) executed within the AWS account, aiding in troubleshooting and auditing.
  * ...