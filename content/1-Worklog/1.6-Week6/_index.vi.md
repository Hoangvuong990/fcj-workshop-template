---
title: "Worklog Tuần 6"
date: 2026-05-25
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---
### Mục tiêu tuần 6:

* Nắm vững các khái niệm cơ bản về Cơ sở dữ liệu: Transaction Log, Buffer, Khóa chính/Khóa ngoại, Index và phân biệt SQL vs NoSQL.
* Hiểu cách sử dụng và cấu hình dịch vụ Amazon RDS & Amazon Aurora cho các ứng dụng giao dịch (OLTP).
* Tìm hiểu kiến trúc dịch vụ kho dữ liệu Amazon Redshift và Redshift Spectrum cho các tác vụ phân tích dữ liệu lớn (OLAP).
* Tìm hiểu cơ chế quản lý tập trung nhiều tài khoản với AWS Organizations và kiểm tra an toàn cấu hình hệ thống với AWS Security Hub.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | **Cơ sở dữ liệu căn bản & Quản trị tài khoản AWS Organizations** <br> - **Database Concepts**: Định nghĩa CSDL, khái niệm Phiên (Session), Khóa chính/ngoại, thiết lập Index, Partitioning, và Execution Plan. <br> - **AWS Organizations**: Quản lý nhiều tài khoản tập trung qua Organizational Unit (OU), gom hóa đơn qua Consolidated Billing, và kiểm soát quyền cao nhất bằng Service Control Policies (SCP) áp dụng "deny-based policy". | 25/05/2026 | 25/05/2026 | <https://docs.aws.amazon.com/organizations/> |
| 3 | **Phân loại Cơ sở dữ liệu & Tìm hiểu dịch vụ Amazon RDS / Amazon Aurora** <br> - **Cơ chế hoạt động**: Tìm hiểu Database Log (phục hồi/đồng bộ dữ liệu) và Buffer (bộ đệm tăng tốc độ truy xuất). <br> - **Phân loại CSDL**: So sánh SQL (RDBMS) và NoSQL (Document, Key-value, Wide-column, Graph). <br> - **Amazon RDS**: Dịch vụ RDBMS được quản lý bởi AWS (MySQL, PostgreSQL, MS SQL, Oracle, MariaDB), hỗ trợ tự động sao lưu, Read Replica (phục vụ read workload và có thể tách thành Primary), Multi-AZ (tự động failover), mã hóa at-rest/in-transit và Auto-scaling. | 26/05/2026 | 26/05/2026 | <https://docs.aws.amazon.com/rds/> |
| 4 | **Khám phá Amazon Redshift (Dịch vụ Data Warehouse)** <br> - Tìm hiểu Amazon Redshift: dịch vụ kho dữ liệu (Data Warehouse) được quản lý bởi AWS, dựa trên PostgreSQL và được tối ưu cho các tác vụ phân tích (OLAP). <br> - Nghiên cứu cấu trúc phân tán: Kiến trúc xử lý song song Massively-Parallel Processing (MPP), dữ liệu được phân chia sang các Compute node dưới sự điều phối của Leader Node. <br> - Tìm hiểu Columnar Storage (lưu trữ cột) để tối ưu hóa truy vấn phân tích, và kết nối qua SQL, JDBC, ODBC. | 27/05/2026 | 27/05/2026 | <https://docs.aws.amazon.com/redshift/> |
| 5 | **Nghiên cứu kiến trúc truy vấn Redshift & Redshift Spectrum** <br> - Phân tích luồng truy vấn từ client thông qua JDBC/ODBC tới Leader node, sau đó Leader node phân phối tác vụ song song xuống các Compute node. <br> - Tìm hiểu tính năng Redshift Spectrum để thực hiện truy vấn trực tiếp trên dữ liệu nằm ngoài cluster (lưu trữ trên S3), giúp tối ưu hóa chi phí lưu trữ. | 28/05/2026 | 28/05/2026 | <https://docs.aws.amazon.com/redshift/> |
| 6 | **Tổng kết Database & Đánh giá bảo mật với AWS Security Hub** <br> - **Database Recap**: So sánh điểm khác biệt cốt lõi giữa Amazon RDS (cho OLTP) và Amazon Redshift (cho OLAP). <br> - **AWS Security Hub**: Tìm hiểu cơ chế Security Hub tự động kiểm tra cấu hình theo tiêu chuẩn ngành (PCI DSS), chấm điểm bảo mật (security score), quét liên tục để nhận diện rủi ro cấu hình sai. <br> - **Ôn tập tổng kết**: Review các dịch vụ bảo mật trong tuần (Organizations, Identity Center, KMS, Security Hub). | 29/05/2026 | 29/05/2026 | <https://docs.aws.amazon.com/securityhub/> |


### Kết quả đạt được tuần 6:

* **Thứ 2 (25/05/2026):** Hiểu rõ khái niệm CSDL, mối quan hệ Khóa chính/Khóa ngoại và các phương pháp tối ưu hóa truy vấn. Đồng thời, nắm vững cơ chế quản lý tập trung nhiều tài khoản AWS (OU, Consolidated Billing) và chính sách kiểm soát quyền hạn SCP của AWS Organizations.
* **Thứ 3 (26/05/2026):** Phân biệt được sự khác nhau giữa SQL và các nhóm NoSQL. Nắm vững tính năng của dịch vụ Amazon RDS (sao lưu tự động, Read Replica, Multi-AZ failover, mã hóa bảo mật).
* **Thứ 4 (27/05/2026):** Hiểu rõ dịch vụ kho dữ liệu Amazon Redshift, kiến trúc xử lý song song MPP (Leader Node & Compute Nodes) và tối ưu hóa phân tích bằng Columnar storage.
* **Thứ 5 (28/05/2026):** Hiểu cơ chế phân phối truy vấn song song của Redshift và cách sử dụng Redshift Spectrum để truy vấn trực tiếp dữ liệu trên S3 mà không cần load vào cluster.
* **Thứ 6 (29/05/2026):** Phân biệt rõ các kịch bản sử dụng giữa dịch vụ OLTP (RDS/Aurora) và OLAP (Redshift). Đồng thời, nắm được cơ chế Security Hub quét và chấm điểm bảo mật để quản trị cấu hình hệ thống an toàn.
