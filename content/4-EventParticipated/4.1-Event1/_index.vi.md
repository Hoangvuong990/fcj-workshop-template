---
title: "Sự kiện 1: AWS FIRST CLOUD AI JOURNEY COMMUNITY DAY"
date: 2026-07-09
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

### Thông tin chung về sự kiện
* **Tên sự kiện:** AWS FIRST CLOUD AI JOURNEY COMMUNITY DAY
* **Thời gian:** 09:00, Ngày 23/05/2026
* **Địa điểm:** Tầng 26, Tháp Bitexco, 02 Hải Triều, Phường Sài Gòn, Thành phố Hồ Chí Minh
* **Vai trò:** Người tham dự (Attendee)
* **Diễn giả:** Tinh Truong, Anh Pham, Thinh Nguyen, Mai Nguyen, Uyen Le, Thao Nguyen, Duc Dao, Vy Lam

### Nội dung trọng tâm & Giá trị thu hoạch

**1. Bảo mật Hạ tầng & Tối ưu hóa tại Biên (Edge)**
Diễn giả Thinh Nguyen đã trình bày một khía cạnh đột phá của Amazon CloudFront khi định hình dịch vụ này thành lớp lá chắn bảo mật kiên cố thay vì chỉ đóng vai trò phân phối nội dung (CDN) đơn thuần. Giải pháp áp dụng cơ chế giá cố định (Flat-rate Pricing) giúp hệ thống phòng ngừa rủi ro phát sinh chi phí khổng lồ khi đối mặt với các đợt tấn công từ chối dịch vụ (DDoS). Các giải pháp kỹ thuật nổi bật được đề cập gồm Origin Cloaking (ẩn náu máy chủ gốc trong VPC Origin) cùng khả năng ngăn chặn hiểm họa ngay tại biên mạng.

**2. Bản chất của Tương tác AI & Cơ chế LLM**
Hai phần chia sẻ từ diễn giả đã giúp tôi thay đổi hoàn toàn cách tiếp cận khi làm việc với mô hình ngôn ngữ lớn (LLM):
*   **Kỹ thuật tối ưu ngữ cảnh:** Diễn giả Tinh Truong cho biết chất lượng phản hồi từ AI phụ thuộc lớn vào việc chuẩn hóa đầu vào. Muốn ứng dụng AI thực sự hiệu quả, hệ thống cần tuân thủ bộ khung tiêu chuẩn gồm Mục tiêu, Thông tin nền, Ràng buộc và Tiêu chí đánh giá thành công.
*   **Độ chính xác của tính tất định:** Diễn giả Duc Dao đã làm rõ hiểu lầm rằng đặt Temperature = 0 sẽ luôn nhận được một câu trả lời duy nhất. Trên thực tế, do sai số trong tính toán dấu phẩy động của GPU và cách gộp batch của API, kết quả vẫn có độ lệch nhẹ. Phương án tối ưu là sử dụng mức Temp=0.1 kết hợp thiết kế hệ thống có khả năng chịu lỗi.

**3. Hệ thống Đa tác nhân (Multi-Agent) & Tự động hóa Dữ liệu**
*   **Đánh giá tín dụng tự động:** Diễn giả Vy Lâm chia sẻ một mô hình thực tế ấn tượng về việc áp dụng kiến trúc Multi-Agent trên Amazon Bedrock để thẩm định hồ sơ tài chính của startup. Bằng cách phân công nhiệm vụ cho các tác nhân ảo làm việc trong vùng VPC bảo mật biệt lập, quy trình xử lý đã được tăng tốc lên tới 95%.
*   **Tự động phân tích dữ liệu:** Phần trình bày của diễn giả Anh Pham về Amazon QuickSight Q cho thấy khả năng tự động chuyển đổi các nguồn dữ liệu phức tạp thành báo cáo đồ họa và quy trình tự động trực quan chỉ bằng các câu lệnh ngôn ngữ tự nhiên thông thường.

**4. Phát triển Sản phẩm Nhanh (Rapid Prototyping)**
Nhóm LotusHacks (với các thành viên Mai, Uyên, Thảo) đã mang đến câu chuyện thực tế về 36 giờ thiết kế và lập trình công cụ UTMorpho. Dự án chứng minh những sản phẩm xuất sắc thường bắt nguồn từ nhu cầu thực tiễn của người dùng, đồng thời chia sẻ cách tối ưu hóa chi phí gọi API bằng thuật toán smart-diffing nhằm giảm lượng token tiêu thụ khi AI sinh mã nguồn giao diện.

### Đánh giá và bài học rút ra
Chương trình đã đem đến cầu nối thực tiễn giữa lý thuyết học thuật về AI và môi trường vận hành thực tế ở quy mô doanh nghiệp. Các giải pháp như cô lập tài nguyên bằng VPC và thiết lập phòng thủ tại biên của CloudFront mang lại định hướng rất tốt cho tôi khi thiết kế hạ tầng dự án. Sau sự kiện, tôi nhận thức rõ rằng ứng dụng AI thành công cần được nâng đỡ bởi một nền tảng mạng an toàn, bảo vệ dữ liệu tối đa và kiểm soát ngữ cảnh đầu vào chặt chẽ.

### Hình ảnh Sự kiện

![Hình ảnh sự kiện](/images/4-EventParticipated/event1.1.jpg)
![Hình ảnh sự kiện](/images/4-EventParticipated/event1.2.jpg)