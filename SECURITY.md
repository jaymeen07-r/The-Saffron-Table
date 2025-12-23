# Security Policy

The Saffron Table – Restaurant QR Ordering System takes security seriously, especially because it handles order, billing, and customer contact information. This document explains which versions are supported and how to report vulnerabilities.

---

## Supported Versions

Only actively maintained versions receive security updates. Older or experimental branches may not be patched.

| Version   | Supported          |
|---------- |--------------------|
| 1.x       | ✅                 |
| 0.x (beta)| ⚠️ Security fixes only if feasible |
| < 0.x     | ❌                 |

> Update to the latest stable `1.x` release to ensure you receive security and bug fixes.

---

## Reporting a Vulnerability

If you discover a security vulnerability, **do not create a public issue or pull request** describing it. Instead, follow the process below to help keep users safe while it is being fixed.

### How to report

Please send a detailed report via:

- **Email:** `security@thesaffrontable.com` (example – replace with your real address)
- **Subject line:** `Security Report – The Saffron Table QR System`

Include, where possible:

- A clear description of the issue.
- Steps to reproduce (proof-of-concept if available).
- Impact assessment (what can an attacker do).
- Any logs, screenshots, or environment details that help reproduce.

If you are unsure whether something is a security issue, report it privately anyway.

---

## Response Process & Expectations

When you report a potential vulnerability, you can expect:

1. **Acknowledgment:**  
   - An initial response within **3–5 business days** confirming that the report has been received.

2. **Assessment:**  
   - The issue will be triaged and its severity assessed (low, medium, high, critical).
   - You may be contacted for additional information or clarification.

3. **Remediation:**  
   - For valid vulnerabilities, a fix will be developed and tested.
   - Depending on severity, a patched release or hotfix branch may be published.
   - In some cases, configuration or deployment guidance may be recommended instead of a code change.

4. **Disclosure:**  
   - You will be informed when the issue is fixed and a release is available.
   - Public disclosure details (if any) will be coordinated with you.  
   - Credit may be given to the reporter if requested and appropriate.

---

## Scope

This security policy applies to:

- The application code in this repository.
- Configuration and infrastructure templates shipped with the project (if any).

Out of scope (but you can still report if you are unsure):

- Third-party dependencies, unless they are bundled in a way that cannot be updated by deployers.
- Misconfiguration by individual deployments (e.g., weak passwords, exposed admin panels in production, etc.).

---

## Best Practices for Deployers

If you are deploying The Saffron Table – Restaurant QR Ordering System:

- Always run the **latest stable version**.
- Use **strong, unique passwords** for all admin and staff accounts.
- Ensure the application is served over **HTTPS** in production.
- Restrict access to **admin and staff panels** via network rules or VPN where possible.
- Regularly review **server and application logs** for suspicious activity.
- Keep the underlying OS, database, and runtime (Node, Python, etc.) up to date with security patches.

If you have questions about securing your deployment, you can ask using the same contact channel used for vulnerability reports (clearly indicate it is a **support/security hardening question**, not a vulnerability).
