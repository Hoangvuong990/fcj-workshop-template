---
title: "Worklog Tuần 2"
date: 2026-04-27
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---
### Mục tiêu tuần 2:

* Hiểu cách sử dụng AWS Cost Management để quản lý chi phí và tài nguyên.
* Nắm vững các loại Budget (Cost, Usage, Reservation, Savings Plans) và cách thiết lập cảnh báo tự động qua email/SNS.
* Thực hành tạo, theo dõi và dọn dẹp các ngân sách ngân quỹ trên Cloud.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | **Truy cập Billing & Khám phá AWS Budgets** <br> - Truy cập AWS Management Console, điều hướng đến Billing. <br> - Tìm hiểu cách tạo Budget từ template có sẵn (Cost budget, Usage budget, RI budget, Savings Plans budget). <br> - Thực hành tạo Cost Budget mới: đặt tên budget, chu kỳ (monthly, quarterly, annually), bắt đầu từ tháng mong muốn. Chọn phương thức tính toán (fixed hoặc auto-adjusting) và nhập số tiền ngân sách mong muốn. | 27/04/2026   | 27/04/2026      | <https://docs.aws.amazon.com/cost-management/> |
| 3   | **Thiết lập cảnh báo Cost Budget & Tạo Usage Budget** <br> - Thiết lập ngưỡng cảnh báo (Alert threshold) cho Cost Budget (dựa trên chi phí thực tế hoặc dự báo) và tỷ lệ phần trăm ngưỡng (% of budgeted amount). <br> - Cấu hình thông báo qua email hoặc Amazon SNS khi chi phí vượt ngưỡng. <br> - Thực hành tạo Usage Budget: xác định loại tài nguyên/dịch vụ cần theo dõi mức sử dụng (EC2 running hours, Data transfer), thiết lập số lượng đơn vị sử dụng cho phép và ngưỡng cảnh báo. | 28/04/2026   | 28/04/2026      | <https://docs.aws.amazon.com/cost-management/> |
| 4   | **Tìm hiểu và tạo Reservation Budget (RI Budget)** <br> - Xác định mục tiêu tiết kiệm chi phí bằng cách sử dụng các Reserved Instances (RI). <br> - Thiết lập ngân sách theo dõi tỷ lệ sử dụng (utilization) hoặc độ bao phủ (coverage) của các Reserved Instances. <br> - Cấu hình cảnh báo qua email/SNS nếu tỷ lệ sử dụng hoặc độ bao phủ giảm xuống dưới mức mong đợi. | 29/04/2026   | 29/04/2026      | <https://docs.aws.amazon.com/cost-management/> |
| 5   | **Tìm hiểu và tạo Savings Plans Budget** <br> - Thiết lập ngân sách để theo dõi tỷ lệ sử dụng hoặc độ bao phủ của các gói Savings Plans. <br> - Cấu hình cảnh báo tự động khi các chỉ số này không đạt yêu cầu nhằm đảm bảo hiệu quả tối ưu chi phí. | 30/04/2026   | 30/04/2026      | <https://docs.aws.amazon.com/cost-management/> |
| 6   | **Quản lý và dọn dẹp các Budget không sử dụng** <br> - Học cách quản lý, chỉnh sửa danh sách các Budget hiện có. <br> - Thực hành dọn dẹp hạ tầng: Chọn các Budget không còn sử dụng và tiến hành xác nhận xóa để tránh lộn xộn trong bảng quản lý. | 01/05/2026   | 01/05/2026      | <https://docs.aws.amazon.com/cost-management/> |


### Kết quả đạt được tuần 2:

* **Thứ 2 (27/04/2026):**
  * Nắm vững giao diện Billing & Cost Management trên AWS Management Console.
  * Hiểu rõ 4 nhóm ngân sách mẫu: Cost budget, Usage budget, RI budget và Savings Plans budget.
  * Khởi tạo thành công Cost Budget đầu tiên với các thiết lập về chu kỳ thanh toán và hạn mức chi phí cố định/tự động điều chỉnh.
* **Thứ 3 (28/04/2026):**
  * Thành thạo thiết lập ngưỡng cảnh báo (Alert thresholds) dựa trên chi phí thực tế và chi phí dự báo.
  * Cấu hình thành công cảnh báo tự động gửi về email cá nhân khi vượt hạn mức.
  * Tạo thành công Usage Budget để kiểm soát lượng tài nguyên sử dụng (như thời gian chạy EC2, lưu lượng truyền tải dữ liệu).
* **Thứ 4 (29/04/2026):**
  * Hiểu rõ khái niệm Reserved Instances (RI) và cách thiết lập Reservation Budget để tối ưu hóa chi phí.
  * Biết cách theo dõi tỷ lệ sử dụng (utilization) và độ bao phủ (coverage) của RI để tránh lãng phí.
* **Thứ 5 (30/04/2026):**
  * Nắm vững cách thức hoạt động của Savings Plans và cách tạo Savings Plans Budget tương ứng.
  * Thiết lập cảnh báo chủ động khi hiệu suất sử dụng của gói tiết kiệm giảm xuống dưới mức mong đợi.
* **Thứ 6 (01/05/2026):**
  * Làm quen với quy trình quản lý, sửa đổi cấu hình ngân sách hiện có.
  * Thực hành dọn dẹp môi trường Lab bằng cách xóa các Budgets không dùng tới, đảm bảo giao diện quản lý gọn gàng, tránh nhầm lẫn.


