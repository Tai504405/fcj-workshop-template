---
title: "Nhật ký công việc"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1. </b> "
---

Trang này tổng hợp nhật ký làm việc (worklog) qua 12 tuần thực tập, trải qua lộ trình từ trang bị kiến thức cơ bản về AWS Cloud cho đến bước hoạch định, thiết kế và phát triển hoàn chỉnh dự án `GlobalMart` trên AWS.

Tóm tắt các nhiệm vụ theo từng tuần:

- **Tuần 1:** [Tổng quan Cloud, AWS Fundamentals & Bảo mật cơ bản](1.1-week1/) - Tiếp cận kiến thức điện toán đám mây căn bản, tạo tài khoản Free Tier, bật MFA, quản lý chi phí AWS Budgets và Well-Architected Framework.

- **Tuần 2:** [Dịch vụ Tính toán Compute & Giám sát cơ bản](1.2-week2/) - Tìm hiểu Amazon EC2, dịch vụ lưu trữ EBS/EFS, cấu hình Auto Scaling, Amazon Lightsail, CloudWatch giám sát hệ thống và dịch vụ chuyển đổi AWS MGN.

- **Tuần 3:** [Hệ thống mạng AWS & Liên kết mạng nâng cao](1.3-week3/) - Nghiên cứu sâu về VPC, subnet, bảng định tuyến, security group, NACL, IGW/NAT Gateway, Route 53, VPC Peering, Transit Gateway và Session Manager.

- **Tuần 4:** [Lưu trữ Cloud & Cơ sở dữ liệu RDS](1.4-week4/) - Thao tác với Amazon S3, cơ sở dữ liệu Amazon RDS MySQL, kiến trúc Amazon Aurora và quản lý sao lưu với AWS Backup.

- **Tuần 5:** [Quản lý an ninh, Định danh & Quản trị tài khoản](1.5-week5/) - Nắm vững cơ chế xác thực với Amazon Cognito, AWS Organizations, IAM Identity Center (SSO), khóa mã hóa KMS và Security Hub.

- **Tuần 6:** [Phân tích Dữ liệu, Data Lake & Caching](1.6-week6/) - Tìm hiểu DynamoDB, Redshift, ElastiCache, AWS Glue (ETL), Athena truy vấn serverless, QuickSight trực quan hóa và các công cụ di chuyển dữ liệu DMS, SCT.

- **Tuần 7:** [Lưu trữ Hybrid, Di trú & Khôi phục sau thảm họa](1.7-week7/) - Nghiên cứu AWS Storage Gateway, thiết bị di chuyển Snow Family, VM Import/Export và giả lập khôi phục dữ liệu thảm họa.

- **Tuần 8:** [Khảo sát yêu cầu, Thiết kế kiến trúc & Phát triển local](1.8-week8/) - Phân tích nghiệp vụ, phác thảo kiến trúc 3 lớp cho dự án `GlobalMart`, khởi tạo mã nguồn React và Spring Boot chạy thử local.

- **Tuần 9:** [Hoàn thiện code ứng dụng, Dockerize & Đẩy lên ECR](1.9-week9/) - Đóng gói ứng dụng bằng Docker với multi-stage build, tạo kho chứa Amazon ECR và đẩy các Docker image lên ECR.

- **Tuần 10:** [Triển khai hạ tầng mạng dự án & Database](1.10-week10/) - Xây dựng hệ thống mạng VPC phân lớp bảo mật cho GlobalMart và triển khai database RDS MySQL trong private subnet B.

- **Tuần 11:** [Triển khai Container và Load Balancing](1.11-week11/) - Khởi chạy cụm ECS Cluster Fargate, viết Task Definitions, cấu hình bộ cân bằng tải ALB public/internal và khởi chạy ECS Services.

- **Tuần 12:** [Cấu hình API Gateway, CI/CD tự động, Backup/Monitoring & Hoàn thiện báo cáo](1.12-week12/) - Thiết lập API Gateway + VPC Link, xây dựng pipeline CI/CD với GitHub Actions, cấu hình tự động backup RDS lên S3, giám sát CloudWatch Logs, SNS và viết báo cáo.
