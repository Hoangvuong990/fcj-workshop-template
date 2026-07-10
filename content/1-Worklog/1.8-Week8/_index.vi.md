---
title: "Worklog Tuần 8"
date: 2026-06-08
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---
### Mục tiêu tuần 8:

* Đồng bộ hóa cấu trúc dữ liệu API contract (request/response) giữa các bộ phận Frontend, Backend và AI.
* Dựng các component giao diện tĩnh cho các bước lựa chọn hành trình của ứng dụng Wakan.
* Tích hợp thành công cơ chế đăng nhập và quản lý phiên người dùng bằng dịch vụ Amazon Cognito User Pool.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | **Đồng bộ hóa API Contract hệ thống** <br> - Họp cùng nhóm để thảo luận và chốt cấu hình chuẩn của các API endpoint. <br> - Thống nhất cấu trúc dữ liệu JSON đầu vào/đầu ra giữa Frontend và Lambda AI Processor. | 08/06/2026 | 08/06/2026 | |
| 3 | **Dựng component giao diện tĩnh cho bước chọn Trải nghiệm** <br> - Bắt đầu lập trình mã nguồn HTML/CSS/JS cho component lựa chọn loại trải nghiệm và ngân sách. <br> - Đảm bảo cấu trúc code modular để dễ dàng quản lý trạng thái. | 09/06/2026 | 09/06/2026 | |
| 4 | **Dựng các component cho bước chọn Phương tiện & Hành trình** <br> - Xây dựng các component tĩnh phục vụ bước lựa chọn phương tiện di chuyển, đối tượng đồng hành và số ngày đi. <br> - Kiểm tra hiển thị tĩnh của các thẻ lựa chọn trên trình duyệt. | 10/06/2026 | 10/06/2026 | |
| 5 | **Tích hợp Amazon Cognito User Pool để xác thực người dùng** <br> - Tìm hiểu cách sử dụng thư viện AWS Amplify SDK cho Javascript để kết nối với Cognito. <br> - Dựng giao diện Đăng ký/Đăng nhập và viết code logic kết nối xác thực với Cognito User Pool do nhóm đã dựng. | 11/06/2026 | 11/06/2026 | <https://docs.aws.amazon.com/cognito/> |
| 6 | **Kiểm thử tích hợp đăng nhập & Tối ưu bố cục component** <br> - Thực hiện kiểm tra luồng đăng ký tài khoản, đăng nhập nhận token từ Cognito. <br> - Sắp xếp, ghép nối các component tĩnh lại với nhau tạo thành khung sườn giao diện tổng thể của ứng dụng. | 12/06/2026 | 12/06/2026 | |


### Kết quả đạt được tuần 8:

* **Thứ 2 (08/06/2026):** Thống nhất và chốt thành công đặc tả API Contract với định dạng JSON chuẩn giữa Frontend, Backend và AI.
* **Thứ 3 (09/06/2026):** Dựng thành công component giao diện tĩnh đầu tiên cho bước lựa chọn trải nghiệm hành trình và ngân sách.
* **Thứ 4 (10/06/2026):** Hoàn thành xây dựng các thành phần giao diện tĩnh để chọn phương tiện, đối tượng đồng hành và thời gian di chuyển.
* **Thứ 5 (11/06/2026):** Tích hợp thành công thư viện AWS SDK kết nối với Amazon Cognito User Pool và hoàn thiện khung đăng nhập/đăng ký.
* **Thứ 6 (12/06/2026):** Xác thực thành công luồng đăng nhập nhận token Cognito và ghép nối thành công khung sườn các component tĩnh trên giao diện.
