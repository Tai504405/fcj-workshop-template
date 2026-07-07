---
title: "Nhật ký Tuần 8"
date: 2026-06-08
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu định hướng trong tuần 8:

* Khảo sát và phân tích yêu cầu nghiệp vụ hệ thống của dự án `GlobalMart`.
* Thiết kế bản vẽ kiến trúc hạ tầng và sơ đồ luồng dữ liệu của dự án.
* Khởi tạo cấu trúc source code Frontend (React) và Backend (Spring Boot).
* Thiết lập cơ sở dữ liệu MySQL local để phục vụ lập trình và kiểm nghiệm ban đầu.

### Nhiệm vụ cụ thể cần triển khai:
| Ngày | Nhiệm vụ chi tiết | Ngày bắt đầu | Ngày hoàn thành | Nguồn tham khảo |
| --- | --- | --- | --- | --- |
| Thứ 2 | Đọc kỹ tài liệu yêu cầu, phân tích các tính năng của ứng dụng thương mại điện tử `GlobalMart`. | 08/06/2026 | 08/06/2026 | [Tài liệu Đặc tả](../../2-Proposal/) |
| Thứ 3 | Vẽ sơ đồ kiến trúc 3 lớp (3-tier) bảo mật và có khả năng phục hồi cao, tối ưu chi phí trên đám mây AWS. | 09/06/2026 | 09/06/2026 | https://aws.amazon.com/vi/solutions/ |
| Thứ 4 | Khởi tạo mã nguồn dự án: viết code giao diện React SPA và thiết lập khung REST API Spring Boot. | 10/06/2026 | 10/06/2026 | [Mã nguồn GitHub](https://github.com/KENTksl/globalmart-production-cicd.git) |
| Thứ 5 | Cài đặt và thiết lập cơ sở dữ liệu MySQL local dưới máy phát triển cá nhân, cấu hình kết nối ứng dụng. | 11/06/2026 | 11/06/2026 | [Mã nguồn GitHub](https://github.com/KENTksl/globalmart-production-cicd.git) |
| Thứ 6 | Kiểm thử luồng trao đổi dữ liệu toàn cục giữa client và API cục bộ. Tổng kết Tuần 8. | 12/06/2026 | 12/06/2026 | [Mã nguồn GitHub](https://github.com/KENTksl/globalmart-production-cicd.git) |

### Kết quả thu hoạch thực tế sau Tuần 8:

* Hoàn thiện bản vẽ thiết kế kiến trúc hệ thống 3 lớp cho dự án GlobalMart.
* Tạo lập khung source code sạch sẽ, chạy kiểm thử kết nối local thành công ổn định.
* Định nghĩa đầy đủ danh sách các API endpoints giao tiếp giữa Frontend và Backend.
