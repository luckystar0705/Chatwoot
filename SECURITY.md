# Chatwoot Security Policy

Chatwoot is committed to working with security researchers worldwide to keep our platform and users safe.  
If you discover a vulnerability in our systems or applications, please follow the steps below.

---
We track security issues on **GitHub**.  
If you believe you’ve found a vulnerability, please disclose it via this [form](https://github.com/chatwoot/chatwoot/security/advisories/new).  

This helps us:
- Review the report
- Fix the issue promptly
- Reward your efforts

If you have questions about the process, email **security@chatwoot.com**.  
> **Note:** Disclosures must be submitted via GitHub, not by email.  
> Please avoid opening public GitHub issues or sharing on social media.

---

## Supported Versions

| Version  | Supported |
|----------|-----------|
| latest   | ✅         |
| < latest | ❌         |

---

## In-Scope Vulnerabilities

Please test against a **self-hosted instance**, not production services.  
We’re particularly interested in:

- Remote Command Execution (RCE)
- SQL Injection
- Authentication Bypass
- Privilege Escalation
- Cross-Site Scripting (XSS)
- Unauthorized Admin Actions
- Cross-Site Request Forgery (CSRF)

Learn more about our [triaging process](https://www.chatwoot.com/docs/contributing-guide/security-reports).

---

## Out-of-Scope Vulnerabilities

The following are generally **not considered** valid reports (exceptions may apply):

- Missing HTTP security headers
- Incomplete or missing SPF/DKIM
- Automated scanner reports
- Theoretical attacks without proof
- Social engineering
- Reflected file download
- Physical attacks
- Weak SSL/TLS/SSH configurations
- Attacks requiring physical device/network compromise (e.g., MITM)
- Self-inflicted user attacks
- Denial of Service (DoS)
- Brute force attacks
- DNSSEC-related issues

If unsure, please still [submit a report](https://github.com/chatwoot/chatwoot/security/advisories/new).

---

## Acknowledgment

Thank you for helping us keep Chatwoot and our users safe. 🙇
