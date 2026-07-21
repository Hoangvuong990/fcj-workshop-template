---
title: "Week 2 Worklog"
date: 2026-04-27
weight: 2
chapter: false
pre: " <b> 1.2. </b> "
---
### Week 2 Objectives:

* Understand how to use AWS Cost Management to manage costs and resources.
* Master different budget types (Cost, Usage, Reservation, Savings Plans) and configure automated email/SNS alerts.
* Practice creating, monitoring, and cleaning up cloud budgets.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | **Accessing Billing & Exploring AWS Budgets** <br> - Access AWS Management Console, navigate to Billing. <br> - Learn how to create budgets from available templates (Cost budget, Usage budget, RI budget, Savings Plans budget). <br> - Create a new Cost Budget: set budget name, period (monthly, quarterly, annually), starting month, choose budgeting method (fixed or auto-adjusting), and input the desired budget amount. | 04/27/2026 | 04/27/2026      | <https://docs.aws.amazon.com/cost-management/> |
| 3   | **Configuring Cost Budget Alerts & Creating Usage Budgets** <br> - Set up alert thresholds for Cost Budget (based on actual or forecasted cost) and threshold percentage (% of budgeted amount). <br> - Configure email or Amazon SNS notifications when thresholds are exceeded. <br> - Create a Usage Budget: define resource or service usage to track (e.g. EC2 running hours, Data transfer), set allowed usage amount, and set alert thresholds. | 04/28/2026 | 04/28/2026      | <https://docs.aws.amazon.com/cost-management/> |
| 4   | **Understanding and Creating Reservation Budgets (RI Budgets)** <br> - Differentiate and determine saving goals using Reserved Instances (RIs). <br> - Establish budgets to monitor the utilization or coverage of Reserved Instances. <br> - Configure alerts if utilization or coverage falls below expected levels. | 04/29/2026 | 04/29/2026      | <https://docs.aws.amazon.com/cost-management/> |
| 5   | **Understanding and Creating Savings Plans Budgets** <br> - Establish budgets to track the utilization or coverage of Savings Plans. <br> - Similarly to RI budgets, configure alerts when these metrics fail to meet requirements. | 04/30/2026 | 04/30/2026      | <https://docs.aws.amazon.com/cost-management/> |
| 6   | **Managing and Cleaning Up Unused Budgets** <br> - Learn how to manage, evaluate, and edit existing Budgets. <br> - Practice infrastructure cleanup: select unused budgets and confirm their deletion to maintain a clean dashboard. | 05/01/2026 | 05/01/2026      | <https://docs.aws.amazon.com/cost-management/> |


### Week 2 Achievements:

* **Monday (04/27/2026):**
  * Mastered navigation of the Billing & Cost Management interface in the AWS Management Console.
  * Acquired a clear understanding of the 4 budget templates: Cost, Usage, RI, and Savings Plans budgets.
  * Created the first Cost Budget with customized billing periods, start months, and fixed/auto-adjusting budgeting methods.
* **Tuesday (04/28/2026):**
  * Gained proficiency in setting alert thresholds based on both actual and forecasted costs.
  * Configured automatic email notifications for budget threshold crossings.
  * Created a Usage Budget to monitor resource metrics, such as EC2 running hours and data transfer limits.
* **Wednesday (04/29/2026):**
  * Understood the concept of Reserved Instances (RIs) and set up Reservation Budgets for cost optimization.
  * Learned to monitor RI utilization and coverage to ensure maximum savings and minimal wastage.
* **Thursday (04/30/2026):**
  * Grasped Savings Plans mechanics and configured a Savings Plans Budget.
  * Configured proactive alerts for when Savings Plans utilization or coverage falls below targeted thresholds.
* **Friday (05/01/2026):**
  * Learned how to manage, edit, and evaluate existing cloud budgets.
  * Practiced resource hygiene by clean-deleting unused test budgets from the AWS console.

