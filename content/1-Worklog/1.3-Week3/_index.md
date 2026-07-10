---
title: "Week 3 Worklog"
date: 2026-05-04
weight: 3
chapter: false
pre: " <b> 1.3. </b> "
---
### Week 3 Objectives:

* Understand the AWS Support system, case creation process, and severity levels.
* Master networking fundamentals on AWS (Amazon VPC, Subnets, NACL & Security Group security).
* Differentiate hybrid connection solutions (VPN, AWS Direct Connect) and Elastic Load Balancing (ELB).

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | **Overview of AWS Support & Case Types** <br> - Study the support access workflow and distinguish the case categories: Account & Billing Support, Service Limit Increase (quota adjustment), and Technical Support. <br> - Understand contact channels for Technical Support: email/web for Developer plan, phone/chat for Business/Enterprise. Note that the Basic plan does not cover technical support cases. | 05/04/2026 | 05/04/2026 | <https://docs.aws.amazon.com/awssupport/> |
| 3 | **Creating and Managing Support Cases** <br> - Practice creating a case for account activation: access the Support console, select **Create case** -> **Account and billing support** (Type: Account, Category: Activation). <br> - Write clear subjects/descriptions, upload screenshots, select Chat as contact method, and submit to connect with AWS agents. | 05/05/2026 | 05/05/2026 | <https://docs.aws.amazon.com/awssupport/> |
| 4 | **Understanding Case Severity & Response Times** <br> - Study severity definitions and response times: General guidance (< 24h), System impaired (< 12h), Production system impaired (< 4h - Business+), Production system down (< 1h - Business+), Business-critical system down (< 15m - Enterprise). <br> - Note that Developer plan SLA response hours apply only during local business hours (8 AM - 6 PM on weekdays). | 05/06/2026 | 05/06/2026 | <https://docs.aws.amazon.com/awssupport/> |
| 5 | **Amazon VPC & Network Security on AWS** <br> - **VPC Fundamentals**: Learn about IP ranges (CIDR), limits (5 VPCs/Region), and the purpose of environment isolation (Dev/Test/Prod). <br> - **Network Security**: Differentiate between Security Groups (stateful virtual firewalls, allow-only rules, applied at Network Interface level) and Network Access Control Lists - NACLs (stateless, allow and deny rules, applied at Subnet level). | 05/07/2026 | 05/07/2026 | <https://docs.aws.amazon.com/vpc/> |
| 6 | **Network Connectivity Solutions & Elastic Load Balancing (ELB)** <br> - **Network Connectivity**: Study VPN types (Site-to-Site VPN for hybrid connections, Client VPN for host access) and AWS Direct Connect (dedicated, low-latency 20-30ms, Hosted vs. Dedicated Connections). <br> - **ELB**: Understand AWS-managed load balancing to distribute traffic (HTTP, HTTPS, TCP, SSL) to EC2/Containers, supporting public/private subnets resolved via DNS. | 05/08/2026 | 05/08/2026 | <https://docs.aws.amazon.com/vpc/>, <https://docs.aws.amazon.com/elasticloadbalancing/> |


### Week 3 Achievements:

* **Monday (05/04/2026):** Understood the AWS Support structure, differentiated the three types of support cases (Account/Billing, Service limits, Technical), and recognized Basic plan limitations.
* **Tuesday (05/05/2026):** Mastered the step-by-step case creation workflow, including attachment uploading and initiating a live chat with AWS support even before account activation.
* **Wednesday (05/06/2026):** Learned the 5 case severity levels and their corresponding SLA response times, along with the business-hours rule for Developer plan cases.
* **Thursday (05/07/2026):** Acquired foundational knowledge of Amazon VPC, and differentiated between stateful Security Groups (allow-only) and stateless NACLs (allow/deny).
* **Friday (05/08/2026):** Mastered hybrid network connectivity solutions (Site-to-Site VPN, Client VPN, AWS Direct Connect) and the routing principles of AWS Elastic Load Balancing (ELB).
