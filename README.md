# OWASP Juice Shop Vulnerability Assessment

## Project Overview

This project presents a comprehensive **Web Application Vulnerability Assessment and Penetration Testing (VAPT)** conducted on the **OWASP Juice Shop** application. The assessment was performed in a controlled laboratory environment to identify common web application security vulnerabilities and gain hands-on experience with industry-standard penetration testing methodologies.

The testing focused on identifying vulnerabilities aligned with the **OWASP Top 10 Web Application Security Risks**, including SQL Injection, Broken Access Control, Security Misconfiguration, and Information Disclosure. Each identified vulnerability was analyzed, validated, documented with supporting evidence, and accompanied by practical remediation recommendations.

Throughout this project, manual testing techniques were used to understand how security weaknesses can be exploited and how organizations can mitigate these risks through secure development practices. The assessment demonstrates practical skills in vulnerability identification, exploitation, risk analysis, documentation, and security reporting.

---

# Project Objectives

- Perform a security assessment of the OWASP Juice Shop application.
- Identify and validate common web application vulnerabilities.
- Document findings with supporting screenshots and technical evidence.
- Map vulnerabilities to the OWASP Top 10 security categories.
- Provide mitigation strategies and security recommendations.
- Develop practical experience in Web Application Penetration Testing (VAPT).

---

# Scope of Assessment

The assessment included testing multiple functionalities of the OWASP Juice Shop application to identify security weaknesses related to:

- SQL Injection
- Broken Access Control
- Security Misconfiguration
- Information Disclosure
- File Validation Issues
- Hidden Resource Discovery

---

# Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| **Burp Suite** | Intercepted and analyzed HTTP/HTTPS requests to identify and validate web application vulnerabilities. |
| **Mozilla Firefox** | Configured with Burp Suite proxy for manual security testing and vulnerability verification. |
| **Google Chrome** | Used for cross-browser testing and validating application functionality. |
| **Kali Linux** | Primary penetration testing environment for performing manual security assessments. |
| **Windows** | Host operating system used for virtualization, documentation, and report preparation. |
| **OWASP Juice Shop** | Deliberately vulnerable web application used for security testing and demonstrating OWASP Top 10 vulnerabilities. |

---

# Assessment Results

The vulnerability assessment successfully identified multiple security issues within the application.

| Vulnerability | OWASP Category | Status |
|---------------|----------------|--------|
| SQL Injection | A03:2021 – Injection | ✅ Completed |
| Admin Registration | A01:2021 – Broken Access Control | ✅ Completed |
| Misplaced Signature File | A05:2021 – Security Misconfiguration | ✅ Completed |
| Poison Null Byte | A01:2021 – Broken Access Control | ✅ Completed |
| Forgotten Sales Backup | A05:2021 – Security Misconfiguration | ✅ Completed |
| Easter Egg | Hidden Resource Discovery | ✅ Completed |

### Key Results

- Successfully performed manual Web Application Penetration Testing.
- Identified multiple OWASP Top 10 vulnerabilities.
- Validated vulnerabilities with screenshots and technical evidence.
- Documented findings using a professional VAPT report.
- Mapped each finding to the relevant OWASP category.
- Recommended remediation techniques for improving application security.

---

# Remediation Recommendations

### SQL Injection
- Use parameterized queries (Prepared Statements).
- Validate and sanitize user inputs.
- Avoid dynamic SQL queries.
- Apply least-privilege access to database accounts.

### Broken Access Control
- Implement Role-Based Access Control (RBAC).
- Enforce server-side authorization checks.
- Restrict administrative functionality.
- Prevent privilege escalation.

### Security Misconfiguration
- Remove backup and unnecessary files from production.
- Disable directory listing.
- Secure server configurations.
- Perform regular configuration reviews.

### Information Disclosure
- Restrict access to sensitive resources.
- Remove exposed confidential files.
- Configure proper file permissions.
- Encrypt sensitive information.

### File Validation Issues
- Validate filenames and file paths.
- Reject null-byte injection attempts.
- Prevent directory traversal attacks.
- Restrict unauthorized file access.

### General Security Best Practices
- Follow the OWASP Top 10 Secure Coding Guidelines.
- Conduct regular Vulnerability Assessments and Penetration Testing (VAPT).
- Keep applications and dependencies up to date.
- Implement secure authentication and session management.
- Monitor logs for suspicious activities.
- Perform periodic security reviews and code audits.

---

# Learning Outcomes

This project helped strengthen practical knowledge in:

- Web Application Penetration Testing (VAPT)
- Manual Vulnerability Assessment
- Burp Suite Proxy Configuration
- HTTP Request & Response Analysis
- SQL Injection Testing
- Broken Access Control Testing
- Security Misconfiguration Assessment
- Information Disclosure Analysis
- Vulnerability Documentation
- Technical Report Writing
- Security Best Practices
- OWASP Top 10 Methodology

---

# Conclusion

The assessment successfully demonstrated the identification and validation of multiple web application vulnerabilities within the OWASP Juice Shop environment. The project enhanced practical knowledge of penetration testing methodologies, vulnerability assessment, risk analysis, and professional security reporting. By providing remediation recommendations for each finding, this assessment highlights the importance of secure coding practices, proper access control, and continuous security testing to strengthen the overall security posture of web applications.

---

# Disclaimer

This project was conducted in a controlled laboratory environment using the intentionally vulnerable OWASP Juice Shop application for educational and ethical learning purposes only. No unauthorized systems or production environments were targeted during this assessment.
