---
title: "Nhật ký Tuần 10"
date: 2026-06-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu định hướng trong tuần 10:

* Xây dựng cơ sở hạ tầng mạng ảo VPC an toàn cho dự án `GlobalMart` trên AWS.
* Cấu hình các subnet và bảng định tuyến (Route Table) đảm bảo định tuyến đúng hướng.
* Triển khai cơ sở dữ liệu Amazon RDS MySQL trong vùng mạng private an toàn tuyệt đối.
* Tạo lập cấu trúc bảng database trên RDS thông qua máy chủ EC2 trung gian (Bastion host).

### Nhiệm vụ cụ thể cần triển khai:
| Ngày | Nhiệm vụ chi tiết | Ngày bắt đầu | Ngày hoàn thành | Nguồn tham khảo |
| --- | --- | --- | --- | --- |
| Thứ 2 | Khởi tạo VPC mạng dự án (`globalmart-vpc`, CIDR `10.0.0.0/16`) và chia nhỏ các public/private subnet. | 22/06/2026 | 22/06/2026 | Mã nguồn dự án |
| Thứ 3 | Cấu hình Internet Gateway (IGW), NAT Gateway kết nối mạng và thiết lập Route Table cho từng subnet. | 23/06/2026 | 23/06/2026 | Mã nguồn dự án |
| Thứ 4 | Thiết lập các Security Group bảo mật: chặn mọi kết nối vào database ngoại trừ kết nối từ Backend. | 24/06/2026 | 24/06/2026 | Mã nguồn dự án |
| Thứ 5 | Khởi tạo cơ sở dữ liệu Amazon RDS MySQL (Single-AZ, `db.t3.micro`) đặt hoàn toàn ở private subnet B. | 25/06/2026 | 25/06/2026 | https://aws.amazon.com/rds/ |
| Thứ 6 | Khởi chạy một EC2 instance tạm thời để truy cập vào RDS MySQL, tiến hành khởi tạo cấu trúc bảng dữ liệu. Tổng kết Tuần 10. | 26/06/2026 | 26/06/2026 | Mã nguồn dự án |

### Kết quả thu hoạch thực tế sau Tuần 10:

* Xây dựng thành công hạ tầng mạng 3 lớp (3-tier) bảo mật cao cho dự án.
* Triển khai cơ sở dữ liệu quan hệ RDS MySQL cô lập hoàn toàn với internet.
* Kết nối và khởi tạo thành công schema dữ liệu trên đám mây RDS.
