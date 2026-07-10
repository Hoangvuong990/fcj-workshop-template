---
title: "Worklog Tuần 5"
date: 2026-05-18
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---
### Mục tiêu tuần 5:

* Tìm hiểu sâu về dịch vụ lưu trữ đối tượng Amazon S3, các cơ chế bảo mật, phân quyền truy cập và host website tĩnh.
* Nắm vững các giải pháp lưu trữ và di chuyển dữ liệu hybrid: dòng sản phẩm AWS Snow Family và AWS Storage Gateway.
* Hiểu rõ Mô hình trách nhiệm chung (Shared Responsibility Model) và hệ thống quản lý danh tính, phân quyền AWS IAM (Identity and Access Management).

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| 2 | **Tổng quan về Amazon S3 (Simple Storage Service)** <br> - Tìm hiểu khái niệm lưu trữ đối tượng (object storage), tính năng WORM (ghi một lần đọc nhiều lần). <br> - Nghiên cứu thông số kỹ thuật: Không giới hạn dung lượng bucket, đối tượng tối đa 5TB, tự động sao chép trên 3 AZ. <br> - Tìm hiểu cơ chế trigger event (kích hoạt tác vụ khi thao tác đối tượng) và kỹ thuật *multipart upload* để tối ưu tải file dung lượng lớn. | 18/05/2026 | 18/05/2026 | <https://docs.aws.amazon.com/s3/> |
| 3 | **Cấu hình S3 nâng cao: Host Website, CORS, Access Control & Storage Classes** <br> - Tìm hiểu host website tĩnh trên S3, cấu hình CORS (chia sẻ tài nguyên chéo nguồn) và S3 Access Point quản lý truy cập theo nhóm. <br> - Phân tích các lớp lưu trữ (Storage Classes: Standard, Intelligent-Tiering, Glacier) để tối ưu chi phí qua Lifecycle Management. <br> - Tìm hiểu bảo mật phân quyền qua S3 ACL, Bucket Policy kết hợp IAM, và tính năng *Versioning* chống ghi đè/ransomware. | 19/05/2026 | 19/05/2026 | <https://docs.aws.amazon.com/s3/> |
| 4 | **Giải pháp di chuyển dữ liệu Snow Family & AWS Storage Gateway** <br> - **Snow Family**: Nghiên cứu dòng sản phẩm di chuyển dữ liệu lớn (PB đến EB) gồm Snowball (80TB), Snowball Edge (100TB, có compute cục bộ), và Snowmobile (100PB). <br> - **Storage Gateway**: Tìm hiểu giải pháp lưu trữ Hybrid tích hợp on-premises với Cloud qua 3 phương thức: File Gateway (NFS/SMB), Volume Gateway (iSCSI), và Tape Gateway (VTL). | 20/05/2026 | 20/05/2026 | <https://docs.aws.amazon.com/snowball/>, <https://docs.aws.amazon.com/storagegateway/> |
| 5 | **Mô hình Trách nhiệm Chung (Shared Responsibility Model)** <br> - Nghiên cứu ranh giới bảo mật: AWS chịu trách nhiệm bảo mật *cho* đám mây (phần cứng hạ tầng), Khách hàng bảo mật *trong* đám mây (dữ liệu, OS, cấu hình firewall, mã hóa, IAM). <br> - Tìm hiểu các dịch vụ bảo mật bổ trợ như IAM, Cognito, AWS Organizations, AWS Identity Center (SSO), và KMS. | 21/05/2026 | 21/05/2026 | <https://aws.amazon.com/compliance/shared-responsibility-model/> |
| 6 | **Quản lý Danh tính & Truy cập AWS IAM (Identity and Access Management)** <br> - **Root Account**: Nắm vững các Best Practices bảo vệ tài khoản gốc (không dùng hàng ngày, chuyển sang dùng IAM Admin, kích hoạt MFA, cập nhật email thường xuyên). <br> - **IAM Principal & User**: Phân biệt các thực thể truy cập (Root, IAM User, Federated User, IAM Role). Hiểu cách phân quyền qua IAM Policy gắn trực tiếp hoặc qua IAM Group. | 22/05/2026 | 22/05/2026 | <https://docs.aws.amazon.com/iam/> |


### Kết quả đạt được tuần 5:

* **Thứ 2 (18/05/2026):** Hiểu rõ khái niệm lưu trữ đối tượng của Amazon S3, các chỉ số độ bền (11 số 9) và phương pháp tải file lớn bằng multipart upload.
* **Thứ 3 (19/05/2026):** Nắm vững cách host website tĩnh trên S3, thiết lập cấu hình CORS, tối ưu chi phí với Lifecycle/Storage Classes và bảo vệ dữ liệu bằng Versioning/Bucket Policy.
* **Thứ 4 (20/05/2026):** Hiểu cách thức hoạt động của thiết bị vật lý Snow Family trong di chuyển dữ liệu lớn và các giải pháp lưu trữ đám mây lai với Storage Gateway.
* **Thứ 5 (21/05/2026):** Nắm vững ranh giới trách nhiệm bảo mật giữa AWS và khách hàng trên môi trường Cloud để thiết kế hệ thống tuân thủ an toàn thông tin.
* **Thứ 6 (22/05/2026):** Nắm chắc các nguyên tắc bảo mật tài khoản Root, cách quản lý định danh người dùng qua IAM Users/Groups/Policies và cơ chế phân quyền truy cập AWS Console/CLI/SDK.
