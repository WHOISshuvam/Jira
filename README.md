

### Jira


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

### Deleting WorkType

![Pasted image 20260321190355.png](images/Pasted%20image%2020260321190355.png)

![Pasted image 20260321190552.png](images/Pasted%20image%2020260321190552.png)

Work types that are no longer relevant can be removed to keep the project clean and organized. Jira also allows the creation of custom fields to capture additional information specific to a project, improving data tracking and reporting.

![Pasted image 20260321191006.png](images/Pasted%20image%2020260321191006.png)


**Creating WorkType**
1. Navigate to "Add Work Type", choose a logo and add work-type name.
2. Add description if needed and click on "Create".

![Pasted image 20260321191318.png](images/Pasted%20image%2020260321191318.png)

![Pasted image 20260321191327.png](images/Pasted%20image%2020260321191327.png)

Certain fields, such as “People,” can be marked as required to ensure that critical information is always provided when creating tasks. 

![Pasted image 20260321192440.png](images/Pasted%20image%2020260321192440.png)

### Creating Tasks and Business Requests

> Tasks represent individual units of work and can be created either directly from spaces or through boards.

Each task can include detailed descriptions, attachments, comments, and assigned users, making it a central place for collaboration and tracking.

![Pasted image 20260322174803.png](images/Pasted%20image%2020260322174803.png)

Creating Business Requests



![Pasted image 20260322175140.png](images/Pasted%20image%2020260322175140.png)

Smaller tasks can also be created under the subtask by navigating on the Task > Create Sub task.

![Pasted image 20260322175411.png](images/Pasted%20image%2020260322175411.png)

**Task Creation with Atlassian Intelligence**
1. Go to the task description and enter /ai and enter the prompt and hit enter.
![Pasted image 20260322181712.png](images/Pasted%20image%2020260322181712.png)


![Pasted image 20260322181902.png](images/Pasted%20image%2020260322181902.png)

We can also summarize the comments in teask using Rovo.

**Inviting Users**

1. Go to Spaces > Space Settings > Access.
2. Click on Add people and add the user.
![Pasted image 20260322182359.png](images/Pasted%20image%2020260322182359.png)

![Pasted image 20260322182458.png](images/Pasted%20image%2020260322182458.png)

Users can also customize the roles in Jira.

![Pasted image 20260322182724.png](images/Pasted%20image%2020260322182724.png)

The filter by assignee allows user to view who is assigned to specific task in jira.

![Pasted image 20260322183111.png](images/Pasted%20image%2020260322183111.png)

### Automating Work in Jira
Automation in jira helps to reduce manual tasks by automatically performing the action.

![Pasted image 20260322183415.png](images/Pasted%20image%2020260322183415.png)


Rule can be created in 3 ways in Jira - via templates, "Create with AI" or via "Create rule".

![Pasted image 20260322183915.png](images/Pasted%20image%2020260322183915.png)

**Creating automation template in Jira**

![[Pasted image 20260323103512.png]]

1. Click on the trigger template box and select the from and to status.
![[Pasted image 20260323104003.png]]

2. Select what happens next when the item is transitioned to whom the work is assigned and and click on next. In this example we are choosing "User in a defined list".
![[Pasted image 20260323104213.png]]

3. Select the user and "Click on next". We can also add a component in the pre-existing template.


Creating automation from scratch:

![[Pasted image 20260323104810.png]]

1. Click on Create from scratch and add a trigger.

![[Pasted image 20260323104910.png]]

2. Select the from and to status.
![[Pasted image 20260323104932.png]]

3. Add a condition, for the example we are using work item field condition and set the field to priority level , set condition as "is one of" and add value High/Critical.
 ![[Pasted image 20260323105121.png]]

4. Add a component and click on assign work item and specify the manager/project manager.
5. Click on Turn on rule to activate the rule.


**Creating a Automation with Rovo**

1. Go to automation from the space settings and add a prompt to the Rovo.
![[Pasted image 20260323105600.png]]

2. Review the automation rule.
![[Pasted image 20260323105745.png]]

We can review the audit log of the automation that ran from the "Audit log tab".


**Jira Dashboards**
A **dashboard** is a centralized interface that presents key metrics, data, and activities in an organized and visual way, helping users track, analyze, and manage their work efficiently.

![[Pasted image 20260323111140.png]]

![[Pasted image 20260323111317.png]]

