---
title: "Nhật ký Tuần 2"
date: 2026-04-27
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---

### Mục tiêu định hướng trong tuần 2:

* Tìm hiểu các giải pháp tính toán (Compute) đa dạng trên AWS.
* Thực hành tạo lập và kết nối máy ảo EC2, gắn thêm không gian lưu trữ EBS.
* Cấu hình tự động co giãn số lượng máy chủ (Auto Scaling) và ổ đĩa dùng chung EFS.
* Thiết lập giám sát hạ tầng với CloudWatch và nghiên cứu dịch vụ chuyển đổi máy chủ AWS MGN.

### Nhiệm vụ cụ thể cần triển khai:
| Ngày | Nhiệm vụ chi tiết | Ngày bắt đầu | Ngày hoàn thành | Nguồn tham khảo |
| --- | --- | --- | --- | --- |
| Thứ 2 | Tìm hiểu Amazon EC2: cách chọn cấu hình máy ảo, tạo Key Pair bảo mật và gắn thêm ổ đĩa Amazon Elastic Block Store (EBS). | 27/04/2026 | 27/04/2026 | https://000004.awsstudygroup.com |
| Thứ 3 | Học cách thiết lập hệ thống tự động co giãn Auto Scaling Group để đáp ứng tải thay đổi và tạo ổ đĩa chia sẻ dùng chung Amazon EFS. | 28/04/2026 | 28/04/2026 | https://000004.awsstudygroup.com |
| Thứ 4 | Nghiên cứu dịch vụ Lightsail để chạy ứng dụng nhanh gọn. Học cách sử dụng CloudWatch để theo dõi tài nguyên hệ thống. | 29/04/2026 | 29/04/2026 | https://000006.awsstudygroup.com |
| Thứ 5 | Thực hành dựng hoàn chỉnh luồng ASG tự động tăng/giảm số lượng EC2 khi giả lập quá tải CPU, cấu hình cảnh báo CloudWatch Alarm. | 30/04/2026 | 30/04/2026 | https://000006.awsstudygroup.com |
| Thứ 6 | Nghiên cứu nguyên lý hoạt động của AWS Application Migration Service (MGN) phục vụ di chuyển hệ thống lên đám mây. Tổng kết Tuần 2. | 01/05/2026 | 01/05/2026 | https://aws.amazon.com/mgn/ |

### Kết quả thu hoạch thực tế sau Tuần 2:

* Khởi chạy thành công các instance EC2 và đính kèm thêm ổ đĩa EBS hoạt động bình thường.
* Thiết lập cấu hình Auto Scaling tự động co giãn linh hoạt dựa trên tải CPU thực tế.
* Tạo thành công Dashboard giám sát và Alarm gửi thông báo tự động khi CPU quá tải.
* Hiểu quy trình dịch chuyển máy chủ vật lý lên Cloud thông qua công cụ MGN.
