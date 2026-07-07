---
title: "Week 3 Worklog"
date: 2026-05-04
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Key Focus & Objectives of Week 3:

* Master custom network designs on AWS, covering VPC blocks, subnet scopes, and route paths.
* Implement firewall security policies using Security Groups and subnet NACL tables.
* Examine transit routing topologies: VPC Peering, Transit Gateway, and Route 53 resolvers.
* Configure secure bastionless SSH connections using Systems Manager Session Manager.

### Detailed Weekly Action Items:
| Day | Activity Description | Start | End Date | Documentation |
| --- | --- | --- | --- | --- |
| Mon | Design a custom VPC architecture: define IP CIDRs, split subnets, and configure Route Tables, IGWs, and NAT Gateway. | 04/05/2026 | 04/05/2026 | https://000003.awsstudygroup.com |
| Tue | Compare stateful Security Group filters with stateless NACL access rules. Activate VPC Flow Logs. | 05/05/2026 | 05/05/2026 | https://000003.awsstudygroup.com |
| Wed | Study traffic load balancing via ALBs/NLBs and custom domain mapping using Route 53 DNS records. | 06/05/2026 | 06/05/2026 | https://000010.awsstudygroup.com |
| Thu | Establish VPC Peering connections and centralize routing paths via Transit Gateway configurations. | 07/05/2026 | 07/05/2026 | https://000019.awsstudygroup.com <br> https://000020.awsstudygroup.com |
| Fri | Access console shells on private hosts via Systems Manager Session Manager. Week 3 review. | 08/05/2026 | 08/05/2026 | https://000058.awsstudygroup.com |

### Key Accomplishments & Deliverables - Week 3:

* Engineered virtual networks containing separate public ingress and private backends.
* Secured inbound/outbound ports using SG rules and NACL configurations.
* Routed internal traffic between VPCs using Peering links and Transit Gateway hubs.
* Managed private shell sessions securely using AWS Systems Manager.
