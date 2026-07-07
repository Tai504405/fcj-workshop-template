---
title: "Worklog Tuần 5"
date: 2026-05-18
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu định hướng trong tuần 5:

* Nắm vững lý thuyết về bảo mật và quản lý định danh nâng cao (SSO, Cognito).
* Tìm hiểu cách thiết lập cấu trúc phân cấp doanh nghiệp qua AWS Organizations.
* Học cách khởi tạo khóa mã hóa KMS bảo mật tệp và đĩa cứng.
* Giám sát tình trạng tuân thủ bảo mật thông qua AWS Security Hub.

### Nhiệm vụ cụ thể cần triển khai:
| Ngày | Nhiệm vụ chi tiết | Ngày bắt đầu | Ngày hoàn thành | Nguồn tham khảo |
| --- | --- | --- | --- | --- |
| Thứ 2 | Tìm hiểu mô hình trách nhiệm bảo mật chung (Shared Responsibility Model) và hệ thống quản trị định danh đăng nhập Amazon Cognito. | 18/05/2026 | 18/05/2026 | https://000009.awsstudygroup.com |
| Thứ 3 | Nghiên cứu quản trị đa tài khoản bằng AWS Organizations (tạo OU, áp dụng SCP) và dịch vụ AWS IAM Identity Center (SSO). | 19/05/2026 | 19/05/2026 | https://000009.awsstudygroup.com |
| Thứ 4 | Học cách tạo và quản lý khóa mật mã tĩnh AWS KMS và kiểm tra lỗi an toàn hệ thống bằng AWS Security Hub. | 20/05/2026 | 20/05/2026 | https://000009.awsstudygroup.com |
| Thứ 5 | Thực hành cấu hình tài khoản AWS Identity Center để truy cập SSO vào các môi trường, khởi tạo khóa KMS tự quản lý. | 21/05/2026 | 21/05/2026 | https://000009.awsstudygroup.com |
| Thứ 6 | Xây dựng các tiêu chuẩn đặt thẻ định danh (Tagging policy) phục vụ quản lý và phân tích chi phí. Tổng kết Tuần 5. | 22/05/2026 | 22/05/2026 | https://aws.amazon.com/kms/ |

### Kết quả thu hoạch thực tế sau Tuần 5:

* Cấu hình thành công cổng SSO cho phép truy cập tài khoản an toàn qua cổng tập trung.
* Mã hóa thành công dữ liệu lưu trữ trên EBS và S3 bằng khóa KMS tự quản lý.
* Hiểu rõ quy trình phân tích và vá lỗi an ninh do Security Hub cảnh báo.
