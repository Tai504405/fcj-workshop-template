---
title: "Week 11 Journal"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Key Focus & Objectives of Week 11:

* Deploy application containers to Amazon Elastic Container Service (ECS) with AWS Fargate.
* Configure Application Load Balancers (ALBs) to distribute incoming application traffic.
* Create Target Groups and define HTTP endpoints for container health checking.
* Draft Task Definitions specifying compute metrics and variable bindings for services.

### Detailed Weekly Action Items:
| Day | Activity Description | Start | End Date | Documentation |
| --- | --- | --- | --- | --- |
| Mon | Launch the ECS Fargate Cluster (`globalmart-cluster`) to host application workloads. | 29/06/2026 | 29/06/2026 | Project Codebase |
| Tue | Draft ECS Task Definitions: allocate CPU/Memory metrics and configure database bindings. | 30/06/2026 | 30/06/2026 | Project Codebase |
| Wed | Deploy internet-facing Public ALB for frontend ingress and private Internal ALB for backend APIs. | 01/07/2026 | 01/07/2026 | https://aws.amazon.com/elasticloadbalancing/ |
| Thu | Establish Target Groups and configure health checks at `/actuator/health`. | 02/07/2026 | 02/07/2026 | Project Codebase |
| Fri | Create ECS Services to run container tasks and bind them to load balancer listeners. Week 11 review. | 03/07/2026 | 03/07/2026 | Project Codebase |

### Key Accomplishments & Deliverables - Week 11:

* Deployed and managed containerized services on serverless AWS Fargate hosts.
* Balanced traffic distribution using Public and Internal ALBs.
* Configured automatic container recycles via health check alarms.
