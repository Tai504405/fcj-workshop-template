---
title: "Worklog Tuần 3"
date: 2026-05-04
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---

### Mục tiêu tuần 3:

* Tìm hiểu sâu về hệ thống mạng AWS Networking (VPC, subnet, routing).
* Phân biệt cơ chế bảo mật mạng giữa Security Group và Network ACL (NACL).
* Nghiên cứu các giải pháp liên kết mạng VPC Peering, Transit Gateway và định tuyến Route 53.
* Thực hành kết nối an toàn không cần Key Pair qua AWS Systems Manager Session Manager.

### Nhiệm vụ thực hiện chi tiết:
| Thứ tự | Nội dung công việc | Bắt đầu | Kết thúc | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2 | Học về VPC, cách chia nhỏ subnet (public/private), Route Table, Internet Gateway (IGW) và NAT Gateway. | 04/05/2026 | 04/05/2026 | https://000003.awsstudygroup.com |
| 3 | Phân tích Security Group (stateful) vs NACL (stateless). Tìm hiểu VPC Flow Logs để kiểm tra lưu lượng mạng. | 05/05/2026 | 05/05/2026 | https://000003.awsstudygroup.com |
| 4 | Nghiên cứu Elastic Load Balancing (ALB/NLB), Route 53 và các chính sách định tuyến tên miền. | 06/05/2026 | 06/05/2026 | https://000010.awsstudygroup.com |
| 5 | Thực hành cấu hình VPC Peering và Transit Gateway kết nối đa mạng độc lập. | 07/05/2026 | 07/05/2026 | https://000019.awsstudygroup.com <br> https://000020.awsstudygroup.com |
| 6 | Thực hành kết nối máy chủ private qua AWS Systems Manager Session Manager. Tổng kết tuần 3. | 08/05/2026 | 08/05/2026 | https://000058.awsstudygroup.com |

### Kết quả thu hoạch sau Tuần 3:

* Xây dựng thành công hạ tầng mạng VPC hoàn chỉnh với thiết kế phân tách public/private subnet.
* Nắm rõ cách cấu hình phân quyền truy cập cổng mạng bằng SG và NACL.
* Cấu hình định tuyến tên miền trên Route 53 và thiết lập liên kết VPC Peering.
* Truy cập thành công máy chủ nội bộ an toàn qua Session Manager mà không cần mở cổng 22 (SSH).
