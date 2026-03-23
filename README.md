

### Jira

> **Jira** is a project management and issue-tracking tool developed by Atlassian. It is widely used by teams to plan, track, and manage work, especially in Agile environments such as Scrum and Kanban.

Jira helps teams organize tasks, assign responsibilities, track progress, automate workflows, and gain insights through dashboards and reports. It is commonly used by developers, project managers, and business teams to collaborate efficiently and deliver projects on time.

![Pasted image 20260321173909.png](images/Pasted%20image%2020260321173909.png)
Figure 01 : Showing Sample Space

Notes : 
> In Jira, spaces act as individual projects where all tasks, workflows, and team collaboration take place. Each space is designed to organize work efficiently for a specific team or objective.

Spaces allow teams to manage their work in a structured way, and multiple users can collaborate within the same space. Team members can be invited and assigned different roles based on their responsibilities.

![Pasted image 20260321174819.png](images/Pasted%20image%2020260321174819.png)
Figure 02: Showing Invite members page
## Board

> Boards provide a visual representation of all tasks in a project, making it easier to track progress and manage workload.

Boards are commonly used in Agile methodologies such as Scrum or Kanban. They allow users to create tasks, move them between stages (e.g., To Do, In Progress, Done), and monitor overall progress in real time. Boards improve visibility and help teams stay aligned on current work.

![Pasted image 20260321175412.png](images/Pasted%20image%2020260321175412.png)
Figure 03 : Showing board
## Workflow

Workflows define how a task progresses through different stages from creation to completion. They represent the lifecycle of work items and ensure that processes are consistent across the team.

![Pasted image 20260321175738.png](images/Pasted%20image%2020260321175738.png)
Figure 04: Showing sample workflow

![Pasted image 20260321181921.png](images/Pasted%20image%2020260321181921.png)
Figure  05: Showing Sample Workflow

> The “Any” option in a workflow means that any team member within the space can transition a task to that status without restrictions, providing flexibility in task management.

Workflows can be customized depending on project needs, and tasks can also be moved across different boards if required.

## Managing WorkType

Work types define the nature of tasks, such as bugs, features, or general tasks. They help categorize work and make it easier to organize, filter, and report on different types of activities within a project.

![Pasted image 20260321190235.png](images/Pasted%20image%2020260321190235.png)

Figure 06: Showing Work Type Management
### Deleting WorkType

![Pasted image 20260321190355.png](images/Pasted%20image%2020260321190355.png)
Figure 07: Showing Delete Work Type Option

![Pasted image 20260321190552.png](images/Pasted%20image%2020260321190552.png)
Figure 08 : Displaying Workflow Editor 

Work types that are no longer relevant can be removed to keep the project clean and organized. Jira also allows the creation of custom fields to capture additional information specific to a project, improving data tracking and reporting.

![Pasted image 20260321191006.png](images/Pasted%20image%2020260321191006.png)  
Figure 09: Showing Custom Field Creation

**Creating WorkType**
1. Navigate to "Add Work Type", choose a logo and add work-type name.
2. Add description if needed and click on "Create".

![Pasted image 20260321191318.png](images/Pasted%20image%2020260321191318.png)  
*Figure 10: Showing Work Type Creation Page*

![Pasted image 20260321191327.png](images/Pasted%20image%2020260321191327.png)  
Figure 11: Showing Business Request Creation

Certain fields, such as “People,” can be marked as required to ensure that critical information is always provided when creating tasks. 

![Pasted image 20260321192440.png](images/Pasted%20image%2020260321192440.png)
Figure 12: Showing Required Field Configuration
### Creating Tasks and Business Requests

> Tasks represent individual units of work and can be created either directly from spaces or through boards.

Each task can include detailed descriptions, attachments, comments, and assigned users, making it a central place for collaboration and tracking.

![Pasted image 20260322174803.png](images/Pasted%20image%2020260322174803.png)
Figure 13: Showing Task Details View

**Creating Business Requests**

Business requests are typically used to capture structured requests from users or stakeholders, ensuring proper tracking and handling.

![Pasted image 20260322175140.png](images/Pasted%20image%2020260322175140.png)
Figure 14: Showing Business Request Creation

