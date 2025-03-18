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
Access the application via http://localhost:3000

Use tools like Burp Suite and OWASP ZAP to intercept and analyze requests

Perform the necessary penetration testing attacks as per the OWASP Top 10

Findings and Reports

The following table outlines the vulnerabilities found during testing:

| Vulnerability            | Exploited Feature | Impact   | Mitigation Recommendations                                      |
|--------------------------|------------------|----------|----------------------------------------------------------------|
| **SQL Injection (SQLi)** | Login Form       | High     | Use prepared statements, input validation                      |
| **Cross-Site Scripting (XSS)** | Comment Section  | Medium   | Implement output encoding, CSP headers                         |
| **Cross-Site Request Forgery (CSRF)** | Account Settings | High     | Implement CSRF tokens, same-site cookies                       |
| **Broken Authentication** | Login Session    | Critical | Use secure session management, multi-factor authentication     |
| **Security Misconfigurations** | Server Headers   | Medium   | Remove unnecessary headers, configure security settings properly |

📌 Future Improvements

Enhance API security testing with Postman and Burp Suite API scanning

Automate security scans using Nikto and OWASP ZAP scripting

Implement Real-Time Monitoring using SIEM solutions

Explore container security and hardening for deployments

📢 Conclusion

This project provided hands-on experience with web application penetration testing techniques. By exploiting vulnerabilities and documenting findings, we can better understand how to secure modern web applications. Future work will focus on advanced attack vectors, automation, and integrating security best practices into the DevSecOps pipeline.


