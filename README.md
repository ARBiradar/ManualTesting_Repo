Guru99 Login Application – Manual & Security Testing Report
This repository contains a comprehensive manual and security testing report for the Guru99 Login Application. The objective is to validate core login functionality and assess the application’s security posture through structured test scenarios and documented findings.

📋 Project Overview
Application Under Test: Guru99 Login Page

Testing Types: Functional, UI, and Security Testing

Environment: Chrome, Firefox, Edge

Tools Used:

Excel/Google Sheets (Test Case Tracking)

Burp Suite / Browser DevTools

Screenshot Tool

✅ Scope of Testing
In Scope:

Login functionality

Error message handling

Session management

Password masking

Security checks (XSS, SQL Injection, Broken Authentication)

Browser navigation behavior

Out of Scope:

Backend database verification

API-level security

Load and stress testing

🧪 Test Artifacts
Test Scenarios: 20 (Functional + Security)

Test Cases: 40 total

Bug Reports: 7 open issues (Critical, Major, Medium, Minor)

Test Summary:

Duration: 2 days

Passed: 28

Failed: 12

Blocked: 0

🐞 Key Findings
SQL Injection vulnerability in login fields

XSS input not sanitized

Session does not expire on inactivity

Browser back button allows unauthorized access post-logout

Password autocomplete enabled

Error messages expose internal details

Application served over HTTP (no HTTPS)

📌 Conclusion
The application is not secure for production until all critical and major vulnerabilities are resolved. This report provides actionable insights to improve the security and reliability of the login system.
