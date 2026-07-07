---
title: "Worklog Tuần 12"
date: 2026-07-06
weight: 12
chapter: false
pre: " <b> 1.12. </b> "
---

### Mục tiêu tuần 12:

* Cấu hình kết nối an toàn API Gateway kết hợp VPC Link.
* Thiết lập luồng CI/CD tự động hóa việc build và deploy bằng GitHub Actions.
* Triển khai sao lưu cơ sở dữ liệu định kỳ ra S3 và giám sát CloudWatch Logs.
* Hoàn thành toàn bộ tài liệu báo cáo thực tập.

### Nhiệm vụ thực hiện chi tiết:
| Thứ tự | Nội dung công việc | Bắt đầu | Kết thúc | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2 | Tạo API Gateway kết nối an toàn đến Backend private thông qua cấu hình VPC Link. | 06/07/2026 | 06/07/2026 | Mã nguồn dự án |
| 3 | Thiết lập GitHub Actions tự động hóa quy trình: Push code → Build image ECR → Redeploy ECS. | 07/07/2026 | 07/07/2026 | Tài liệu GitHub Actions |
| 4 | Cấu hình xuất tự động RDS Snapshot sang S3 Backup bucket để lưu trữ lâu dài. | 08/07/2026 | 08/07/2026 | https://aws.amazon.com/s3/ |
| 5 | Cài đặt CloudWatch Alarms giám sát hiệu năng, cấu hình SNS gửi cảnh báo qua Email/SMS. | 09/07/2026 | 09/07/2026 | https://aws.amazon.com/cloudwatch/ |
| 6 | Tổng kết toàn bộ hệ thống dự án, viết tài liệu và kiểm tra toàn bộ báo cáo thực tập. Kết thúc. | 10/07/2026 | 10/07/2026 | Báo cáo thực tập |

### Kết quả thu hoạch sau Tuần 12:

* Thiết lập thành công API Gateway làm cổng truy cập bảo mật duy nhất cho ứng dụng Backend.
* Tích hợp thành công quy trình CI/CD chuyên nghiệp với GitHub Actions.
* Hệ thống vận hành an toàn nhờ có cơ chế sao lưu tự động và cảnh báo tức thời khi có sự cố.
* Hoàn thành xuất sắc bài báo cáo thực tập cuối khóa.
