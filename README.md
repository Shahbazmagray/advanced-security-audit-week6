 Advanced Security Audits & Final Deployment

## Project Overview
This project demonstrates advanced web application security auditing, vulnerability assessment, and penetration testing using industry-standard cybersecurity tools.

Target application: OWASP Juice Shop (localhost:3000)

---

## Tools Used

- OWASP ZAP
- Nikto
- Lynis
- Metasploit Framework
- npm audit
- Kali Linux

---

## Tasks Completed

### 1. Security Audit (OWASP ZAP)
Performed automated vulnerability scanning and analyzed security headers and alerts.

### 2. Web Server Scan (Nikto)
Checked for misconfigurations, missing headers, and potential security issues.

### 3. System Audit (Lynis)
Performed system-level security audit and reviewed hardening suggestions.

### 4. Dependency Check
Used npm audit to ensure no vulnerable packages exist.

Result: **0 vulnerabilities found**

### 5. Penetration Testing (Metasploit)
Used Metasploit to perform:

- TCP Port Scan
- HTTP Service Enumeration

Findings:
- Port 3000 is open
- Web application is accessible
- No exploitable services detected

---

## Security Improvements Implemented

- Input validation
- Password hashing (bcrypt)
- JWT authentication
- Rate limiting
- API key security
- Helmet security headers
- CSP + HSTS
- Winston logging
- Fail2Ban monitoring

---

## Conclusion
This project demonstrates practical application of cybersecurity auditing, penetration testing, and web application hardening techniques.

---

## Author
Shahbaz Iftikhar
BS Software Engineering
