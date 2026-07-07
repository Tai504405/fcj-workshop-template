---
title: "Nhật ký Tuần 3"
date: 2026-05-04
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu định hướng trong tuần 3:

* Nghiên cứu chuyên sâu về kiến trúc mạng và định tuyến trên AWS (VPC, Subnet, Route Table).
* Phân tích cơ chế bảo mật cổng mạng qua Security Group và Network ACL (NACL).
* Tìm hiểu các phương thức liên kết mạng như VPC Peering, Transit Gateway và hệ thống Route 53.
* Thực hành kết nối đầu cuối an toàn không cần qua internet bằng AWS Systems Manager Session Manager.

### Nhiệm vụ cụ thể cần triển khai:
| Ngày | Nhiệm vụ chi tiết | Ngày bắt đầu | Ngày hoàn thành | Nguồn tham khảo |
| --- | --- | --- | --- | --- |
| Thứ 2 | Học cách thiết lập mạng ảo VPC, thiết kế dải mạng cho public/private subnet, cấu hình Route Table, IGW và NAT Gateway. | 04/05/2026 | 04/05/2026 | https://000003.awsstudygroup.com |
| Thứ 3 | So sánh Security Group (bảo mật cấp máy chủ) vs NACL (bảo mật cấp subnet). Sử dụng VPC Flow Logs kiểm tra lịch sử truy cập mạng. | 05/05/2026 | 05/05/2026 | https://000003.awsstudygroup.com |
| Thứ 4 | Học cách sử dụng Load Balancer (ALB/NLB) phân phối lưu lượng và Route 53 cấu hình định tuyến tên miền. | 06/05/2026 | 06/05/2026 | https://000010.awsstudygroup.com |
| Thứ 5 | Thực hành cấu hình VPC Peering và Transit Gateway để liên kết các mạng nội bộ độc lập. | 07/05/2026 | 07/05/2026 | https://000019.awsstudygroup.com <br> https://000020.awsstudygroup.com |
| Thứ 6 | Sử dụng Systems Manager Session Manager kết nối terminal vào EC2 nằm trong private subnet mà không cần mở cổng 22. Tổng kết Tuần 3. | 08/05/2026 | 08/05/2026 | https://000058.awsstudygroup.com |

### Kết quả thu hoạch thực tế sau Tuần 3:

* Tự xây dựng thành công môi trường mạng VPC cô lập và bảo mật tốt.
* Nắm vững nguyên lý hoạt động của bộ lọc cổng mạng Security Group và NACL.
* Cấu hình kết nối an toàn giữa các VPC khác nhau bằng Peering và điều hướng Route 53.
* Truy cập vào shell máy chủ an toàn thông qua Session Manager để quản lý hệ thống.
