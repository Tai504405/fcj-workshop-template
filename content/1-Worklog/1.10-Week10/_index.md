---
title: "Week 10 Worklog"
date: 2026-06-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Focus & Objectives of Week 10:

* Establish isolated cloud networking infrastructure for the `GlobalMart` project on AWS.
* Deploy a managed Amazon RDS MySQL instance into a private database subnet group.
* Design tiered Security Groups to restrict database ports.
* Initialize schemas and test database routing from a temporary EC2 bastion host.

### Detailed Weekly Action Items:
| No. | Task Description | Start | Completion | Reference Links |
| --- | --- | --- | --- | --- |
| 2 | Provision the VPC network (CIDR 10.0.0.0/16) with dedicated public and private subnets. | 22/06/2026 | 22/06/2026 | Project Source |
| 3 | Configure Internet Gateways, NAT Gateways, and subnet Route Tables. | 23/06/2026 | 23/06/2026 | Project Source |
| 4 | Set up layered Security Groups restricting inbound rules for database access. | 24/06/2026 | 24/06/2026 | Project Source |
| 5 | Deploy Amazon RDS MySQL (Single-AZ, db.t3.micro) in private DB subnets. | 25/06/2026 | 25/06/2026 | https://aws.amazon.com/rds/ |
| 6 | Launch a temporary EC2 instance to seed tables and test DB access. Review Week 10. | 26/06/2026 | 26/06/2026 | Project Source |

### Key Accomplishments - Week 10:

* Created a secure 3-tier networking blueprint under custom VPC scopes.
* Successfully deployed isolated MySQL engines with zero public access.
* Verified database connectivity and completed table creation procedures.
