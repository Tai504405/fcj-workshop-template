---
title: "Nhật ký công việc"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1. </b> "
---

Trang này tổng hợp nhật ký làm việc (worklog) qua 12 tuần thực tập, trải qua lộ trình từ trang bị kiến thức cơ bản về AWS Cloud cho đến bước hoạch định, thiết kế và phát triển hoàn chỉnh dự án `GlobalMart` trên AWS.

Tóm tắt các nhiệm vụ theo từng tuần:

- **Tuần 1:** [Tìm hiểu AWS & các dịch vụ cốt lõi](1.1-week1/) - Tiếp cận kiến thức điện toán đám mây căn bản, làm quen các dịch vụ nền tảng của AWS, cơ chế quản lý định danh IAM, công cụ Budgets giám sát chi phí và Well-Architected Framework.

- **Tuần 2:** [Hệ thống mạng AWS & thực hành Lab Networking](1.2-week2/) - Nghiên cứu sâu về VPC, subnet, bảng định tuyến, security group, NACL, các giải pháp hybrid network và cân bằng tải. Hoàn thành bài thực hành Route 53, VPC Peering, Transit Gateway và AWS Systems Manager.

- **Tuần 3:** [Dịch vụ tính toán Compute & triển khai hạ tầng](1.3-week3/) - Tìm hiểu Amazon EC2, dịch vụ lưu trữ EBS/EFS, cấu hình tự động mở rộng Auto Scaling, Amazon Lightsail, CloudWatch giám sát hệ thống và dịch vụ chuyển đổi AWS MGN.

- **Tuần 4:** [Lưu trữ dữ liệu Storage, Backup & Disaster Recovery](1.4-week4/) - Nghiên cứu Amazon S3, giải pháp Snow Family, Storage Gateway cùng các phương án sao lưu, phục hồi dữ liệu. Luyện tập thực hành cấu hình AWS Backup, VM Import/Export và File Storage Gateway.

- **Tuần 5:** [An ninh bảo mật Security, IAM & Identity Management](1.5-week5/) - Nắm vững mô hình trách nhiệm chung (Shared Responsibility), quản trị tài khoản qua Cognito, AWS Organizations, Identity Center, KMS mã hóa dữ liệu và Security Hub.

- **Tuần 6:** [Cơ sở dữ liệu Database & dịch vụ dữ liệu trên Cloud](1.6-week6/) - Củng cố nền tảng database, học cách vận hành Amazon RDS, Aurora, Redshift, ElastiCache và sử dụng công cụ di chuyển dữ liệu DMS, SCT.

- **Tuần 7:** [Phân tích Analytics, Data Lake & trực quan hóa dữ liệu](1.7-week7/) - Tìm hiểu Amazon DynamoDB, AWS Glue tích hợp dữ liệu, Athena truy vấn serverless và QuickSight dựng biểu đồ báo cáo.

- **Tuần 8:** [Khảo sát yêu cầu & thiết kế kiến trúc hệ thống](1.8-week8/) - Phân tích bài toán, phác thảo sơ đồ kiến trúc ứng dụng `GlobalMart` tích hợp luồng CI/CD, Containerization trên ECS Fargate, cơ sở dữ liệu RDS và cơ chế giám sát.

- **Tuần 9:** [Khởi tạo & phát triển mã nguồn GlobalMart](1.9-week9/) - Khởi tạo mã nguồn cho Frontend (React) và Backend (Spring Boot), triển khai luồng xử lý API, kết nối database và chuẩn bị môi trường CI/CD cục bộ.

- **Tuần 10:** [Triển khai hạ tầng GlobalMart lên Cloud AWS](1.10-week10/) - Xây dựng hệ thống tài nguyên mạng (VPC, Subnet, SG) và tài nguyên tính toán bao gồm ECR, RDS, ALB, cấu hình Target Group, ECS Cluster, Task Definition và khởi chạy ECS Services.

- **Tuần 11:** [Cấu hình liên kết, CI/CD tự động, Backup & Giám sát](1.11-week11/) - Thiết lập API Gateway tích hợp VPC Link cho kết nối nội bộ an toàn, xây dựng pipeline CI/CD với GitHub Actions, cấu hình tự động backup dữ liệu lên S3, và cài đặt giám sát CloudWatch kết hợp cảnh báo qua SNS.

- **Tuần 12:** [Tổng hợp kết quả & hoàn thiện báo cáo thực tập](1.12-week12/) - Tổng kết toàn bộ quá trình thực tập, rà soát lại các mốc công việc và hoàn tất tài liệu báo cáo cuối kỳ.
