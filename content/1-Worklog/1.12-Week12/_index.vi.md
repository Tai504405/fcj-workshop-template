---
title: "Nhật ký Tuần 12"
date: 2026-07-06
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---

### Mục tiêu định hướng trong tuần 12:

* Tạo kết nối an toàn cho Frontend gọi Backend private bằng API Gateway kết hợp VPC Link.
* Xây dựng pipeline CI/CD tự động build, push image và deploy thông qua GitHub Actions.
* Triển khai kế hoạch tự động sao lưu dữ liệu RDS ra S3 và giám sát hệ thống.
* Hoàn thành toàn bộ nội dung và rà soát báo cáo thực tập.

### Nhiệm vụ cụ thể cần triển khai:
| Ngày | Nhiệm vụ chi tiết | Ngày bắt đầu | Ngày hoàn thành | Nguồn tham khảo |
| --- | --- | --- | --- | --- |
| Thứ 2 | Thiết lập API Gateway tích hợp VPC Link liên kết trực tiếp với Internal ALB để gọi Backend an toàn. | 06/07/2026 | 06/07/2026 | [Hướng dẫn Workshop](../../5-Workshop/) |
| Thứ 3 | Xây dựng tệp workflow GitHub Actions tự động hóa: Code push → login ECR → build image → deploy ECS Service. | 07/07/2026 | 07/07/2026 | [Tài liệu CI/CD](../../5-Workshop/) |
| Thứ 4 | Cấu hình sao lưu RDS Snapshot tự động định kỳ, thiết lập xuất tệp backup lưu trữ lâu dài trên S3 Bucket. | 08/07/2026 | 08/07/2026 | https://aws.amazon.com/s3/ |
| Thứ 5 | Tạo các CloudWatch Alarms giám sát quá tải và liên kết SNS tự động gửi cảnh báo về email cá nhân. | 09/07/2026 | 09/07/2026 | https://aws.amazon.com/cloudwatch/ |
| Thứ 6 | Kiểm định hoạt động toàn hệ thống dự án, viết tài liệu và kiểm tra toàn bộ báo cáo thực tập. Kết thúc thực tập. | 10/07/2026 | 10/07/2026 | [Trang chủ Báo cáo](../../) |

### Kết quả thu hoạch thực tế sau Tuần 12:

* Bảo vệ cổng kết nối API Backend thông qua API Gateway kết hợp VPC Link.
* Tích hợp luồng CI/CD tự động hóa hoàn toàn quy trình đóng gói và triển khai ứng dụng.
* Dữ liệu được bảo vệ an toàn nhờ có cơ chế sao lưu tự động và cảnh báo tức thời từ CloudWatch.
* Hoàn thành xuất sắc toàn bộ nội dung báo cáo thực tập cuối khóa.
