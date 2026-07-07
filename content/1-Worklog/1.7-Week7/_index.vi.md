---
title: "Worklog Tuần 7"
date: 2026-06-01
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---

### Mục tiêu định hướng trong tuần 7:

* Tìm hiểu các giải pháp lưu trữ tích hợp và di chuyển dữ liệu dung lượng lớn (Storage Gateway, Snow Family).
* Học cách kết nối máy ảo và di chuyển máy chủ vật lý bằng công cụ VM Import/Export.
* Thực hành giải pháp chia sẻ file cầu nối File Storage Gateway kết nối lưu trữ On-Premises lên AWS S3.
* Lập kịch bản khôi phục và phục hồi dữ liệu thảm họa (Disaster Recovery) bảo đảm an toàn hệ thống.

### Nhiệm vụ cụ thể cần triển khai:
| Ngày | Nhiệm vụ chi tiết | Ngày bắt đầu | Ngày hoàn thành | Nguồn tham khảo |
| --- | --- | --- | --- | --- |
| Thứ 2 | Nghiên cứu gia đình thiết bị di chuyển dữ liệu vật lý AWS Snow Family (Snowcone, Snowball Edge). | 01/06/2026 | 01/06/2026 | https://000005.awsstudygroup.com |
| Thứ 3 | Tìm hiểu các loại cổng kết nối dữ liệu của AWS Storage Gateway: File/Volume/Tape Gateway. | 02/06/2026 | 02/06/2026 | https://000005.awsstudygroup.com |
| Thứ 4 | Học cách sử dụng công cụ VM Import/Export để chuyển các file ảnh đĩa máy ảo thành các máy ảo EC2 hoạt động trên đám mây. | 03/06/2026 | 03/06/2026 | https://aws.amazon.com/ec2/vm-import/ |
| Thứ 5 | Thực hành cấu hình dịch vụ File Storage Gateway tạo cầu nối lưu trữ NFS/SMB đồng bộ lên S3. | 04/06/2026 | 04/06/2026 | https://000005.awsstudygroup.com |
| Thứ 6 | Luyện tập lập kịch bản diễn tập sao lưu dữ liệu, khôi phục từ bản lưu trữ dự phòng cũ để kiểm chứng. Tổng kết Tuần 7. | 05/06/2026 | 05/06/2026 | https://000005.awsstudygroup.com |

### Kết quả thu hoạch thực tế sau Tuần 7:

* Hiểu rõ phương án vận chuyển hàng chục Terabyte dữ liệu không dùng đường truyền internet bằng thiết bị Snowball.
* Thiết lập thành công cầu nối File Gateway liên kết ổ đĩa mạng nội bộ lên S3.
* Nắm vững các phương pháp khôi phục hạ tầng nhanh khi xảy ra thảm họa hệ thống mạng.
