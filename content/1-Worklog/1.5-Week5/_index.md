---
title: "Week 5 Worklog"
date: 2026-05-18
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---
### Week 5 Objectives:

* Deep dive into Amazon S3 object storage, static website hosting, access management, and data protection mechanisms.
* Master hybrid storage and migration solutions: AWS Snow Family products and AWS Storage Gateway.
* Understand the Shared Responsibility Model and AWS Identity and Access Management (IAM) framework.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | **Overview of Amazon S3** <br> - Learn object storage concepts and S3's WORM (Write Once Read Many) characteristics. <br> - Study S3 specifications: unlimited bucket storage, 5TB max object size, and automatic 3-AZ replication. <br> - Explore S3 event triggers for automation and *multipart upload* to optimize large file ingestion. | 05/18/2026 | 05/18/2026 | <https://docs.aws.amazon.com/s3/> |
| 3 | **Advanced S3 Configuration: Website Hosting, CORS, Access Control & Storage Classes** <br> - Study S3 static website hosting, Cross-Origin Resource Sharing (CORS) configurations, and S3 Access Points. <br> - Evaluate S3 Storage Classes (Standard, Intelligent-Tiering, Glacier) to optimize storage costs using Lifecycle Management. <br> - Understand access control (ACLs, Bucket Policies) and use *Versioning* to prevent accidental deletion and mitigate ransomware. | 05/19/2026 | 05/19/2026 | <https://docs.aws.amazon.com/s3/> |
| 4 | **Data Migration via Snow Family & AWS Storage Gateway** <br> - **Snow Family**: Examine large-scale offline migration devices (PB to EB scale) including Snowball (80TB), Snowball Edge (100TB with local compute capability), and Snowmobile (100PB). <br> - **Storage Gateway**: Learn hybrid cloud storage configurations: File Gateway (NFS/SMB), Volume Gateway (iSCSI), and Tape Gateway (VTL). | 05/20/2026 | 05/20/2026 | <https://docs.aws.amazon.com/snowball/>, <https://docs.aws.amazon.com/storagegateway/> |
| 5 | **AWS Shared Responsibility Model** <br> - Analyze security boundaries: AWS secures *of* the cloud (underlying global infrastructure) while customers secure *in* the cloud (data, OS patch management, firewall/SG settings, encryption, and IAM). <br> - Review supporting security services such as IAM, Cognito, AWS Organizations, AWS Identity Center (SSO), and KMS. | 05/21/2026 | 05/21/2026 | <https://aws.amazon.com/compliance/shared-responsibility-model/> |
| 6 | **Identity & Access Management (AWS IAM)** <br> - **Root Account**: Study AWS security best practices (avoid daily Root use, establish IAM Admin users, enforce MFA, and maintain updated registration emails). <br> - **IAM Principals & Users**: Classify access entities (Root, IAM User, Federated User, IAM Role). Apply permissions via IAM Policies attached to users directly or via IAM Groups. | 05/22/2026 | 05/22/2026 | <https://docs.aws.amazon.com/iam/> |


### Week 5 Achievements:

* **Monday (05/18/2026):** Grasped Amazon S3 object storage concepts, its 11-nines durability rating, and large file optimization via multipart upload.
* **Tuesday (05/19/2026):** Mastered static website hosting on S3, CORS configuration, lifecycle management using S3 Storage Classes, and versioning for data recovery.
* **Wednesday (05/20/2026):** Understood the operation of physical Snow Family migration appliances and hybrid storage gateways (File, Volume, Tape).
* **Thursday (05/21/2026):** Understood the security split of the Shared Responsibility Model to design compliant, secure cloud architectures.
* **Friday (05/22/2026):** Mastered Root account protection principles, IAM identity management (Users, Groups, Roles), and programmatic/console policy authorization.
