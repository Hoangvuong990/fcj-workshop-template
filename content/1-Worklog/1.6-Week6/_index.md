---
title: "Week 6 Worklog"
date: 2026-05-25
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---
### Week 6 Objectives:

* Master basic Database concepts: Transaction Logs, Buffers, Primary/Foreign keys, Indexes, and differentiate SQL vs NoSQL.
* Understand the usage and configuration of Amazon RDS & Amazon Aurora for transactional workloads (OLTP).
* Learn the architecture of Amazon Redshift Data Warehouse and Redshift Spectrum for analytical workloads (OLAP).
* Study central account governance with AWS Organizations and configuration compliance auditing using AWS Security Hub.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | **Database Fundamentals & AWS Organizations Account Governance** <br> - **Database Concepts**: Understand database definitions, Sessions, Primary/Foreign Keys, Indexing, Partitioning, and Execution Plans to optimize queries. <br> - **AWS Organizations**: Centrally manage multiple AWS accounts via Organizational Units (OUs), combine invoicing using Consolidated Billing, and implement top-level restrictions using Service Control Policies (SCPs) with deny-based configurations. | 05/25/2026 | 05/25/2026 | <https://docs.aws.amazon.com/organizations/> |
| 3 | **Database Classification & Amazon RDS / Aurora** <br> - **Mechanisms**: Study Database Logs (recovery and sync) and Buffers (in-memory read acceleration). <br> - **Classification**: Compare SQL (RDBMS) vs. NoSQL (Document, Key-value, Wide-column, Graph). <br> - **Amazon RDS**: Learn about AWS-managed RDBMS engines (MySQL, PostgreSQL, MS SQL, Oracle, MariaDB), supporting automated backups, Read Replicas (promotable to Primary), Multi-AZ failover, encryption, and storage auto-scaling. | 05/26/2026 | 05/26/2026 | <https://docs.aws.amazon.com/rds/> |
| 4 | **Exploring Amazon Redshift (Data Warehouse)** <br> - Study Amazon Redshift: an AWS-managed analytical Data Warehouse service built on PostgreSQL and optimized for OLAP tasks. <br> - Analyze distributed structure: Massively-Parallel Processing (MPP) architecture where data is partitioned across Compute Nodes under the coordination of a Leader Node. <br> - Learn about Columnar storage and standard integration using SQL, JDBC, and ODBC drivers. | 05/27/2026 | 05/27/2026 | <https://docs.aws.amazon.com/redshift/> |
| 5 | **Redshift Query Architecture & Redshift Spectrum** <br> - Trace query flows from clients through JDBC/ODBC connections to the Leader Node, which then dispatches parallel executions to Compute Nodes. <br> - Study Redshift Spectrum to query files stored directly on Amazon S3 without loading them into the cluster, optimizing storage costs. | 05/28/2026 | 05/28/2026 | <https://docs.aws.amazon.com/redshift/> |
| 6 | **Database Recap & Compliance Evaluation with AWS Security Hub** <br> - **Database Recap**: Differentiate OLTP (RDS/Aurora) and OLAP (Redshift) use cases. <br> - **AWS Security Hub**: Explore automated security posture management, industry standards auditing (PCI DSS), and risk scoring (security score) using continuous scanning. <br> - **Summary Review**: Review security tools studied during the week (Organizations, Identity Center, KMS, Security Hub). | 05/29/2026 | 05/29/2026 | <https://docs.aws.amazon.com/securityhub/> |


### Week 6 Achievements:

* **Monday (05/25/2026):** Understood fundamental database concepts and query optimization. Mastered multi-account governance structures (OUs, Consolidated Billing) and top-level policy enforcement via AWS Organizations SCPs.
* **Tuesday (05/26/2026):** Distinguished SQL from NoSQL models. Mastered Amazon RDS functionalities, including automatic backups, Read Replicas, Multi-AZ failover, and encryption.
* **Wednesday (05/27/2026):** Grasped Amazon Redshift Data Warehouse characteristics, MPP parallel query execution (Leader & Compute nodes), and Columnar storage optimization.
* **Thursday (05/28/2026):** Understood Redshift's query dispatch workflow and learned how Redshift Spectrum enables querying S3 data directly to minimize cost.
* **Friday (05/29/2026):** Contrasted OLTP vs. OLAP service architectures. Mastered automated configuration auditing and compliance scoring via AWS Security Hub.
