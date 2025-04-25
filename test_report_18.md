# Test Report 18: Report Export

## Title: Report Export

### Description:
This test evaluates the functionality of exporting reports from SuiteCRM to common formats such as PDF or Excel, ensuring data integrity is maintained during export.

### Objective:
To verify that reports generated in SuiteCRM can be successfully exported to standard formats while maintaining data integrity and formatting.

### What is being tested:
The report export functionality in SuiteCRM.

### Prerequisites:
- A valid user account with permissions to create and export reports.
- Access to the SuiteCRM instance at crm.alunostds.dev.br using a supported browser (Chrome, Firefox, or Edge).
- At least one custom report already created in the system.
- Successfully logged in to the system.

### Test Procedure:
1. Log in to the SuiteCRM system using valid credentials.
2. Navigate to the Reports module.
3. Select an existing report or create a new one.
4. Run the report to generate the data.
5. Locate and click on the export option.
6. Select different export formats to test (if available):
   a. Export to PDF
   b. Export to Excel/CSV
   c. Export to any other available formats
7. Download each exported file.
8. Open each exported file using the appropriate application.
9. Verify that all data from the original report is present in the exported file.
10. Verify that formatting is maintained appropriately for each format.

### Expected Result:
The system should successfully export the report to each selected format, maintaining all data integrity. The exported files should be downloadable, openable in appropriate applications, and should contain all the data from the original report with appropriate formatting for the selected format.

### Actual Result:
[A ser preenchido após a execução do teste]

### Result Analysis:
The test is successful if reports can be exported to all available formats with complete data integrity and appropriate formatting maintained.

### Error Description (if applicable):
[A ser preenchido se o teste falhar]

### Evidence:
- Screenshot of the report before export.
- Screenshot of the export options/process.
- Screenshots of the exported files opened in appropriate applications.
- System specifications: [Sistema operacional], [Navegador e versão], Screen Resolution [resolução]
