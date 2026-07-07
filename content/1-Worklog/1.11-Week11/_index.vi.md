---
title: "Worklog Tuần 11"
date: 2026-06-29
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu tuần 11:

* Triển khai nền tảng container hóa trên đám mây AWS ECS sử dụng AWS Fargate.
* Cấu hình các bộ cân bằng tải Application Load Balancer (ALB) cho dịch vụ.
* Thiết lập Target Group và Task Definition chạy các tác vụ Frontend/Backend.
* Kiểm tra tính sẵn sàng của hệ thống container và cấu hình định tuyến lưu lượng.

### Nhiệm vụ thực hiện chi tiết:
| Thứ tự | Nội dung công việc | Bắt đầu | Kết thúc | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2 | Khởi tạo cụm máy chủ container ECS Cluster (`globalmart-cluster`) chạy kiểu Fargate. | 29/06/2026 | 29/06/2026 | Mã nguồn dự án |
| 3 | Tạo Task Definition định nghĩa tham số tài nguyên CPU, RAM và port container cho Frontend/Backend. | 30/06/2026 | 30/06/2026 | Mã nguồn dự án |
| 4 | Khởi tạo Application Load Balancer công khai (Public ALB) cho Frontend và ALB nội bộ (Internal ALB) cho Backend. | 01/07/2026 | 01/07/2026 | https://aws.amazon.com/elasticloadbalancing/ |
| 5 | Tạo Target Group cấu hình HTTP Health Check tương ứng để đảm bảo trạng thái hoạt động tốt của container. | 02/07/2026 | 02/07/2026 | Mã nguồn dự án |
| 6 | Khởi chạy ECS Service để giám sát duy trì số lượng container Frontend và Backend ổn định. Tổng kết Tuần 11. | 03/07/2026 | 03/07/2026 | Mã nguồn dự án |

### Kết quả thu hoạch sau Tuần 11:

* Triển khai thành công ứng dụng trên ECS Fargate serverless giúp giảm gánh nặng quản lý máy chủ.
* Cấu hình thành công ALB phân phối tải thông minh đến các Task chạy ngầm.
* Ứng dụng chạy ổn định và tự động kiểm tra trạng thái sức khỏe định kỳ thông qua health check.
