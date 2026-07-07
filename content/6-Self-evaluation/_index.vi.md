---
title: "Tự đánh giá"
date: 2024-01-01
weight: 6
chapter: false
pre: " <b> 6. </b> "
---

Trải qua chặng đường thực tập đầy thử thách tại **First Cloud AI Journey (FCAJ)**, bản thân tôi đã gặt hái được rất nhiều bài học thực tiễn giá trị. Chương trình không chỉ dừng lại ở việc cung cấp lý thuyết nền tảng về hạ tầng đám mây AWS mà còn thúc đẩy tôi dấn thân vào các dự án giả lập thực tế, học cách tự tìm tòi tài liệu kỹ thuật, chuẩn bị dự án cuối khóa `GlobalMart` và liên tục tối ưu hóa hệ thống.

Nhìn lại 12 tuần vừa qua, tôi nhận thấy mình đã có những bước tiến rõ rệt về mặt kỹ thuật lẫn tư duy giải quyết vấn đề. Dưới đây là bảng tự nhìn nhận và đánh giá năng lực cá nhân một cách khách quan nhất:

| STT | Tiêu chí | Mô tả tiêu chuẩn | Tốt | Khá | Trung bình |
| :--- | :--- | :--- | :---: | :---: | :---: |
| 1 | **Kiến thức và kỹ năng chuyên môn** | Nắm bắt cấu trúc AWS, triển khai hệ thống thực tế, chất lượng sản phẩm | ☐ | ☐ | ✅ |
| 2 | **Khả năng học hỏi** | Tiếp thu công nghệ mới (Docker, CI/CD, ECS, API Gateway) | ☐ | ✅ | ☐ |
| 3 | **Chủ động** | Tự giác nghiên cứu tài liệu, debug lỗi hệ thống trước khi hỏi mentor | ☐ | ☐ | ✅ |
| 4 | **Tinh thần trách nhiệm** | Đảm bảo tiến độ công việc và hoàn thành báo cáo worklog đúng hạn | ✅ | ☐ | ☐ |
| 5 | **Kỷ luật** | Tuân thủ tuyệt đối quy định giờ giấc, quy trình bảo mật tài khoản lab | ✅ | ☐ | ☐ |
| 6 | **Tính cầu tiến** | Tiếp thu ý kiến đóng góp từ mentor để cải thiện cấu trúc dự án | ☐ | ✅ | ☐ |
| 7 | **Giao tiếp** | Diễn đạt ý kiến cá nhân, giải trình lỗi kỹ thuật khi làm việc nhóm | ☐ | ✅ | ☐ |
| 8 | **Hợp tác nhóm** | Phối hợp phân chia module frontend/backend, hỗ trợ đồng đội sửa lỗi | ☐ | ✅ | ☐ |
| 9 | **Ứng xử chuyên nghiệp** | Tác phong chuẩn mực, tôn trọng tập thể và các quy tắc cộng đồng | ✅ | ☐ | ☐ |
| 10 | **Tư duy giải quyết vấn đề** | Phân tích log lỗi CloudWatch, giải quyết lỗi CORS, tối ưu hóa VPC Link | ☐ | ☐ | ✅ |
| 11 | **Đóng góp vào dự án/tổ chức** | Đóng góp giải pháp xây dựng pipeline CI/CD tự động cho GlobalMart | ☐ | ☐ | ✅ |
| 12 | **Tổng thể** | Đánh giá chung về toàn bộ nỗ lực trong suốt kỳ thực tập | ☐ | ☐ | ✅ |

### Điểm cần cải thiện và định hướng phát triển

Dù đã đạt được một số kết quả nhất định, tôi hiểu rằng bản thân vẫn còn những thiếu sót cần khắc phục trong thời gian tới:
- **Tối ưu hóa khả năng debug độc lập:** Đôi khi gặp các lỗi phức tạp liên quan đến kết nối mạng VPC hoặc định tuyến tải (Route Tables, NAT Gateway), tôi vẫn mất khá nhiều thời gian để cô lập lỗi. Tôi cần cải thiện kỹ năng đọc và phân tích log hệ thống sâu hơn.
- **Kỹ năng thuyết trình giải pháp kỹ thuật:** Khi cần giải trình về kiến trúc hệ thống hoặc lý giải tại sao chọn VPC Link thay vì HTTP Integration thông thường, tôi cần rèn luyện cách nói gãy gọn, tập trung vào trọng tâm kỹ thuật để thuyết phục người nghe hiệu quả hơn.
- **Nâng cao kiến thức bảo mật đám mây:** Cần nghiên cứu sâu hơn về cách áp dụng IAM Policy phân quyền chi tiết (Least Privilege) thay vì các quyền quá rộng, cũng như cấu hình WAF và KMS bảo mật dữ liệu ở mức cao hơn.
- **Kỹ năng quản lý tài nguyên:** Cần chú ý hơn đến việc dọn dẹp các tài nguyên không sử dụng trên AWS (như EBS volumes dư thừa, NAT Gateway nhàn rỗi) để tránh phát sinh chi phí ngoài ý muốn trong môi trường lab doanh nghiệp.
