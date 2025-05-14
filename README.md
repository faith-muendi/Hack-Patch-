# Hack & Patch Lab

## 🔍 Overview
This lab simulates a hands-on web application pentesting environment, where I identify and exploit common vulnerabilities in intentionally vulnerable web applications (DVWA and bWAPP). It also demonstrates how to "patch" or mitigate vulnerabilities after exploitation, reinforcing secure coding and security best practices.

## 🛠 Tools & Technologies
- Burp Suite (Community Edition)
- OWASP ZAP
- DVWA (Damn Vulnerable Web Application)
- bWAPP (Buggy Web Application)
- Kali Linux (Offensive Security Tools)
- XAMPP (Local Web Server)

## 🧪 Vulnerabilities Covered
- **Injection** (SQLi, Command Injection)
- **Broken Authentication**
- **Sensitive Data Exposure**
- **Cross-Site Scripting** (XSS – Reflected, Stored)
- **Insecure Direct Object References** (IDOR)
- **Security Misconfiguration**
- **Cross-Site Request Forgery** (CSRF)
- **Broken Access Control**
- **Insecure Deserialization**
- **Using Components with Known Vulnerabilities**

## 🧠 Key Objectives
- Reproduce and exploit OWASP Top 10 vulnerabilities.
- Use Burp Suite and OWASP ZAP for intercepting and modifying requests.
- Capture and document proof-of-concept (PoC) exploits.
- Identify vulnerabilities and recommend patches to secure the applications.



## 📁 Repo Structure
- `/payloads/` – SQLi, XSS payloads, and scripts
- `/screenshots/` – Proof-of-concept images of exploits
- `/reports/` – Documentation of vulnerabilities, impact, and mitigations

## 📝 Sample Exploits
- **XSS**: `<script>alert('Hacked!')</script>`
- **SQLi**: `' OR '1'='1' --`
- **CSRF**: Crafted malicious form submission
- **IDOR**: Accessing unauthorized resources via manipulated URLs

## 🔒 Mitigation Tips
- Validate and sanitize user input.
- Use prepared statements for SQL queries.
- Implement secure session management and authentication protocols.
- Ensure proper access control mechanisms are in place.

## 🚀 Future Improvements
- Expand tests to modern web frameworks like React/Node.js.
- Automate testing using Burp Suite extensions and scripts.
- Add additional vulnerability scenarios like SSRF and XXE (XML External Entities).

---

> ⚠️ **Note**: This lab is created for educational purposes. All tests were performed on intentionally vulnerable applications in a controlled environment.
