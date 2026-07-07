---
title: "Week 11 Worklog"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Focus & Objectives of Week 11:

* Deploy the containerized workloads onto Amazon Elastic Container Service (ECS) with AWS Fargate.
* Configure Application Load Balancers (ALBs) to route client and API traffic.
* Draft Task Definitions and Target Groups managing container states.
* Verify service container health checks and resolve load balancer forwardings.

### Detailed Weekly Action Items:
| No. | Task Description | Start | Completion | Reference Links |
| --- | --- | --- | --- | --- |
| 2 | Create the ECS Fargate Cluster (`globalmart-cluster`) on the AWS console. | 29/06/2026 | 29/06/2026 | Project Source |
| 3 | Write ECS Task Definitions defining CPU allocations, memory, and container ports. | 30/06/2026 | 30/06/2026 | Project Source |
| 4 | Deploy an internet-facing ALB for the frontend and an internal ALB for the backend APIs. | 01/07/2026 | 01/07/2026 | https://aws.amazon.com/elasticloadbalancing/ |
| 5 | Configure Target Groups and health checks to ensure continuous routing paths. | 02/07/2026 | 02/07/2026 | Project Source |
| 6 | Launch ECS Services to maintain tasks and link them with load balancer endpoints. Review Week 11. | 03/07/2026 | 03/07/2026 | Project Source |

### Key Accomplishments - Week 11:

* Deployed scalable microservices on serverless container hosts.
* Established ALBs for directing web ingress and API service networks.
* Stabilized task deployments with custom health indicators.
