---
title: "Worklog Tuần 9"
date: 2026-06-15
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu định hướng trong tuần 9:

* Đóng gói mã nguồn ứng dụng bằng công nghệ Docker container.
* Tối ưu hóa các tệp Dockerfile bằng kỹ thuật Multi-stage build nhằm giảm dung lượng hình ảnh.
* Khởi tạo kho lưu trữ Docker Image bảo mật trên Amazon ECR.
* Đăng nhập ECR từ xa và thực hiện đẩy (push) các image ứng dụng lên AWS.

### Nhiệm vụ cụ thể cần triển khai:
| Ngày | Nhiệm vụ chi tiết | Ngày bắt đầu | Ngày hoàn thành | Nguồn tham khảo |
| --- | --- | --- | --- | --- |
| Thứ 2 | Nghiên cứu Docker, viết Dockerfile cho Frontend (React) sử dụng máy chủ Nginx để tối ưu hóa tệp tĩnh. | 15/06/2026 | 15/06/2026 | [Mã nguồn GitHub](https://github.com/KENTksl/globalmart-production-cicd.git) |
| Thứ 3 | Viết Dockerfile cho Backend (Spring Boot Java), tối ưu hóa thời gian build và dung lượng tệp JAR thành phẩm. | 16/06/2026 | 16/06/2026 | [Mã nguồn GitHub](https://github.com/KENTksl/globalmart-production-cicd.git) |
| Thứ 4 | Khởi tạo các repository chứa ảnh `globalmart-frontend` và `globalmart-backend` trên Amazon Elastic Container Registry (ECR). | 17/06/2026 | 17/06/2026 | https://aws.amazon.com/ecr/ |
| Thứ 5 | Đăng nhập dịch vụ ECR bằng AWS CLI và thực hiện push các Docker image từ local lên ECR. | 18/06/2026 | 18/06/2026 | https://aws.amazon.com/ecr/ |
| Thứ 6 | Xác nhận các image đẩy lên đã xuất hiện an toàn trên bảng điều khiển AWS ECR Console. Tổng kết Tuần 9. | 19/06/2026 | 19/06/2026 | https://aws.amazon.com/ecr/ |

### Kết quả thu hoạch thực tế sau Tuần 9:

* Đóng gói thành công các image Docker siêu nhỏ gọn thông qua multi-stage build.
* Khởi tạo và cấu hình phân quyền đẩy code thành công lên Amazon ECR.
* Bảo mật và chuẩn hóa các phiên bản Docker image trên đám mây AWS.
