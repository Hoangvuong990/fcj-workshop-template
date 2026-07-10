---
title: "Week 9 Worklog"
date: 2026-06-15
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---
### Week 9 Objectives:

* Finalize the user interface (UI) selection flow for all trip planning parameters.
* Integrate the Frontend application with the actual AWS API Gateway endpoints deployed by Backend/AI.
* Program UX indicators such as loading states and user-friendly error handlers.
* Perform cross-team code reviews to ensure clean repository consolidation.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| 2 | **API Integration Preparation** <br> - Fetch the active API Gateway endpoints and verify the JSON response payload. <br> - Write API helper utility functions to handle HTTP requests. | 06/15/2026 | 06/15/2026 | <https://docs.aws.amazon.com/apigateway/> |
| 3 | **Connecting UI Flow to Live APIs** <br> - Code integration logic to trigger API requests when the user submits their choices. <br> - Map and send user choices (interests, transport, budget) to API Gateway. | 06/16/2026 | 06/16/2026 | |
| 4 | **Implementing Loading States & Error Handlers** <br> - Design and code UI loading indicators (skeletons or spin animations) while waiting for AI generation. <br> - Implement try/catch blocks and display custom messages for HTTP errors (400, 500). | 06/17/2026 | 06/17/2026 | |
| 5 | **Cross-Team Code Reviews** <br> - Conduct the weekly review session with Backend and AI developers to audit codebase compatibility. <br> - Refactor Frontend code based on peer feedback to align with guidelines. | 06/18/2026 | 06/18/2026 | |
| 6 | **Interaction Flow Optimization** <br> - Verify end-to-end local behavior from Cognito login, parameter selection, data submission, to receiving raw responses. <br> - Verify that server responses are stored correctly in the Frontend state. | 06/19/2026 | 06/19/2026 | |


### Week 9 Achievements:

* **Monday (06/15/2026):** Developed HTTP helper functions for smooth communication with the backend API Gateway.
* **Tuesday (06/16/2026):** Integrated the live API for the parameters selection flow, successfully transmitting inputs in JSON.
* **Wednesday (06/17/2026):** Implemented loading skeletons and custom error displays to guide the user in case of connection failures.
* **Thursday (06/18/2026):** Completed the code review meeting and refactored API fetch code to improve repository maintenance.
* **Friday (06/19/2026):** Tested and verified authentication, parameter submission, and raw payload caching in local storage.
