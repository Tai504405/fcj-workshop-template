---
title: "Worklog Tuần 9"
date: 2026-06-15
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:

* Đóng gói ứng dụng thành các Docker image chuẩn hóa.
* Nghiên cứu cách tối ưu kích thước Dockerfile sử dụng Multi-stage build.
* Khởi tạo các kho chứa hình ảnh Docker tập trung trên Amazon ECR.
* Thực hiện đẩy thành công các Docker image Frontend/Backend lên đám mây AWS.

### Nhiệm vụ thực hiện chi tiết:
| Thứ tự | Nội dung công việc | Bắt đầu | Kết thúc | Tài liệu tham khảo |
| --- | --- | --- | --- | --- |
| 2 | Tìm hiểu về Docker, viết Dockerfile cho ứng dụng Frontend (React) đóng gói bằng Nginx. | 15/06/2026 | 15/06/2026 | Tài liệu Docker |
| 3 | Viết Dockerfile cho Backend (Spring Boot Java JAR), tối ưu hóa dung lượng file chạy. | 16/06/2026 | 16/06/2026 | Tài liệu Docker |
| 4 | Tạo các repository chứa ảnh `globalmart-frontend` và `globalmart-backend` trên Amazon ECR. | 17/06/2026 | 17/06/2026 | https://aws.amazon.com/ecr/ |
| 5 | Thực hiện đăng nhập và đẩy (push) các Docker image từ local lên kho chứa ECR. | 18/06/2026 | 18/06/2026 | https://aws.amazon.com/ecr/ |
| 6 | Kiểm tra tính đúng đắn của các image và tags trên giao diện console ECR. Tổng kết Tuần 9. | 19/06/2026 | 19/06/2026 | https://aws.amazon.com/ecr/ |

### Kết quả thu hoạch sau Tuần 9:

* Đóng gói thành công ứng dụng bằng Docker với kỹ thuật multi-stage build giúp giảm thiểu dung lượng image.
* Cấu hình thành công kho chứa ECR và phân quyền đẩy image từ xa.
* Toàn bộ image ứng dụng đã được lưu trữ bảo mật trên đám mây AWS ECR.
