# Web Application Security Testing (Task 1)

## 📌 Introduction
This repository contains **Task 1: Web Application Security Testing** completed as part of the **Future Interns Cybersecurity Program (Batch 01)**.  
The task involved testing a vulnerable web application (DVWA) for common web vulnerabilities and documenting findings with remediation.

---

## 🎯 Objectives
- Perform penetration testing on a sample web application (DVWA).  
- Identify vulnerabilities such as SQL Injection, XSS, IDOR, etc.  
- Document findings with screenshots and CVSS scoring.  
- Provide remediation measures for each vulnerability.  

---

## 🛠️ Tools & Environment
- **DVWA (Damn Vulnerable Web App)**  
- **Burp Suite Community Edition**  
- **OWASP ZAP**  
- **Nmap, Nikto**  
- **Kali Linux**  

---

## ⚙️ Implementation
1. Setup DVWA in Kali Linux.  
2. Performed vulnerability analysis using Burp Suite & ZAP.  
3. Exploited sample vulnerabilities (SQLi, XSS, File Inclusion, IDOR).  
4. Captured requests & modified parameters to test business logic flaws.  
5. Documented findings with proof-of-concept screenshots.  

---

## 🔍 Findings
- **SQL Injection** – able to extract database info.  
- **XSS** – executed malicious JavaScript in user context.  
- **IDOR** – accessed unauthorized user data.  

Each vulnerability was scored using **CVSS v3.1** and remediation was suggested.  

---

## 🔒 Remediation
- Use parameterized queries to prevent SQL Injection.  
- Encode and sanitize user input to mitigate XSS.   
- Enforce authorization checks to prevent IDOR.
