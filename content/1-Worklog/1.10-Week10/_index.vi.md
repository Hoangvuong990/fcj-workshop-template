---
title: "Worklog Tuần 10"
date: 2026-06-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---
### Mục tiêu tuần 10:

* Xây dựng giao diện hiển thị lịch trình hành trình chi tiết theo trục thời gian (Timeline) và tích hợp bản đồ trực quan.
* Tối ưu hóa khả năng hiển thị tương thích (Responsive Design) trên các thiết bị di động.
* Tham gia kiểm thử hệ thống từ đầu đến cuối (End-to-End Test) và phối hợp sửa lỗi (bug fixing).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | **Thiết kế giao diện hiển thị Timeline lịch trình** <br> - Lập trình component Timeline hiển thị thông tin chi tiết các ngày, địa điểm và thời gian hoạt động của chuyến đi nhận từ AI. <br> - Căn chỉnh CSS hiển thị đẹp mắt, rõ ràng cho các mốc thời gian. | 22/06/2026 | 22/06/2026 | |
| 3 | **Tích hợp bản đồ trực quan hóa địa điểm** <br> - Tích hợp thư viện bản đồ (như Mapbox hoặc OpenStreetMap) để hiển thị vị trí các địa điểm du lịch trong hành trình. <br> - Vẽ các điểm marker định vị địa điểm tương ứng với từng chặng trên Timeline. | 23/06/2026 | 23/06/2026 | |
| 4 | **Tối ưu hóa thiết kế Responsive trên Mobile** <br> - Sử dụng CSS Media Queries để điều chỉnh giao diện hiển thị tối ưu trên màn hình điện thoại di động và máy tính bảng. <br> - Điều chỉnh layout sidebar và bản đồ sang dạng cuộn đứng để nâng cao trải nghiệm người dùng. | 24/06/2026 | 24/06/2026 | |
| 5 | **Tham gia kiểm thử End-to-End (E2E) lần đầu** <br> - Kết nối hoàn chỉnh từ giao diện Frontend qua API Gateway đến Lambda AI và hiển thị dữ liệu lịch trình thực tế. <br> - Thực hiện kiểm thử toàn bộ luồng sử dụng cùng cả nhóm (bấm nút → nhận lịch trình trực tiếp). | 25/06/2026 | 25/06/2026 | |
| 6 | **Họp nhóm tổng kết & Khắc phục lỗi tích hợp** <br> - Phối hợp sửa các lỗi phát sinh trong quá trình truyền dữ liệu (như parse lỗi JSON, hiển thị sai định dạng ngày/tháng). <br> - Cập nhật các bản vá lỗi và tối ưu hiệu năng hiển thị cho các component giao diện. | 26/06/2026 | 26/06/2026 | |


### Kết quả đạt được tuần 10:

* **Thứ 2 (22/06/2026):** Hoàn thành component Timeline hiển thị chi tiết lịch trình chuyến đi theo thời gian trực quan.
* **Thứ 3 (23/06/2026):** Tích hợp thành công bản đồ hiển thị các điểm Marker địa điểm du lịch tương ứng với lịch trình.
* **Thứ 4 (24/06/2026):** Tối ưu hóa thành công giao diện tương thích (Responsive) giúp hiển thị mượt mà trên thiết bị di động.
* **Thứ 5 (25/06/2026):** Tham gia cùng nhóm hoàn thành bài test End-to-End đầu tiên, kiểm chứng luồng hoạt động từ Frontend lên AWS.
* **Thứ 6 (26/06/2026):** Khắc phục triệt để các lỗi parse dữ liệu JSON từ AI phản hồi về và chốt bản thử nghiệm hoạt động ổn định.