Tasks can be broken down further into subtasks, allowing teams to divide complex work into smaller, manageable pieces. Smaller tasks can also be created under the subtask by navigating on the Task > Create Sub task.

![Pasted image 20260322175411.png](images/Pasted%20image%2020260322175411.png)
Figure 15: Showing Subtask Creation

**Task Creation with Atlassian Intelligence**
Atlassian Intelligence introduces AI-powered assistance to simplify task creation and improve productivity.

1. Navigate to the task description field.
2. Type `/ai`, enter a prompt, and press Enter to generate content automatically.

![Pasted image 20260322181712.png](images/Pasted%20image%2020260322181712.png)
Figure 16: Showing Atlassian Intelligence Prompt

![Pasted image 20260322181902.png](images/Pasted%20image%2020260322181902.png)  
Figure 17: Showing AI Generated Task Content

Additionally, Rovo can be used to summarize comments within tasks, helping users quickly understand discussions without reading everything manually.

**Inviting Users**
Users can be added to a space to collaborate on tasks and projects.

1. Navigate to Spaces → Space Settings → Access.
2. Click “Add people” and invite users by assigning appropriate roles.

![[Pasted image 20260323115056.png]]    
Figure 18: Showing Invite Users Page

![Pasted image 20260322182458.png](images/Pasted%20image%2020260322182458.png)                       
Figure 19: Showing User Role Assignment

Roles in Jira can be customized to control permissions, ensuring that users have the correct level of access based on their responsibilities.

![Pasted image 20260322182724.png](images/Pasted%20image%2020260322182724.png)  
Figure 20: Showing Role Customization

The filter by assignee allows user to view who is assigned to specific task in jira.

![Pasted image 20260322183111.png](images/Pasted%20image%2020260322183111.png)

Figure 21: Showing Filter by Assignee
### Automating Work in Jira
Automation in Jira helps reduce repetitive manual work by automatically performing actions based on predefined triggers and conditions. This improves efficiency and ensures consistency in workflows.

![Pasted image 20260322183415.png](images/Pasted%20image%2020260322183415.png)
Figure 22: Showing Automation Type in Jira

Automation rules can be created using pre-built templates, AI assistance, or from scratch, depending on the level of customization required.

![Pasted image 20260322183915.png](images/Pasted%20image%2020260322183915.png)
Figure 23: Showing Automation Rule Options

**Creating automation template in Jira**
![[Pasted image 20260323103512.png]]
Figure 24: Showing Automation Template Selection

1. Click on the trigger template box and select the from and to status.
![[Pasted image 20260323104003.png]]
Figure 25: Showing Automation Trigger Setup

2. Select what happens next when the item is transitioned to whom the work is assigned and and click on next. In this example we are choosing "User in a defined list".
![[Pasted image 20260323104213.png]]
Figure 26: Showing Automation Action Configuration

3. Select the user and "Click on next". We can also add a component in the pre-existing template.

**Creating automation from scratch:**

![[Pasted image 20260323104810.png]]
Figure 27: Showing Create Automation from Scratch

1. Click on Create from scratch and add a trigger.

![[Pasted image 20260323104910.png]]

2. Define the transition between statuses.
![[Pasted image 20260323104932.png]]
Figure 28: Showing Automation Trigger Definition
3. Add a condition, for the example we are using work item field condition and set the field to priority level , set condition as "is one of" and add value High/Critical.
 ![[Pasted image 20260323105121.png]]
4. Add a component and click on assign work item and specify the manager/project manager.
5. Click on Turn on rule to activate the rule.


**Creating a Automation with Rovo**

1. Go to automation from the space settings and add a prompt to the Rovo.
![[Pasted image 20260323105600.png]]
Figure 29: Showing Rovo Automation Prompt
2. Review the automation rule.
![[Pasted image 20260323105745.png]]
Figure 30: Showing Generated Automation Rule

We can review the audit log of the automation that ran from the "Audit log tab".


**Jira Dashboards**
A **dashboard** is a centralized interface that presents key metrics, data, and activities in an organized and visual way, helping users track, analyze, and manage their work efficiently.

![[Pasted image 20260323111140.png]]
Figure 31: Showing Jira Dashboard Overview

![[Pasted image 20260323111317.png]]
Figure 32: Showing Dashboard Widgets