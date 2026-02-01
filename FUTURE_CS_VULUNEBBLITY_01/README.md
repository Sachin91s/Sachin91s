<div align="center">

# 🛡️ VULNERABILITY ASSESSMENT REPORT

### Read-Only Web Security Assessment  
**Ethical • Non-Intrusive**

![Status](https://img.shields.io/badge/Status-Completed-success)
![Assessment](https://img.shields.io/badge/Type-Vulnerability_Assessment-blue)
![Method](https://img.shields.io/badge/Method-Read--Only-pink)
![Risk](https://img.shields.io/badge/Overall_Risk-Medium-orange)

</div>

---

## 📌 About This Repository

This repository contains a **professional Read-Only Vulnerability Assessment Report** conducted on a publicly accessible test website.  
The assessment focuses on identifying **security misconfigurations and weaknesses** using **passive and ethical testing methods**, without exploiting the target system.

---

## 📋 Project Summary

| Parameter | Description |
|---------|-------------|
| **Target Application** | `testphp.vulnweb.com` |
| **Assessment Category** | Web Vulnerability Assessment |
| **Testing Mode** | Passive / Non-Intrusive |
| **Performed By** | Sachin Kumar |
| **Assessment Period** | January 2026 |
| **Total Findings** | **09 Vulnerabilities** |

---

## 🎯 Objective

The primary objective of this assessment is to:

- Evaluate the **security posture** of the web application  
- Identify **common web security weaknesses**  
- Demonstrate **real-world vulnerability assessment methodology**  
- Provide **clear remediation recommendations** in business-friendly language  

No exploitation, data modification, or service disruption was performed.

---

## 🔍 Scope Definition

### ✔️ In Scope
- Publicly accessible pages
- Passive vulnerability scanning
- HTTP header & client-side analysis
- Open port and service visibility

### ❌ Out of Scope
- Authentication-based testing
- Active exploitation
- Denial-of-Service attacks
- Brute-force or intrusive techniques

---

## 🛠️ Tools & Environment

| Tool | Usage |
|-----|------|
| **Nmap** | Port & service visibility |
| **OWASP ZAP** | Passive vulnerability detection |
| **Browser DevTools** | Header, cookie & client-side review |
| **Canva** | Professional report presentation |

---

## 🌐 Target Environment Overview

| Attribute | Value |
|---------|------|
| **URL** | `http://testphp.vulnweb.com/` |
| **Protocol** | HTTP |
| **Web Server** | nginx 1.19.0 |
| **Backend** | PHP 5.6.40 |
| **Hosting Provider** | Amazon Web Services (AWS) |
| **Exposure Level** | Medium |

---

## 🚨 Vulnerability Findings

A total of **9 findings** were identified during the assessment.

### 🔶 Medium Risk (3)

1. **Absence of Anti-CSRF Tokens**  
   → Risk of unauthorized user actions

2. **Missing Content Security Policy (CSP)**  
   → Increased exposure to XSS attacks

3. **Missing Anti-Clickjacking Protection**  
   → Application vulnerable to UI redressing attacks

---

### 🔹 Low Risk (3)

4. **In-Page Banner Information Disclosure**  
5. **X-Powered-By Header Information Leak**  
6. **Server Header Version Disclosure**

---

### ℹ️ Informational (3)

7. **Missing X-Content-Type-Options Header**  
8. **Charset Mismatch**  
9. **Modern Web Application Identified**

---

## 📊 Risk Classification Summary

| Severity | Count |
|--------|-------|
| Medium | 3 |
| Low | 3 |
| Informational | 3 |
| **Total** | **9** |

---

## ✅ Key Recommendations

- Implement **Anti-CSRF protection**
- Enforce **Content Security Policy (CSP)**
- Hide server & technology version details
- Add missing security headers:
  - `X-Frame-Options`
  - `X-Content-Type-Options`

---

## 🧠 Conclusion

The assessment confirms that while the application is functional, it lacks **baseline security hardening** expected in modern web applications.  
Addressing the identified issues will significantly improve the application's security posture and reduce attack surface.

---

## ⚠️ Disclaimer

This assessment was conducted **strictly for educational and security awareness purposes** using **read-only techniques**.  
No exploitation or harmful activity was performed.  
The author is not responsible for misuse of this information.

---

<div align="center">

### 👤 Author  
**Sachin Kumar**

*Cyber Security | Vulnerability Assessment | Web Security*

</div>
