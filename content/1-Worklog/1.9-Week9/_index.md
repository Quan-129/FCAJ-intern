---
title: "Week 9 Report"
date: 2026-07-27
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Objectives for Week 9:

* Build a foundational understanding of Data Lakes and Serverless Data Analytics tools on AWS.
* Explore and integrate fully managed Artificial Intelligence (AI) and Machine Learning (ML) services into practical applications.

### Tasks to be implemented this week:

| Day | Task                                                                                                                                                                                                                                                          | Start Date | End Date   | Resources                                 |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ---------- | ----------------------------------------- |
| 2   | - Study Data Lake architecture and AWS Glue: <br>&emsp; + Differences between Data Lakes (S3) and Data Warehouses (Redshift) <br>&emsp; + AWS Glue data integration service (ETL) <br>&emsp; + Operating mechanism of the Glue Data Catalog                   | 27/07/2026 | 27/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Explore Amazon Athena: <br>&emsp; + Concept of Serverless data querying <br>&emsp; + **Hands-on:** Use Athena to write standard SQL statements querying raw log files (CSV/JSON) directly from an S3 Bucket                                                 | 28/07/2026 | 28/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Investigate AWS Managed AI Services ecosystem: <br>&emsp; + Amazon Rekognition (Image/Video analysis) <br>&emsp; + Amazon Comprehend (Natural Language Processing - NLP) <br>&emsp; + Amazon Textract (Text extraction)                                     | 29/07/2026 | 29/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Survey Machine Learning platform - Amazon SageMaker: <br>&emsp; + Overview of the ML project lifecycle (Build, Train, Deploy) <br>&emsp; + Introduction to SageMaker Studio and its capabilities for data scientists                                        | 30/07/2026 | 30/07/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Hands-on AI Integration Lab:** <br>&emsp; + Write a Lambda function triggered by an image upload to S3 <br>&emsp; + The Lambda function calls the Rekognition API to detect objects/labels in the image <br>&emsp; + Store the results in DynamoDB      | 31/07/2026 | 31/07/2026 | <https://cloudjourney.awsstudygroup.com/> |


### Achievements in Week 9:

* Mastered concepts of Big Data storage and processing on the Cloud:
  * Understood the principles of building cost-effective Data Lakes using Amazon S3.
  * Gained the ability to use AWS Glue to automatically discover metadata and create a Data Catalog.
  * Successfully queried raw data using standard SQL via Amazon Athena without provisioning database servers.
  * ...

* Took the first steps in integrating AI into application architectures:
  * Identified various AWS Managed AI services available for solving computer vision and natural language processing tasks.
  * Knew how to use code (SDK/CLI) to invoke APIs of services like Rekognition and Comprehend for rapid data analysis.
  * ...

* Understood the Machine Learning model training workflow:
  * Grasped the big picture of the Machine Learning lifecycle on the AWS platform through Amazon SageMaker.
  * Successfully built a fully automated, serverless architecture that detects and classifies images.
  * ...