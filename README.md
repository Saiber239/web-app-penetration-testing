# 🛡️ Web Application Penetration Testing

## 🔍 Overview
This project demonstrates practical web application penetration testing techniques using **OWASP Juice Shop**, **DVWA**, and other intentionally vulnerable web applications. The goal is to identify, exploit, and document common web application vulnerabilities following the **OWASP Top 10**.

---

## ⚔️ Attacks Performed
| Vulnerability | Description                     | Status |
|---------------|---------------------------------|--------|
| SQL Injection (SQLi) | Extracted sensitive data by bypassing login forms | ✅ |
| Cross-Site Scripting (XSS) | Injected malicious JavaScript into user input | ✅ |
| Cross-Site Request Forgery (CSRF) | Performed unauthorized actions on behalf of users | ✅ |
| Broken Authentication | Exploited weak session management | ✅ |
| Security Misconfigurations | Identified improper server settings | ✅ |

---

## 🛠️ Tools Used
- ⚡ **Burp Suite**
- ⚡ **OWASP ZAP**
- ⚡ **Nikto**
- ⚡ **SQLMap**
- ⚡ **Postman** (for API testing)
- ⚡ **Nmap**
- ⚡ **Firefox Developer Tools**

---

## 🚀 How to Run
1. Clone the vulnerable application (example: OWASP Juice Shop):
    ```bash
    git clone https://github.com/juice-shop/juice-shop.git
    cd juice-shop
    npm install
    npm start
    ```



