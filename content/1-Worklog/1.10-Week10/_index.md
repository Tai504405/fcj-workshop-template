---
title: "Week 10 Journal"
date: 2026-06-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Key Focus & Objectives of Week 10:

* Provision secure custom VPC networks for the `GlobalMart` production setup.
* Configure route tables and gateway nodes (IGW and NAT) for subnet routing.
* Deploy a managed Amazon RDS MySQL instance in private database subnets.
* Establish database tables in RDS using an EC2 bastion host configuration.

### Detailed Weekly Action Items:
| Day | Activity Description | Start | End Date | Documentation |
| --- | --- | --- | --- | --- |
| Mon | Build a dedicated VPC (`globalmart-vpc`, CIDR `10.0.0.0/16`) and allocate public and private subnets. | 22/06/2026 | 22/06/2026 | Project Codebase |
| Tue | Configure Internet Gateways, NAT Gateways, and set up Route Tables for subnets. | 23/06/2026 | 23/06/2026 | Project Codebase |
| Wed | Configure layered Security Group rules, locking port 3306 database ingress to backend nodes. | 24/06/2026 | 24/06/2026 | Project Codebase |
| Thu | Launch Amazon RDS MySQL instance (Single-AZ, db.t3.micro) inside private database subnets. | 25/06/2026 | 25/06/2026 | https://aws.amazon.com/rds/ |
| Fri | Deploy a temporary bastion EC2 instance to execute database schema seeding. Week 10 review. | 26/06/2026 | 26/06/2026 | Project Codebase |

### Key Accomplishments & Deliverables - Week 10:

* Engineered a secure 3-tier network topology under custom VPC configurations.
* Launched isolated RDS MySQL engines with no direct public access paths.
* Successfully seeded SQL schemas into the cloud database.
