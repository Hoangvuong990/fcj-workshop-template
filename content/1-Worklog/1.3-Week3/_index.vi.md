---
title: "Worklog Tuần 3"
date: 2026-05-04
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---
### Mục tiêu tuần 3:

* Tìm hiểu hệ thống AWS Support, quy trình khởi tạo case hỗ trợ và các cấp độ nghiêm trọng của sự cố.
* Nắm vững kiến thức căn bản về mạng trên AWS (Amazon VPC, Subnet, cơ chế bảo mật NACL & Security Group).
* Hiểu các giải pháp kết nối hybrid (VPN, AWS Direct Connect) và hoạt động của bộ cân bằng tải Elastic Load Balancing (ELB).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | **Khái quát về AWS Support & Các loại yêu cầu hỗ trợ (Support Cases)** <br> - Tìm hiểu tổng quan quy trình truy cập AWS Support và phân biệt các loại case: Hỗ trợ Tài khoản & Thanh toán (cho mọi người dùng), Mở rộng giới hạn dịch vụ (tăng quota tài nguyên), và Hỗ trợ kỹ thuật. <br> - Phân tích cơ chế liên lạc Hỗ trợ kỹ thuật: gói Developer (qua email/web), gói Business/Enterprise (qua điện thoại/chat). Lưu ý gói Basic không hỗ trợ tạo case kỹ thuật. | 04/05/2026 | 04/05/2026 | <https://docs.aws.amazon.com/awssupport/> |
| 3 | **Khởi tạo và quản lý Yêu cầu hỗ trợ (Support Case)** <br> - Thực hành các bước thực tế tạo case hỗ trợ kích hoạt tài khoản thủ công: truy cập Support console, chọn **Create case** -> **Account and billing support** (Type: Account, Category: Activation). <br> - Viết tiêu đề (Subject) và mô tả (Description) chi tiết lỗi kèm file ảnh đính kèm (Attachments). Chọn phương thức liên hệ Chat trực tuyến và gửi yêu cầu (**Submit**). | 05/05/2026 | 05/05/2026 | <https://docs.aws.amazon.com/awssupport/> |
| 4 | **Lựa chọn Mức độ nghiêm trọng (Severity) & Thời gian phản hồi** <br> - Nghiên cứu định nghĩa các mức độ nghiêm trọng và thời gian phản hồi: General guidance (< 24h), System impaired (< 12h), Production system impaired (< 4h - từ gói Business), Production system down (< 1h - từ gói Business), Business-critical system down (< 15p - gói Enterprise). <br> - Tìm hiểu quy định thời gian phản hồi của gói Developer (chỉ tính trong giờ hành chính 8h-18h ngày thường). | 06/05/2026 | 06/05/2026 | <https://docs.aws.amazon.com/awssupport/> |
| 5 | **Amazon VPC & Cơ chế bảo mật mạng trên AWS** <br> - **VPC căn bản**: Tìm hiểu dải IP (CIDR), giới hạn mặc định (5 VPC/Region), mục đích phân tách các môi trường (Dev/Test/Prod). <br> - **Bảo mật mạng**: Phân biệt tường lửa ảo Security Group (stateful, chỉ cho phép "allow", áp dụng cho Network Interface) và Network Access Control List - NACL (stateless, cho phép cả "allow" và "deny", áp dụng ở cấp độ Subnet). | 07/05/2026 | 07/05/2026 | <https://docs.aws.amazon.com/vpc/> |
| 6 | **Giải pháp kết nối mạng & Cân bằng tải Elastic Load Balancing (ELB)** <br> - **Kết nối mạng**: Tìm hiểu các cơ chế VPN (Site-to-Site VPN cho hybrid cloud, Client-to-Site VPN truy cập host) và AWS Direct Connect (đường truyền riêng, trễ thấp 20-30ms, gồm Hosted và Dedicated Connection). <br> - **ELB**: Tìm hiểu dịch vụ cân bằng tải quản lý bởi AWS để phân phối lưu lượng (HTTP, HTTPS, TCP, SSL) đến EC2/Container, hỗ trợ đặt ở public/private subnet qua định danh DNS. | 08/05/2026 | 08/05/2026 | <https://docs.aws.amazon.com/vpc/>, <https://docs.aws.amazon.com/elasticloadbalancing/> |


### Kết quả đạt được tuần 3:

* **Thứ 2 (04/05/2026):** Hiểu tổng quan về AWS Support, phân biệt được 3 loại yêu cầu hỗ trợ (Tài khoản/Thanh toán, Tăng hạn mức dịch vụ, Hỗ trợ kỹ thuật) và các giới hạn của gói Basic.
* **Thứ 3 (05/05/2026):** Thành thạo quy trình khởi tạo lỗi lên AWS Support, đính kèm minh họa và gửi chat trực tuyến với nhân viên hỗ trợ ngay cả khi tài khoản chưa kích hoạt thành công.
* **Thứ 4 (06/05/2026):** Nắm vững 5 mức độ nghiêm trọng sự cố (Severity) tương ứng với thời gian phản hồi của AWS và quy định giờ làm việc hành chính đối với gói Developer.
* **Thứ 5 (07/05/2026):** Hiểu rõ khái niệm Amazon VPC và phân biệt được cơ chế hoạt động của tường lửa có trạng thái Security Group (stateful, chỉ Allow) và tường lửa không trạng thái NACL (stateless, có cả Allow/Deny).
* **Thứ 6 (08/05/2026):** Nắm vững cách thức hoạt động của các giải pháp kết nối mạng hybrid (Site-to-Site VPN, Client VPN, AWS Direct Connect) và nguyên lý phân phối lưu lượng của bộ cân bằng tải Elastic Load Balancing (ELB).
