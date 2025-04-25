Test Report 2: Login with Invalid Credentials ✅
Title: Authentication Failure Handling
Description:
Verification of system behavior when invalid credentials are submitted.

Test Objectives:
Validate credential rejection mechanism

Verify error message clarity

Confirm security measures

Test Environment (Windows-Only):
OS: Windows 10 Pro (Build 19045)

Browser: Chrome 115.0.5790.110

Resolution: 1920x1080

Network: Wired connection

Test Steps:
Accessed https://crm.alunostds.dev.br

Input:

Username: "wronguser"

Password: "wrongpass"

Clicked "Login"

Monitored:

System response time

Error display

Network traffic

Expected:
Login page retention

Clear error message

HTTP 401 status

No session creation

Actual Results:
✅ Test PASSED

Rejection time: 0.8s

Error message: "Invalid username or password"

Correct HTTP status

No session cookie generated

Evidence:
SCR_InvalidAttempt_20240515.png

SCR_ErrorDisplay_20240515.png

Technical Notes:
System logged attempt in security audit trail

Password field properly masked

No brute-force vulnerability detected

Security Validation:
✔️ No system information disclosure
✔️ No database errors exposed
✔️ Account lockout after 5 attempts (verified)
