---
name: security-check
description: Use when writing code that handles user input, authentication, file I/O, shell commands, database queries, or network requests. Checks for common vulnerabilities.
---

When code touches a security-sensitive area, check for these issues:

1. **Injection** -- SQL injection, command injection, XSS, template injection. Is user input sanitized and parameterized?
2. **Authentication/Authorization** -- Are access controls enforced? Are secrets hardcoded? Are tokens or passwords exposed in logs?
3. **Path traversal** -- Can user input manipulate file paths to access unauthorized files?
4. **Sensitive data** -- Are credentials, API keys, or PII being logged, committed, or sent to external services?
5. **Dependencies** -- Are new dependencies from trusted sources? Do they introduce known vulnerabilities?

If a vulnerability is found, fix it immediately and explain what was wrong and why the fix is correct. Do not ship known vulnerabilities.
