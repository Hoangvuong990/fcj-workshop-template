---
title: "Worklog Tuần 1"
date: 2026-04-17
weight: 1
chapter: false
pre: " <b> 1.1. </b> "
---

### Mục tiêu tuần 1:

* Kết nối, làm quen với các thành viên trong First Cloud Journey.
* Hiểu dịch vụ AWS cơ bản, cách dùng console & CLI.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | **1. Nắm vững quy trình làm việc và báo cáo của chương trình FCJ** <br> - Đã tìm hiểu và hiểu rõ nguyên tắc tự học (self-study) cốt lõi của chương trình thực tập trong vòng 12 tuần (từ 17/04 đến 10/07). <br> - Thiết lập thành công công cụ theo dõi tiến độ công việc hàng ngày (Daily Worklog) qua hệ thống Google Sheet fcj-workshop-template. <br> **2. Khởi tạo môi trường thực hành Cloud** <br> - Bắt đầu tiếp cận Module 1: Explore AWS Services. <br> - Đã tìm hiểu tài liệu hướng dẫn và nắm được quy trình đăng ký tài khoản đám mây. Chuẩn bị xong các thông tin cần thiết (thẻ thanh toán quốc tế) để tiến hành thiết lập môi trường AWS Free Tier, phục vụ cho các bài lab về hạ tầng và mạng (Networking/VPC, EC2) trong những ngày tới. <br> - Định hình chiến lược học tập: Mục tiêu hoàn thành dứt điểm Module đầu tiên trong tháng 4 để đảm bảo đúng tiến độ giới hạn của chương trình.                                                                                        | 20/04/2026   | 20/04/2026      | <https://rules.fcjuni.com/> |
| 3   | **Chủ đề: Tổng quan về Điện toán đám mây & Hạ tầng toàn cầu của AWS** <br> - **Kiến thức:** <br>&emsp; + Cloud Computing: Thuê tài nguyên IT qua internet (pay-as-you-go), giúp tiết kiệm chi phí CapEx và giảm rủi ro. <br>&emsp; + AWS Global Infrastructure: Tìm hiểu Data Center (máy chủ tinh chỉnh riêng), Availability Zone (AZ - độc lập, cách ly rủi ro, tối thiểu 2 AZ khi chạy app), Region (khu vực địa lý chứa tối thiểu 3 AZ), Edge Locations (mạng biên phân phối nội dung CDN/CloudFront). <br> - **Thực hành:** <br>&emsp; + Tạo tài khoản AWS mới. <br>&emsp; + Phân biệt Root User và IAM User. <br>&emsp; + Thiết lập bảo mật MFA cho Root User. | 21/04/2026   | 21/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | **Chủ đề: Các công cụ tương tác với AWS & Làm quen với trợ lý Kiro AI** <br> - **Kiến thức:** <br>&emsp; + Tìm hiểu 3 cách làm việc với AWS: AWS Management Console (web), AWS CLI (dòng lệnh), AWS SDK (lập trình gọi API). <br>&emsp; + Làm quen với Kiro AI: Trợ lý AI đồng hành (Assistant và tương lai là Autonomous Agent). <br>&emsp; + Spec-Driven Development: Phát triển phần mềm dựa trên tài liệu thay vì Vibe coding. Kiro tự động sinh kiến trúc và code từ file product.md, tech.md, structure.md. <br> - **Thực hành:** <br>&emsp; + Đăng nhập AWS Management Console qua IAM User. <br>&emsp; + Tìm hiểu và làm quen giao diện một số dịch vụ cơ bản. | 22/04/2026   | 22/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | **Chủ đề: Khám phá sâu các tính năng của Kiro AI & Tối ưu hóa chi phí AWS** <br> - **Kiến thức:** <br>&emsp; + Tính năng Kiro AI: Agent Hook (kích hoạt workflow khi lưu file), Property-Based Testing (PBT - sinh hàng trăm test case tự động), Timeline Checkpointing (rollback khi code lỗi), Kiro CLI & Custom Agents (chuyên biệt hóa cho DevOps, Database). <br>&emsp; + Tối ưu hóa chi phí (Cost Optimization): Tắt tài nguyên không dùng, right-sizing máy chủ, dùng dịch vụ Serverless/Managed, tận dụng gói giảm giá. <br> - **Thực hành:** <br>&emsp; + Tự thiết kế Spec cho dự án nhỏ để Kiro IDE tự động tạo kiến trúc hệ thống. | 23/04/2026   | 23/04/2026      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | **Chủ đề: AWS Support, Well-Architected Framework & Hoàn thiện checklist Module 1** <br> - **Kiến thức:** <br>&emsp; + AWS Support: Tìm hiểu 4 gói hỗ trợ (Basic, Developer, Business, Enterprise) và cách mở ticket hỗ trợ/tăng hạn mức. <br>&emsp; + AWS Well-Architected Framework: Tìm hiểu tiêu chuẩn và best practices xây dựng hệ thống trên Cloud an toàn, hiệu năng tốt, tiết kiệm chi phí. <br> - **Thực hành:** <br>&emsp; + Thiết lập AWS Budgets (ngân sách cảnh báo qua email khi vượt ngưỡng). <br>&emsp; + Cài đặt thành công Kiro IDE và Kiro CLI trên máy tính. | 24/04/2026   | 24/04/2026      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 1:

* **Thứ 2 (20/04/2026):**
  * Nắm vững quy trình làm việc, báo cáo kỹ thuật Git/GitHub, viết Daily Worklog và cơ chế hoạt động của Hugo.
  * Lập kế hoạch học tập Module 1 và chuẩn bị tài liệu đăng ký tài khoản AWS Free Tier.
* **Thứ 3 (21/04/2026):**
  * Hiểu rõ khái niệm Điện toán đám mây (Cloud Computing), các mô hình thanh toán (pay-as-you-go, CapEx vs OpEx).
  * Nắm vững cấu trúc hạ tầng AWS toàn cầu (Region, Availability Zone, Data Center, Edge Locations).
  * Tạo thành công tài khoản AWS, phân biệt được Root User/IAM User và kích hoạt MFA bảo vệ tài khoản gốc.
* **Thứ 4 (22/04/2026):**
  * Hiểu và phân biệt được 3 phương thức tương tác với tài nguyên AWS: Console, CLI và SDK.
  * Tiếp cận mô hình Spec-Driven Development và hiểu cách trợ lý Kiro AI hỗ trợ tự động hóa viết code từ các tài liệu.
  * Thực hành đăng nhập và thao tác cơ bản trên AWS Console bằng tài khoản IAM User.
* **Thứ 5 (23/04/2026):**
  * Nắm vững các tính năng nâng cao của Kiro AI (Agent Hook, Property-Based Testing, Timeline Checkpointing, Custom Agents).
  * Hiểu các nguyên tắc tối ưu hóa chi phí trên Cloud (Right-sizing, Serverless, tắt tài nguyên nhàn rỗi).
  * Tự lên ý tưởng và viết Spec hoàn chỉnh để Kiro IDE sinh kiến trúc ứng dụng mẫu.
* **Thứ 6 (24/04/2026):**
  * Nắm vững 4 cấp độ dịch vụ AWS Support và cách tạo ticket hỗ trợ kỹ thuật hoặc yêu cầu tăng quota.
  * Hiểu 6 trụ cột của AWS Well-Architected Framework để làm nền tảng thiết kế hệ thống chuẩn Cloud.
  * Thiết lập cảnh báo chi phí bằng AWS Budgets qua email.
  * Cài đặt và cấu hình thành công Kiro IDE cùng Kiro CLI trên máy tính cá nhân.


