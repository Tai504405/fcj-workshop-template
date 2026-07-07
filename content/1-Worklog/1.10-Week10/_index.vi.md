---
title: "Worklog Tuần 10"
date: 2026-06-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

* Thiết lập mạng cơ bản và phân vùng mạng an toàn cho dự án `GlobalMart` trên AWS.
* Triển khai cơ sở dữ liệu quan hệ Amazon RDS MySQL vào private subnet an toàn.
* Cấu hình các Security Group lớp mạng chặt chẽ để cô lập database.
* Khởi tạo dữ liệu mẫu và kiểm thử kết nối mạng từ máy EC2 trung gian đến RDS.

### Nhiệm vụ thực hiện chi tiết:
| Thứ tự | Nội dung công việc | Bắt đầu | Kết thúc | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2 | Tạo VPC mạng dự án (`globalmart-vpc`, CIDR `10.0.0.0/16`) cùng các subnet (public/private). | 22/06/2026 | 22/06/2026 | Mã nguồn dự án |
| 3 | Thiết lập Route Table, Internet Gateway kết nối mạng bên ngoài và NAT Gateway cho mạng nội bộ. | 23/06/2026 | 23/06/2026 | Mã nguồn dự án |
| 4 | Tạo các Security Group phân lớp bảo mật cho ứng dụng (Frontend, Backend, Load Balancer, Database). | 24/06/2026 | 24/06/2026 | Mã nguồn dự án |
| 5 | Khởi tạo database RDS MySQL (Single-AZ, `db.t3.micro`) đặt hoàn toàn trong private subnet B. | 25/06/2026 | 25/06/2026 | https://aws.amazon.com/rds/ |
| 6 | Triển khai một máy chủ EC2 tạm thời để thiết lập cấu trúc bảng database cho RDS MySQL. Tổng kết Tuần 10. | 26/06/2026 | 26/06/2026 | Mã nguồn dự án |

### Kết quả thu hoạch sau Tuần 10:

* Thiết lập thành công mạng VPC phân tách 3 lớp bảo mật riêng biệt.
* Khởi chạy thành công cơ sở dữ liệu RDS MySQL riêng tư không công khai ra ngoài internet.
* Hoàn thành kết nối an toàn từ EC2 trung gian để chuẩn bị cơ sở dữ liệu cho dự án.
