  
---
name: Kanban Story
about: Collect data to help the next person or step in the process
title: Backlog
labels: Backlog
assignees: ''

---

## Basic Story Card
### Capture Details and Information Needed for the Next Action.
* The goal is to empower the next person working on this card and remove as much friction as possible, by providing the information or links needed to take action, they should be able to do their work without seeking information.
Who, What, When, Where, & Why

- [ ] **Who?**
  - Who or what entity like an internal team or client needs this story.

- [ ] **What?**
  - What is needed, define the requirements.

- [ ] **When?**
  - When is it needed, define the schedule.

- [ ] **Where?**
  - Where will the output of this work be used? In what part of the application ecosystem will the change be applied.

- [ ] **Why?**
  - Why do we need to do this work.

- [ ] **Related?**
  - Any related details, issues, prs, projects, deliverables, etc.


## Prioritization via Kanban
Kanban Terms for Reference:
[Kanban](https://kanbanzone.com/resources/kanban)


  - **Cost of Delay**
    > - Cost of Delay combines urgency and value – two things that are not very easy to distinguishing between. To make decisions, we need to understand not just how valuable something is, but how urgent it is.
    > - https://kanbanize.com/kanban-resources/getting-started/kanban-encyclopedia

  How important and valuable is this work?
  - This helps the team determine the value of this story over time, it may increase or decrease.
    > * Delaying the release of a version of your software which is aimed at giving you a competitive advantage will have a high cost of delay.
    > * Not being able to immediately release a solution to a critical production issue entails a high cost of delay.

- **Cost of Service** is the effort required to complete this task by the service level assigned. It a cost of percent of persons WIP Limit by categorization of the level of service required.

    > - Kanban classes of service allow you to manage dependencies according to the cost of delay (CoD) for each project. CoD is the economic impact of failing to deliver your product or service on time or, simply said – the amount of money you will lose by delaying the delivery. By calculating CoD, you can understand the importance of delivering your projects on time.
    > - The logic is simple. When the cost of delay is small, or there’s enough time to start early, there’s no need to manage dependencies explicitly. You can just let them emerge and manage them dynamically.
    > - However, when the CoD is high, you need to plan your capacity in a way that will allow you to start early and complete the project with greater efficiency, even if it results in delaying other projects with lower costs of delay.
    > - https://kanbanize.com/kanban-resources/getting-started/kanban-classes-of-service

    - Expedited
      - Represents an immediate need due to the extremely high CoD to the business.
      - Is not counted against a WIP Limit, this will overburden the schedule.
      - The goal is to expose these ad hoc issues and remove them from processes.
      - These should be anomalies as they block all other service levels.

    - Fixed Delivery Date
      - Significant economic impact to the business.
      - Must be done on or before schedule.

    - Standard
      - Normal Cadence for Software Delivery by planned milestones and sprint cycle.

    - Intangible
      - Chores, no rush to complete, but should also be reviewed for Toil tasks and automation.

-  **WIP & WIP Limits**
    > - The acronym WIP stands for Work In Progress. WIP is the number of task items that a team is currently working on. It frames the capacity of your team's workflow at any moment. Limiting work in progress is one of the core properties of Kanban. It allows you to manage your process in a way that creates a smooth workflow and prevents overloads.
    > - https://kanbanize.com/kanban-resources/getting-started/what-is-wip
   - WIP
        - WIP or Work In Progress is the amount of work being started, regardless of the subcolumn it is currently in.

   - WIP Limits
        - Setting limits on the work in progress is a strategy to avoid overworking and context switching while focusing on the important things. Applying WIP limits is the second core practice in Kanban and ensures a healthy flow.


#### Cost of Service and Cost of Delivery should be used to determine the risk to the business.

- [ ] **Cost of Delay?**


- [ ] **Cost of Service?**
