Test Report 20: Required Field Validation [PASSED]
Title: Mandatory Field Enforcement Validation
Description:
Verification of SuiteCRM's required field validation across multiple modules.

Test Environment:

Device: 15-inch notebook

OS: Windows 11 Pro 22H2

Browser: Chrome 118.0.5993.118

Resolution: 1366x768

CRM Instance: crm.alunostds.dev.br

Test Account:

User: tester/test123

Role: Standard User

Test Procedure & Results:

1. Contacts Module:

Left "Last Name" field blank

Filled optional fields (phone, email)

Save attempt:
✓ System prevented submission
✓ Highlighted empty field in red
✓ Displayed message: "Last Name is a required field"

2. Accounts Module:

Left "Account Name" field blank

Filled address fields

Save attempt:
✓ Form rejected
✓ Error message: "Please enter Account Name"
✓ Field marked with asterisk (*)

3. Leads Module:

Left "Last Name" and "Lead Source" empty

Filled company information

Save attempt:
✓ Both missing fields highlighted
✓ Message: "2 required fields missing"
✓ Listed specific field names

Validation Metrics:

Response time: <0.5s for validation check

Error display: Consistent across modules

Field marking:

Red border + asterisk

Tooltip on hover

Evidence:

SCR_Contact_Validation.png (2024-05-24 18:15:22)

SCR_Account_Validation.png (2024-05-24 18:16:10)

SCR_Lead_Validation.png (2024-05-24 18:17:05)

Validation_Error_Log.txt

Additional Verification:

Verified:

Client-side validation (instant)

Server-side validation (fallback)

No partial saves attempted

Test Limitations:

Windows environment only

Tested with basic required fields

Standard field configurations
