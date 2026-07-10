---
title: "Worklog Tuần 4"
date: 2026-05-11
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---
### Mục tiêu tuần 4:

* Tìm hiểu tổng quan về dịch vụ máy chủ ảo Amazon EC2 (Elastic Compute Cloud).
* Nắm vững các khái niệm và thành phần bổ trợ: AMI (Amazon Machine Image), EBS (Elastic Block Store), Instance Store, User Data và Metadata.
* Hiểu cách thức hoạt động của Auto Scaling và tích hợp cân bằng tải để tăng tính sẵn sàng cao của hệ thống.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | **Tổng quan về Amazon EC2 (Elastic Compute Cloud)** <br> - Tìm hiểu khái niệm máy chủ ảo EC2, tính linh hoạt và khả năng co dãn tài nguyên. <br> - Nghiên cứu các nhóm ứng dụng thực tế (web hosting, database, authentication). <br> - Học cách lựa chọn Instance Type phù hợp theo nhu cầu CPU (Intel, AMD, Graviton), Memory, Network và Storage. | 11/05/2026 | 11/05/2026 | <https://docs.aws.amazon.com/ec2/> |
| 3 | **AMI, Cơ chế Sao lưu & Cặp khóa Bảo mật (Key Pair)** <br> - Tìm hiểu cách sử dụng AMI để khởi tạo hàng loạt instance đồng bộ chứa sẵn hệ điều hành và cấu hình phần mềm. <br> - Nghiên cứu quy trình sao lưu (backup) bằng snapshot cho ổ đĩa EBS. <br> - Tìm hiểu nguyên lý hoạt động của Key Pair (gồm public key lưu trên AWS và private key lưu trên máy cá nhân) để SSH an toàn. | 12/05/2026 | 12/05/2026 | <https://docs.aws.amazon.com/ec2/> |
| 4 | **Lưu trữ dạng khối với Amazon EBS (Elastic Block Store)** <br> - Tìm hiểu dịch vụ block storage EBS gắn trực tiếp vào EC2, phân biệt 2 loại ổ đĩa SSD và HDD. <br> - Nghiên cứu thiết kế độ tin cậy cao (99.999% SLA) thông qua việc tự động replicate dữ liệu giữa các storage node trong cùng một Availability Zone (AZ). <br> - Phân tích kiến trúc mạng độc lập của EBS giúp duy trì hoạt động riêng biệt với EC2. | 13/05/2026 | 13/05/2026 | <https://docs.aws.amazon.com/ebs/> |
| 5 | **Bộ nhớ tạm thời Instance Store & Lý thuyết khởi tạo User Data** <br> - Nghiên cứu bộ nhớ lưu trữ tạm thời Instance Store (dựa trên ổ đĩa NVMe cục bộ trên physical node) cho các tác vụ cần IOPS cực cao nhưng mất dữ liệu khi stop instance. <br> - Tìm hiểu lý thuyết về EC2 User Data (chạy script tự động hóa bash shell hoặc PowerShell khi boot máy lần đầu). Biết được cơ chế kiểm tra User Data của instance thông qua địa chỉ IP Link-Local `http://169.254.169.254/latest/user-data`. | 14/05/2026 | 14/05/2026 | <https://docs.aws.amazon.com/ec2/> |
| 6 | **Lý thuyết EC2 Metadata & Cơ chế co dãn tự động Auto Scaling** <br> - Tìm hiểu cơ chế hoạt động của EC2 Metadata: các thông tin liên quan tới bản thân EC2 instance (IP, Hostname, SG) được truy xuất tại địa chỉ Link-Local `http://169.254.169.254/latest/meta-data/`. <br> - Nghiên cứu EC2 Auto Scaling: cách thiết lập nhóm co dãn (Auto Scaling Group), chính sách co dãn (scaling policies) phối hợp cùng Load Balancer và phân bố máy chủ qua nhiều AZ. | 15/05/2026 | 15/05/2026 | <https://docs.aws.amazon.com/autoscaling/> |


### Kết quả đạt được tuần 4:

* **Thứ 2 (11/05/2026):** Hiểu rõ khái niệm dịch vụ EC2 và cách phân loại Instance Type phù hợp theo yêu cầu tài nguyên phần cứng.
* **Thứ 3 (12/05/2026):** Thành thạo lý thuyết khởi tạo máy từ AMI, cơ chế snapshot bảo vệ dữ liệu và sử dụng cặp khóa (Key Pair) để SSH bảo mật.
* **Thứ 4 (13/05/2026):** Nắm vững kiến trúc hoạt động độc lập của EBS và cơ chế dự phòng dữ liệu tự động bên trong Availability Zone (AZ).
* **Thứ 5 (14/05/2026):** Phân biệt được sự khác nhau giữa ổ đĩa EBS và ổ đĩa tạm thời Instance Store; nắm được khái niệm User Data dùng để chạy script tự động hóa khi khởi tạo máy thông qua địa chỉ Link-Local `169.254.169.254`.
* **Thứ 6 (15/05/2026):** Hiểu cơ chế truy xuất thông tin cấu hình qua Metadata thông qua địa chỉ IP Link-Local và nguyên lý co dãn tự động (Auto Scaling) kết hợp Load Balancer trên nhiều AZ.
