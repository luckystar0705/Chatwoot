# Security Policy

We welcome responsible disclosure from security researchers. This document explains how to report vulnerabilities and what we consider in-scope.

---

## Reporting a vulnerability

Please **submit security reports via GitHub Security Advisories** so we can track, triage and fix issues effectively:

* **Submit here:** `https://github.com/chatwoot/chatwoot/security/advisories/new`
* For process questions only: `security@chatwoot.com`

> **Important:** Do **not** create public GitHub issues or post vulnerability details on social media. Use the GitHub advisories form.

---

## Supported versions

|  Version | Supported |
| -------: | :-------: |
|   latest |     ✅     |
| < latest |     ❌     |

We provide security fixes for the latest release only.

---

## Test safely

Only test against instances you **own or have explicit permission to test**. Do **not** target production instances you do not control.

---

## In-scope vulnerabilities

We are primarily interested in issues that lead to compromise of confidentiality, integrity, or availability. Typical examples include:

* Remote Command Execution (RCE)
* SQL injection
* Authentication bypass
* Privilege escalation
* Cross-Site Scripting (XSS)
* Unauthorized admin actions
* Cross-Site Request Forgery (CSRF)

See our triage guide for more details: `https://www.chatwoot.com/docs/contributing-guide/security-reports`

---

## Out-of-scope (generally)

The following are usually **not** valid reports unless accompanied by clear exploitability or a practical attack path:

* Missing HTTP security headers (unless chaining to an exploit)
* Missing/incomplete SPF/DKIM
* Automated scanner output without manual validation
* Theoretical attacks without proof-of-concept
* Social engineering
* Reflected file download issues
* Physical-access attacks
* Weak SSL/TLS or SSH configurations without demonstrated exploit
* Attacks requiring an already-compromised environment (e.g., MITM when you control neither end)
* Self-inflicted user attacks
* Denial of Service (DoS) without demonstrated impact
* Brute force attempts without demonstrated escalation
* DNSSEC issues (unless they lead to exploitable impact)

If in doubt, submit a report — we prefer to evaluate borderline cases ourselves.

---

## How to submit a useful report

Please include as much of the following as possible to help us reproduce and fix the issue quickly:

1. **Title (one line)**
2. **Summary** — short description of the issue and impact
3. **Affected versions / configuration**
4. **Reproduction steps / PoC** — minimal, reproducible steps (curl commands, scripts or exploit code)
5. **Impact** — what an attacker can do
6. **Logs/response data** — where applicable (sanitized if sensitive)
7. **Mitigation suggestions** (optional)
8. **Contact** — GitHub handle or email for follow-up

### Minimal report template

```


Steps to reproduce:
1. POST /api/v1/widgets with body: {"q":"1' OR (SELECT 1 FROM users WHERE id=1 AND substr(email,1,1)='a')-- -"}
2. Observe timing-based responses indicating injection.

PoC:
[attach script or curl commands]

Impact:
An attacker could extract data from the database.

Contact:
- github-username (or email@example.com)
```

---

## What happens after you report

1. We will acknowledge receipt via GitHub advisories.
2. We may ask for additional details or a test instance to validate the issue.
3. We will triage and fix confirmed issues as appropriate.
4. Valid reports may be acknowledged in release notes or our security acknowledgements page. Any reward programs are handled case-by-case.

---

## Responsible testing guidelines
* Test only on instances you control or have permission to test.
* Avoid destructive or irreversible tests on shared systems.
* Prefer safe, non-destructive PoCs where possible.

---

## Quick links

* Security advisory form: `https://github.com/chatwoot/chatwoot/security/advisories/new`
* Triage guide: `https://www.chatwoot.com/docs/contributing-guide/security-reports`
* Contact: `security@chatwoot.com`

---

Thank you for helping keep Chatwoot secure.
