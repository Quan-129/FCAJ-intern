---
title: "Week 5 Report"
date: 2026-06-29
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Objectives for Week 5:

* Grasp the design principles and operations of Serverless Architecture.
* Understand how to connect and decouple system components using messaging and queuing services.

### Tasks to be implemented this week:

| Day | Task                                                                                                                                                                                                                                                          | Start Date | End Date   | Resources                                 |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ---------- | ----------------------------------------- |
| 2   | - Study AWS Lambda service: <br>&emsp; + Concepts of Serverless computing <br>&emsp; + Configuring Functions, Triggers, and Destinations <br>&emsp; + Understanding Execution Roles and the billing model                                                     | 29/06/2026 | 29/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Explore Amazon API Gateway: <br>&emsp; + Differentiating REST APIs and HTTP APIs <br>&emsp; + API security methods (IAM, API Keys, Cognito) <br>&emsp; + Throttling and caching mechanisms                                                                  | 30/06/2026 | 30/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - **Hands-on Serverless Lab:** <br>&emsp; + Write a Python Lambda function to process data <br>&emsp; + Use API Gateway to expose an endpoint triggering the Lambda <br>&emsp; + Integrate Lambda to write data into a DynamoDB table                         | 01/07/2026 | 01/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Investigate Application Integration services: <br>&emsp; + Amazon SQS queues (Standard vs FIFO queues, Dead-letter queues) <br>&emsp; + Amazon SNS notification service (Topics, Subscriptions, Fanout architecture)                                        | 02/07/2026 | 02/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Hands-on Event-driven architecture:** <br>&emsp; + Set up S3 Event Notifications for file uploads <br>&emsp; + Trigger a Lambda function to read the event and push a message to SNS <br>&emsp; + Subscribe to receive email notifications via SNS        | 03/07/2026 | 03/07/2026 | <https://cloudjourney.awsstudygroup.com/> |


### Achievements in Week 5:

* Mastered the programming mindset and deployment of Serverless architecture:
  * Successfully initialized and deployed Python source code directly on AWS Lambda without provisioning servers.
  * Clearly understood Execution Roles to grant Lambda secure access to other AWS services.
  * ...

* Gained the ability to build and publish independent APIs:
  * Utilized API Gateway to create RESTful endpoints, routing traffic from users to the backend (Lambda).
  * Knew how to implement throttling to protect backend systems from traffic spikes.
  * ...

* Understood and applied decoupled microservices architecture:
  * Successfully configured SQS queues to buffer pending tasks.
  * Used SNS to broadcast notifications (Fanout) to multiple downstream services or user emails.
  * ...

* Successfully built a basic automated event-driven pipeline (e.g., Upload file to S3 -> Trigger Lambda -> Send SNS notification).
* ...