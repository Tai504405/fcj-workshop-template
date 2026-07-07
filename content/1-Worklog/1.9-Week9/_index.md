---
title: "Week 9 Journal"
date: 2026-06-15
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Key Focus & Objectives of Week 9:

* Standardize and compile application codebases into Docker images.
* Shrink Docker image sizes leveraging multi-stage build patterns.
* Provision cloud container registries inside Amazon Elastic Container Registry (ECR).
* Authenticate remote AWS CLI sessions and push application images to ECR.

### Detailed Weekly Action Items:
| Day | Activity Description | Start | End Date | Documentation |
| --- | --- | --- | --- | --- |
| Mon | Write a Dockerfile for the React frontend utilizing Nginx to serve static files. | 15/06/2026 | 15/06/2026 | [GitHub Repository](https://github.com/KENTksl/globalmart-production-cicd.git) |
| Tue | Draft a multi-stage Dockerfile for the Spring Boot backend jar service to minimize output size. | 16/06/2026 | 16/06/2026 | [GitHub Repository](https://github.com/KENTksl/globalmart-production-cicd.git) |
| Wed | Create remote container repositories for globalmart-frontend and globalmart-backend on Amazon ECR. | 17/06/2026 | 17/06/2026 | https://aws.amazon.com/ecr/ |
| Thu | Run Docker login commands via AWS CLI and push local images to remote ECR endpoints. | 18/06/2026 | 18/06/2026 | https://aws.amazon.com/ecr/ |
| Fri | Inspect pushed images and verify image tags in the Amazon ECR console. Week 9 review. | 19/06/2026 | 19/06/2026 | https://aws.amazon.com/ecr/ |

### Key Accomplishments & Deliverables - Week 9:

* Successfully built lightweight container images using optimized Dockerfiles.
* Established cloud storage paths on Amazon ECR.
* Pushed verified and tagged container builds to the cloud registry.
