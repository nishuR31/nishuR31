# 🔐 Security Policy

[![Security Policy](https://img.shields.io/badge/Security-Policy-blue?style=for-the-badge&logo=shield&logoColor=white)](#security-policy)
[![Responsible Disclosure](https://img.shields.io/badge/Responsible-Disclosure-critical?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nishangithub@gmail.com)
[![Vulnerabilities Welcome](https://img.shields.io/badge/Vulnerabilities-Welcome-success?style=for-the-badge&logo=github&logoColor=white)](#reporting-a-vulnerability)

---

## 🚨 Reporting a Vulnerability

**Do not create public issues or pull requests for security vulnerabilities.**  
We have a dedicated private channel to handle these with care and respect.

### Contact:
[![Report Now](https://img.shields.io/badge/Email-nishangithub@gmail.com-critical?style=flat-square&logo=gmail&logoColor=white)](mailto:nishangithub@gmail.com)

When reporting, please include:
- A clear description of the issue
- Steps to reproduce or a proof-of-concept
- The impact and severity
- Any relevant logs or code

You will receive a response **within 48 hours**, and a fix will be rolled out **within 7–14 days** depending on severity.

---

## 🔐 Security Best Practices We Follow

- Automatic dependency auditing (`npm audit`, `pip-audit`)
- HTTPS enforced for all external calls
- Input sanitization and validation
- Access control logic and permission checks
- No use of `eval`, raw `innerHTML`, or unsanitized inputs
- Environment variables for secrets (`.env` pattern)
- Regularly updated `.gitignore` and secure `.env` handling
- Separate dev and production configs

---

## ✅ Scope of Vulnerability Reports

We welcome reports related to:

- Sensitive data leaks (tokens, emails, user data)
- Broken access control or privilege escalation
- XSS, CSRF, SQLi, or any form of code injection
- Insecure API endpoints
- Unsafe use of libraries or dependencies

Out of scope:

- Denial of service (DoS) through valid input
- Reports from outdated dependencies with no usage in core logic
- Self-XSS without a real-world impact

---

## ✨ Credits & Recognition

We appreciate your contributions to the security of this project! If you disclose a valid vulnerability, you will:
- Be credited in the release notes (if desired)
- Have a special badge added to the project’s `SECURITY.md`
- Possibly be included in a Hall of Fame page (coming soon)

---

## 🧠 Additional Resources

- [Node.js Security Checklist](https://github.com/lirantal/nodejs-security-checklist)
- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [GitHub Security Advisories](https://docs.github.com/en/code-security/security-advisories)

---

## Attribution

This policy is inspired by the practices of major open source projects and aligned with modern security disclosure norms.

[![Contributor Covenant](https://img.shields.io/badge/Follows-Contributor%20Covenant%20v2.1-blueviolet?style=flat-square&logo=github&logoColor=white)](https://www.contributor-covenant.org)

