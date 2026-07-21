---
title: "Week 4 Worklog"
date: 2026-05-11
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---
### Week 4 Objectives:

* Understand the core concepts of Amazon Elastic Compute Cloud (EC2) virtual servers.
* Master auxiliary components: AMI, EBS, Instance Store, User Data, and Metadata.
* Grasp the mechanics of Auto Scaling and its integration with Load Balancers for high availability.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | **Overview of Amazon EC2** <br> - Learn the concepts of EC2 virtual servers, resource flexibility, and scalability. <br> - Study real-world use cases (web hosting, database servers, authentication services). <br> - Understand how to select appropriate Instance Types based on CPU architectures (Intel, AMD, Graviton), Memory, Network, and Storage requirements. | 05/11/2026 | 05/11/2026 | <https://docs.aws.amazon.com/ec2/> |
| 3 | **AMIs, Backups, and Key Pairs** <br> - Learn how to use AMIs to provision uniform instances pre-configured with operating systems and applications. <br> - Understand backup workflows using EBS snapshots. <br> - Study security Key Pairs (public key on AWS, private key on local machine) for secure SSH access. | 05/12/2026 | 05/12/2026 | <https://docs.aws.amazon.com/ec2/> |
| 4 | **Block-level Storage with Amazon EBS** <br> - Differentiate SSD and HDD block storage options directly attached to EC2 instances. <br> - Understand high-availability design (99.999% SLA) achieved by replicating data across storage nodes in the same Availability Zone (AZ). <br> - Analyze the decoupled network architecture of EBS from EC2. | 05/13/2026 | 05/13/2026 | <https://docs.aws.amazon.com/ebs/> |
| 5 | **Temporary Storage (Instance Store) & Bootstrapping Concepts with User Data** <br> - Explore ephemeral storage with Instance Store (NVMe-based disk on physical hosting node) for extreme IOPS workloads that lose data upon stopping instances. <br> - Learn the concepts of EC2 User Data scripting (bash shell or PowerShell) run once during initial boot, and understand how to check it via the Link-Local IP address at `http://169.254.169.254/latest/user-data`. | 05/14/2026 | 05/14/2026 | <https://docs.aws.amazon.com/ec2/> |
| 6 | **EC2 Metadata Theory & Auto Scaling** <br> - Understand the theory of EC2 Metadata: how instance-specific configuration details (IPs, Hostname, SGs) are retrieved via the Link-Local endpoint at `http://169.254.169.254/latest/meta-data/`. <br> - Learn EC2 Auto Scaling: setting up Auto Scaling Groups (ASGs), scaling policies, Load Balancer integrations, and multi-AZ deployment. | 05/15/2026 | 05/15/2026 | <https://docs.aws.amazon.com/autoscaling/> |


### Week 4 Achievements:

* **Monday (05/11/2026):** Differentiated EC2 instance types and selected the optimal configuration based on hardware requirements.
* **Tuesday (05/12/2026):** Understood the AMI provisioning flow, EBS snapshot backup procedures, and secure SSH key pair authentication.
* **Wednesday (05/13/2026):** Mastered independent EBS network architecture and data replication within the Availability Zone.
* **Thursday (05/14/2026):** Contrasted EBS and Instance Store storage behaviors, and understood the concept of using User Data via Link-Local IP `169.254.169.254` to bootstrap servers.
* **Friday (05/15/2026):** Understood how to retrieve instance configuration details via the Link-Local Metadata endpoint, and grasped the coordination of Auto Scaling Groups with Elastic Load Balancing.
