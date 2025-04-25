# Test Report 20: Required Field Validation

## Title: Required Field Validation

### Description:
This test evaluates the system's validation of required fields, ensuring that records cannot be saved when mandatory fields are left empty.

### Objective:
To verify that the system properly enforces required field validation and displays appropriate error messages when mandatory fields are not filled.

### What is being tested:
The form validation mechanism for required fields in SuiteCRM.

### Prerequisites:
- A valid user account with permissions to create records.
- Access to the SuiteCRM instance at crm.alunostds.dev.br using a supported browser (Chrome, Firefox, or Edge).
- Successfully logged in to the system.

### Test Procedure:
1. Log in to the SuiteCRM system using valid credentials.
2. Navigate to the Contacts module.
3. Click on "Create Contact" to open the new contact form.
4. Leave known required fields blank (e.g., Last Name is typically required in CRM systems).
5. Fill in some optional fields.
6. Click the "Save" button.
7. Observe the system's response and any error messages.
8. Repeat the test with other modules (e.g., Accounts, Leads) to verify consistent behavior.

### Expected Result:
The system should prevent the form from being submitted when required fields are empty. It should display clear error messages indicating which fields are required and need to be filled before the record can be saved.

### Actual Result:
[A ser preenchido após a execução do teste]

### Result Analysis:
The test is successful if the system correctly prevents saving records with empty required fields and displays appropriate error messages that clearly identify which fields need to be filled.

### Error Description (if applicable):
[A ser preenchido se o teste falhar]

### Evidence:
- Screenshot of the form with empty required fields.
- Screenshot of the error messages displayed after attempting to save.
- Screenshots of similar tests in other modules.
- System specifications: [Sistema operacional], [Navegador e versão], Screen Resolution [resolução]
