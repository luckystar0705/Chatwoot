# Chatwoot Security Policy

We at Chatwoot are committed to working with security researchers worldwide to keep our platform and users safe.  
If you discover a vulnerability, please follow the process below.

---

## Reporting a Vulnerability

We track security issues on **GitHub**.  
Please submit reports through this [form](https://github.com/chatwoot/chatwoot/security/advisories/new).

This allows us to:
- Review the issue
- Fix it promptly
- Reward your contribution

For questions about the process, contact **security@chatwoot.com**.  

> **Note:** Disclosures must be submitted via GitHub, not by email.  
> Please avoid creating public GitHub issues or sharing reports on social media.

---

## Supported Versions

| Version  | Supported |
|----------|-----------|
| latest   | ✅         |
| < latest | ❌         |

---

## In-Scope Vulnerabilities

Please test only against a **self-hosted instance**, not production services.  
We are primarily interested in:

- Remote Command Execution (RCE)
- SQL Injection
- Authentication Bypass
- Privilege Escalation
- Cross-Site Scripting (XSS)
- Unauthorized Admin Actions
- Cross-Site Request Forgery (CSRF)

See our [triaging process](https://www.chatwoot.com/docs/contributing-guide/security-reports) for more details.

---

## Out-of-Scope Vulnerabilities

The following are generally **not considered valid reports** (with rare exceptions):

- Missing HTTP security headers  
- Incomplete or missing SPF/DKIM  
- Automated scanner output without validation  
- Theoretical attacks without proof of exploitability  
- Social engineering  
- Reflected file download  
- Physical attacks  
- Weak SSL/TLS/SSH configurations  
- Attacks requiring physical access or already compromised networks/devices (e.g., MITM)  
- Self-inflicted user attacks  
- Denial of Service (DoS)  
- Brute force attacks  
- DNSSEC-related issues  

If in doubt, please still [submit a report](https://github.com/chatwoot/chatwoot/security/advisories/new).

---

## Acknowledgment

Thank you for helping us keep Chatwoot and our users safe.
