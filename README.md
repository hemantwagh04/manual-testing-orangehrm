Manual Testing Project — OrangeHRM HRMS Application

🎯 Project Overview
This repository contains a complete Manual Testing project for the
OrangeHRM Human Resource Management System (HRMS) demo web application.
All testing was performed manually covering functional, negative,
boundary and UI test scenarios.

Application Under Test:** https://opensource-demo.orangehrmlive.com
Tester: Hemant Wagh
Testing Period:April 2026
Testing Type: Manual Functional Testing

---

📁 Repository Structure

| Folder | Contents |
|---|---|
| 01-Test-Plan | Test Plan document — scope, approach, entry/exit criteria |
| 02-Test-Cases | 45 test cases across Login, PIM and Leave modules |
| 03-Bug-Reports | 5 bug reports with screenshots |
| 04-RTM | Requirement Traceability Matrix — 100% coverage |
| 05-Test-Summary-Report | Final test summary with recommendations |

---

📋 Modules Tested

- Login Module — Valid/Invalid login, session management, field validation
- PIM Module — Add/Edit/Delete Employee, photo upload, search, field validation
- Leave Module — Leave List, filtering, Leave Entitlement, access control

---

📊 Test Execution Summary

| Module | Total TCs | Passed | Failed | Pass % |
|---|---|---|---|---|
| Login | 15 | 13 | 2 | 86.67% |
| PIM | 15 | 13 | 2 | 86.67% |
| Leave | 15 | 14 | 1 | 93.33% |
| Total | 45| 40 | 5 | 88.89% |

---

🐛 Bugs Found

| Bug ID | Module | Summary | Severity | Priority |
|---|---|---|---|---|
| BUG001 | Login | Username case sensitivity not enforced | Major | Medium |
| BUG002 | Login | Back button after logout returns to Dashboard | Major | High |
| BUG003 | PIM | First Name accepts numeric characters | Major | Medium |
| BUG004 | PIM | First Name accepts special characters | Major | Medium |
| BUG005 | Leave | Leave Type dropdown missing some types | Major | Medium |

---

🛠️ Tools Used

- JIRA — Bug tracking and test management
- Google Sheets — Test case and RTM documentation
- Google Docs — Test Plan and Test Summary Report
- Chrome DevTools — Browser inspection
- GitHub — Version control and project showcase

---

🔍 Test Environment

- Browser: Google Chrome (Latest)
- OS: Windows 11
- Application URL: https://opensource-demo.orangehrmlive.com

---

👤 About Me

Hemant Wagh — Aspiring QA Engineer
- 📧 contact.hemantwagh@gmail.com
- 💼 linkedin.com/in/hemantwagh04
- 🎓 B.E. Computer Engineering — G.E.S. R.H. Sapat College, Nashik (2026)
