# Test Report 14: Task Creation

## Title: Task Creation

### Description:
This test evaluates the functionality of creating new tasks within the SuiteCRM system, verifying that all required fields can be properly filled and the task is correctly stored.

### Objective:
To ensure that the Tasks module allows users to successfully create new task records with all necessary information properly stored in the system.

### What is being tested:
The task creation functionality in the SuiteCRM Tasks module.

### Prerequisites:
- A valid user account with permissions to create tasks.
- Access to the SuiteCRM instance at crm.alunostds.dev.br using a supported browser (Chrome, Firefox, or Edge).
- Successfully logged in to the system.

### Test Procedure:
1. Log in to the SuiteCRM system using valid credentials.
2. Navigate to the Tasks module by clicking on "Tasks" in the navigation menu.
3. Click on the "Create Task" button.
4. Fill in the required fields:
   a. Subject: [Test Task Subject]
   b. Status: (select from dropdown, e.g., "Not Started")
   c. Priority: (select from dropdown, e.g., "High")
   d. Due date: (select a future date)
   e. Description: [Test task description]
5. Fill in any additional optional fields as needed.
6. Click the "Save" button.
7. Verify that the system redirects to the task detail view.

### Expected Result:
The system should successfully create the new task record, store all entered information correctly, and redirect to the task detail view showing all the information that was entered.

### Actual Result:
[A ser preenchido após a execução do teste]

### Result Analysis:
The test is successful if the task is created without errors and all entered information is correctly displayed in the task detail view.

### Error Description (if applicable):
[A ser preenchido se o teste falhar]

### Evidence:
- Screenshot of the task creation form with filled information.
- Screenshot of the task detail view after successful creation.
- System specifications: [Sistema operacional], [Navegador e versão], Screen Resolution [resolução]
