# Test Report 15: Task Assignment

## Title: Task Assignment

### Description:
This test evaluates the functionality of assigning tasks to specific users in the SuiteCRM system and verifies that the assignment notifications work correctly.

### Objective:
To ensure that tasks can be properly assigned to users and that the system generates appropriate notifications for task assignments.

### What is being tested:
The task assignment functionality and notification system in the SuiteCRM Tasks module.

### Prerequisites:
- A valid admin account with permissions to assign tasks.
- At least one standard user account to receive task assignments.
- Access to the SuiteCRM instance at crm.alunostds.dev.br using a supported browser (Chrome, Firefox, or Edge).
- Successfully logged in to the system.

### Test Procedure:
1. Log in to the SuiteCRM system using admin credentials.
2. Navigate to the Tasks module by clicking on "Tasks" in the navigation menu.
3. Create a new task or select an existing task.
4. Assign the task to a specific user:
   a. If creating a new task, select the user in the "Assigned To" field.
   b. If editing an existing task, change the "Assigned To" field to the target user.
5. Save the task.
6. Log out from the admin account.
7. Log in as the user to whom the task was assigned.
8. Check for notifications about the task assignment.
9. Navigate to the Tasks module and verify that the assigned task appears in the user's task list.

### Expected Result:
The system should successfully assign the task to the specified user, generate a notification about the assignment, and the task should appear in the assigned user's task list when they log in.

### Actual Result:
[A ser preenchido após a execução do teste]

### Result Analysis:
The test is successful if the task is properly assigned to the specified user, a notification is generated, and the task appears in the user's task list.

### Error Description (if applicable):
[A ser preenchido se o teste falhar]

### Evidence:
- Screenshot of the task assignment process.
- Screenshot of the saved task showing the assigned user.
- Screenshot of the notification received by the assigned user.
- Screenshot of the assigned user's task list showing the assigned task.
- System specifications: [Sistema operacional], [Navegador e versão], Screen Resolution [resolução]
