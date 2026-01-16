# 🔐 Guru99 Login Application – Manual & Security Testing Report

This repository contains a **comprehensive Manual and Security Testing report** for the **Guru99 Login Application**.  
The goal of this project is to validate the **functional behavior**, **usability**, and **security posture** of the login module through structured test scenarios and documented findings.

This project reflects **real-world QA and security testing practices** and is suitable for portfolios, interviews, and academic submissions.

---

## 📋 Project Overview

- **Application Under Test (AUT):** Guru99 Login Page  
- **Module Tested:** Login / Authentication  
- **Testing Approach:** Black-box testing  
- **Testing Type:** Manual Testing  

### 🎯 Objectives
- Verify correct login functionality with valid and invalid inputs  
- Validate UI behavior and error message handling  
- Identify security vulnerabilities in authentication flow  
- Analyze session handling and browser navigation behavior  

---

## 🧪 Types of Testing Performed

### ✅ Functional Testing
- Valid and invalid login scenarios  
- Mandatory field validation  
- Boundary value testing  
- Error message verification  

### 🎨 UI / Usability Testing
- UI alignment and consistency  
- Placeholder and label validation  
- Password masking  
- Cross-browser compatibility  

### 🔐 Security Testing
- SQL Injection testing  
- Cross-Site Scripting (XSS)  
- Broken authentication checks  
- Session management validation  
- Browser back/refresh behavior after logout  

---

## 🌐 Test Environment

| Parameter | Details |
|--------|--------|
| Browsers | Chrome, Firefox, Microsoft Edge |
| OS | Windows |
| Testing Level | System Testing |
| Test Data | Valid, Invalid, Malicious Inputs |

---

## 🛠 Tools Used

- Excel / Google Sheets – Test case design & tracking  
- Burp Suite – Security testing  
- Browser Developer Tools – Network & console analysis  
- Screenshot Tool – Defect evidence  

---

## ✅ Scope of Testing

### ✔ In Scope
- Login functionality  
- Input validations  
- Error handling  
- Password masking  
- Session creation & termination  
- Basic security vulnerabilities  
- Browser navigation behavior  

### ❌ Out of Scope
- Backend database validation  
- API security testing  
- Performance / load testing  
- Role-based authorization  

---

## 🧪 Test Artifacts

- **Test Scenarios:** 20  
  - Functional: 12  
  - Security: 8  

- **Test Cases:** 40  

### 📊 Test Execution Summary

| Status | Count |
|------|------|
| Passed | 28 |
| Failed | 12 |
| Blocked | 0 |

- **Execution Duration:** 2 Days  

---

## 🐞 Defect Summary

| Severity | Count |
|--------|-------|
| Critical | 2 |
| Major | 3 |
| Medium | 1 |
| Minor | 1 |

---

## 🚨 Key Findings

- SQL Injection vulnerability in login fields  
- XSS inputs not properly sanitized  
- Session does not expire after inactivity  
- Browser back button allows access after logout  
- Password autocomplete enabled  
- Error messages expose internal details  
- Application served over HTTP (no HTTPS)  

---

## 📌 Recommendations

- Implement proper input validation and sanitization  
- Use prepared statements to prevent SQL Injection  
- Enforce HTTPS with SSL/TLS  
- Improve session timeout and invalidation  
- Disable password autocomplete  
- Display generic error messages  
- Perform regular security testing (VAPT)  

---

## 📌 Conclusion

The Guru99 Login Application is **not secure for production use** in its current state.  
Multiple **critical and major vulnerabilities** were identified that pose serious security risks.

Fixing the reported issues will significantly improve the **security, reliability, and user trust** of the application.

---

## 📂 Repository Structure

