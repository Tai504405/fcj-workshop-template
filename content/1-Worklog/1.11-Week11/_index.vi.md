---
title: "Nhật ký Tuần 11"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu định hướng trong tuần 11:

* Triển khai ứng dụng container hóa lên AWS ECS sử dụng kiểu serverless AWS Fargate.
* Cấu hình các bộ cân bằng tải Application Load Balancer (ALB) để điều hướng lưu lượng truy cập.
* Thiết lập Target Group kiểm tra trạng thái hoạt động (Health Check) của container.
* Tạo Task Definition định nghĩa tài nguyên và biến môi trường cho các container.

### Nhiệm vụ cụ thể cần triển khai:
| Ngày | Nhiệm vụ chi tiết | Ngày bắt đầu | Ngày hoàn thành | Nguồn tham khảo |
| --- | --- | --- | --- | --- |
| Thứ 2 | Khởi tạo cụm máy chủ ảo chạy container ECS Fargate Cluster (`globalmart-cluster`). | 29/06/2026 | 29/06/2026 | [Hướng dẫn Workshop](../../5-Workshop/) |
| Thứ 3 | Viết Task Definition cấu hình CPU, bộ nhớ RAM và cấu hình các biến môi trường kết nối database cho Backend/Frontend. | 30/06/2026 | 30/06/2026 | [Hướng dẫn Workshop](../../5-Workshop/) |
| Thứ 4 | Tạo bộ cân bằng tải Public ALB đính kèm vào mạng public cho Frontend và Internal ALB đính kèm vào mạng private cho Backend. | 01/07/2026 | 01/07/2026 | https://aws.amazon.com/elasticloadbalancing/ |
| Thứ 5 | Thiết lập Target Group và cấu hình endpoint HTTP Health Check kiểm tra trạng thái sống/chết của các container ứng dụng. | 02/07/2026 | 02/07/2026 | [Hướng dẫn Workshop](../../5-Workshop/) |
| Thứ 6 | Khởi chạy các ECS Service quản lý và duy trì hoạt động ổn định của các container Frontend/Backend. Tổng kết Tuần 11. | 03/07/2026 | 03/07/2026 | [Hướng dẫn Workshop](../../5-Workshop/) |

### Kết quả thu hoạch thực tế sau Tuần 11:

* Chạy thành công ứng dụng trên ECS Fargate serverless, giải phóng công việc quản trị OS.
* Phân phối tải lưu lượng mạng ổn định qua hệ thống Application Load Balancer.
* Toàn bộ các container tự động phục hồi nhờ cấu hình health check thông minh.
