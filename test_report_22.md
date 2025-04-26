Test Report 22: System Logs and Audit Verification [FAILED]
Title: Audit Trail Functionality Validation
Description:
Verification of SuiteCRM's ability to record and display user actions for security auditing purposes.

Test Environment:

Device: 15-inch notebook

OS: Windows 11 Pro 22H2

Browser: Chrome 118.0.5993.118

Resolution: 1366x768

CRM Instance: crm.alunostds.dev.br

Test Accounts:

Admin: admin/admin123

Standard User: user1/user123

Performed Actions:

Created contact "Carlos Mendes" (ID: CT-2150)

Modified account "Acme Corp" (ID: ACC-3012)

Deleted task "Follow-up" (ID: TSK-8925)

Performed login/logout cycles

Expected Log Entries:

Contact creation with field-level changes

Account modification with before/after values

Task deletion with metadata

Login timestamps

Actual Results:

Missing Data:

No field-level changes recorded for account modification

Deleted task metadata incomplete

Inconsistent Timestamps:

Login events showed UTC time instead of local timezone

Action times had 2-3 minute discrepancies

System Errors:

Audit log search failed with >500 results

"Export Logs" function timed out

Security Gaps:

Standard users could access some admin audit functions

No IP address recording

Error Analysis:
Root Cause:

Database schema limitations for change tracking

Timezone configuration mismatch

Missing permission checks on audit UI

Evidence:

SCR_Missing_Field_Logs.png (2024-05-24 19:05:15)

SCR_Failed_Log_Search.png (2024-05-24 19:07:30)

SCR_Timezone_Discrepancy.png (2024-05-24 19:08:45)

Error_Logs.txt

Recommended Actions:

Database schema update for:

Complete change capture

Proper metadata storage

Configuration fixes for:

Timezone handling

Permission controls

UI improvements for:

Large dataset handling

Export functionality

Workarounds:

Manual database queries for critical audits

Third-party logging extensions

Test Limitations:

Windows environment only

Basic CRUD operations tested

Limited stress testing
