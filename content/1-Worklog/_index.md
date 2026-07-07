---
title: "Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1. </b> "
---

This page aggregates the 12-week internship worklog, tracing the path from acquiring core AWS Cloud competencies to planning, designing, and fully implementing the `GlobalMart` production-ready architecture.

Weekly task summaries:

- **Week 1:** [Cloud Overview, AWS Fundamentals & Basic Security](1.1-week1/) - Explored foundational cloud concepts, created Free Tier accounts, enabled MFA, managed costs with AWS Budgets, and reviewed the Well-Architected Framework.

- **Week 2:** [Compute Services & Cloud Monitoring](1.2-week2/) - Studied Amazon EC2 instances, EBS/EFS storage, configured Auto Scaling, explored Amazon Lightsail, CloudWatch metrics, and AWS MGN migration structures.

- **Week 3:** [AWS Networking & Connectivity](1.3-week3/) - Explored VPC network components, subnets, route tables, IGW/NAT Gateways, Security Groups vs NACLs, Route 53, VPC Peering, Transit Gateway, and Session Manager.

- **Week 4:** [Managed Storage & Database Services](1.4-week4/) - Interacted with Amazon S3 buckets, deployed Amazon RDS MySQL databases, studied high-performance Aurora, and structured backup policies via AWS Backup.

- **Week 5:** [Cloud Security, Governance & Directory Services](1.5-week5/) - Explored user management using Amazon Cognito, configured multi-account governance through AWS Organizations, IAM Identity Center (SSO), KMS encryption, and Security Hub compliance.

- **Week 6:** [Data Lakes, Analytics & Caching](1.6-week6/) - Examined DynamoDB tables, Redshift warehousing, ElastiCache in-memory stores, AWS Glue ETL flows, Athena serverless querying, QuickSight visualization, and database migration using DMS and SCT.

- **Week 7:** [Hybrid Storage, Migration & Disaster Recovery](1.7-week7/) - Explored AWS Storage Gateway systems, physical data transport via Snow Family, virtual machine migration via VM Import/Export, and ran disaster recovery backup drills.

- **Week 8:** [Requirements Assessment, Architecture Design & Local Development](1.8-week8/) - Conducted business specs analysis, designed the 3-tier cloud architecture blueprint for the `GlobalMart` system, and initialized React and Spring Boot starter codes running locally.

- **Week 9:** [Application Development, Dockerization & ECR Repository setup](1.9-week9/) - Packaged frontend/backend web services into multi-stage Docker images, created ECR repositories, and pushed container assets to ECR registries.

- **Week 10:** [Network Infrastructure & Database Deployment](1.10-week10/) - Built the core VPC network infrastructure (VPC, Subnets, SG) for GlobalMart and deployed the RDS MySQL engine in private subnets.

- **Week 11:** [Container Orchestration & Load Balancing](1.11-week11/) - Launched the serverless ECS Fargate Cluster, configured Public/Internal ALBs, Target Groups, Task Definitions, and deployed ECS Services.

- **Week 12:** [API Gateway Connectivity, GitHub Actions CI/CD, Backup/Monitoring & Final Report](1.12-week12/) - Provisioned HTTP API Gateway with VPC Links, configured automated CI/CD via GitHub Actions, structured automated S3 RDS backups, set up CloudWatch alarms, SNS warnings, and finalized the report.
