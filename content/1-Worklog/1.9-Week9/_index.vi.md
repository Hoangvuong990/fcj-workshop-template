---
title: "Worklog Tuần 9"
date: 2026-06-15
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---
### Mục tiêu tuần 9:

* Hoàn thiện toàn bộ luồng giao diện người dùng (UI) chọn lựa các tham số chuyến đi.
* Kết nối giao diện Frontend với các API Gateway endpoint thực tế của hệ thống Backend/AI.
* Lập trình các trạng thái tương tác người dùng như tải dữ liệu và thông báo lỗi.
* Thực hiện review chéo mã nguồn cùng các thành viên trong nhóm.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | **Kiểm tra và chuẩn bị tích hợp API Gateway** <br> - Nhận API endpoint thực tế từ Backend và kiểm tra cấu trúc dữ liệu JSON phản hồi. <br> - Viết các helper function để xử lý các yêu cầu HTTP Request gọi đến API. | 15/06/2026 | 15/06/2026 | <https://docs.aws.amazon.com/apigateway/> |
| 3 | **Kết nối API thật cho luồng chọn lựa thông số** <br> - Viết logic kết nối gọi API khi người dùng nhấn nút gửi thông tin lựa chọn. <br> - Truyền tải các tham số lựa chọn (sở thích, phương tiện, ngân sách) lên API Gateway. | 16/06/2026 | 16/06/2026 | |
| 4 | **Xử lý trạng thái tải & các trạng thái lỗi** <br> - Thiết kế và lập trình giao diện chờ (skeleton loaders hoặc spin indicator) trong thời gian chờ AI xử lý lịch trình. <br> - Viết code bắt lỗi (try/catch) để xử lý các mã lỗi HTTP (400, 500) khi API bị gián đoạn. | 17/06/2026 | 17/06/2026 | |
| 5 | **Review chéo code (Cross-review) cùng cả nhóm** <br> - Tổ chức buổi họp nhóm để review chéo mã nguồn giữa các phần Frontend, Backend và AI. <br> - Tối ưu hóa lại cấu trúc code Frontend theo góp ý của các thành viên. | 18/06/2026 | 18/06/2026 | |
| 6 | **Tối ưu hóa luồng tương tác người dùng** <br> - Kiểm tra lại toàn bộ trải nghiệm từ bước đăng nhập Cognito, chọn thông số, gửi dữ liệu, đến khi nhận phản hồi thô. <br> - Đảm bảo dữ liệu phản hồi được lưu trữ tạm thời chính xác trên Frontend state. | 19/06/2026 | 19/06/2026 | |


### Kết quả đạt được tuần 9:

* **Thứ 2 (15/06/2026):** Viết thành công các hàm helper phục vụ gửi nhận HTTP request đến API Gateway của hệ thống.
* **Thứ 3 (16/06/2026):** Kết nối thành công API thật của luồng chọn lựa thông số và truyền tải dữ liệu đầu vào lên AWS đúng cấu trúc JSON.
* **Thứ 4 (17/06/2026):** Hoàn thiện các hiệu ứng loading mượt mà và viết các hàm bắt lỗi hệ thống hiển thị thông tin rõ ràng cho người dùng.
* **Thứ 5 (18/06/2026):** Hoàn thành buổi review chéo code và thực hiện tái cấu trúc một số hàm xử lý API của Frontend.
* **Thứ 6 (19/06/2026):** Kiểm thử thành công toàn bộ luồng đăng nhập, gửi lựa chọn thông số và lưu trữ dữ liệu thô nhận về từ API.
